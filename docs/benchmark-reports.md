# 패션업 CEO 보고서 벤치마크 리서치

> **목적**: (주)인동에프엔 CEO Summary Report 설계를 위해, 글로벌·국내 패션기업의 IR 보고서·내부 매니지먼트 보고서·KPI 대시보드·시각화 패턴을 1차 자료 기준으로 벤치마크한다.
> **범위**: 글로벌 5개사(Inditex / H&M / Fast Retailing / LVMH / Ralph Lauren) + 국내 5개사(한섬 / 신세계인터내셔날 / LF / F&F / 한세실업) + 컨설팅/SaaS 템플릿 + 시각화 베스트프랙티스 + 한국 특화 컨텍스트.
> **작성일**: 2026-05-24
> **선행 문서**: `docs/research-ceo-report-scope.md` (1차 KPI/구조 리서치)
> **방법**: WebSearch로 IR PDF 메타데이터·요약·기사 본문 확보. 1차 PDF 본문 직접 파싱은 환경 제약(WebFetch 비활성)으로 불가했으며, 본문 내 단언은 검색 결과에서 확인된 표현에 한정한다. 페이지 수·섹션 비중 등 1차 파싱이 필요한 정량 정보는 **(추정)** 또는 "1차 확인 필요"로 표기한다.

---

## Executive Summary (한 페이지 요약)

1. **글로벌 IR 표준 구조는 4단**: ① 1페이지 Highlight ② 손익/현금흐름 ③ 채널·지역·브랜드 세그먼트 ④ 전략/지속가능성/가이던스 + 부록. Inditex·H&M·Fast Retailing 모두 이 골격을 공유하며, 인동에프엔도 그대로 차용 가능.
2. **Amazon WBR이 운영 보고서의 글로벌 표준**: 매주 같은 포맷·같은 순서로 400~500개 지표를 본다. 핵심 시각화는 **"6-12 차트"**(좌: 6주 추세, 우: 12개월 추세). Input metric → Output metric → Financial metric 순서가 캐논.
3. **한국 동종사는 IR 자료 공개가 빈약**: 한섬·신세계인터내셔날은 사업보고서 PDF 외 별도 IR Deck 공개가 제한적이며, **DART 사업보고서 표준 11개 섹션 구조**(회사 개요 → 사업 → 재무 → 이사회 → 주주 → 임원 보수 등)가 사실상 한국 비상장/외감법인의 공통 골격이다.
4. **인동에프엔에 즉시 적용 가능한 4대 시사점**: ① 1p Executive Summary + 3개 메시지 고정 포맷, ② 브랜드(SHESMISS/LIST/SISTINA) × 채널(백화점/IDFmall/아울렛/베트남) **매트릭스 표 1장**, ③ Inditex식 "Store Sales + Online Sales + Channel-blind 매출" 3중 분리, ④ Amazon식 **6-12 차트**를 자사몰·재고에 적용.
5. **한국 특화 KPI 5종 필수 포함**: ① 백화점 판매수수료율(평균 23.7%, 신세계 최대 38%) ② 특약매입 vs 직매입 비중 ③ S/S vs F/W 매출 비중(F/W가 약 50%) ④ 아울렛/행사매장 매출 기여 ⑤ 베트남 직영공장 가동률 + 원화 환율 민감도.

---

## 1. 글로벌 IR / Annual Report 구조 분석

> **핵심 인사이트**: 글로벌 패션 리더 5사는 **"1p 하이라이트 → 매크로 트렌드 → 손익 → 현금흐름 → 채널·지역·브랜드 → 지속가능성 → 가이던스 → 부록"**의 동일한 8단 구조를 공유한다. 페이지 수만 다를 뿐 섹션 순서는 거의 일치한다.

### 1-1. 회사별 비교표

