# data-sample — CEO 리포트용 샘플 데이터

> 본 폴더는 `src/report-template.html`에 사용할 **샘플 데이터**다.
> 실제 ERP/POS 데이터 연결 전, 리포트 구조·시각화 검증용으로 합리적 추정치를 포함한 모의 데이터셋이다.
> 최초 작성: 2026-05-25

---

## 파일 구성

| 파일 | 내용 | 출처 신뢰도 |
|------|------|------------|
| `brands.json` | 3개 브랜드 메타 (포지셔닝·가격대·매장수·채널 mix 등) | 일부 실제(company-info.md), 매장수·점유율은 추정 |
| `stores.json` | 41개 대표 매장 (백화점·아울렛·자사몰 mix) | 채인·지점명은 실제 브랜드, 매핑은 추정 |
| `categories.json` | 여성복 품목 카테고리 트리 (5 대분류 × 4~5 하위) | 업계 표준 카테고리 |
| `sales-fy2025.json` | 분기·브랜드·채널·카테고리 매출 롤업 | 총매출 3,040억 = audit-report 일치, 분해는 추정 |
| `top-sku-fy2025.json` | 베스트 10 / 워스트 5 SKU | 합리적 추정 (실 SKU 매칭 필요) |
| `inventory-fy2025.json` | 재고·sell-through·마크다운·aging | 총재고 350억 추정 (회전 4.5회), 분해는 시즌성 반영 |

### 데이터 정합성 (cross-check 완료)

- 매출 합계 3,040억: byQuarter / byBrand / byChannel / byCategory 모두 일치
- 영업이익 합계 316억: byQuarter / byBrand 모두 일치
- 재고 합계 350억: byBrand / agingByBrand 모두 일치 (±1% 반올림 오차)

## 스키마 규칙

- **네이밍**: camelCase (기존 `audit-report/financial-data.json`과 일관)
- **금액**: 원(KRW) 단위 정수. 표시용 변환(억원)은 리포트 측에서 처리
- **날짜**: ISO 8601 (`YYYY-MM-DD`, `YYYY-MM`)
- **ID**: 케밥 케이스 영문 소문자 (`shesmiss`, `lotte-bonjeom-shesmiss`)
- **회계연도**: 12월 결산 → FY2025 = 2025-01-01 ~ 2025-12-31

## 사용 시 주의

⚠️ **이 폴더의 모든 매출·점유율·매장수 수치는 추정값**이다.
공식 수치(재무제표)는 `docs/audit-report/financial-data.json` 참조.
브랜드별·채널별 상세는 외부에 공개되지 않으므로, 실제 데이터 연결 시 갱신 필수.

## 데이터 갱신 절차 (실 데이터 연결 시)

1. ERP/POS 추출 형식을 본 스키마에 매핑
2. `metadata.asOf` / `metadata.note` 업데이트
3. `recommendUpdate` 플래그를 `false`로 변경
4. `src/report-template.html`이 참조하는 필드 경로 확인
