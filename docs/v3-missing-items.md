# v3 누락 항목 리서치 — CEO Summary Report v4 후보 발굴

> **목적**: 현행 v3(`report-structure-v3.md`)에 빠져 있는 KPI·시각화·서사 후보를 8개 도메인에 걸쳐 발굴하고, 인동에프엔(매출 3,015억, 비상장, 여성복 3브랜드+자사몰, 베트남 직영공장) 맥락에서 **추가 가치가 있는 항목만** 선별해 v4 구조 설계 인풋으로 제공.
> **작성**: 2026-05-24
> **대상**: 인동에프엔 CEO 장기권 (Operator × Strategist 페르소나)
> **방법**: 글로벌(Inditex/H&M/Fast Retailing/Zara) + 한국 동종(한섬/신세계인터내셔날/LF/F&F/한세실업) 사례를 WebSearch로 수집, v3 갭과 1:1 매핑.

---

## 0. v3 빠짐 진단 (1줄 요약)

v3는 ① 재무·재고·공급망·자사몰 funnel·브랜드 4-up·한국 특화 5종까지 **운영 관점은 90% 커버**한다. 하지만 다음 7개 영역에는 **거의 공백**이거나, 부록 ⑧ 한 줄로만 처리돼 있어 CEO가 "이게 없네"라고 지적할 가능성이 높다.

1. **상품기획·MD KPI** (디자인 적중률·신상품 sell-through curve·트렌드 픽업률)
2. **브랜드 자산 가치** (인지도·NPS·EMV·인플루언서 ROI)
3. **디지털·SNS·검색 점유율·라이브커머스**
4. **고객 경험·반품·VOC**
5. **ESG 정량지표** (Scope 1·2·3·재활용 소재 비율·BSCI·DPP)
6. **해외 진출 (판매)** — v3는 부록 한 줄
7. **HR 정량** (디자이너·MD 이직률·인당 매출·핵심인재 retention)

---

## Executive Summary — 새로 발견한 TOP 10 후보

> 의사결정 영향(★1-5) × 데이터 가용성(★1-5)으로 평가. v3 본문(Weekly) 또는 월간/분기 부록 편입을 권장.

| 순위 | 항목 | 영역 | 의사결정영향 | 데이터가용성 | Cadence | v3 어디에 |
|------|------|------|------------|------------|---------|----------|
| 1 | **신상품 sell-through 30/60/90일 곡선** (브랜드별) | 상품기획 | ★★★★★ | ★★★★ (POS) | Weekly | §3-④ 4-up 슬라이드 행 추가 |
| 2 | **반품률 + 반품 사유 Top 3** (자사몰·백화점 구분) | 고객경험 | ★★★★★ | ★★★★ (IDFmall/CS) | Weekly | §5 자사몰 funnel 다음 |
| 3 | **디자이너·MD 이직률** + 핵심인재 retention | HR | ★★★★ | ★★★★ (HRIS) | Quarterly | §8 부록 → 본문 승격 |
| 4 | **자사몰 회원 등급별 매출 비중·LTV·재구매율** | 디지털 | ★★★★ | ★★★★ (IDFmall) | Monthly | §5 funnel 옆 6-12 차트 |
| 5 | **마크다운 폭(평균 할인율) + 정상가 sell-through 비중** | 재무 | ★★★★★ | ★★★★ (POS) | Weekly | §7 한국특화 5종 → 6종 |
| 6 | **SNS 인게이지먼트·검색 점유율 (네이버 데이터랩)** 브랜드별 | 디지털 | ★★★ | ★★★ (외부 API) | Monthly | §4 4-up Comment 행에 1줄 |
| 7 | **베트남 공장 BSCI/SA8000 audit score + 이직률** | ESG | ★★★★ | ★★★★ (자체 MES) | Quarterly | §3 공급망 헬스에 1행 |
| 8 | **해외 판매 (면세점·역직구·중국·일본)** GMV·매장수 | 해외 | ★★★★ | ★★ (자체+세관) | Monthly | §6 채널성과 신규 컬럼 |
| 9 | **인당 매출·인당 영업이익** (productivity) | HR | ★★★ | ★★★★★ (재무) | Quarterly | §7 재무 옆 1줄 |
| 10 | **EU DPP/ESPR·한국 ISSB 의무화 임박 알림** | ESG/거시 | ★★★ | ★★★★★ (정책) | Quarterly | §8 거시 부록 |

---

## 1. 디자인·MD·상품기획 KPI

### 1-1. 신상품 적중률 (New Product Hit Rate) ★★★★★

- **정의**: 신상품 입고 후 N일 내 sell-through가 목표선을 넘은 SKU 비율
- **산식**: `(목표 ST율 달성 SKU 수) / (신상품 SKU 총 수)`. 통상 **30일/60일/90일** 3 cut으로 측정.
- **글로벌 벤치마크**:
  - 강한 컬렉션 기준: 30일 40% / 60일 65% / 90일 80% sell-through (Digital Fashion Academy)
  - Zara: 마크다운 비중 15~20% (업계 평균 30~40%), 연 재고회전 12회 (업계 3~4회)
- **한국 벤치마크**: 한섬·신세계인터내셔날 외감 보고서 5년 영업이익률 지속 하락 — **트렌드 적중률 저하가 원인**으로 지목됨 (시사저널e).
- **인동에프엔 적용**: SHESMISS/LIST/SISTINA 3브랜드 각각 신상품 sell-through 30/60/90일 곡선을 4-up 슬라이드(§3-④)에 행으로 추가. SISTINA(★)는 특히 적중률이 신브랜드 검증 핵심.
- **데이터 소스**: POS + ERP 입고 데이터 조인
- **우선순위**: ★★★★★ (Weekly)

### 1-2. 컬렉션 라이프사이클 — 단계별 매출 분포 ★★★★

- **정의**: 정상가 → 1차 세일(10~20%) → 2차 세일(30~40%) → 클리어런스(50%+) 매출 비중
- **산식**: 각 단계별 `매출 / 시즌 전체 매출 × 100%`. **정상가 비중**(Full-Price Sell-Through, FPST)이 핵심 KPI.
- **글로벌 벤치마크**: Inditex FPST 약 80%, H&M 약 60% (Coresight Research)
- **인동에프엔 적용**: SISTINA는 신브랜드라 정상가 비중 50%+ 목표, SHESMISS는 70%+ 목표 등 브랜드별 기준선 설정 가능
- **데이터 소스**: POS의 할인율 필드 + 시즌 코드
- **우선순위**: ★★★★ (Weekly — 이미 §7-5-2 특약매입에 일부 시그널이 있지만 별도 차트 권장)

### 1-3. 트렌드 픽업률 / 트렌드 적중률 ★★★

