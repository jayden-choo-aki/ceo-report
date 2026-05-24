# v3 기존 항목 필요성 검토 (YAGNI 관점)

> 목적: v3 구조의 모든 섹션/KPI를 4축으로 비판적 검토 → Keep/Promote/Demote/Merge/Drop/Defer/Question 판정.
> 동기: 보고서가 "정보는 많은데 결정이 안 되는" 함정을 피하기 위함.
> 작성: 2026-05-24

---

## 0. 검토 프레임워크 (4축)

| 축 | 질문 | 점수 |
|----|------|------|
| **D — 의사결정 영향도** | 이 정보로 CEO가 결정을 다르게 할 수 있는가? | High / Med / Low |
| **A — 데이터 가용성** | 현재 ERP/POS/IDFmall로 즉시 집계되는가? | Y / Partial / N / ? |
| **C — Cadence 적정성** | v3가 정한 주기가 실효성 있는가? | OK / Tight (너무 빈번) / Loose (너무 드뭄) |
| **R — 중복/대체** | 다른 지표로 갈음하거나 통합 가능한가? | None / Partial / Full |

### 판정 코드

- ✅ **Keep** — 현 상태 유지
- ⬆ **Promote** — 비중·노출 강화
- ⬇ **Demote** — cadence·노출 낮춤
- 🔀 **Merge** — 다른 항목과 통합
- ❌ **Drop** — 제거
- ⏸ **Defer** — 데이터 갖춰지면 재논의
- ❓ **Question** — CEO/실무자 확인 필요

---

## 1. Headline Strip (8개 숫자) — ⚠ 가장 큰 검토 대상

| # | 지표 | D | A | C | R | 판정 | 코멘트 |
|---|------|---|---|---|---|------|--------|
| 1 | 매출 (주간) | High | Y | OK | None | ✅ Keep | 가장 즉각적 신호 |
| 2 | 영업이익 (주간) | High | **Partial** | **Tight** | None | ⬇ **Demote → "Est."** | **매출원가는 월말 마감 전 정확치 어려움**. 주간은 추정치임을 명시 (예: "OP 6.8억 (Est.)") |
| 3 | GM % (주간) | High | **Partial** | **Tight** | None | ⬇ **Demote → "Est."** | 동일 이유 |
| 4 | D2C 비중 | High | Y | OK | **Partial (⑤와 중복)** | ✅ Keep | Headline엔 둠. 본문 ⑤는 drill-down |
| 5 | 재고 일수 | High | Y | OK | Partial (③과 중복) | ✅ Keep | 본문은 브랜드별 분해 |
| 6 | Sell-through % | **High★** | Y | OK | Partial (③과 중복) | ⬆ **Promote** | 가장 핵심 지표, 색상 강조 |
| 7 | 베트남 가동률 % | High | Y | OK | None | ✅ Keep | Input metric, daily data 가능 |
| 8 | 환율 ₩/USD | **Low (주간)** | Y | **Tight** | None | ⬇ **Demote → Monthly로 이동** | 주간 변동이 의사결정에 직결되는 일 드묾. 월간 평균이 충분 |

### Headline Strip 권고

- **현 8개 → 6개로 압축** (OP/GM은 추정치 표기, 환율은 빼고 월간 섹션으로)
- 6개: **매출·재고일수·Sell-through·D2C·베트남가동률·OP(Est.)**
- 정확도 라벨링: 마감 전 추정치는 "Est." 또는 "*" 표기 강제

---

## 2. ① 의사결정 안건 TOP 3

| 컬럼 | D | A | 판정 | 코멘트 |
|------|---|---|------|--------|
| 안건명 | High | Y | ✅ Keep | |
| 배경 수치 | High | Y | ✅ Keep | |
| 옵션 (2~3개) | High | Y | ✅ Keep | |
| 기한 | High | Y | ✅ Keep | |
| 영향 추정 (매출·재고) | High | **Partial** | ❓ **Question** | "추정 정확도" 신뢰구간 표기 필요. CEO가 추정 절대값을 의사결정 근거로 쓰면 위험 |

### 추가 권고

- ❓ **"안건이 없는 주"는 강제로 채우지 않음** — 매주 3개 만들기 강박은 보고서 신뢰도 훼손
- ⬆ **"지난 안건 결과 추적" 1줄 추가** — 이전 결정의 outcome을 다음 보고서에 (closed-loop)
- ❓ **안건 발굴 SOP 필요** — 누가, 어떤 회의에서, 언제 후보를 올리는지 (현 v3는 미정)

---

## 3. ② 변곡점 트래커 (가설 3 + 신호 3)