| 회사 | 대표 보고서 (FY24) | 페이지 수 | 섹션 순서 (요약) | 핵심 KPI | 시각화 특징 | URL |
|------|-------------------|----------|----------------|---------|------------|-----|
| **Inditex** | FY2024 Results (Press Pack) | ~30p (추정) | ① 1p Highlights ② Strategy ③ Sales (Store + Online + Geo) ④ Margins (GP/EBITDA/EBIT) ⑤ Net Cash ⑥ Stores Update ⑦ Sustainability ⑧ Outlook ⑨ Annexes (재무제표) | Sales(€38.6B), GP 57.8%, EBITDA €10.7B, EBIT €7.6B, Net income €5.9B, Net cash €11.0B, Online Sales(€10.2B, 26.7%), Footfall, Dividend(€1.68/sh) | 지역(Europe ex-Spain 50.6% / Americas 18.6% / Asia 15.7% / Spain 15.1%) Donut + Stacked Bar. 분기 YoY 라인. 매장 수 변동 Waterfall. 환율 영향 별도 표기. | [PDF](https://www.inditex.com/itxcomweb/api/media/2ca3e758-1c78-419f-8adf-7057207022e8/FY2024_Results.pdf) / [Press](https://www.inditex.com/itxcomweb/aq/en/press/news-detail/6f8d8db5-4d7a-43db-91b9-0c38065aec1e/fy2024-results) |
| **Inditex** | Annual Report 2024 (Consolidated Accounts & Directors Report) | ~300p+ (전체) | ① CEO Statement ② Group Profile ③ 8 Brands ④ People ⑤ Sustainability ⑥ Governance ⑦ Consolidated Financial Statements ⑧ Notes | 위 + ESG 비율(73% lower-impact fibres), 매장수(5,563), 인원 | 인포그래픽 위주, 인터랙티브 microsite ([static.inditex.com](https://static.inditex.com/annualreport2024/en/)) | [Annual Accounts](https://www.inditex.com/itxcomweb/api/media/84135f02-0208-4439-b9c0-b13608fbfeb5/Annualaccountsanddirectorsreport2024consolidated.pdf) |
| **H&M Group** | Full-year Report 2024 (Q4) | ~25p (추정) | ① CEO Comment ② Q4 Summary ③ Full-Year Summary ④ Sales by Region ⑤ Brand Portfolio ⑥ Sustainability ⑦ Outlook ⑧ Financial Statements (IAS 34) ⑨ Footnotes | Net sales(SEK 234.5B), GM 53.4%, Op profit (SEK 17.3B, +28% ex-JV), Op margin 7.4%, 지역별 매출/이익 | Region별 YoY 막대(서유럽 ‑4%, 동유럽 +10%, Asia/Oceania/Africa ‑4%, Americas ‑2%). Portfolio brands(Monki·Weekday·Afound 등) 별도 segment. | [PDF](https://hmgroup.com/wp-content/uploads/2025/01/H-M-Hennes-Mauritz-AB-Full-year-report-2024.pdf) / [Reports hub](https://hmgroup.com/investors/reports/) |
| **Fast Retailing** | FY2024 Results (10/10/2024) | ~40p (추정) | ① Highlights ② Consolidated P&L ③ Consolidated B/S & CF ④ UNIQLO Japan ⑤ UNIQLO International ⑥ GU ⑦ Global Brands ⑧ FY2025 Estimates ⑨ Dividend ⑩ Long-term Vision | Revenue(¥3.10T, +12.2%), Op profit(¥500.9B, +31.4%), Net income(¥371.9B, +25.6%), 세그먼트별 매출/영업이익(UQ JP ¥932B / GU ¥319B 등) | 세그먼트별 4-up 슬라이드(매출/이익/SSS/매장수). 지역별 Same-Store Sales 라인. 분기별 트렌드. | [PDF](https://www.fastretailing.com/eng/ir/library/pdf/20241010_results_en.pdf) / [Summary HTML](https://www.fastretailing.com/eng/ir/news/2410101800.html) |
| **LVMH** | 2024 Annual Results Press Release | ~15p (추정) | ① Highlights ② Group P&L ③ 5 Business Groups(Wines & Spirits / Fashion & Leather Goods / Perfumes & Cosmetics / Watches & Jewelry / Selective Retailing) ④ Cash Flow ⑤ Outlook | Revenue(€84.7B), Recurring Op income, FLG segment(€41B, ‑3%) | 세그먼트별 매출/이익 한 페이지 매트릭스. 브랜드별 코멘트 텍스트(Louis Vuitton, Dior, Celine 등). | [Press PDF](https://voda.akamaized.net/lvmh/2050279_678e15ab3de5a/files/Press%20Release%20-%20LVMH%20Annual%20results%202024.pdf) / [Page](https://www.lvmh.com/en/publications/lvmh-achieves-a-solid-performance-despite-an-unfavorable-global-economic-environment) |
| **Ralph Lauren** | Form 10-K FY2024 | ~120p (SEC 표준) | ① Business(세그먼트/유통/매장수) ② Risk Factors ③ Properties ④ Legal ⑤ MD&A ⑥ Financial Statements ⑦ Notes ⑧ Internal Controls ⑨ Executive Comp | 3 Reportable Segments(North America / Europe / Asia, Asia=24%), 채널 3종(Retail/Wholesale/Licensing), 매장 564 + Shop-in-shop 699 | SEC 표준 텍스트 위주. 부속 Investor Presentation에 채널·지역·카테고리 차트. | [10-K SEC](https://www.sec.gov/Archives/edgar/data/0001037038/000103703824000014/rl-20240330.htm) |

### 1-2. Inditex 보고서 구조 — 가장 모범적 사례 (디테일)

Inditex의 "FY Results" PDF는 패션업 IR 보고서의 **사실상 글로벌 표준**으로 평가받는다. 검색 결과에서 확인된 섹션 순서와 핵심 표현:

- **Page 1 — Headline Strip**: "Sales €38.6B (+7.5%), Net income €5.9B (+9.0%), Online sales €10.2B (+12.0%)" 같은 1줄 요약 + 6~8개 숫자.
- **Strategic priorities**: "improvement of fashion proposition and customer experience, clear focus on sustainability and taking care of talent" 같은 3~4문장.
- **Sales section**: Store sales(+5.9%), Online sales(+12.0%), Geographic breakdown(Europe ex-Spain 50.6% / Americas 18.6% / Asia & RoW 15.7% / Spain 15.1%) — 채널-blind 매출, 채널별 매출, 지역별 매출의 3중 분리.
- **Margins**: GP %, EBITDA, EBIT 각각 YoY 변화율 + bps 표시(예: "GM 57.8% +8 bps").
- **Net cash position**: 분기별 추이 + 배당 정책 연계.
- **Outlook / Guidance**: 다음 분기 일자별 비교가능 매출 가이드(예: "1~11 March +4% in constant FX").
- **Annexes**: 정식 Consolidated Income Statement / Balance Sheet / Cash Flow + 세그먼트 노트.

> 시사점: 1페이지에 모든 핵심 숫자를 압축한 뒤, 2페이지부터 같은 숫자를 단계적으로 풀어주는 **"Tell-Twice"** 구조. CEO/임원이 시간이 없으면 1페이지만 봐도 결론이 잡힌다.

### 1-3. Fast Retailing 구조 — 세그먼트 보고의 모범

Fast Retailing은 **세그먼트(UNIQLO Japan / UNIQLO International / GU / Global Brands)별로 한 슬라이드에 매출·영업이익·증감률·SSS(Same-Store Sales)·매장수·코멘트를 한꺼번에 표기**한다. 인동에프엔처럼 멀티브랜드 회사가 그대로 차용 가능한 포맷.

```
[UNIQLO JAPAN — FY2024]
Revenue:       ¥932.2B (+4.7% YoY)
Op profit:     ¥155.8B (+32.2% YoY)
SSS:           +4.0%
Stores:        801 (net +5)
Comment:       "Record annual performance ... Functional materials drove top sellers ..."
```

> 시사점: 인동에프엔 보고서에 **"브랜드별 4-up 슬라이드"**(SHESMISS/LIST/SISTINA + IDFmall) 한 페이지를 고정 섹션으로.

---

## 2. 한국 동종사 IR / 사업보고서 구조

> **핵심 인사이트**: 한국 상장 패션사는 **DART 사업보고서 11개 표준 섹션**(회사 개요 → 사업 → 재무 → 이사회 → 주주 → 임원 등 → 계열사 → 이해관계자 → 기타)을 따른다. IR Deck 별도 공개는 한섬·신세계인터내셔날 모두 분기 실적 단발성이 많고, 글로벌 사 대비 **시각화 밀도가 낮다**. 인동에프엔은 비상장 외감법인이므로 DART에는 감사보고서(재무제표 + 외부감사인 의견)만 올라간다.

### 2-1. 회사별 비교표

| 회사 | 대표 보고서 | 페이지 수 | 섹션 순서 | 핵심 KPI 노출 | 시각화 특징 | URL |
|------|-----------|----------|----------|--------------|------------|-----|
| **한섬** | 사업보고서 + 분기보고서(KIND) | 100~150p (사업보고서 표준) | DART 11개 섹션 표준 (회사 개요·사업·재무·임원·주주·이사회·계열사…) | 연결 매출(1조 4,853억, ‑2.9%), 영업이익(635억, ‑37%), Op margin 4.3% | 표 위주, 차트 적음. IRGO 페이지에 분기 실적·주가 차트 별도. | [DART 검색](https://dart.fss.or.kr/) / [IRGO](https://m.irgo.co.kr/IR-COMP/020000/) / [공식 IR](https://www.handsome.co.kr/ko/ir/financialInfo01.do) / [KIND 공시](https://kind.krx.co.kr/common/disclsviewer.do?method=search&acptno=20251114001431) |
| **신세계인터내셔날** | 사업보고서 (2024.03 공시) | ~150p | DART 표준 + **부문 3분할**(패션 라이프스타일 / 코스메틱 / JAJU 생활) | 매출 부문 비중(패션·라이프 67% / 코스메틱 33%), 분기별 부문 매출/영업이익 표 | 부문별 P&L 표, 브랜드 포트폴리오 텍스트 리스트(자체+수입). | [공식 PDF](https://img.sikorea.co.kr/files/upload2/noticePdf/202403/%5B%EC%8B%A0%EC%84%B8%EA%B3%84%EC%9D%B8%ED%84%B0%EB%82%B4%EC%85%94%EB%82%A0%5D%EC%82%AC%EC%97%85%EB%B3%B4%EA%B3%A0%EC%84%9C(2024.03.12)_1710898478589.pdf) / [IRGO](https://m.irgo.co.kr/IR-COMP/031430/) / [공식 IR](https://www.sikorea.co.kr/investors/resultsAndReports) |
| **LF** | 사업보고서 | ~150p | DART 표준 + **사업 다각화 4분할**(패션 76.4% / 식품 16.8% / 금융 6.3% / 기타) | 매출(약 2조 1,500억, +4.2%), 영업이익(약 1,400억, +5.7%) | 패션 부문 내 브랜드(닥스/헤지스/아떼) 코멘트 텍스트 중심. | [DART](https://dart.fss.or.kr/) / [기업현황](https://comp.wisereport.co.kr/company/c1010001.aspx?cmp_cd=093050) |
| **F&F** | 사업보고서 + 지주(F&F홀딩스) | ~120p+ | DART 표준 + **브랜드 라이선스 구조** 별도 기술 | 매출(MLB 65% / 디스커버리 23%), 1Q 매출 5,609억 +10.9%, 영업이익 1,535억 +24.2%, 영업이익률 27.4%(매우 높음) | 라이선스 사업의 특수성 — 지급수수료(연 4,535억) 별도 라인. 중국 법인 매출 별도 노출. | [F&F홀딩스 정보](https://comp.fnguide.com/SVO2/asp/SVD_Main.asp?gicode=A007700) |
| **한세실업** | 사업보고서(2024.03.20 / 2026.03.18) | ~150p | DART 표준 + **OEM/ODM 바이어 별도 기술**(TARGET, OLD NAVY, GAP, KOHL'S, WAL-MART, PINK, H&M 등) | 매출, 베트남·니카라과·인도네시아 법인별 생산, 과테말라 수직계열화(C&T 염색·ECOSPIN 방적·TEXOLLINI 인수) | 글로벌 생산 거점 지도, 바이어별 매출 비중. | [PDF 2024](https://www.hansae.com/upload/%ED%95%9C%EC%84%B8%EC%8B%A4%EC%97%85_%EC%82%AC%EC%97%85%EB%B3%B4%EA%B3%A0%EC%84%9C(2024.03.20).pdf) / [PDF 2026](https://www.hansae.com/upload/%5B%ED%95%9C%EC%84%B8%EC%8B%A4%EC%97%85%5D%EC%82%AC%EC%97%85%EB%B3%B4%EA%B3%A0%EC%84%9C(2026.03.18).pdf) / [IRGO](https://m.irgo.co.kr/IR-COMP/105630/) |

### 2-2. DART 사업보고서 11개 표준 섹션 (한국 비상장 외감 포함 공통)

DART 사업보고서·감사보고서는 「자본시장법 제159조」 기반 표준 양식으로, 한국 모든 외감법인이 다음 골격을 공유한다:

1. **회사의 개요** (지배구조·연혁·자본금 변동)
2. **사업의 내용** (산업·매출 비중·생산설비·시장점유율)
3. **재무에 관한 사항** (요약재무정보·연결재무제표·주석·외부감사인 의견)
4. **이사의 경영진단 및 분석 의견** (MD&A)
5. **회계감사인의 감사의견** (감사보고서)
6. **이사회 등 회사의 기관에 관한 사항**
7. **주주에 관한 사항**
8. **임원 및 직원 등에 관한 사항**
9. **계열회사 등에 관한 사항**
10. **이해관계자와의 거래내용**
11. **그밖에 투자자 보호를 위하여 필요한 사항**

> 인동에프엔이 DART에 공시하는 감사보고서도 위 골격 일부(특히 1·2·3·5)를 사용한다. **CEO Summary Report는 이 골격을 "재포장"해서 만들면 외부 IR 자료로도 일부 재활용 가능**.

### 2-3. 한국 동종사의 IR 자료 약점 (벤치마크 포인트)

- **분기 실적 발표 슬라이드 수가 적다** (대개 10~20p) → 글로벌 사 대비 컨텍스트·전략 설명 부족.
- **차트 밀도가 낮다** — 표 위주, 그래프는 매출/영업이익 막대 정도.
- **온라인 매출 비중·전환율 등 디지털 KPI 공개가 빈약** — 인동에프엔이 IDFmall KPI를 강조하면 차별화 가능.
- **세그먼트 정의가 모호** — F&F는 브랜드, 신세계인터는 카테고리, LF는 산업으로 가르는 등 비교 어려움. 인동에프엔은 **"브랜드 × 채널" 2축**으로 통일하면 일관성 확보.

---

## 3. 내부 매니지먼트 보고서 패턴 (Board Pack / WBR / MBR)

> **핵심 인사이트**: 운영 보고서의 글로벌 표준은 **Amazon WBR**(Weekly Business Review). 같은 포맷·같은 순서로 매주 400~500개 지표를 60분 안에 본다. 핵심은 ① **6-12 차트**(6주 + 12개월 동시), ② Input → Output → Financial 순서, ③ 메트릭마다 Owner + R/Y/G. 인동에프엔은 KPI 갯수를 줄여 (15~30개) 같은 mechanism을 도입 가능.

### 3-1. Amazon WBR — 글로벌 운영 표준

| 항목 | 내용 |
|------|------|
| **주기** | 매주 수요일 오전 (전사). 월·화는 산하 팀별 WBR로 데이터 roll-up. |
| **시간** | 60분, 모든 임원 의무 참석 — "회사에서 가장 비싼 회의" |
| **포맷** | 첫 10분 침묵 독서(Reading) → Facilitator(Finance) 진행 → 메트릭 owner가 설명 |
| **메트릭 수** | 400~500개 (대형 조직), 소형 조직은 30~50개 |
| **표준 차트** | **6-12 Graph** — 좌측: 직전 6주 / 우측: 직전 12개월. 같은 메트릭을 두 시간 축에 동시 표시. 그래프 아래 요약 표(WTD / MTD / QTD / YTD + YoY %). |
| **메트릭 순서** | ① Controllable Input(트래픽·신규회원 등) → ② Output(매출·전환율 등) → ③ Financial(이익·현금흐름). 부서별로 이 패턴 반복. |
| **색상 코딩** | R/Y/G — 목표 대비 미달/주의/달성. 한 슬라이드 안에서 동일 색팔레트, 동일 라인 수, 동일 기간 비교 유지. |
| **프레임워크** | "Risks, Observations, Trends, Challenges" (ROTC) — 메트릭별 owner가 이 4개 답변. |
| **소형 사례** | 큰 조직이 retail WBR, 작은 sub-team이 jewelry WBR / men's apparel WBR / Alexa devices WBR — **카테고리별 mini-WBR이 인동에프엔 브랜드별 WBR(SHESMISS/LIST/SISTINA)**에 그대로 매핑 가능. |

**핵심 인용**:
> "A 6_12Graph displays the trailing 6 weeks of data along with the trailing 12 months ... It also has a summary table below the chart that lists the last week, MTD, QTD, and YTD data along with the relevant period-over-period comparisons expressed as a percentage."
> — Working Backwards WBR App ([source](https://workingbackwards.com/wbr-app/user-manual/))

> "Output metrics are the results ... and input metrics are the drivers ... While output metrics like revenue or customer retention are important, input metrics provide clarity on the levers you can pull to improve those outputs."
> — Paul Duvall, ex-Amazon ([source](https://www.paulmduvall.com/the-wbr-mechanism-architecture-of-a-weekly-business-review-system/))

### 3-2. MBR (Monthly Business Review) — 표준 구조

월간 보고는 주간 WBR을 더 전략적으로 종합한 것. 일반적인 MBR 템플릿 구조:

1. **Executive Summary** — 한 달 헤드라인 3~5개
2. **Financial Performance** — P&L 요약, GM% 추이, 예산 대비 달성률 (한 슬라이드)
3. **Operational Metrics** — 생산성·품질·납기·재고 (delivery efficiency, quality, safety)
4. **Strategic Goals (OKR)** — 분기 OKR 3~4개와 진척률 indicator
5. **Cash Flow** — 현금 inflow/outflow 시계열, A/R Aging (DSO + 채권 잔액 + Top 채무자)
6. **Risks & Issues** — 잠재 리스크 vs 현재 영향 중 이슈
7. **Action Items** — Owner + 기한 명시

### 3-3. McKinsey/BCG/Bain Board Pack 스타일

| 요소 | 표준 패턴 |
|------|----------|
| **슬라이드 구조** | Headline statement (페이지 제목 = 메시지) → Body(차트+불릿) → Bumper statement (하단 핵심 takeaway) |
| **차트** | 한 슬라이드 1~2개 차트 원칙. 데이터 ink 최대화, 색상 3색 이내 |
| **두께** | 변혁 프로젝트 readout이 80~100p (WMATA 사례 89p) — 분기/연간 stra 검토용 |
| **포트폴리오 분석** | BCG Matrix (Star/Cash Cow/Question Mark/Dog) — 인동에프엔 브랜드 분류에 적용 가능 |

### 3-4. McKinsey State of Fashion (연간 산업 보고서 표준)

McKinsey×BoF가 매년 발간하는 **"State of Fashion"**은 패션 산업 보고서의 글로벌 표준이며 매년 같은 골격:

- **Macro Outlook** — 글로벌 경제, 인플레이션, 환율, 소비심리
- **Industry Health** — Top 20 fashion companies 주가/이익 분포(Economic Profit Curve)
- **10 Themes** — 그 해의 핵심 주제 10개 (예: 2025년판: 가격민감도·Dupes·Silver Generation·AI 75% 도입·Asia 성장)
- **Regional Deep Dives** — 미주/유럽/중국/동남아
- **Sustainability**

> 시사점: 인동에프엔 분기/연간 보고서에 **"10 Themes" 페이지를 차용**해 거시·트렌드·경쟁사 3개씩 묶어서 한 페이지로.

### 3-5. CEO 주간 대시보드 — KPI 갯수 가이드

- **CEO 주간 검토 최대 15개 메트릭** — 7일 안에 의미 있게 변하지 않거나 CEO가 액션 못 취하는 KPI는 월/분기로 빼야 함.
- **상태(R/Y/G)와 추세(7일·30일 방향)를 분리**해서 동시 표시.
- 패션 특화 인풋 메트릭: Daily Unique Visitors, CAC by channel.
- 패션 특화 아웃풋 메트릭: Conversion rate, Gross margin %, Sell-through, Repeat purchase rate.

---

## 4. KPI 대시보드 템플릿 (SaaS / BI 도구)

> **핵심 인사이트**: Modeliks·NetSuite·Tableau·Power BI 모두 패션/리테일 전용 템플릿을 제공하나, **공통 5대 영역**(① Network/Store KPIs ② Store Performance ③ Product Category ④ Marketing ⑤ Supplier Collaboration)으로 수렴한다. 인동에프엔도 이 5영역 매핑부터 시작하면 된다.

### 4-1. Modeliks — 7종 패션 전용 대시보드

Modeliks는 비즈니스 세부 형태별로 7종 패션 KPI 대시보드 템플릿을 제공:

1. **Clothing Brand KPIs Dashboard** — 인동에프엔 본사에 가장 부합
2. Clothing Boutique KPIs Dashboard (단일 매장)
3. **Fashion Designer KPIs Dashboard** — 신상품 sell-through·디자인 ROI
4. **Custom Clothing Production KPIs Dashboard** — 베트남 직영공장 가동률에 적용 가능
5. Fashion Accessories Production KPIs Dashboard
6. Sportswear and Athletic Apparel Manufacturing KPIs Dashboard
7. **Niche Apparel E-commerce KPIs Dashboard** — IDFmall에 적용

**공통 메트릭**: customer retention, AOV, website conversion, **sell-through rate**, revenue/profit/margins, cash flow, working capital, client acquisition.

URL: [Fashion KPIs Dashboard](https://www.modeliks.com/industries/retail/fashion-kpis-dashboard)

### 4-2. NetSuite — 역할 기반 패션 대시보드

- **포맷**: Role-based, 단일 화면에 실시간 데이터. Dashboard tile = role-specific 정보 3~4개 링크.
- **레이아웃 옵션** 4종 (상단 우측 Layout 버튼).
- **KPI Scorecard Portlet** — GP%, DSO, Inventory Turnover를 여러 컬럼에 시계열로 노출.
- **10 Apparel & Fashion KPIs** (NetSuite 공식 가이드):
  - Sell-Through Rate
  - Inventory Turnover
  - GMROI (Gross Margin Return on Investment)
  - Sales per Square Foot
  - Average Transaction Value
  - Conversion Rate
  - Customer Retention Rate
  - Return Rate
  - Days Sales of Inventory
  - Stock-to-Sales Ratio

URL: [10 Apparel and Fashion KPIs](https://www.netsuite.com/portal/resource/articles/erp/apparel-kpis.shtml) / [Brainyard Benchmarks](https://www.netsuite.com/portal/business-benchmark-brainyard/kpi/apparel-footwear.shtml)

### 4-3. Tableau / Power BI Retail 템플릿

- **Power BI Retail Analysis Sample** — "This Year Sales by Chain", "Total Sales Variance %", US Map 시각화 포함.
- **공통 5대 영역** (Datawiz BI 분류): ① Network KPIs ② Store Performance ③ Product Category Analysis ④ Marketing Analysis ⑤ Supplier Collaboration.
- **주 차트 유형**: Bar, Line, Donut, Custom visuals, Bubble, Map(geo), Gantt(공급망), Heatmap.

URL: [Power BI Retail Sample](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-retail-analysis)

### 4-4. ClickUp Fashion Designers KPI Template

- 분기 OKR 형식
- 디자이너 단위 (개인 KPI까지 drill-down) — 인동에프엔 디자인본부에 적용 가능

URL: [ClickUp Template](https://clickup.com/templates/kpi/fashion-designers)

### 4-5. 대시보드 화면 구성 패턴 (공통)

```
+----------------------------------------------------------+
| [HEADER]  Date range · Filters · Export                 |
+--------------------+-----------------+-------------------+
| [Top-line KPI #1]  | [KPI #2]        | [KPI #3]          |
| Revenue $XB +X%    | GM% XX% +X bps  | Op profit $XB     |
+--------------------+-----------------+-------------------+
| [Sales Trend — Line, 12 months]                          |
+--------------------+-----------------+-------------------+
| [Channel Mix]      | [Region Mix]    | [Top SKU Table]   |
| Donut              | Stacked bar     | Sorted table      |
+--------------------+-----------------+-------------------+
| [Inventory Health] | [Sell-through]  | [Markdown %]      |
| Gauge              | Cohort table    | Waterfall         |
+--------------------+-----------------+-------------------+
| Drill-down: Click any KPI → store/SKU detail            |
+----------------------------------------------------------+
```

---

## 5. 시각화 · 차트 패턴 모음

> **핵심 인사이트**: 패션 보고서 잘 만든 차트는 **3개 축**(시간/카테고리/지표)을 1장에 압축한다. 안티패턴 1순위는 **"파이 차트에 카테고리 6개 이상"**, 2순위는 **"한 라인 차트에 KPI 10개 이상"**.

### 5-1. 패션 보고서 표준 차트 11종

| 차트 유형 | 용도 | 권장 위치 |
|----------|------|----------|
| **6-12 Graph** (Amazon식) | 6주 + 12개월 트렌드 동시 | WBR 매 페이지 |
| **Sell-through Curve** | 시즌 진척률 (입고 → 정상가 → 세일 → 클리어런스) — 시즌 시작 기준 % 곡선 | 재고 섹션 |
| **Markdown Waterfall** | 시작 GM% → 할인 → 폐기 → 최종 GM%의 단계별 영향 | 마진 분석 |
| **Channel Mix Donut** | 백화점/자사몰/아울렛/B2B 비중 | 매출 섹션 |
| **Stacked Bar (Region/Brand)** | 지역×브랜드 매출 동시 | 매출 섹션 |
| **Cohort Retention Heatmap** | 가입월별 재구매율 (행=가입월, 열=경과월) | 자사몰 섹션 |
| **CAC vs LTV Scatter** | 채널별 효율 | 마케팅 섹션 |
| **Inventory Aging Bar** | 신상/30일/60일/90일+/300일+ 재고 비중 | 재고 섹션 |
| **Same-Store Sales Line** | 기존점 신장률 분기 추이 | 매장 섹션 |
| **Geographic Map** | 국가/지역별 매출 buoble | IR 자료 |
| **BCG Matrix** | 브랜드 4분면(Star/Cash Cow/Question/Dog) | 분기/연간 |

### 5-2. 잘 만든 사례

- **Inditex**: Region Donut + Period 비교 표 + 환율 영향 별도 표기 — **3-layer**.
- **Fast Retailing**: 세그먼트 4-up + 각 세그먼트마다 "Revenue / Op profit / SSS / Stores / Comment" 5요소 고정.
- **Amazon WBR 6-12 차트**: 같은 포맷·같은 색·같은 라인 수를 매주 반복 → 임원이 "패턴 자체"를 학습.

### 5-3. 안티패턴 (피해야 할 것)

| 안티패턴 | 문제 | 대안 |
|----------|------|------|
| **파이 차트 카테고리 6개 이상** | 인간 눈이 각도 비교 불가 | Bar chart 또는 ranked table |
| **한 라인 차트에 KPI 10개 이상** | "스파게티 차트" — 비교 불가 (사례: 14 KPI × 24개월) | Small multiples (KPI별 미니 차트) |
| **15개 초과 KPI를 한 대시보드** | 인지 부하, 40% 낮은 engagement | 5~7개 primary + drill-down |
| **상태(R/Y/G)만, 추세 없음** | 단발성 색 변화에 휘둘림 | 색상 + 7일/30일 방향 화살표 병기 |
| **단순 YTD 누적만** | 최근 변화 못 잡음 | 6-12 차트 (단기 + 장기 동시) |
| **세그먼트 정의 무일관** | 분기마다 비교 어려움 | 한 번 정한 세그먼트 1년 고정 |
| **차트 색 매주 바뀜** | 임원이 패턴 학습 못함 | 같은 메트릭 = 같은 색 영구 고정 |

### 5-4. 패션 특화 시각화 베스트프랙티스 (검색 결과 기반)

- **Sell-through 목표**: 첫 1개월 후 50~80% (시즌 런칭은 더 높게).
- **Markdown 영향**: 매출의 20~50%를 할인이 소비. McKinsey 추정 — disciplined markdown 최적화로 마진 +400~800 bps 개선 가능.
- **Cohort retention**: 평균으로 보면 안 됨 — 최근 코호트가 빠르게 이탈하는지, 직전 분기 코호트의 객단가가 떨어지는지 봐야.
- **Channel별 비교**: D2C의 LTV가 마켓플레이스 대비 평균 2.5배 — 인동에프엔 IDFmall 강조 근거.

---

## 6. 한국 패션업 특화 고려사항

> **핵심 인사이트**: 한국 패션 보고서에는 글로벌에 없는 5종 특수 KPI가 반드시 들어가야 한다 — ① 백화점 판매수수료, ② 특약매입 vs 직매입 비중, ③ S/S vs F/W 시즌 사이클, ④ 아울렛 비중, ⑤ 환율(여기에 인동에프엔 베트남 공장 추가).

### 6-1. 백화점 채널의 한국적 특수성

- **3가지 거래 형태**: 특약매입 67.2% (반품 가능 외상매입), 매장 임대 25.8%, 직매입 21.4%.
- **평균 판매수수료율**: 백화점 **23.7%**, 대형마트 20.5%. 의류·생활용품·잡화에서 가장 높음.
- **개별 백화점 최대 수수료율**: 신세계 38.0% > 롯데 36.0% > 갤러리아 33.0% > AK 30.0% > 현대 26.0%.
- **직매입 평균 마진율**: 백화점 23.9%, 대형마트 20.4%.

> 시사점: 인동에프엔 보고서는 **백화점 점별 수수료율을 별도 컬럼으로 노출**해야 마진 누수 가시화. SHESMISS/LIST/SISTINA의 백화점별 P&L = (매출) ‑ (수수료 23~38%) ‑ (직접 비용) 구조로 봐야 함.

### 6-2. 시즌 사이클

- **S/S 시즌 (봄·여름)**: 약 34.9조 원 소비액 (한국 전체 패션, 캐주얼 +27.1%, 스포츠 +12.3%).
- **F/W 시즌 (가을·겨울)**: 약 47.9조 원 — **전체 패션 소비의 약 50%**.
- 여성복은 특히 F/W (겨울 아우터) 의존도가 매우 높음. CEO 보고서는 **반기/시즌 단위 비교**가 필수.

> 시사점: 인동에프엔 보고서에 **"시즌 진척률 (S/S 1~12주, F/W 1~12주)"** 차트 추가. 입고 → 정상가 판매 → 세일 → 클리어런스 곡선.

### 6-3. 아울렛 / 행사매장

- 아울렛은 오프라인 채널 중 선호도 1위 (25.9%) > 백화점 (24.6%) > 복합쇼핑몰 (16.1%).
- 2024년 국내 3대 아울렛 35개 점포 매출 **8조 9,680억 원** (+3.3% YoY).
- 여성복 브랜드는 시즌 끝 재고 처분을 아울렛에 의존 → **아울렛 매출 비중 = 정상가 sell-through의 역지표**.

> 시사점: 아울렛 매출 비중이 너무 높으면 정상가 sell-through 부진 신호. 보고서에 **"아울렛 매출 비중 vs 정상가 sell-through" 상관 차트** 권장.

### 6-4. 자사몰 (D2C) 한국 컨텍스트

- 국내 이커머스 평균 구매전환율 1.33%, 상위 브랜드 3% 수준.
- D2C 브랜드의 고객 **LTV가 마켓플레이스 대비 2.5배**.
- 배송 2일 달성 시 재구매율 35% → 52% 점프 사례.
- 카페24 배송 솔루션 도입 사례: 구매전환율 +33%, 신규회원 +59.6%, 총주문 +34.2%.

> 시사점: IDFmall KPI 섹션에 **"전환율·AOV·재구매율·배송 SLA"** 4종을 6-12 차트로.

### 6-5. 환율·원재료·OEM/ODM 의존

- 베트남 직영공장 보유 = 환율(VND/KRW/USD) 직접 노출.
- 면화·유가 등 원자재 가격은 한국 패션 마진의 핵심 변수 (한세실업 사업보고서가 가장 상세).

> 시사점: 인동에프엔 분기 보고서에 **"환율·면화·유가 1페이지"**(이중 축 라인 + 마진 민감도 표) 권장.

### 6-6. 비상장 외감법인의 공시 제약과 기회

- 인동에프엔은 DART에 사업보고서 의무 없음 (감사보고서만 제출).
- 반대로 **IR 자료 공개 자유도가 높음** — 외부 컨설팅·M&A·은행권 IR 시 자유로운 포맷 사용 가능.
- 비상장이라도 글로벌 standard에 맞춘 보고서를 만들어두면, 향후 IPO·해외 진출 시 즉시 활용 가능.

---

## 7. 인동에프엔에 시사점 (Top 5 권고)

> 한국 중견 + 비상장 외감 + 자사몰(IDFmall) + 베트남 직영공장 + 여성복 멀티브랜드(SHESMISS/LIST/SISTINA) 4가지 컨텍스트를 종합한 우선순위 권고.

### 권고 1 — **1페이지 Executive Summary 고정 포맷**
- Inditex FY Results Page 1 모방: "매출 X억 (+Y%), 영업이익 X억 (Y%), Net cash X억, 자사몰 X% (+Y%)" 같은 1줄 7~8개 숫자.
- 그 아래 "이번 주/달 TOP 3 메시지"(Decision-needed / Watch / Win) 고정 슬롯.
- **매주·매월·매분기 동일 포맷** — CEO가 패턴 자체를 학습.

### 권고 2 — **브랜드 × 채널 매트릭스 1장**
- Fast Retailing 세그먼트 4-up 차용.
- 행: SHESMISS / LIST / SISTINA / IDFmall (브랜드)
- 열: 매출 / 영업이익 / GM% / Sell-through / Stores / SSS / Comment
- 한 페이지에 인동에프엔 사업의 80% 이해 가능.

### 권고 3 — **Amazon WBR 6-12 차트를 5개 핵심 메트릭에 도입**
- ① 매출 (전사) ② 자사몰 전환율 ③ 재고 일수 ④ Markdown % ⑤ 신상품 sell-through
- 각각 좌: 6주 / 우: 12개월 / 하단: WTD·MTD·QTD·YTD + YoY %.
- 매주 같은 색·같은 라인 수·같은 순서 → 임원이 "정상 모양"을 학습.

### 권고 4 — **한국 특화 5종 KPI 별도 섹션**
- ① 백화점 판매수수료율 (점별, 23~38%)
- ② 특약매입 vs 직매입 비중
- ③ S/S vs F/W 진척률 + 시즌 곡선
- ④ 아울렛 매출 비중 (정상가 sell-through 역지표)
- ⑤ 환율 (VND/KRW/USD) + 면화·유가 민감도 + 베트남 공장 가동률
- 글로벌 보고서에는 없는 한국 패션의 진짜 변수.

### 권고 5 — **분기 보고서에 "10 Themes" 페이지 차용**
- McKinsey State of Fashion 골격: 거시 3개 + 트렌드 3개 + 경쟁사 동향 3개 + 인동에프엔 대응 1개.
- 한섬·신세계인터·LF의 분기 실적 발표에서 **3개 KPI(매출·영업이익·핵심 코멘트) 표**를 한 페이지에 묶어 비교.
- 인동에프엔이 비상장이라서 오히려 자유롭게 경쟁사 데이터 인용 가능 — 상장사는 못 함.

### (보너스) 권고 6 — **보고서 자동화 단계화**
- Phase 1 (1~3개월): 수동 Excel + PPT — 골격 검증
- Phase 2 (3~6개월): Google Sheets / Looker Studio — 자사몰 데이터 연결
- Phase 3 (6~12개월): NetSuite/Power BI dashboard + 자동 PDF 출력
- 시작은 수동, **포맷이 굳어진 뒤에 자동화**.

---

## 8. 출처

### 8-1. 글로벌 IR / Annual Report (1차 자료)

**Inditex**
- [Inditex FY2024 Results Press Pack (PDF)](https://www.inditex.com/itxcomweb/api/media/2ca3e758-1c78-419f-8adf-7057207022e8/FY2024_Results.pdf)
- [Inditex FY2024 Full Year Results (PDF #2)](https://www.inditex.com/itxcomweb/api/media/16843322-c524-4f36-b84f-133989e4e569/INDITEXFullYear2024Results.pdf)
- [Inditex FY2024 Annual Results Annexes (PDF)](https://www.inditex.com/itxcomweb/api/media/4a47faab-1d1f-4ed5-b37b-374162394b7c/2024AnnualResultsAnnexes.pdf)
- [Inditex Annual Accounts & Directors Report 2024 Consolidated (PDF)](https://www.inditex.com/itxcomweb/api/media/84135f02-0208-4439-b9c0-b13608fbfeb5/Annualaccountsanddirectorsreport2024consolidated.pdf)
- [Inditex Annual Report 2024 — Interactive Microsite](https://static.inditex.com/annualreport2024/en/download-center)
- [Inditex CEO Statement (HTML)](https://static.inditex.com/annualreport2024/en/ceo-statement)
- [Inditex FY2024 Press Release](https://www.inditex.com/itxcomweb/aq/en/press/news-detail/6f8d8db5-4d7a-43db-91b9-0c38065aec1e/fy2024-results)
- [Inditex FY2024 Conference Call Script Transcript (PDF)](https://www.inditex.com/itxcomweb/api/media/53f13101-cd88-4494-9a55-662c6f6f8116/Transcript_FY2024.pdf)
- [Inditex 9M2024 Interim Results (PDF)](https://www.inditex.com/itxcomweb/api/media/44327d2d-dfd7-4b0a-9bb7-c0ebfe1d4bd1/INDITEX9M2024Results.pdf)
- [Inditex 1H2024 Interim Results (PDF)](https://www.inditex.com/itxcomweb/api/media/2e2b8f82-90ca-4278-af1d-b202e97481ba/1H2024+Results.pdf)

**H&M**
- [H&M Full-year Report 2024 Q4 (PDF)](https://hmgroup.com/wp-content/uploads/2025/01/H-M-Hennes-Mauritz-AB-Full-year-report-2024.pdf)
- [H&M Nine-month Report 2024 Q3 (PDF)](https://hmgroup.com/wp-content/uploads/2024/09/H-M-Hennes-Mauritz-AB-Nine-month-report-2024.pdf)
- [H&M Investor Reports Hub](https://hmgroup.com/investors/reports/)
- [H&M Annual Report Page](https://hmgroup.com/about-us/corporate-governance/annual-report/)
- [H&M Full-year Report 2025 Q4 (PDF, 최신)](https://hmgroup.com/wp-content/uploads/2026/01/H-M-Hennes-Mauritz-AB-Full-year-report-2025.pdf)

**Fast Retailing (Uniqlo)**
- [Fast Retailing FY2024 Results & FY2025 Estimates (PDF, 2024/10/10)](https://www.fastretailing.com/eng/ir/library/pdf/20241010_results_en.pdf)
- [Fast Retailing FY2024 Results Summary (HTML)](https://www.fastretailing.com/eng/ir/news/2410101800.html)
- [Fast Retailing FY2025 Results & FY2026 Estimates (PDF, 최신)](https://www.fastretailing.com/eng/ir/library/pdf/20251009_results_en.pdf)
- [Fast Retailing Results Summary Index](https://www.fastretailing.com/eng/ir/financial/summary.html)
- [Fast Retailing Annual / Integrated Report Library](https://www.fastretailing.com/eng/ir/library/annual.html)

**LVMH**
- [LVMH Annual Results 2024 Press Release (PDF)](https://voda.akamaized.net/lvmh/2050279_678e15ab3de5a/files/Press%20Release%20-%20LVMH%20Annual%20results%202024.pdf)
- [LVMH 2024 Results Page](https://www.lvmh.com/en/publications/lvmh-achieves-a-solid-performance-despite-an-unfavorable-global-economic-environment)
- [Christian Dior Annual Report 2024 (PDF)](https://www.dior-finance.com/pdf/d/2/1124/Christian%20Dior%20-%20Annual%20Report%20as%20of%20December%2031,%202024.pdf)

**Ralph Lauren**
- [Ralph Lauren FY2024 Form 10-K (SEC)](https://www.sec.gov/Archives/edgar/data/0001037038/000103703824000014/rl-20240330.htm)
- [Ralph Lauren 10-K PDF (Stocklight)](https://stocklight.com/stocks/us/nyse-rl/ralph-lauren/annual-reports/nyse-rl-2024-10K-24978686.pdf)
- [Ralph Lauren 10-Q FY2025 Q2 (PDF)](https://investor.ralphlauren.com/static-files/7680cd0c-16d0-454e-a61c-05306fd72bb8)

### 8-2. 한국 동종사 IR / 사업보고서

- [DART 전자공시시스템](https://dart.fss.or.kr/)
- [KIND 한국거래소 공시채널](https://kind.krx.co.kr/)
- [OPEN DART — 사업보고서 주요정보](https://opendart.fss.or.kr/disclosureinfo/biz/main.do)

**한섬**
- [한섬 공식 IR 페이지](https://www.handsome.co.kr/ko/ir/financialInfo01.do)
- [한섬 IRGO](https://m.irgo.co.kr/IR-COMP/020000/)
- [한섬 분기보고서 (KIND)](https://kind.krx.co.kr/common/disclsviewer.do?method=search&acptno=20251114001431)
- [한섬 흥국증권 리포트 (PDF)](https://www.heungkuksec.co.kr/download.do?type=Board&key=27598)

**신세계인터내셔날**
- [신세계인터내셔날 사업보고서 2023 (2024.03.12 공시 PDF)](https://img.sikorea.co.kr/files/upload2/noticePdf/202403/%5B%EC%8B%A0%EC%84%B8%EA%B3%84%EC%9D%B8%ED%84%B0%EB%82%B4%EC%85%94%EB%82%A0%5D%EC%82%AC%EC%97%85%EB%B3%B4%EA%B3%A0%EC%84%9C(2024.03.12)_1710898478589.pdf)
- [신세계인터내셔날 IRGO](https://m.irgo.co.kr/IR-COMP/031430/)
- [신세계인터내셔날 IR 페이지](https://www.sikorea.co.kr/investors/resultsAndReports)

**LF / F&F / 한세실업**
- [LF 기업 현황 (Wisereport)](https://comp.wisereport.co.kr/company/c1010001.aspx?cmp_cd=093050)
- [LF 재무제표 (FnGuide)](https://comp.fnguide.com/SVO2/asp/SVD_Finance.asp?pGB=1&gicode=A093050)
- [F&F홀딩스 기업정보 (FnGuide)](https://comp.fnguide.com/SVO2/asp/SVD_Main.asp?gicode=A007700)
- [한세실업 사업보고서 2024.03.20 (PDF)](https://www.hansae.com/upload/%ED%95%9C%EC%84%B8%EC%8B%A4%EC%97%85_%EC%82%AC%EC%97%85%EB%B3%B4%EA%B3%A0%EC%84%9C(2024.03.20).pdf)
- [한세실업 사업보고서 2026.03.18 (PDF)](https://www.hansae.com/upload/%5B%ED%95%9C%EC%84%B8%EC%8B%A4%EC%97%85%5D%EC%82%AC%EC%97%85%EB%B3%B4%EA%B3%A0%EC%84%9C(2026.03.18).pdf)
- [한세실업 IRGO](https://m.irgo.co.kr/IR-COMP/105630/)

### 8-3. Amazon WBR / 매니지먼트 보고서

- [Commoncog — The Amazon Weekly Business Review (WBR)](https://commoncog.com/the-amazon-weekly-business-review/)
- [Paul Duvall — Mastering Weekly Business Reviews](https://www.paulmduvall.com/mastering-weekly-business-reviews-insights-from-amazons-iconic-wbr/)
- [Paul Duvall — The WBR Mechanism Architecture](https://www.paulmduvall.com/the-wbr-mechanism-architecture-of-a-weekly-business-review-system/)
- [Paul Duvall — From Dashboard Hell to One-Click WBRs](https://www.paulmduvall.com/from-dashboard-hell-to-one-click-wbrs-automating-amazon-s-weekly-business-review/)
- [Working Backwards — WBR App User Manual](https://workingbackwards.com/wbr-app/user-manual/)
- [Working Backwards — Sample WBR Report](https://workingbackwards.com/wbr-app/sample-wbr-report/)
- [GitHub — working-backwards/wbr-app](https://github.com/working-backwards/wbr-app)
- [Row Zero — How to Run a Weekly Business Review](https://rowzero.com/blog/weekly-business-review)
- [Holistics — This is How Amazon Measures Itself](https://www.holistics.io/blog/how-amazon-measures/)
- [Data Analysis Substack — How Amazon Runs a Weekly Business Review](https://dataanalysis.substack.com/p/how-amazon-runs-a-weekly-business-review)
- [Conikeec Substack — The Secret Sauce Behind Amazon's WBR Part 2](https://conikeec.substack.com/p/the-secret-sauce-behind-amazons-weekly-98f)
- [Strategic Nerds — The WBR Survival Guide](https://www.strategicnerds.com/blog/the-wbr-survival-guide)

### 8-4. MBR / Board Pack 템플릿

- [Infodiagram — Monthly Business Report PowerPoint Template](https://www.infodiagram.com/diagrams/mbr-powerpoint-template-company-financial-performance-review-monthly-summary-presentation/)
- [Infodiagram Blog — Presenting Monthly Business Report](https://blog.infodiagram.com/2024/05/how-present-monthly-business-report-powerpoint-mbr.html)
- [SaaS Operations — Monthly Business Review Template](https://saasoperations.com/monthly-business-review-template/)
- [Kainexus — How to Conduct High-Value Monthly Business Reviews](https://blog.kainexus.com/how-to-conduct-high-value-monthly-business-reviews-for-continuous-improvement)
- [SlideBazaar — MBR Dashboard Deck Template](https://slidebazaar.com/templates/monthly-business-review-dashboard-powerpoint-google-slides/)
- [SlideTeam — Top 10 MBR Templates](https://www.slideteam.net/blog/top-10-monthly-business-review-templates-with-samples-and-examples)
- [Hyperbots — What is Monthly Business Review (MBR)?](https://www.hyperbots.com/glossary/monthly-business-review-mbr)
- [Slideworks — 100+ Real McKinsey Presentations](https://slideworks.io/resources/47-real-mckinsey-presentations)
- [Slideworks — 105 Real BCG Presentations](https://slideworks.io/resources/54-real-bcg-presentations)
- [Slideworks — 55+ Real Bain Presentations](https://slideworks.io/resources/30-real-bain-presentations)

### 8-5. McKinsey State of Fashion

- [McKinsey — State of Fashion 2024](https://www.mckinsey.com/industries/retail/our-insights/state-of-fashion-2024)
- [McKinsey — State of Fashion 2025 (Challenges at every turn)](https://www.mckinsey.com/industries/retail/our-insights/state-of-fashion)
- [McKinsey — State of Fashion Archive 2017-2024](https://www.mckinsey.com/industries/retail/our-insights/state-of-fashion-archive)
- [State of Fashion 2024 PDF (McKinsey Germany)](https://www.mckinsey.com/de/~/media/mckinsey/locations/europe%20and%20middle%20east/deutschland/news/presse/2023/2023-11-28%20state%20of%20fashion%202024/sof24_report.pdf)
- [BoF — State of Fashion 2025 Report](https://www.businessoffashion.com/reports/news-analysis/the-state-of-fashion-2025-bof-mckinsey-report/)
- [Marist Circle — I Read 150+ Pages of The State of Fashion 2025](https://www.maristcircle.com/arts-entertainment/2024/12/13/i-read-150-pages-of-a-bof-mckinsey-report-so-you-dont-have-to-the-state-of-fashion-2025)

### 8-6. KPI 대시보드 (SaaS / BI)

**Modeliks**
- [Fashion KPIs Dashboard](https://www.modeliks.com/industries/retail/fashion-kpis-dashboard)
- [Clothing Brand KPIs Dashboard](https://www.modeliks.com/industries/retail/clothing-brand-kpis-dashboard)
- [Niche Apparel E-commerce KPIs Dashboard](https://www.modeliks.com/industries/e-commerce/niche-apparel-e-commerce-kpis-dashboard)
- [Fashion Designer KPIs Dashboard](https://www.modeliks.com/industries/manufacturing/fashion-designer-kpis-dashboard)
- [Custom Clothing Production KPIs Dashboard](https://www.modeliks.com/industries/professional-services/custom-clothing-production-kpis-dashboard)

**NetSuite**
- [10 Apparel and Fashion KPIs to Track Today](https://www.netsuite.com/portal/resource/articles/erp/apparel-kpis.shtml)
- [Brainyard — Apparel, Footwear & Accessories KPIs](https://www.netsuite.com/portal/business-benchmark-brainyard/kpi/apparel-footwear.shtml)
- [33 Inventory Management KPIs and Metrics](https://www.netsuite.com/portal/resource/articles/inventory-management/inventory-management-kpis-metrics.shtml)
- [Insider's Guide to NetSuite Dashboards](https://www.netsuite.com/portal/resource/articles/business-strategy/an-insider%E2%80%99s-guide-to-getting-the-most-out-of-your-netsuite-dashboards.shtml)
- [NetSuite Inventory Turnover Report Docs](https://docs.oracle.com/en/cloud/saas/netsuite/ns-online-help/section_N2356560.html)

**Tableau / Power BI / ClickUp / Others**
- [Power BI Retail Analysis Sample (Microsoft Learn)](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-retail-analysis)
- [Tableau — Business Intelligence Dashboard Examples](https://www.tableau.com/dashboard/business-intelligence-dashboard-examples)
- [Datawiz — Best Examples of BI Dashboards For Retail](https://datawiz.io/en/blog/best-examples-of-bi-dashboards-for-retail)
- [ClickUp — Fashion Designers KPI Template](https://clickup.com/templates/kpi/fashion-designers)
- [Cascade — Fashion KPI Strategy](https://www.cascade.app/)
- [Mandrill — KPI Dashboard Examples For Weekly CEO Reviews 2026](https://www.mandrill.com.my/blog/kpi-dashboard-examples-ceo-reviews/)
- [FinancialModelsLab — 7 Fashion Retail KPIs](https://financialmodelslab.com/blogs/kpi-metrics/fashion-retail)
- [FinancialModelsLab — 7 Fashion Design KPIs](https://financialmodelslab.com/blogs/kpi-metrics/fashion-design-company)
- [Vizio AI — 6 Key Metrics for Fashion & Apparel](https://www.vizio.ai/blog/6-key-metrics-to-track-for-the-fashion-and-apparel-industry)

### 8-7. 시각화 베스트프랙티스 / 안티패턴

- [ZebraBI — 10 Common Mistakes in Power BI Visualization](https://zebrabi.com/power-bi-dashboard-design-mistakes/)
- [DataCamp — Effective Dashboard Design](https://www.datacamp.com/tutorial/dashboard-design-tutorial)
- [ThoughtSpot — Dashboard Design Examples](https://www.thoughtspot.com/data-trends/dashboard-design-examples-best-practices)
- [iDashboards — Top 10 Dashboard Mistakes to Avoid](https://www.idashboards.com/top-10-dashboard-mistakes-to-avoid/)
- [clariBI — 10 Data Visualization Mistakes to Avoid 2026](https://claribi.com/blog/post/data-visualization-mistakes-to-avoid/)
- [Dataslayer — 5 Misused Graphs in Reports](https://www.dataslayer.ai/blog/misused-report-charts)
- [Pipedrive — What Waterfall Charts Tell You](https://www.pipedrive.com/en/blog/waterfall-chart)
- [Inforiver — Power Up Sales Analysis with Waterfall Charts](https://inforiver.com/insights/power-up-sales-analysis-waterfall-charts/)
- [Microsoft Learn — Waterfall Charts in Power BI](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-waterfall-charts)
- [StyleMatrix — Sell-Through Benchmarks Decoded](https://stylematrix.io/stylematrix-sell-through-decoding-retail-sell-through-benchmarks-for-success/)
- [StyleMatrix — Store Level Size Curve Optimisation](https://stylematrix.io/size-curve-optimisation-deciding-the-right-store-level-size-curve/)
- [Wair AI — Why Poor Size Curve Planning Hurts Sell-through](https://wair.ai/size-curve-planning-sell-through/)
- [Pattern — How to Manage Markdowns in Fashion Retail](https://patternretail.com/how-to-do-markdowns-in-fashion-retail/)
- [Markmi AI — 2026 Guide to Markdown Management in Fashion Retail](https://markmi.ai/blog/the-2026-guide-to-markdown-management-in-fashion-retail)
- [Saras Analytics — Customer Retention Analytics Comprehensive Guide](https://www.sarasanalytics.com/blog/customer-retention-analytics)
- [Saras Analytics — Cohort Retention Analysis](https://www.sarasanalytics.com/blog/cohort-retention-analysis)
- [Chakril — Advanced Analytics for Fashion & Apparel 2025](https://www.chakril.com/solutions/setting-up-analytics/for/fashion-stores/)
- [Improvado — Cohort Analysis Guide](https://improvado.io/blog/cohort-analysis)

### 8-8. 한국 패션업 특화 컨텍스트

**백화점 수수료**
- [한국경제 — 백화점이 매출 24% 가져갔다](https://www.hankyung.com/article/202512091860i)
- [경향신문 — 100만원 팔면 24만원 남는데 수수료는 38만원](https://www.khan.co.kr/article/202512091657001)
- [시사저널 — 백화점 수입 90% 매장 제공 수수료](https://www.sisajournal.com/news/articleView.html?idxno=116472)
- [시사저널 — 백화점이 매출 23.7% 가져갔다 중소기업 울리는 판매수수료](https://www.sisajournal.com/news/articleView.html?idxno=355793)
- [경기신문 — 백화점·대형마트 입점업체 판매수수료 20% 안팎](https://www.kgnews.co.kr/news/article.html?no=755860)

**시즌 사이클 / 아울렛**
- [한국섬유신문 — 1년 간 패션제품에 83조원 소비](https://ktnews.com/news/articleView.html?idxno=139352)
- [한국섬유신문 — 주요 百 12월 매출 신장률 패션부문 부진](https://www.ktnews.com/news/articleView.html?idxno=131254)
- [어패럴뉴스 — 2024년 국내 3대 아울렛 35개 점포 매출 순위](http://www.apparelnews.co.kr/news/news_view/?idx=214897&cat=CAT100)
- [어패럴뉴스 — 주요 34개 아울렛 매출 21.2% 신장](https://m.apparelnews.co.kr/news/news_view/?idx=198453)
- [패션포스트 — 12월 첫 주 매출 반짝 회복](https://www.fpost.co.kr/board/bbs/board.php?bo_table=newsinnews&wr_id=855&sfl=wr_subject&stx=2&sop=and&page=63)

**자사몰 / D2C**
- [브이리뷰 — 이커머스 마케팅 근본 KPI 3가지](https://vreview.tv/blog/content/ecommerce-marketing-kpi)
- [오픈서베이 — 자사몰(D2C) 고객 이탈을 막는 진짜 소통](https://blog.opensurvey.co.kr/research-tips/d2c-ltv-survey-strategy-1/)
- [Shopify 한국 — 2025년 주목할 20가지 전자상거래 지표](https://www.shopify.com/kr/blog/basic-ecommerce-metrics)
- [Brunch — 국내 이커머스 평균 전환율](https://brunch.co.kr/@biginsight/36)
- [DITODAY — 국내 이커머스 평균 전환율 문제 파악](https://ditoday.com/%EA%B5%AD%EB%82%B4-%EC%9D%B4%EC%BB%A4%EB%A8%B8%EC%8A%A4-%ED%8F%89%EA%B7%A0-%EC%A0%84%ED%99%98%EC%9C%A8-%EB%AC%B8%EC%A0%9C%EC%9D%98-%ED%8C%8C%EC%95%85-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%ED%9D%AC%EB%A7%9D/)
- [WaveOn — KPI 웹 서비스 핵심 성과 지표 6가지](https://www.waveon.io/blog/important-kpi-metrics-for-web-service-ko)
- [BizWatch — 패션업계 자사몰 카드 만지작](https://news.bizwatch.co.kr/article/consumer/2026/03/19/0027)
- [한국경제 — 플랫폼 종속 끝났다 D2C 자사몰의 반격](https://www.hankyung.com/article/2026030990901)
- [이코노믹리뷰 — 자사몰서 직접 판매 패션한국 D2C시대](https://www.econovill.com/news/articleView.html?idxno=538981)

**경쟁사 분기 실적**
- [CEOSCOREDAILY — 한섬 실적 추이 그래픽](https://m.ceoscoredaily.com/page/view/2026011911023714572)
- [TopDaily — 나홀로 수익성 개선 LF](https://www.topdaily.kr/articles/103585)
- [패션인사이트 — 패션부문 고민 깊은 LF](https://www.fi.co.kr/main/view.asp?idx=86180)
- [BizWatch — 사업 다각화로 웃은 LF 본업 패션 고삐](http://news.bizwatch.co.kr/article/consumer/2024/05/17/0025)
- [Beautynury — 신세계인터내셔날 2024 1Q 분석](https://www.beautynury.com/news/view/104914/cat/10)
- [Beautynury — 신세계인터내셔날 2024 상반기 분석](https://www.beautynury.com/news/view/105852/cat/10)
- [시사저널e — M&A로 성장한 신세계인터 3I 전략](https://www.sisajournal-e.com/news/articleView.html?idxno=418996)
- [패션비즈 — F&F 글로벌 매출 50% 돌파](https://fashionbiz.co.kr/article/210102)
- [어패럴뉴스 — F&F 디스커버리 MLB로 국내 매출 1조 돌파](http://m.apparelnews.co.kr/news/news_view/?idx=203280)
- [아시아투데이 — MLB 패션 F&F 글로벌 신사업](https://www.asiatoday.co.kr/kn/view.php?key=20260506010000729)

### 8-9. 인동에프엔 컨텍스트

- [패션포스트 — 인동에프엔 4500억 목표](http://fpost.co.kr/board/bbs/board.php?bo_table=special&wr_id=387&page=2)

---

## 부록 A. 보고서 자동 점검 체크리스트 (인동에프엔용)

다음 분기 보고서를 만들 때 한 줄씩 자기 점검:

- [ ] 1페이지에 매출/영업이익/Net cash/자사몰 4종 1줄 요약이 있는가?
- [ ] 브랜드(SHESMISS/LIST/SISTINA) × 채널(백화점/IDFmall/아울렛/베트남) 매트릭스 1장이 있는가?
- [ ] 매출 chart는 store sales + online sales + 채널-blind 매출 3중 분리되어 있는가?
- [ ] 핵심 5개 KPI에 6-12 차트(6주 + 12개월)가 적용되어 있는가?
- [ ] 백화점 점별 수수료율 컬럼이 마진 표에 들어 있는가?
- [ ] 시즌 진척률 (S/S 또는 F/W) 곡선이 있는가?
- [ ] 환율(VND/KRW/USD)·면화 민감도 1페이지가 있는가?
- [ ] Cohort retention heatmap이 자사몰 섹션에 있는가?
- [ ] 파이 차트에 6개 이상 카테고리는 없는가?
- [ ] 한 라인 차트에 10개 이상 KPI는 없는가?
- [ ] 모든 KPI에 R/Y/G 상태 + 7일/30일 추세 화살표가 같이 있는가?
- [ ] 같은 메트릭이 매번 같은 색·같은 위치인가?
- [ ] 액션 아이템에 Owner + 기한이 명시되어 있는가?

---

## 부록 B. 다음 단계 (Backlog 업데이트)

1차 리서치(`docs/research-ceo-report-scope.md`) Backlog를 본 벤치마크 기준으로 갱신:

- [ ] `docs/report-template.md` — 본 권고 1·2·3·4를 반영한 인동에프엔 1차 템플릿 골격
- [ ] Inditex FY2024 Results PDF 30페이지 직접 파싱 → 섹션별 페이지 수 정밀 측정 (현재는 추정)
- [ ] Fast Retailing FY2024 PDF 40페이지 직접 파싱 → 세그먼트 슬라이드 레이아웃 캡처
- [ ] 한섬·신세계인터내셔날 사업보고서 PDF에서 DART 11개 섹션의 실제 페이지 비중 측정
- [ ] McKinsey State of Fashion 2025 150p PDF 입수 → "10 Themes" 페이지 차용 가능성 검토
- [ ] 인동에프엔 ERP/POS/IDFmall 데이터 소스 매핑 → 어떤 메트릭이 자동화 가능한지
- [ ] 보고 도구 선정: Phase 1 Excel/PPT → Phase 2 Looker Studio → Phase 3 NetSuite/PowerBI