- **정의**: 시즌 트렌드 키워드(예: '오버사이즈 블레이저', '버건디')를 자사 신상품 라인업에 포함시킨 비율, 그리고 그 트렌드 상품의 sell-through
- **벤치마크**: 한국 패션 평론은 정성 평가 위주. 정량화는 네이버 데이터랩 검색량 vs 자사 매출 상관 분석으로 가능.
- **인동에프엔 적용**: 분기 1회, 시즌 트렌드 키워드 10개 → 자사 라인업 매칭률 + 그 SKU 매출 기여
- **데이터 소스**: 트렌드 외부 자료(WGSN·삼성디자인넷·Stylus) + 자사 ERP 상품 마스터
- **우선순위**: ★★★ (Quarterly)

### 1-4. SKU 효율성 (SKU productivity) ★★★

- **정의**: 평균 SKU당 매출, SKU 수 vs 매출 ratio
- **산식**: `시즌 매출 / 시즌 출시 SKU 수`
- **글로벌 벤치마크**: Zara biweekly 상품 갱신 — SKU 수는 많지만 평균 SKU 회전이 빠름 (12회/년)
- **인동에프엔 적용**: SISTINA의 SKU 수가 매출 대비 과잉인지 점검. MD 효율성 측정.
- **데이터 소스**: ERP 상품 마스터 + POS
- **우선순위**: ★★★ (Monthly)

### 1-5. 보충(Replenishment) 의사결정 정확도 ★★★

- **정의**: 추가 발주한 SKU가 정상가에 모두 팔렸는지 비율
- **산식**: `(추가 발주 후 마크다운 없이 sold-out된 SKU) / (추가 발주된 SKU 총 수)`
- **인동에프엔 적용**: 베트남 직영공장 가동률과 직접 연결 — "수직통합의 가치"를 보충 정확도로 입증
- **데이터 소스**: ERP 발주 이력 + POS
- **우선순위**: ★★★ (Monthly)

---

## 2. 마케팅·브랜드 자산 KPI

### 2-1. 브랜드 인지도 (Aided / Unaided Awareness) ★★★

- **정의**: Aided = 브랜드 이름 제시 시 인지 비율 / Unaided = 자발적 회상
- **산식**: 분기 소비자 패널 조사 (오픈서베이·엠브레인 등)
- **글로벌 벤치마크**: Brand Tracker 표준 측정 — Statista의 Zara UK Aided Awareness 약 90%
- **한국 벤치마크**: 한섬 ('타임'·'마인'), 신세계인터내셔날 ('보브'·'스튜디오 톰보이')은 비공개
- **인동에프엔 적용**: SHESMISS/LIST/SISTINA 3브랜드 분기 1회 Aided/Unaided 트래킹. **SISTINA**(2021 신브랜드)는 인지도 성장 곡선이 본인 결정 검증의 핵심.
- **데이터 소스**: 오픈서베이 / 엠브레인 / 닐슨 패널 (분기 비용 약 1,000~3,000만원)
- **우선순위**: ★★★ (Quarterly)

### 2-2. NPS (Net Promoter Score) ★★★★

- **정의**: "친구에게 추천하시겠습니까?" 0-10점, Promoter(9-10) - Detractor(0-6) %
- **벤치마크**: 패션 리테일 typical NPS 30-50 (Drive Research)
- **인동에프엔 적용**: IDFmall 가입자 대상 분기 1회 + 백화점 매장 POS 영수증 QR로 측정
- **데이터 소스**: IDFmall 자체 설문 + 매장 키오스크
- **우선순위**: ★★★★ (Quarterly)

### 2-3. EMV (Earned Media Value) ★★★

- **정의**: 인플루언서·PR·UGC가 만들어낸 비유료 노출의 광고 환산가
- **산식**: `Impressions × CPM` (기본형) / 또는 Tribe Dynamics·Launchmetrics 방식
- **벤치마크**: 인플루언서 마케팅 1$당 평균 ROI $5.20~$5.78 (Influencer Marketing Hub 2026)
- **인동에프엔 적용**: 끌라베·헌치 등 신생 브랜드가 인플루언서로 빠르게 성장하는 트렌드. 인동에프엔도 3브랜드별 EMV 트래킹.
- **데이터 소스**: 직접 측정 어려움 → Modash·Influential·국내 캐스팅엔 등 외부 서비스
- **우선순위**: ★★★ (Monthly)

### 2-4. CAC vs LTV (브랜드·채널별) ★★★★

- **정의**: 신규 회원 1명 획득 비용 vs 그 회원의 12개월 누적 매출
- **벤치마크**:
  - 패션 DTC CLV: 24개월 $180~$340 (BestColorfulSocks)
  - LTV/CAC 건강 비율: 3:1 (적정), 4~6 (탁월)
- **인동에프엔 적용**: IDFmall 신규 회원 채널별(네이버 검색·인스타·카카오·KOL) CAC vs LTV. 마케팅 예산 ROI 의사결정 직접 영향.
- **데이터 소스**: IDFmall GA + 광고 플랫폼 + ERP
- **우선순위**: ★★★★ (Monthly)

### 2-5. 인플루언서·앰배서더 ROI ★★★

- **정의**: 인플루언서·셀럽 협업의 매출 기여·매출 lift
- **산식**: 인플루언서 전용 코드 / UTM 추적 매출 / 또는 협업 전후 매출 대비
- **벤치마크**: 한국 여성복은 신뢰도 높은 셀럽·아나운서 캐스팅이 핵심 (끌라베 사례)
- **인동에프엔 적용**: 분기별 인플루언서 협업 캠페인 1개씩 ROI 측정
- **데이터 소스**: 광고 플랫폼 + 인플루언서 계약서
- **우선순위**: ★★★ (Quarterly)

---

## 3. 디지털·SNS·콘텐츠

### 3-1. SNS 팔로워·인게이지먼트 (브랜드별) ★★★

- **정의**: 인스타·유튜브·틱톡 팔로워 수, 게시물 평균 인게이지먼트율(좋아요+댓글/팔로워)
- **벤치마크**: 패션 인스타 평균 인게이지먼트 1~3%, 우수 5%+
- **인동에프엔 적용**: 4-up 슬라이드(§3-④)의 Comment 행에 "SHESMISS IG 12.3만 명 (+2.1% WoW), 평균 ER 2.4%" 정도 1줄
- **데이터 소스**: Meta Business Suite, YouTube Analytics, TikTok 분석
- **우선순위**: ★★★ (Monthly)

### 3-2. SNS → 자사몰 유입 funnel ★★★★

- **정의**: 인스타 게시물·릴스·광고 → IDFmall 방문 → 가입 → 구매 단계별 전환율
- **벤치마크**: 패션 e-commerce CVR 1.5~2.5%
- **인동에프엔 적용**: 이미 §5 자사몰 funnel 있음 — **SNS 채널을 funnel 상단 source로 명시적 분리**해서 트래픽 출처별 CVR/AOV 표시
- **데이터 소스**: GA + Meta Pixel + 카카오 픽셀
- **우선순위**: ★★★★ (Weekly — §5 확장)