| 항목 | D | A | C | 판정 | 코멘트 |
|------|---|---|---|------|--------|
| 가설1: SHESMISS 핵심고객 이탈 (30대 후반 재구매율) | High | **Partial** | OK | ❓ **Question** | 연령대 데이터는 멤버십 기반. 비회원 매출 비중이 크면 측정 불완전 |
| 가설2: 백화점 채널 노후화 (동매점 매출 YoY) | High | Y | OK | ✅ Keep | + 보조: **"백화점 매출 비중 변화"** 추가 권장 (채널 자체 축소 vs 점포 효율 둘 다 봐야) |
| 가설3: 신상품 적중률 하락 (New % of Sales, 입고 6주차) | High | Y | OK | ⬆ **Promote** | 패션업 표준, 가장 강한 진단 지표 |
| 신호1: D2C 비중 → 25% | High | Y | OK | ✅ Keep | Headline과 중복 OK (트래커에선 임계치 진척 강조) |
| 신호2: SISTINA 매출 비중 → 15% | High | Y | OK | ✅ Keep | 본인 결정 검증 |
| 신호3: 베트남 내재화율 → 40% | Med | Y | **Loose** | ⬇ **Demote → Monthly** | 주간 변동 폭이 작음. 월간 갱신으로 충분 |

### 추가 권고

- 가설/신호의 **임계치는 CEO와 협의 후 분기마다 갱신** (현 v3는 미확정)
- ⬆ **"가설별 보강 검증 데이터 1줄"** 추가 — 단일 지표만으로 가설 검증 위험

---

## 4. ③ 재고·공급망 헬스 (6개 항목)

| 항목 | D | A | C | R | 판정 | 코멘트 |
|------|---|---|---|---|------|--------|
| Sell-through (브랜드×주차×카테고리 heatmap) | **High★** | Y | OK | None | ⬆ **Promote** | 핵심 중 핵심 |
| 재고 일수 (Days on Hand, 브랜드별) | High | Y | OK | Partial (Headline) | ✅ Keep | Headline은 전사, 여기는 브랜드 |
| 마크다운율 (waterfall) | High | Y | OK | None | ✅ Keep | 마진 압박 선행지표 |
| 베트남 공장 가동률 + 납기 준수율 | High | Y | OK | Partial (Headline) | ✅ Keep | Headline은 가동률만, 여기는 +납기 |
| **내재화율 (자체/외주 비율)** | Med | Y | **Loose** | None | ⬇ **Demote → Monthly** | 주간 변동 거의 없음 |
| 시즌 입고 진척 (계획 대비 %) | High | Y | OK (시즌 중) | None | ✅ Keep | 시즌 외(비수기)엔 자동 숨김 |

### 추가 권고

- 🔀 **재고일수와 Sell-through는 짝 차트로** (한 화면에) — GMROI 계산 자동화 가능
- ❓ **카테고리 정의 합의** (Top/Bottom/Dress/OPS 등) — 브랜드 간 분류 일치 확인 필요

---

## 5. ④ 브랜드 4-up 슬라이드

| 행 | D | A | C | 판정 | 코멘트 |
|----|---|---|---|------|--------|
| 매출 W21 | High | Y | OK | ✅ Keep | |
| YoY % | High | Y | OK | ⬆ **Promote** | 절대값보다 변동률이 의사결정에 직결 |
| 마진 (Op/GM) | High | **Partial** | **Tight** | ⬇ **Demote → Monthly** | 주간 마진은 추정치, 본문엔 노출하지 않거나 Est. 표기 |
| Sell-through | High | Y | OK | ✅ Keep | |
| Comment 1줄 | High | Y (수기) | OK | ✅ Keep | **누가 작성하는지** 명시 필요 (브랜드장? 기획팀?) |
| ★SISTINA 누적 진척 1줄 | High | Y | OK | ✅ Keep | |
| ★IDFmall 신규회원·재구매 1줄 | High | Y | OK | ✅ Keep | |

### 추가 권고

- ❓ **IDFmall은 "브랜드"가 아닌 "채널"** — 4-up에 같이 두는 게 맞나? 또는 별도 행으로?
  - 대안 A: 현 구조 유지 (CEO 본인 의사결정 검증 관점에서 같은 카드)
  - 대안 B: 브랜드 3-up + IDFmall은 ⑤ 자사몰 섹션에서만 다룸
  - → CEO 선호 확인 후 결정

---

## 6. ⑤ 자사몰 Funnel