### 3-3. 검색 트렌드 / 검색 점유율 (네이버 데이터랩) ★★★

- **정의**: '쉬즈미스'·'리스트'·'시스티나' vs 경쟁 브랜드 키워드 검색량 비교 (Share of Search Volume, SoSV)
- **벤치마크**: SoSV는 6개월 선행 시장점유율 예측 지표 (Les Binet 연구)
- **인동에프엔 적용**: 4-up 슬라이드(§3-④) 또는 §8 거시 부록에 브랜드별 SoSV 추이 1차트
- **데이터 소스**: 네이버 데이터랩 (무료) + 구글 트렌드
- **우선순위**: ★★★ (Monthly)

### 3-4. 라이브커머스 매출·참여율 ★★★

- **정의**: 네이버 쇼핑라이브·카카오쇼핑라이브 1회 매출, 시청자수, 구매 전환
- **벤치마크**:
  - 한국 라이브커머스 시장 2024년 25조원 (KISA)
  - 네이버 쇼핑라이브 점유 84.1%, 카카오 54.6%, 쿠팡 47.6%
  - 네이버 LC 2023년 8천억 → 2026년 2.8조 전망
- **인동에프엔 적용**: 월 라이브커머스 횟수·매출·평균 시청자·CVR 트래킹. 자사몰과 별도 채널로 §6 채널성과에 1행.
- **데이터 소스**: 네이버 쇼핑라이브 백오피스 + 카카오 셀러센터
- **우선순위**: ★★★ (Monthly)

### 3-5. AI Try-on / 가상 피팅 / Generative AI 도입률 ★★

- **정의**: 자사몰에서 가상 피팅·AI 추천·AI 어시스턴트 사용 회원 비중
- **벤치마크**: Goldman Sachs 가상 피팅 시장 2028년 $12B. 도입 brand는 CVR +40%, 반품 -50% (Style3D AI)
- **인동에프엔 적용**: 분기 1회 산업 트렌드 모니터링 (도입 여부는 별도 의사결정). §8 거시 부록.
- **데이터 소스**: 산업 보고서 (BoF, Style3D, Vogue Business)
- **우선순위**: ★★ (Quarterly, 산업 모니터링용)

---

## 4. 고객 경험·VOC·반품

### 4-1. 반품률 + 반품 사유 분석 ★★★★★

- **정의**: 채널별·브랜드별·카테고리별 반품률, 반품 사유 Top 5
- **벤치마크**:
  - 한국 온라인 의류 반품률 약 30% (Realpacking, 한섬·신성통상·LF 비교 분석)
  - Z세대 반품 빈도 증가 (한국섬유신문, 오픈서베이 2025)
  - 글로벌: AI 가상피팅 도입 시 반품 -50% (Style3D)
- **인동에프엔 적용**: 자사몰·백화점 분리, 사유 Top 3 (사이즈/색감/품질). **마진 직접 영향** → Weekly 본문급.
- **데이터 소스**: IDFmall 반품 DB, CS 티켓 분류, 백화점 POS 반품 코드
- **우선순위**: ★★★★★ (Weekly — §5 자사몰 funnel 다음 행)

### 4-2. CSAT (고객 만족도) ★★★

- **정의**: 구매 후 5점 척도 만족도
- **벤치마크**: 한국 패션 CSAT 4.2~4.5/5.0 평균
- **인동에프엔 적용**: IDFmall 자동 발송 설문 (구매 7일 후), 매장은 영수증 QR
- **데이터 소스**: 자체 설문 시스템
- **우선순위**: ★★★ (Monthly)

### 4-3. 리뷰 평점 + 부정 리뷰 비율 ★★★

- **정의**: 평균 별점, 1~2점 리뷰 비중, 부정 키워드 (사이즈·품질·배송 등) 빈도
- **인동에프엔 적용**: IDFmall + 카카오톡 채널 + 인스타 댓글 종합. AI 자연어 처리로 키워드 클러스터링.
- **데이터 소스**: IDFmall 리뷰 + 외부 채널 크롤링
- **우선순위**: ★★★ (Monthly)

### 4-4. CS 응대 시간 + 해결률 ★★

- **정의**: 평균 응대 시간(First Response Time), 1회 해결률(First Contact Resolution)
- **벤치마크**: 우수 e-commerce FRT < 4시간, FCR > 70%
- **인동에프엔 적용**: 분기 모니터링
- **데이터 소스**: 채널톡·카카오 비즈니스·자체 CS 시스템
- **우선순위**: ★★ (Quarterly)

### 4-5. 회원 등급별 LTV / 휴면률 / 이탈률 ★★★★

- **정의**: VIP/우수/일반 등급별 평균 12개월 매출, 6개월 미구매 휴면 회원 비율, 90일 이탈률
- **벤치마크**:
  - 한섬 VVIP 기준 연 1,000만원 이상
  - 무신사 신규 등급 '레벨 9 블랙다이아몬드' 누적 포인트 1억점 (2025년 7월 도입)
  - 패션 DTC 90일 재구매율 20~35%, 연 retention 20~30%
  - 패션 DTC LTV/CAC 적정 3:1, 우수 4~6
- **인동에프엔 적용**: IDFmall 회원 등급(가설: 5단계) × 채널 매트릭스. 등급별 LTV 추이 6-12 차트. 휴면 회원 재활성화 캠페인 ROI.
- **데이터 소스**: IDFmall CRM
- **우선순위**: ★★★★ (Monthly — §5 funnel과 함께)

---

## 5. ESG·지속가능성 정량지표

### 5-1. GHG Scope 1·2·3 배출량 ★★★

- **정의**: Scope 1 (직접 배출, 자체 보일러 등), Scope 2 (구매 전력), Scope 3 (가치사슬 — 원자재·물류·판매·폐기 포함)
- **벤치마크**:
  - H&M 2025: Scope 1+2 -41%, Scope 3 -34.6% (vs 2019)
  - Inditex 2025: 총 12.7B kg CO2e (Scope 3가 12.6B로 99%+)
  - 패션업 Scope 3는 전체의 95~98% 차지가 일반적
- **한국 규제**: 2028 사업연도부터 자산 30조 이상 코스피 ISSB 의무공시, 2029 10조 이상, 2033 전체. Scope 3는 3년 유예. **인동에프엔은 비상장 외감 → 의무 대상 아님**, 단 B2B·해외 진출 시 요구받음.
- **인동에프엔 적용**: 베트남 공장의 Scope 1+2 측정(전력·연료), 면화·합섬 원자재 Scope 3 추정. 분기 1회 트래킹, 연간 1회 보고서 외부 공개 검토.
- **데이터 소스**: 베트남 공장 MES + 전력공사 청구서 + 원자재 LCA DB
- **우선순위**: ★★★ (Quarterly — 산업 표준 진입, 해외 진출의 entry ticket)

### 5-2. 재활용 소재 / 친환경 소재 비율 ★★★

- **정의**: 전체 사용 원단 중 GRS·OCS·BCI 등 인증 소재 비율
- **벤치마크**:
  - H&M 2025: 91% 재활용·지속가능 소재, 그 중 32% 재활용
  - Inditex 2025: 88% 저영향 소재, 47% 재활용, 30% 유기·재생
- **인동에프엔 적용**: 모토에 '지속가능성' 포함됨에도 정량 지표 없음. 분기 1회 비중 추적.
- **데이터 소스**: 원단 구매 데이터 + 인증서
- **우선순위**: ★★★ (Quarterly)

### 5-3. 베트남 공장 노동·안전 KPI (BSCI / SA8000) ★★★★

- **정의**: BSCI(amfori) 또는 SA8000 audit score, 산업재해율, 이직률, 평균 임금 vs 현지 최저임금
- **벤치마크**:
  - BSCI audit 9개 영역 (단결권·차별·임금·노동시간·산보·아동노동·강제노동·환경·윤리)
  - SA8000 2026 신판 발표 — 글로벌 기준 강화
  - 베트남 공장 인증 사례: Thai Son S P, Capital World Group (SA8000), Girlfriend Collective도 사용
- **인동에프엔 적용**: **직영공장이라 audit 통제 가능** — 본인 의사결정의 ESG 검증. 분기 1회 score + 이직률·재해율.
- **데이터 소스**: 자체 HRIS + 외부 audit (분기 또는 연 1회)
- **우선순위**: ★★★★ (Quarterly — §3 공급망 헬스 1행 추가)

### 5-4. ESG 평가 등급 (MSCI ESG / Sustainalytics / KCGS) ★★

- **정의**: 외부 ESG 평가기관 등급 (AAA~CCC, 1~5 단계 등)
- **벤치마크**: 비상장은 평가 대상 제한적. 한국 ESG 기준원(KCGS)는 상장사 위주.
- **인동에프엔 적용**: 비상장이라 평가 대상 아닌 경우 다수. **자체 ESG 보고서 (연 1회)** 발간으로 대체 권장.
- **데이터 소스**: KRX ESG 포털 동종사 벤치마크 (한섬·신세계인터내셔날·LF·F&F 비교)
- **우선순위**: ★★ (Annual)

### 5-5. EU DPP / ESPR 대비 + 한국 ISSB 일정 ★★★

- **정의**: 디지털제품여권(DPP), 미판매 의류 폐기 금지(2026년 7월 대형 brand 시작), 한국 ISSB 의무공시 (2028~)
- **벤치마크**:
  - EU ESPR: 2026년 7월 DPP 레지스트리 의무, 텍스타일 적용 2027~
  - 한국 ISSB: Scope 3 3년 유예, 30조→10조→전체 단계 적용
  - 한국 패션 수출 시 EU/중국/미국 ESG 요구 사항 충족 필수
- **인동에프엔 적용**: 비상장·국내 위주라 ISSB 의무 대상 아님. 하지만 **글로벌 공급망 확장 시 entry ticket** — 분기 1회 정책 동향 모니터링.
- **데이터 소스**: 금융위·산업부 보도자료, EU Commission 공식 사이트
- **우선순위**: ★★★ (Quarterly, §8 거시 부록)

---

## 6. 해외 진출 (판매) KPI

### 6-1. 해외 판매 채널별 GMV·매장수 ★★★★

- **정의**: 면세점·역직구·중국(티몰·타오바오·도우인)·일본(라쿠텐·조조)·동남아(쇼피)·미국(아마존) 각각 매출, 매장수, 객단가
- **벤치마크**:
  - F&F MLB: 중국 2022년 ~$1B, 2024년 해외 매출 1조원+ (2025년 2조 목표)
  - F&F Discovery Expedition: 중국 2025년 +100 매장 목표
  - 한섬: 글로벌 진출 강화 보도 (2025)
- **인동에프엔 적용**: 보도상 '글로벌 공급망 강화'만 강조 — **'글로벌 판매'는 측정 KPI 부재**. 신설 필요. §6 채널성과에 '해외' 컬럼 분리.
- **데이터 소스**: 자체 ERP + 외부 채널 백오피스 + 세관 수출 신고
- **우선순위**: ★★★★ (Monthly — §6 신규 행)

### 6-2. 해외 동종사 벤치마크 (해외 매출 비중) ★★★

- **정의**: 한섬·신세계인터내셔날·LF·F&F·한세실업의 해외 매출 비중 vs 인동에프엔
- **벤치마크**: F&F 해외 매출 비중 약 50%+ (MLB 효과). 한세실업은 OEM이라 별도. 한섬·신세계·LF는 한자릿수.
- **인동에프엔 적용**: 분기 1회 동종사 IR 자료 정리하여 §8 부록 또는 분기 회고에 반영
- **데이터 소스**: 동종사 사업보고서·DART
- **우선순위**: ★★★ (Quarterly)

### 6-3. K-fashion 해외 채널 점유 ★★

- **정의**: 면세점 채널(롯데·신라·신세계 면세) 의류 매출 점유, 중국 라이브 (도우인·콰이쇼우) 매출
- **벤치마크**: 중국 면세 시장 보고서 (LinkedIn 2025), F&F MLB의 도우인·티몰 성공 사례
- **인동에프엔 적용**: 글로벌 전략 결정 시 진입 채널 우선순위 판단용
- **데이터 소스**: 외부 보고서 (KOTRA·산업통상자원부)
- **우선순위**: ★★ (Quarterly)

---

## 7. 사람·조직 (HR 정량)

### 7-1. 디자이너·MD 이직률 ★★★★

- **정의**: 디자이너·MD 직군의 연간 자발적 이직률
- **벤치마크**: 한국 패션업 디자이너 평균 이직률 추정 15~25% (정확한 공개 통계는 없으나 산업 통념상 일반 사무직 대비 1.5~2배 높음)
- **인동에프엔 적용**: CEO 페르소나에 "인력 안정 = 품질·납기 안정" 가설 명시 — 이직률은 **본인 가치관의 정량 검증** 지표. 직군별 분리(디자이너·MD·생산·CS).
- **데이터 소스**: 자체 HRIS
- **우선순위**: ★★★★ (Quarterly — §8 부록에서 본문 승격)

### 7-2. 인당 매출·인당 영업이익 (Productivity) ★★★