| 항목 | D | A | C | R | 판정 | 코멘트 |
|------|---|---|---|---|------|--------|
| GMV (주간) | High | Y | OK | None | ✅ Keep | |
| CVR (전환율) | High | Y | OK | None | ⬆ **Promote** | 자사몰의 가장 강한 운영 신호 |
| AOV (객단가) | High | Y | OK | None | ✅ Keep | |
| 객수 (UV/Order) | High | Y | OK | None | ✅ Keep | |
| 신규회원 | High | Y | OK | None | ✅ Keep | |
| 재구매율 | High | Y | OK | None | ⬆ **Promote** | LTV 선행지표 |
| 멤버십 등급별 매출 | Med | Y | **Loose** | None | ⬇ **Demote → Monthly** | 주간 변동 적음 |
| D2C 비중 | High | Y | OK | **Full (Headline)** | 🔀 **Merge** → Headline에 두고 여기선 brand-별 분해만 |
| Funnel drop-off | High | Y | OK | None | ✅ Keep | |
| 모바일 vs 데스크탑 / 앱 vs 웹 | Med | Y | **Loose** | None | ⬇ **Demote → Monthly** | 변화 매우 느림 |

---

## 7. ⑥ 채널 성과 (월간)

| 항목 | D | A | C | R | 판정 | 코멘트 |
|------|---|---|---|---|------|--------|
| 채널 mix (백화점/아울렛/자사몰/해외/B2B) | High | Y | OK | None | ✅ Keep | |
| 평당 매출 | High | Y | OK | None | ✅ Keep | |
| 동매점 매출 YoY (SSS) | **High★** | Y | OK | None | ⬆ **Promote** | 점포 효율의 핵심, Fast Retailing 양식의 표준 |
| 신규/폐점 | Med | Y | **Loose** | None | ⬇ **Demote → Quarterly** | 월 단위 변동 적음 |
| **백화점 수수료 가중평균** | High | **N (?)** | OK | **Full (⑦과 중복)** | 🔀 **Merge → ⑦로 통합** | ⑦에 한국 특화 5종에 이미 포함됨. ⑥에선 빼기 |

### 추가 권고

- ⏸ **백화점 수수료율 데이터 가용성 점검** — 점별 계약서가 회계팀에 모여있는지 확인. 안 모여있으면 분기 1회 수집 부담 큼 → Quarterly 로 demote 가능

---

## 8. ⑦ 재무 + 한국 특화 KPI 5종 (월간)

| 항목 | D | A | C | R | 판정 | 코멘트 |
|------|---|---|---|---|------|--------|
| 매출·OP·마진 (Variance) | **High★** | Y | OK | Partial (Headline) | ✅ Keep | 월말 확정치는 여기서 |
| 매출원가율·판관비율 (트렌드) | High | Y | OK | None | ✅ Keep | 신세계인터내셔날 판관비 50% 벤치마크 |
| 운전자본·재고자산·현금성 | High | Y | OK | None | ✅ Keep | 베트남 투자 후 변동 추적 |
| **백화점 수수료율 가중평균** (점별) | High | **N(?)** | OK | None | ⏸ **Defer** | 데이터 수집 부담 큼. 분기 1회 + 점 등급별 평균으로 시작 권장 |
| 특약매입 vs 직매입 비중 | High | **Partial** | OK | None | ❓ **Question** | 백화점 매출만 해당. 정의(상품별 vs 점별) 합의 필요 |
| S/S vs F/W 시즌 곡선 (누적 sell-through) | **High★** | Y | OK | None | ⬆ **Promote** | 마크다운 사전 경고, 가장 한국적 |
| 아울렛/행사매장 매출 기여 | High | Y | OK | None | ✅ Keep | 정상가 sell-through 역지표 |
| **환율/면화/베트남 가동률 민감도 표** | Med | **Partial (모델링 필요)** | **Loose** | None | ⬇ **Demote → Quarterly** | 1% 영향 모델은 분기마다 갱신해도 충분. 월간엔 환율 현재값만 |

### 추가 권고

- ⏸ **백화점 수수료·특약매입은 데이터 수집 SOP가 우선** — 데이터 없이 KPI만 정의하면 작동 안 함
- 🔀 **민감도 표는 분기 보고서로 이동**, 월간엔 "환율 1행"만

---

## 9. ⑧ 부록 (drill-down)

| 항목 | C | R | 판정 | 코멘트 |
|------|---|---|------|--------|
| SKU·매장 디테일 | On-demand | None | ✅ Keep | 부록은 본문에 안 들어간 것 |
| ESG (분기) | OK | None | ✅ Keep | 거시 메시지만, 정량은 v4 (누락 리서치 결과 반영) |
| HR (분기) | OK | None | ✅ Keep | 인당 매출·이직률 |
| 경쟁사 (분기 IR 시점) | OK | None | ✅ Keep | 한섬·신세계인터내셔날·LF 분기 실적 한 줄 |
| 거시 (월간) | OK | None | ✅ Keep | 소비심리·환율·면화 |

---

## 10. 시각화 카탈로그 (10종)

| # | 차트 | 판정 | 코멘트 |
|---|------|------|--------|
| 1 | 6-12 차트 | ✅ Keep | 핵심 표준 |
| 2 | Headline Strip | ✅ Keep | |
| 3 | 4-up Slide | ✅ Keep | |
| 4 | Sell-through Curve | ✅ Keep | |
| 5 | Markdown Waterfall | ✅ Keep | |
| 6 | Channel Mix Donut | ❓ **Question** | Donut은 비교 어려움. **Stacked Bar로 대체 검토** (vs YoY 비교 시) |
| 7 | Funnel (자사몰) | ✅ Keep | |
| 8 | Heatmap (브랜드×주차) | ✅ Keep | |
| 9 | Stacked Bar (시즌 곡선) | ⬆ **Promote** | 시즌 비교의 핵심 |
| 10 | YoY 변동 막대 | ✅ Keep | |

---

## 11. Cadence 매핑 — 통합 변경안

기존 v3 cadence 표에 위 검토 결과 반영:

| 섹션 | v3 | v3.1 변경 | 변경 이유 |
|------|----|----|---------|
| Headline Strip (8 → 6) | Weekly | **Weekly (6개로 압축)** | OP/GM은 Est. 표기, 환율은 월간 |
| ② 변곡점 신호3 (내재화율) | Weekly | **Monthly** | 변동 적음 |
| ③ 내재화율 | Weekly | **Monthly** | 동일 |
| ④ 브랜드별 마진 | Weekly | **Monthly (또는 Est.)** | 마감 전 정확치 어려움 |
| ⑤ 멤버십·디바이스 | Weekly | **Monthly** | 변동 적음 |
| ⑥ 신규/폐점 | Monthly | **Quarterly** | 월 단위 의미 약함 |
| ⑦ 민감도 표 | Monthly | **Quarterly** | 모델 갱신 분기 충분 |
| ⑦ 백화점 수수료·특약매입 | Monthly | **Quarterly (데이터 확보 후 Monthly 검토)** | 수집 부담 |

---

## 12. 종합: v3 항목별 판정 카운트

| 판정 | 개수 | 의미 |
|------|------|------|
| ✅ Keep | ~22개 | 현 상태 유지 |
| ⬆ Promote | 6개 | 비중 강화 (Sell-through, YoY, CVR, 재구매, SSS, S/S vs F/W) |
| ⬇ Demote | 7개 | Weekly → Monthly/Quarterly 강등 |
| 🔀 Merge | 3개 | 중복 통합 |
| ❌ Drop | 0개 | 제거 항목 없음 (구조 자체는 견고) |
| ⏸ Defer | 2개 | 데이터 수집 SOP 선행 필요 |
| ❓ Question | 6개 | CEO/실무자 확인 필요 |

---

## 13. v3.1 (또는 v4) 적용 권고 — TOP 7 액션

1. **Headline Strip 8 → 6개로 압축**, 추정치는 "Est." 강제 표기
2. **마진 지표는 월간으로 강등** (주간엔 추정치만, 굵게 표시 금지)
3. **"안건 없는 주" 허용** + 지난 안건 결과 1줄 추적 (closed-loop)
4. **변곡점 가설 임계치를 CEO와 협의 확정** (현재 placeholder)
5. **백화점 수수료·특약매입 데이터 가용성 점검 우선** (KPI 정의보다 수집 SOP)
6. **카테고리 정의·연령 데이터 정의 합의** (브랜드 간·회원/비회원 간)
7. **IDFmall을 ④에 둘지 별도로 둘지 CEO 선호 확인**

---

## 14. 누락 항목 리서치 (별도 진행)

본 검토는 **v3에 있는 것의 적정성**만 다뤘음. **v3에 없는 항목**(디자인·MD·마케팅·SNS·VOC·ESG 정량·해외판매·HR 정량·산업 트렌드 8개 도메인)은 별도 리서치 `docs/v3-missing-items.md`에서 다룸 (진행 중).

→ 두 문서 통합 후 **v4 (또는 v3.1) 최종 구조**로 진화.

---

## 15. 출처

- `docs/report-structure-v3.md` (검토 대상)
- `docs/persona-ceo.md` (판정 기준)
- `docs/benchmark-reports.md` (cadence·시각화 표준)
- YAGNI 원칙 (Martin Fowler) — 보고서 항목에도 적용