- **정의**: 매출 / 임직원수, 영업이익 / 임직원수
- **인동에프엔 현재**: 매출 3,015억 / 직원 약 243~429명 (출처 편차) = **인당 매출 약 7~12억원** (CSI Market 글로벌 Apparel Retail 평균 약 $200K = 2.7억 수준의 4~5배. 단 한국 패션은 SG&A 비중이 높아 직접 비교 어려움)
- **한국 벤치마크**: 한섬·신세계·LF는 매출 대비 판관비 50%+ (소비자가만드는신문) — 인당 영업이익이 더 의미 있는 지표
- **인동에프엔 적용**: 분기 1회 동종사 비교 막대 차트
- **데이터 소스**: 재무 + HRIS
- **우선순위**: ★★★ (Quarterly)

### 7-3. 핵심 인재 retention (9-box) ★★★

- **정의**: 성과 × 잠재력 9분면, 우상단(High-High) 인재의 retention 비율
- **벤치마크**: GE 인재 매트릭스 표준, IBM·삼성 등 도입
- **인동에프엔 적용**: 디자이너 수석·MD 팀장·생산 키맨 등 20~30명 분기 평가
- **데이터 소스**: 자체 HRIS + 인사평가
- **우선순위**: ★★★ (Semi-annual)

### 7-4. 채용 cost-per-hire / time-to-hire ★★

- **정의**: 1명 채용 평균 비용·소요일수
- **벤치마크**: 패션 신입 채용 약 200~500만원, 경력 디자이너 1,000만원+
- **인동에프엔 적용**: 분기 1회 트래킹
- **데이터 소스**: HRIS + 채용 플랫폼 청구서
- **우선순위**: ★★ (Quarterly)

### 7-5. DE&I 지표 (여성 임원 비율, 출산·육아 복귀율) ★★★

- **정의**: 임원 중 여성 비율, 육아휴직 후 복귀율, 평균 근속
- **벤치마크**: 한국 ESG-S(Social) 평가 핵심 항목
- **인동에프엔 적용**: 여성복 회사 + 출산축하금 1,000만원·육아수당 월 110만원 등 복지 → **여성 친화 정량 지표화**가 자연스러운 강점 노출 기회. 연 1회 보고서.
- **데이터 소스**: 자체 HRIS
- **우선순위**: ★★★ (Annual, ESG 보고서)

---

## 8. 산업·기술 트렌드 (CEO가 알아야 할 거시)

### 8-1. 면화·합섬·운임 시황 ★★★

- **정의**: 면화 ICE futures (¢/lb), 폴리에스터·나일론 가격, 컨테이너 운임 (SCFI)
- **벤치마크**:
  - USDA 2026/27 면화 평균 73 ¢/lb 전망, ICE 2026 March 65.35 / July 66.36 (2025년 12월 기준)
  - 폴리에스터: 유가 연동 변동성, 면화 vs 폴리 가격 우위 변동
  - 베트남 인건비: 글로벌 의류 sourcing 핵심 (IMARC Group)
- **인동에프엔 적용**: §7-5-5 환율·면화 민감도에 이미 포함 — **컨테이너 운임 (SCFI), 폴리에스터** 추가 권장
- **데이터 소스**: USDA FAS, FRED, EmergingTextiles, SCFI 지수
- **우선순위**: ★★★ (Monthly, §7 확장)

### 8-2. 라이브커머스·소셜 커머스 시장 ★★★

- **정의**: 한국 라이브커머스 시장 규모·플랫폼별 점유, 자사 진입 ROI
- **벤치마크**: 2024년 25조원, 네이버 84.1% 등 (위 3-4 참조)
- **인동에프엔 적용**: 위 §3-4 라이브커머스 항목과 통합
- **우선순위**: ★★★

### 8-3. Resale / 중고 시장 ★★

- **정의**: 한국 차란·번개장터·중고나라 패션 거래량, 글로벌 Vestiaire·ThredUp 동향
- **벤치마크**: 글로벌 secondhand 2029년 $367B 전망 (smeuse 2026). Vestiaire $1.7B 가치, 디지털 제품 여권 통합.
- **인동에프엔 적용**: 분기 1회 산업 트렌드 모니터링. SISTINA(시크 컨템포러리)는 resale 친화적 — 향후 재판매 보장 프로그램 검토 여지.
- **데이터 소스**: 산업 보고서
- **우선순위**: ★★ (Quarterly, §8 거시)

### 8-4. AI 패션 (생성·디자인·수요 예측) ★★

- **정의**: Zara·H&M 등의 AI Try-on, AI 디자인 어시스턴트, 수요 예측 알고리즘
- **벤치마크**: AI in Fashion 11개 use case (Aimultiple 2026), 가상 피팅 도입 시 CVR +40%, 반품 -50%
- **인동에프엔 적용**: 자사몰 도입 검토용 ROI 분석. 분기 1회 트렌드 업데이트.
- **우선순위**: ★★ (Quarterly)

### 8-5. 옴니채널 / O4O 트렌드 ★★★

- **정의**: 백화점·자사몰·매장 통합 데이터, O4O(매장 픽업·전시) 매출 기여
- **벤치마크**:
  - 신세계백화점 2025년 자사몰 결제 도입 (계열 분리)
  - 한섬 더한섬닷컴 + H 패션몰 + EQL 연 4,000억+
  - LF 'LF몰 스토어' 픽업 운영
- **인동에프엔 적용**: 백화점 매장 + IDFmall 회원 통합 (Click & Collect) 가능성 분기 1회 점검
- **데이터 소스**: 자체 검토
- **우선순위**: ★★★ (Quarterly)

### 8-6. 환경 규제 (EU CSRD / ESPR / 한국 자원순환법) ★★★

- **정의**: §5-5 참조. CEO 거시 모니터링용.
- **우선순위**: ★★★ (Quarterly)

---

## 9. 종합 권고: v4 구조에 추가/조정할 항목 표

| # | 항목 | 영역 | Cadence | 우선순위 | v3 어디에 추가/조정 | 근거 |
|---|------|------|---------|---------|------------------|------|
| A | 신상품 sell-through 30/60/90일 곡선 | 상품기획 | Weekly | ★★★★★ | §3-④ 4-up 슬라이드 행 추가 | Zara FPST 80% 벤치 / 한국 FPST 부재 |
| B | 반품률 + 사유 Top 3 (자사몰·매장 분리) | 고객경험 | Weekly | ★★★★★ | §5 자사몰 funnel 다음 신규 | 한국 온라인 반품률 30% (Realpacking) |
| C | 마크다운 폭 + 정상가 sell-through 비중 | 재무 | Weekly | ★★★★★ | §7 한국특화 5종 → 6종 | Inditex 마크다운 15~20% vs 평균 30~40% |
| D | 회원 등급별 LTV·재구매율·휴면률 | 디지털 | Monthly | ★★★★ | §5 funnel 옆 6-12 차트 | 한섬 VVIP/무신사 레벨9 트렌드 / DTC 3:1 LTV/CAC |
| E | 디자이너·MD 이직률 + 핵심인재 retention | HR | Quarterly | ★★★★ | §8 → 본문 승격 | 페르소나 "인력=품질" 가설 검증 |
| F | 해외 판매 GMV·매장수 (채널 분리) | 해외 | Monthly | ★★★★ | §6 채널성과 신규 컬럼 | "글로벌 공급망" 보도 vs 판매 KPI 부재 / F&F 벤치 |
| G | 베트남 공장 BSCI/SA8000 + 이직률·재해율 | ESG/공급망 | Quarterly | ★★★★ | §3 공급망 헬스 1행 추가 | 직영 통제 가능 + 해외 진출 entry ticket |
| H | CAC vs LTV (브랜드·채널별) | 마케팅 | Monthly | ★★★★ | §5 funnel 보강 | DTC 표준 3:1, 마케팅 예산 ROI 직접 |
| I | NPS (브랜드·자사몰 분리) | 고객경험 | Quarterly | ★★★ | §5 funnel 옆 박스 | 패션 NPS 30~50 표준 (Drive Research) |
| J | SNS 인게이지먼트 + 검색 점유율(SoSV) | 디지털 | Monthly | ★★★ | §3-④ 4-up Comment 행 1줄 | SoSV는 6개월 선행 점유율 지표 |
| K | 라이브커머스 매출·시청자·CVR | 디지털 | Monthly | ★★★ | §6 채널성과 1행 | 한국 LC 시장 25조, 네이버 84% |
| L | 인당 매출·인당 영업이익 | HR | Quarterly | ★★★ | §7 재무 옆 1줄 | 동종사 판관비 50% / 벤치 비교 |
| M | GHG Scope 1+2 (베트남) + 재활용 소재 비율 | ESG | Quarterly | ★★★ | §8 부록 (연 1회 보고서 별도) | 글로벌 사실상 표준, B2B entry |
| N | 컬렉션 라이프사이클 (정상가/세일/클리어런스) | 상품기획 | Weekly | ★★★★ | §7 한국특화에 통합 | FPST 80% (Inditex) vs 60% (H&M) |
| O | 보충(Replenishment) 의사결정 정확도 | 상품기획 | Monthly | ★★★ | §3 공급망 헬스 1행 | 베트남 직영의 가치 검증 |
| P | 트렌드 픽업률 (네이버 데이터랩 매칭) | 상품기획 | Quarterly | ★★★ | §8 부록 | 한국 패션 적중률 저하 (시사저널e) |
| Q | EU DPP/ESPR + 한국 ISSB 일정 | 거시 | Quarterly | ★★★ | §8 거시 부록 | 2026.7 DPP 레지스트리 / 2028 ISSB |
| R | 면화·폴리에스터·운임(SCFI) | 거시 | Monthly | ★★★ | §7 한국특화 확장 | 환율 외 원자재 변동성 |
| S | EMV·인플루언서 ROI | 마케팅 | Quarterly | ★★★ | §8 부록 | 신생 브랜드 핵심 성장 동력 |
| T | DE&I (여성 임원 비율·복귀율) | HR/ESG | Annual | ★★★ | 연간 ESG 보고서 | 여성복 회사 강점 노출 기회 |
| U | 옴니채널 (백화점+자사몰 통합) 진척 | 거시/전략 | Quarterly | ★★★ | 분기 회고 | 신세계·한섬·LF 모두 도입 중 |
| V | AI Try-on·Resale 트렌드 모니터링 | 거시 | Quarterly | ★★ | §8 부록 | 산업 dirupt 신호 |

### v4 구조 권장 (간략)

v3의 8단 구조를 유지하되 다음 5가지를 가시화:

1. **§3 재고·공급망 헬스에 "수직통합 1행" 추가** — Replenishment 정확도 + BSCI score (Operator 페르소나 강화)
2. **§4 4-up 슬라이드를 6행으로 확장** — (현 5행) + 신상품 ST 30일 + SNS ER/SoSV 1줄
3. **§5 자사몰 funnel 옆 "고객 패널"** 신설 — 반품률/사유, NPS, 등급별 LTV (Weekly)
4. **§7 한국특화 5종 → 7종** — 마크다운 폭, 컬렉션 라이프사이클 추가 (FPST가 마진의 핵심)
5. **§8 부록 → "경영 모니터" 정규화** — HR 본문 승격, 해외 판매 별도 컬럼, ESG 분기 정량, EU/한국 규제 일정

---

## 10. 출처 (URL 분류)

### 글로벌 벤치마크 (Inditex·H&M·Zara·Fast Retailing·F&F)
- [Fashion Big Three Comparative Analysis (Fashionbi)](https://www.fashionbi.com/insights/fast-fashion-s-big-three-a-comparative-analysis-of-h-m-inditex-and-fast-retailing)
- [Apparel Specialty Retail: H&M vs Inditex (Coresight Research)](https://coresight.com/research/head-to-head-in-apparel-specialty-retail-hm-vs-inditex-zara/)
- [Inditex Climate Transition Plan PDF](https://www.inditex.com/itxcomweb/api/media/450e8c9d-3266-4ffe-abb0-62fe206a188c/Inditex+Climate+Transition+Plan.pdf?t=1710345903031)
- [H&M Group Annual & Sustainability Report 2025](https://hmgroup.com/investors/annual-and-sustainability-report/)
- [Inditex Sustainability page](https://www.inditex.com/itxcomweb/es/en/sustainability)
- [MLB by F&F finds favor in China (KED Global)](https://www.kedglobal.com/retail/newsView/ked202305210001)
- [F&F to expand Discovery brand across Asia (KED Global)](https://www.kedglobal.com/fashion/newsView/ked202407290005)
- [How MLB Became China's Hottest Lifestyle Brand (WPIC)](https://wpic.co/blog/how-mlb-became-china-hottest-lifestyle-brand/)
- [Inditex - the golden standard in retail operational excellence (Ada Insights)](https://adainsights.com/blog/inditex-the-golden-standard-in-retail-operational-excellence)

### KPI·메트릭 표준
- [Digital Fashion Academy — Retail & E-commerce KPIs](https://blog.digitalfashionacademy.com/digital-fashion-performance-indicators/)
- [Apparel Retail KPIs Complete Guide (LogicERP)](https://www.logicerp.com/blog/apparel-retail-kpis-a-complete-guide-to-measuring-success-in-fashion-retail-with-key-performance-indicators/)
- [Fashion e-commerce KPIs (Peasy)](https://www.peasy.nu/blog/fashion-e-commerce-kpis-what-metrics-matter-most)
- [Brand KPIs for fashion online shops: Zara UK (Statista)](https://www.statista.com/study/146989/brand-kpis-for-fashion-online-shops-zara-in-the-uk%25E2%2580%258B/)
- [Apparel Retail Industry Efficiency Q4 2025 (CSI Market)](https://csimarket.com/Industry/industry_Efficiency.php?ind=1301)
- [Inventory Dashboard KPIs for Fashion Retail (StyleMatrix)](https://stylematrix.io/essential-inventory-kpis-retail-managers-must-track-using-a-modern-dashboard/)
- [Top 20 Fashion Brand Performance Benchmarking 2025 (BestColorfulSocks)](https://bestcolorfulsocks.com/blogs/news/fashion-brand-performance-benchmarking-statistics)
- [E-commerce Retention Rate Benchmarks 2026 (Finsi.ai)](https://www.finsi.ai/blog/ecommerce-retention-rate-benchmarks/)
- [Cohort Retention Analysis for DTC (Glencoyne)](https://www.glencoyne.com/guides/cohort-retention-analysis-dtc)
- [42 CLV statistics 2026 (Ringly)](https://www.ringly.io/blog/ecommerce-customer-lifetime-value-statistics-2026)

### 브랜드·마케팅 (NPS·EMV·Influencer)
- [EMV Definition & Use (AgencyAnalytics)](https://agencyanalytics.com/kpi-definitions/earned-media-value-emv)
- [EMV in Influencer Marketing (Kolsquare)](https://www.kolsquare.com/en/blog/earned-media-value-emv-a-essential-kpi-in-influence-marketing)
- [Brand Measurement Guide (Improvado)](https://improvado.io/blog/measuring-brand-value-key-metrics)
- [Brand Equity Analysis Guide (Umbrex)](https://umbrex.com/resources/ultimate-guide-to-company-analysis/ultimate-guide-to-marketing-analysis/brand-equity-analysis/)
- [Brand Awareness Survey Steps (Drive Research)](https://www.driveresearch.com/market-research-company-blog/7-steps-to-measure-brand-awareness-survey-company/)
- [Influencer ROI Calculator (MiniWebTool)](https://miniwebtool.com/influencer-roi-calculator/)
- [Critical KPIs in Influencer Marketing (NeoReach)](https://neoreach.com/ko/critical-kpis-influencer-marketing/)
- [Women's Fashion Influencer Marketing Guide (LTK)](https://company.shopltk.com/ultimate-guide-influencer-marketing-womens-fashion-brands)
- [2026 미국 인플루언서 요율표 (Calywire)](https://calywire.com/us-influencer-rates-2026-rate-card/)
- [국내 인플루언서 시딩 사례 (Spray)](https://spray.io/ko/blog/influencer-marketing-example-kr)
- [패션비즈 — 2026 이머징 브랜드](https://fashionbiz.co.kr/article/223202)

### 한국 패션 산업·동종사
- [패션 대기업 신세계·한섬·LF 브랜드 리포지셔닝 (인사이트코리아)](https://www.insightkorea.co.kr/news/articleView.html?idxno=241224)
- [K-패션 다시 쓰다 — 한섬 (시사저널e)](https://www.sisajournal-e.com/news/articleView.html?idxno=419346)
- [신세계인터내셔날·LF·한섬 판관비 분석 (소비자가만드는신문)](https://www.consumernews.co.kr/news/articleView.html?idxno=658488)
- [한섬: 글로벌 진출과 투자 가치 (Goover Public Report)](https://seo.goover.ai/report/202508/go-public-report-ko-8b1b1607-e5ad-4206-968f-83d6838d9107-0-0.html)
- [한섬 VVIP 혜택 페이지](https://m.hfashionmall.com/public/member/membershipInfo/hs)
- [패션넷 — 섬유패션통계](https://www.fashionnet.or.kr/textile-fashion-industry-trend/textile-fashion-statistics/)
- [2025 한국 패션 산업 트렌드 (Goover)](https://seo.goover.ai/report/202506/go-public-report-ko-7ea340b1-04e0-475b-a57c-199e1339dc35-0-0.html)
- [29CM 1분기 거래액 33% 증가 (머니투데이)](https://www.mt.co.kr/living/2026/04/07/2026040709413913175)
- [InvestKOREA — Korean Fashion Industry Trends](https://www.investkorea.org/ik-en/bbs/i-308/detail.do?ntt_sn=488971)
- [Fashion Industry in South Korea (Fashionbi)](https://www.fashionbi.com/insights/fashion-industry-in-south-korea)

### 디지털·라이브커머스·옴니채널
- [패션비즈 — 25조 라이브커머스 시대](https://fashionbiz.co.kr/article/220348)
- [한국 라이브커머스 현황 (거북이 미디어)](https://gobooki.net/%ED%95%9C%EA%B5%AD-%EB%9D%BC%EC%9D%B4%EB%B8%8C-%EC%BB%A4%EB%A8%B8%EC%8A%A4-%ED%98%84%ED%99%A9/)
- [2025 온라인 쇼핑 트렌드 — 자사몰 입지 (오픈서베이)](https://blog.opensurvey.co.kr/article/online-shopping-2025-2/)
- [네이버 데이터랩 활용 가이드 (The Egg)](https://www.theegg.com/seo/korea/naver-data-lab-how-to-gain-insights-on-korean-search-trends/)
- [네이버/카카오/구글 데이터랩 비교 (AmPm Inside)](https://inside.ampm.co.kr/insight/1096)
- [신세계백화점 자사몰 결제 도입 (아시아경제)](https://www.asiae.co.kr/article/2025070915474909888)
- [무신사·29CM VVIP 등급 신설 (디지털투데이)](https://www.digitaltoday.co.kr/news/articleView.html?idxno=569011)
- [패션 이커머스 트렌드 2026 (Shopify Korea)](https://www.shopify.com/kr/blog/ecommerce-fashion-industry)
- [패션업종 퍼포먼스 마케팅 인사이트 (Openads)](https://www.openads.co.kr/content/contentDetail?contsId=18290)

### 고객·반품·VOC
- [의류 반품률 30% — 한섬·신성통상·LF 분석 (RealPacking)](https://www.realpacking.com/ko/blog/how-to-minimize-your-apparel-return-rate-losses)
- [Z세대 반품 — 개인화가 변수 (한국섬유신문)](https://www.ktnews.com/news/articleView.html?idxno=145974)
- [이커머스 반품율 관리 (꿈꾸는섬)](https://happist.com/569154/이커머스의-숙적-반품율-관리를-통한-이익-확대-방안)

### ESG / EU 규제 / 한국 ISSB
- [금융위 지속가능성 공시 로드맵 (Shin & Kim)](https://www.shinkim.com/kor/media/newsletter/3145)
- [국내 ESG 공시 도입 시사점 (Lexology)](https://www.lexology.com/library/detail.aspx?g=2acf2d5d-9c09-4d1f-9a60-896673f6a9fa)
- [기후공시 기준 및 정책 동향 (김·장)](https://www.kimchang.com/ko/insights/detail.kc?sch_section=4&idx=29410)
- [KRX ESG 포털](https://esg.krx.co.kr/)
- [EU DPP Practical Guide for Fashion (Trustrace)](https://trustrace.com/knowledge-hub/how-fashion-brands-can-prepare-for-the-eu-digital-product-passport-a-practical-guide-1)
- [ESPR Textile Crash Course (Carbonfact)](https://www.carbonfact.com/blog/policy/espr-textile)
- [EU Textile Regulations Overview (Carbonfact)](https://www.carbonfact.com/blog/policy/eu-regulations-for-textile-brands)
- [DPP & ESPR for Fashion 2026 (Seamless Source)](https://seamlesssource.com/digital-product-passport-for-fashion-guide-2026/)
- [SA8000 2026 Update (Testcoo)](https://www.testcoo.com/en/blog/sa8000-2026-social-responsibility-standard-update)
- [Vietnam Audit Standards: APSCA/SLCP/SEDEX/Higg (Testcoo)](https://www.testcoo.com/en/blog/compliance-and-audit-in-vietnam)
- [BSCI Audit Overview (TÜV Rheinland)](https://www.tuv.com/usa/en/bsci-supplier-audit.html)
- [SA8000 Certified Clothing Manufacturer in Vietnam (Thaisonsp)](https://thaisonsp.com/certificates-and-forms/sa-8000-certified-clothing-manufacturer-in-vietnam/)
- [신세계 ESG 보고서 2023 (KRX KIND)](https://kind.krx.co.kr/external/2024/08/22/000288/20240822000807/2023%20%EC%8B%A0%EC%84%B8%EA%B3%84%20ESG%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)
- [국내기업 ESG 업종별 가이드북 (대한상의)](https://www.korcham.net/FileWebKorcham/Esg/%EA%B5%AD%EB%82%B4%EA%B8%B0%EC%97%85%20ESG%EA%B2%BD%EC%98%81%20%EC%A7%80%EC%9B%90%EC%9D%84%20%EC%9C%84%ED%95%9C%20%EC%A3%BC%EC%9A%94%20%EC%97%85%EC%A2%85%EB%B3%84%20%EA%B0%80%EC%9D%B4%EB%93%9C%EB%B6%81_.pdf)

### 산업 트렌드 (AI·Resale·원자재)
- [2026 Fashion Tech Trends: AI Virtual Fitting (Style3D)](https://www.style3d.ai/blog/2026-fashion-tech-trends-the-rise-of-the-instant-ai-virtual-fitting-room/)
- [Top 11 AI in Fashion Use Cases 2026 (Aimultiple)](https://research.aimultiple.com/ai-in-fashion/)
- [Generative AI Virtual Try-On (BoF)](https://www.businessoffashion.com/articles/technology/how-generative-ai-is-improving-virtual-try-on/)
- [AI & Secondhand Fashion Market (Smeuse)](https://smeuse.org/posts/ai-fashion-resale)
- [Luxury Resale Market 2025-2030 — Vestiaire (Businesswire)](https://www.businesswire.com/news/home/20260106047735/en/Luxury-Resale-Market-Research-Report-2025-2030-The-RealReal-Vestiaire-Collective-Farfetch-Fashionphile-and-Rebag-Lead-With-AI-Driven-Authentication-and-Trust-Led-Online-Models---ResearchAndMarkets.com)
- [Fashion in 2026: AI, Resale, Social Commerce (Medium)](https://medium.com/@CheekyFit/how-ai-resale-and-social-commerce-are-reshaping-fashion-in-2026-0e740bb1ab4c)
- [USDA Cotton World Markets and Trade PDF](https://apps.fas.usda.gov/psdonline/circulars/cotton.pdf)
- [Cotton 2026 Outlook (Financial Content)](https://markets.financialcontent.com/wral/article/marketminute-2025-12-9-is-cotton-a-buy-analyzing-the-shifting-tides-of-ice-futures-and-market-sentiment-before-2026)
- [Vietnam Textile Market Size 2034 (IMARC)](https://www.imarcgroup.com/vietnam-textile-market)
- [Textile Cost Volatility Tracker April 2026 (Fibre2Fashion)](https://www.fibre2fashion.com/news/marketi-intelligence/textile-cost-volatility-tracker-april-2026-309883-newsdetails.htm)

### 한국 정책·옴니채널·플랫폼
- [O2O→O4O 무경계 쇼핑 진화 (비즈한국)](https://www.bizhankook.com/bk/article/22660)
- [Omni·O2O·O4O 트렌드 (THE K BEAUTY SCIENCE)](https://www.thekbs.co.kr/news/articleView.html?idxno=11015)
- [쿠팡·네이버 정체, 올리브영·무신사 성장 (모비인사이드)](https://www.mobiinside.co.kr/2026/03/05/retail-media/)
- [패션포스트 O2O와 옴니채널](https://fpost.co.kr/board/bbs/board.php?bo_table=fsp29&wr_id=3)
- [Business Focus 이커머스 판도 (삼정KPMG)](https://assets.kpmg.com/content/dam/kpmgsites/kr/pdf/2025/eri/business_focus/%EC%82%BC%EC%A0%95KPMG-%EB%B3%80%ED%99%94%ED%95%98%EB%8A%94-%EC%9D%B4%EC%BB%A4%EB%A8%B8%EC%8A%A4-%ED%8C%90%EB%8F%84-%EC%86%8D-%EC%A3%BC%EB%AA%A9%ED%95%B4%EC%95%BC-%ED%95%A0-%EB%B9%84%EC%A6%88%EB%8B%88%EC%8A%A4-%ED%8A%B8%EB%A0%8C%EB%93%9C-20251121.pdf.coredownload.inline.pdf)

---

## 11. 다음 단계 (v4 작업 backlog)

- [ ] 본 문서의 종합 권고 표 (§9 22개 항목)를 CEO/CSO와 1:1 검증 — **실제 추가 채택 12~15개로 압축**
- [ ] 데이터 소스 매핑 매트릭스 작성 — 어떤 KPI가 즉시 가능 / 신규 시스템 필요 / 외부 구매 필요인지 분류
- [ ] §3-④ 4-up 슬라이드를 6행으로 재설계 — 신상품 ST 30일 + SNS ER 1줄 추가
- [ ] §5 자사몰 funnel을 "고객 패널" 섹션으로 확장 — 반품/NPS/LTV 통합
- [ ] §7 한국특화 5종 → 7종으로 (마크다운 폭, 컬렉션 라이프사이클 추가)
- [ ] §6 채널성과에 '해외' 컬럼 추가 (면세점·역직구·중국·일본 분리)
- [ ] 분기 ESG 미니 보고서 양식 — 베트남 공장 BSCI/SA8000 score + Scope 1+2 + 재활용 소재 비율
- [ ] **CEO 인터뷰 질문 추가** — "다음 중 어느 항목이 가장 빠져있다고 느끼는가?" (§9 표를 카드 형태로 ranking 받기)
