# 우리은행 AI-금융소비자보호 경진대회 — 분야별 심층 리서치

> **조사 기준일:** 2026-05-20
> **목적:** 4개 응모 분야별로 (a) 시장·이슈 현황 (b) 경쟁사 동향 (c) AI 기술 스택 (d) 오픈소스·논문 자료 (e) 우리은행 자산·약점 매핑 (f) 아이디어 후보를 정리해 1등 후보 주제 선정의 근거를 만든다.

---

## 0. 메타: 심사 프레임과 우리은행 컨텍스트

### 0.1 심사 배점 (총 100점)

| 항목 | 배점 | 실전 해석 |
|------|:-:|------|
| 효과성 | 40 | "이게 진짜 사회문제를 푸나? 임팩트가 측정 가능한가?" |
| 실현가능성 | 30 | "내일이라도 우리은행이 도입할 수 있나? 비용·규제·인프라가 현실적인가?" |
| 혁신성 | 30 | "AI를 얼마나 새로운 방식으로 썼나? 다른 팀이 쉽게 따라할 수 없는가?" |

### 0.2 우리은행 2026 시점 핵심 시그널

- **자체 발표 우선순위 (2026.05.14 제1차 금융소비자보호 세미나):**
  1. 청년층 보이스피싱·불법사금융 선제 대응 (지금 1순위)
  2. 6월: 자립준비청년 그룹 공동 금융특강
  3. 하반기: ①보이스피싱 최신 범죄 ②AI 기술의 소비자보호 활용·리스크 ③초고령사회 대응 전략
- **약점 (역으로 경진대회의 절박성):**
  - 2025 금감원 소비자보호 실태평가 **'보통'** 등급 (낙제 수준)
  - 5년간 부당대출·횡령 2,334억원
  - **DLF 불완전판매 사태 (2019)**: 우리은행이 주요 판매사 → 금감원 은행장 중징계, 대규모 배상 (홍콩 ELS 1.4조는 KB국민은행 등 타행 사태 — 우리은행과 혼동 금지)
  - 이사회 내 금융소비자보호위원회 신설 (체계 미흡 인정)
- **이미 보유한 AI 자산 (제안서에 얹을 수 있는 인프라):**
  - **우리GPT**: 사내 생성형 AI (RAG·문서 요약·심층 리서치)
  - **AI뱅커**: 업무 지원 생성형 AI
  - **AI 예·적금 상담원 / AI 대출상담원**: 비대면 전 상품 적용
  - 기업여신 자동심사 시스템
  - 4대 공적연금 비대면 수급계좌 변경 서비스 (시니어 인프라)
  - 트랜드마케팅팀(개인상품마케팅부 내) - 시니어 생애주기 담당
  - 우리원더라이프 (시니어 브랜드)
  - 우리다문화장학재단 (외국인·다문화 접점)

### 0.3 결정적 함의

> **우리은행은 "소비자보호 점수가 떨어진 은행"** 이다. 그래서 이 대회는 단순 마케팅 이벤트가 아니라 **그룹장(CCO)이 사회·금융당국에 "우리는 다르다"를 증명할 도구**다. **우리은행이 지금 가장 사고 싶은 슬라이드는 "우리은행이 소비자보호 1등 은행이 되는 그림"** 이다. 이걸 기억하고 모든 주제를 평가한다.

---

## 1. 분야 1 — 취약계층 권익보호 (시니어·장애인 등)

### 1.1 시장 현황 (숫자로 보는 절박감)

| 지표 | 값 | 출처/배경 |
|------|---:|------|
| **치매머니 (2025년 말)** | 약 172조 원 | 인지장애로 사실상 동결된 자산 |
| **치매머니 2050년 전망** | 약 488조 원 | 저출산고령사회위원회 |
| 60세 이상 보이스피싱 피해 비중 | 약 40% (피해액 기준) | 금감원 |
| 70대 키오스크 활용도 | 100점 만점에 43점 | 한국지능정보사회진흥원 |
| 70대 스마트폰 사용률 | 91% | 그런데 활용은 또 다른 문제 |
| 한국 외국인 거주자 | 약 250만 명 | 1주일에 한 번 일요일 은행 오픈런 |
| 시각장애인 모바일뱅킹 사용 가능률 | 약 30% 미만 | 화면읽기 호환성 부족 |

### 1.2 최근 사건·정책

- **2026.03**: 은행권 공동 "치매환자 금융착취 대책" 가이드라인 제정 논의 (오데일리)
- **2026.04**: 한국일보 "초고령사회, 치매신탁 활성화로 대비해야" — 신탁법 정비론 부상
- **2026.05.07**: 보건복지부+금감원 불법사금융 원스톱 안전망 — 자립준비청년·노인 맞춤 교육
- 키오스크 의무화 추세 vs 디지털 약자 보호 — 사회적 갈등 격화
- 디지털 배움터 예산 60% 삭감 (역설적으로 민간 기업의 역할 ↑)

### 1.3 경쟁사 동향

| 은행 | 주요 행보 | 차별화 포인트 |
|------|----------|---------------|
| **KB국민은행** | 휴머노이드 돌봄로봇 공개, 시니어 대상 **AI 인지검사 무료**, 배리어프리 키오스크 | 가장 적극적, 의료 영역 진입 |
| **신한은행** | '배리어 프리' 정책, 시각장애인 응대 KIT, 청각장애인 자막, 22년 연속 우수콜센터 | 응대 매뉴얼·콜센터 강점 |
| **하나은행** | 외국인 일요일 영업 (가산·안산 등), '컬처뱅크' 다문화 거점 | 외국인·다문화 최강 |
| **농협은행** | NH올원더풀(시니어 브랜드), 시니어 우수고객 초청 행사 | 농촌 시니어 접점 |
| **케이뱅크** | KT 협력 AI 보이스피싱 실시간 탐지, 비대면 시니어 | 기술 + 통신사 시너지 |
| **카카오뱅크** | AI 세이브콜 (음성인식 기반 사기 예방) | 7월부터 현직 경찰관 참여 |
| **새마을금고** | 발달장애인·어린이·시니어 통합 디지털 교육 공간 | 포용 교육 거점 |
| **우리은행** | 우리원더라이프, 4대 공적연금 비대면, 트랜드마케팅팀, 우리이음상담센터 | **시니어 데이터는 있는데 AI 결합 부족** |

### 1.4 활용 가능 AI 기술

#### A. 인지능력 변화 감지 (Cognitive Decline Detection)
- **연구 근거**: 거래 패턴(시간·금액·빈도·수취인)의 점진적 drift는 MoCA(인지검사) 점수와 강한 상관관계
- **2026.04 ScienceDirect 논문**: 생성형 AI의 인지부담 감소 개입 → **사기 거래 38% 감소, 저위험 상품 가입 29% 증가**
- **기법**: 시계열 이상탐지 (Isolation Forest, LSTM Autoencoder), 음성 응답 지연 분석, 모바일 터치/스크롤 패턴

#### B. 행동 바이오메트릭스 (Behavioral Biometrics)
- 시장: 2024 $2.98B → 2033 $18.39B
- 대표 기업: BioCatch, Sardine, Feedzai, Symphony AI
- 시니어 사용자에게는 **마찰을 줄이는 보호** (원클릭 푸시 인증) + **이상 패턴 시 자동 게이트**

#### C. 멀티모달 접근성 AI
- **Google SignGemma** (2025.5 발표): 수어→텍스트 컴퓨터비전 모델
- 시각장애: TTS·STT, 점자 디스플레이 호환 (닷의 Dot Pad 등)
- 청각장애: 실시간 자막, 영상 수어 통역, 화상 전화 상담
- **온디바이스 LLM**: 개인정보 노출 없이 폰에서 직접 처리 (Apple Intelligence, Galaxy AI On-Device)

#### D. 가족 합의 신탁/Family Consent Vault
- 단순 가족 알림 아닌 **사전 합의된 룰 기반 게이트**
- 본인이 인지 또렷할 때 보호 룰 설정 → AI가 이상 거래 감지 시 게이트 발동
- 자기결정권 + 법적·윤리적 깔끔함 = 의료기기 규제 우회

### 1.5 오픈소스·논문

- **PMC10913197** — Artificial intelligence approaches for early detection of neurocognitive disorders among older adults
- **PMC7743272** — Aging and Financial Capacity: Cognitive Correlates as Early Indicator of Functional Decline
- **PMC7741303** — Early Indicators of Cognitive Decline in Online Financially Active Older Adults
- **PMC8721598** — Mild Cognitive Decline Is a Risk Factor for Scam Vulnerability
- **ScienceDirect S2451958826001296** (2026.04) — *The cognitive liquidity trap: How AI unlocks behavioral frictions in elderly financial decision-making* — 38% 사기 감소
- **BioCatch.com** — 상용 솔루션, 시니어 risk profile 기능
- **arxiv 2505.02519** — Deaf in AI: AI language technologies and the erosion of linguistic rights

### 1.6 아이디어 후보

| # | 한 줄 컨셉 | AI 활용 핵심 | 차별화 |
|---|------------|---------------|--------|
| 1-A | **엄마 안심 금고 (Family Consent Vault)** — 치매가 오기 전 가족이 함께 잠그는 계좌 | 이상거래 drift 감지 + RAG 기반 가족 알림 | 사전합의·자기결정권 (법적 안전) |
| 1-B | **AI 인지 트래커** — 평소 거래·음성·앱 사용 패턴으로 인지 변화 조기 신호 | LSTM Autoencoder + 응답 지연 분석 | KB 인지검사는 일회성, 우리는 연속 모니터링 |
| 1-C | **수어 영업점** — 청각장애 고객용 실시간 AI 수어 아바타 상담 | SignGemma + LLM | 국내 은행 최초 |
| 1-D | **다국어 외국인 금융 가디언** — 한·영·베·중·우즈·태 등 동시 통역 + 이주노동자 표적 사기 패턴 알림 | 멀티모달 LLM + 한국 사기 시나리오 DB | 250만 외국인 시장 |
| 1-E | **시니어 모드 UI 자동 생성** — 고객별 인지·시력·운동능력 추정해 앱이 스스로 글자·버튼·플로우 재배치 | 사용자 텔레메트리 + LLM UX 생성 | 모든 시니어가 같은 화면? No |

---

## 2. 분야 2 — 불완전판매 예방

### 2.1 시장 현황·핵심 통계

| 지표 | 값 |
|------|---:|
| 홍콩H ELS 은행권 판매 잔액 | 약 15.9조 원 (전체 19.3조) |
| 홍콩 ELS 손실 (2024.9 기준) | 다수 은행 합산 수조 원대 |
| 우리은행 포함 은행권 과징금 위기 | 약 1.4조 원 (현재 원점 재검토) |
| 2025년 금감원 소비자보호 실태평가 '미흡·보통' 은행 | 우리·케이·광주·수협(보통), 신한·토스(미흡) |
| 국민성장펀드 출시 (5/22) 5대 은행 판매 한도 | 2,200억 원 (KB 650, 신한/하나/우리 각 450, NH 200) |

### 2.2 최근 사건·정책

- **2026.05.13**: 금융위가 금감원의 홍콩 ELS 제재안(과징금) **이례적 반려**, 원점 재검토
- **2026.05.20**: 금융위 권대영 부위원장 주재로 은행·증권 판매사 소집, 국민성장펀드 출시 전 최종 점검 — "전산장애·불완전판매 차단 총력"
- **2026.03**: 금감원 이찬진 원장 "은행 올해 최우선 과제 = 소비자보호"
- **금소법 6대 의무**: ①설명의무 ②적합성 ③적정성 ④부당권유 금지 ⑤광고 규제 ⑥이해 확인

### 2.3 경쟁사 동향

| 은행 | 도입 시스템 | 비고 |
|------|-------------|------|
| **신한은행 (그룹 전체)** | **완전판매 AI 스크립트**, AI 해피콜, 신녹취시스템 | ELS·DLF 사태 이후 가장 빨리 구축, 사실상 표준 |
| **신한투자증권** | 신녹취시스템 + AI 해피콜 (가입 후 검증) | 사후 검증 강점 |
| **KB국민** | AI 자산관리 케이봇쌤 — AI 추천 비중이 PB(45%)를 넘어 55% | 적합성 자동 평가 일부 |
| **하나** | 소비자보호그룹장 부행장 격상 (조직 강화) | 시스템 미디어 노출 적음 |
| **우리카드** | 보이스피싱·불완전판매 통합 내부통제 강화 (영업 출신 김 상무) | 우리은행은 상대적으로 약함 |

### 2.4 활용 가능 AI 기술

#### A. RAG 기반 적합성 자동 평가
- **상품 약관·운용보고서·과거 손익 DB** → 벡터DB(MongoDB Vector, Chroma, Pinecone, Weaviate)
- 고객 프로필(나이·소득·자산·투자경험·KYC) → LLM이 적합성 점수 + 근거 생성
- **출력**: 직원용 풀 보고서 + 고객용 plain-language 3~5개 핵심 요인 (CFPB 권고 패턴)

#### B. 시뮬레이션 기반 설명
- 가입 직전, 본인 자산·시나리오로 **6/12/24개월 후 손익 시각화**
- "홍콩 지수 -25% 시 당신의 통장: 1억 → 6,400만 원" 같은 구체적 미래
- **Generative Video**: Remotion(React), Lottie, D3.js + LLM 시나리오 + TTS

#### C. Plain Language Disclosure (이중 출력)
- EU AI Act 2026.08.02 발효 → 고위험 금융 = 신용평가는 의무화
- **두 가지 출력 강제**: ①규제·내부용 풀 기술 버전 ②고객용 3~5개 요인 평어 버전
- LLM 활용 적격성 매우 높음 (요약·번역·언어 단순화)

#### D. 가입 후 역검증 (Post-Sale Verification)
- 가입 직후 24h 안에 AI가 전화/앱으로 "당신이 가입한 상품, 이런 위험 있는데 이해하셨어요?" 질문
- 응답이 핵심 사항 모르면 → 청약철회 가이드 자동
- **신한의 AI 해피콜과의 차별점**: 신한은 스크립트 기반, 우리는 **고객 응답 LLM 채점**

### 2.5 오픈소스·논문

- **mburaksayici/FinancialAdvisorGPT** — RAG + MongoDB VectorDB + Chroma + FastAPI + LangChain + React (보일러플레이트 그대로 활용 가능)
- **roy2392/Real-Time-pipeline-LLM-Financial-Advisor** — 실시간 RAG 파이프라인 + LLMOps
- **iusztinpaul/hands-on-llms** — 실시간 금융자문 LLM 시스템 (튜토리얼 + 코드)
- **kennethleungty/Finance-LLMs** — 금융권 LLM 실제 도입 사례 종합
- **simranjeet97/LLM-RAG_Finance_UseCases** — 금융 도메인 GenAI 케이스 모음
- **EU AI Act** 2026.08.02 발효 — 우리은행 PT에서 인용하면 가산점

### 2.6 아이디어 후보

| # | 한 줄 컨셉 | AI 활용 핵심 | 차별화 |
|---|------------|---------------|--------|
| 2-A | **AI 적합성 디스클로저** — 모든 상품 가입 직전 본인 데이터로 시뮬레이션 + 평어 3줄 요약 | LLM + 시뮬레이션 + Remotion 영상 | 신한은 스크립트, 우리는 미래 시각화 |
| 2-B | **가입 후 24h LLM 역검증** — 고객이 진짜 이해했는지 LLM이 채점 | 음성 STT + LLM 채점 | 신한 AI 해피콜의 약점 정조준 |
| 2-C | **국민성장펀드 5/22 즉시 적용 가능한 적합성 AI** — 출시 D-2 직격 시의성 | RAG + 적합성 의사결정 트리 | PT에서 "내일이라도 도입" 어필 |
| 2-D | **직원 적합성 KPI** — 판매 후 성과·민원·이탈을 추적해 직원별 적합성 점수 | 시계열 ML + 직원 평가 시스템 | 영업 KPI를 판매액이 아닌 적합성으로 |
| 2-E | **고위험 상품 → AI 카운슬러 의무 매칭** — 일정 위험도 이상은 AI가 1차 적합성 통과해야 가입 가능 | 우리GPT 기반 카운슬러 페르소나 | "기계가 한 번 더 막는다" 신뢰 |

---

## 3. 분야 3 — 민원 예방

### 3.1 시장 현황·이슈

- **챗봇 도입 보편화 + 만족도 하락**: 머니투데이 "차라리 상담원 바꿔줘" — AI 챗봇 한계 명확
- **콜센터 노조 교섭권 인정** (2026.04) → 노봉법 이슈로 AI 도입 진통
- **공공운수노조 실태조사**: 업무 전체 자동화 AI 콜봇은 고객 만족도 ↓, 강성민원 처리 어려움
- 디지털 약자에게 챗봇은 **"AI 장벽"** — 컨슈머뉴스 시리즈
- **신한은행 22년 연속 우수콜센터** (콜센터 품질이 곧 민원 예방)

### 3.2 경쟁사 동향

| 회사 | 시스템 | 강점 |
|------|--------|------|
| **KT AICC** | 음성인식 + TTS + 텍스트 분석 + 대화엔진, 10초 통화 요약, 폭언 자동 종료 | 솔루션 판매 |
| **신한은행** | 그룹통합 AICC + AI 감정분석 + AI 콜봇 | 22년 우수콜센터 |
| **iM뱅크** | AI 은행원 '한아름' + 컨시어지 + 재무 AI | iM GPT 폐쇄망 |
| **카카오뱅크** | 1차 응대 챗봇·보이스봇, 단순 잔액·비밀번호는 자동화 | 데이터·UX 강점 |
| **우리금융캐피탈** | 고객분석부 + 챗봇·콜봇 — AI 인프라 구축 중 (2026.05) | 후발주자 |
| **애큐온저축은행** | CCM 인증 + 민원 유형별 발생 원인 분석 | 작은 곳이 더 빠름 |

### 3.3 활용 가능 AI 기술

#### A. 민원 예측 (Pre-empt Complaint)
- **거래 직후 → 민원 발생 확률 예측** ML 모델
- 입력: 거래 유형, 채널, 직원, 고객 세그먼트, 응대 시간, 이전 민원 이력
- 출력: 24h 안에 민원 발생 확률 + 선제 조치 제안 (예: 안내 SMS, 직원 follow-up)
- 깃허브 다수: Bank Customer Churn Prediction (ANN/XGBoost/RF) — 이걸 민원 예측으로 전환

#### B. 콜센터 감정·맥락 분석
- 실시간 STT + 감정 인식 + 의도 분류 → 직원에게 코칭 메시지
- 강성민원 사전 감지 → 상위 직원 즉시 투입
- 직원의 감정노동 보호 (폭언 자동 차단, 휴식 권고)

#### C. 민원 클러스터링 + 근본원인 분석
- 전체 민원 텍스트를 임베딩 → 클러스터링 → **"이번 달 가장 늘어난 민원 유형 TOP 5"** 자동 리포트
- 우리GPT에 얹으면 임원 보고용 슬라이드 자동 생성
- 시스템·상품·직원·정책의 **근본 원인 매핑**

#### D. AI 후견인 (Senior Advocate)
- 디지털 약자가 챗봇에 막혔을 때 → AI가 **사람 상담원으로 즉시 전환 + 컨텍스트 100% 전달**
- "AI 장벽"이 아니라 **"AI가 안내자 역할"**
- 우리GPT 활용 적합

### 3.4 오픈소스·논문

- **GitHub topics: bank-customer-churn / customer-churn-prediction** — ANN, XGBoost, SMOTE 다수
- **FridahKimathi/Bank-Customer-Churn-Prediction**
- **zunicd/Bank-Churn-Prediction** — 7개 모델 대시보드 (LR, DT, RF, DL, KNN, SVM, XGBoost)
- **sanskaryo/Churn-Prediction-Using_ANN** — Streamlit 데모 (PT용 빠른 시각화)
- 깃허브에서 NLP 민원 예측 직접 매칭은 적음 → **민원 = 이탈 직전 시그널**로 churn 모델 재해석

### 3.5 아이디어 후보

| # | 한 줄 컨셉 | AI 활용 핵심 | 차별화 |
|---|------------|---------------|--------|
| 3-A | **민원 24h 예측 + 자동 선제 응대** | 거래/채널/응대 데이터 ML + LLM 메시지 자동 생성 | 응대 이후 24h 안에 끊기 |
| 3-B | **민원 근본원인 LLM 분석 → 임원 일일 리포트** | 임베딩 + 클러스터링 + LLM 요약 | 우리GPT 위에 얹기 |
| 3-C | **AI 후견인 (Senior Advocate)** — 챗봇 막힌 시니어 즉시 사람 + 컨텍스트 인계 | 의도분석 + STT + 컨텍스트 전달 | "AI 장벽" 비판 정면 돌파 |
| 3-D | **민원 발생 전 직원 코칭** — 실시간 응대 중 LLM이 직원 이어폰에 위험 신호 | 실시간 STT + LLM 코칭 | 강성민원 사전 차단 |
| 3-E | **민원 데이터 → 상품/약관 개선 자동 제안** | 민원 클러스터 → 약관 차이 매핑 → 개정안 LLM 생성 | 사후 처리에서 상품 개선까지 |

### 3.6 위험요소

- **3분야가 가장 평범** — 챗봇/AICC는 이미 모든 은행이 구축. 신선도 부족
- 챗봇 = 비용 절감 도구 인식 — 사용자/직원 모두에게 부정적 정서
- **승부수 부족하면 광탈**

---

## 4. 분야 4 — 금융사기 (보이스피싱) 예방

### 4.1 시장 현황·핵심 통계

| 지표 | 값 |
|------|---:|
| 2025년 1분기 보이스피싱 피해액 | 3,116억 원 (전년比 2.2배 급증) |
| 모바일 폰 통한 보이스피싱 비중 | 68% (전체 공격) |
| AI 음성 클로닝 최소 샘플 | 3초 |
| 싱가포르 2025 금융사기 피해 | 약 USD 7.21억 |
| AI 통화 분석 솔루션 비용 (사기범) | $40/월 보이스 클로닝 구독으로 가능 |

### 4.2 최근 사건·정책

- **2026.05.06**: 신한금융 그룹 FDS 연계 — 2주 만에 8억 원 피해 예방
- **2026.04.07**: 인터넷은행 3사(케뱅·카뱅·토스) 보이스피싱 대응 **AI 연합 모델 6월 적용**
- **2026.04.06**: KB국민은행 + 통신사 협업 실시간 보이스피싱 탐지 (통화 분석 → 즉시 지급정지)
- **2026.04.24**: 신한투자증권 통화패턴 AI 분석 솔루션 하반기 오픈
- **2025.10**: SK텔레콤 익시오 2.0 — **온디바이스 실시간 보이스피싱 탐지 + 위험 URL + AI 전화 대신 받기**
- **2025**: 케이뱅크 + KT 협력 AI 보이스피싱 실시간 탐지
- **2026**: 우리금융 청년층 보이스피싱 선제 대응 (자체 1순위 선언)

### 4.3 경쟁사 동향 (이 분야는 레드오션)

| 회사 | 시스템 | 강점 |
|------|--------|------|
| **신한금융 그룹** | 그룹 FDS 연계, **AI 이상행동탐지 ATM** (연령대별 패턴 + 통화/복장 변화 영상 분석) | 가장 앞섬 |
| **KB국민** | 통신사 협업 실시간 통화 분석 + 지급정지 | 통신사 시너지 |
| **케이뱅크** | KT 협력 + AI FDS — 2025 피해 예방 다수 | 비대면 특화 |
| **카카오뱅크** | AI 세이브콜 (음성인식 사기 예방) | 7월부터 현직 경찰 |
| **인뱅 3사 연합** | 6월 AI 연합 FDS — 중소금융권까지 공유 예정 | 데이터 풀링 |
| **SK텔레콤** | 익시오 2.0 — 온디바이스, 갤럭시 S26 기본 탑재 | 통신사 표준 |
| **신한투자증권** | 통화패턴 AI (하반기) | 후속 단계 |
| **우리은행** | 아직 두드러진 자체 보이스피싱 AI 부재 (불법사금융 예방 캠페인 위주) | **후발주자 — 절박** |

### 4.4 활용 가능 AI 기술

#### A. 멀티모달 음성 탐지
- **MFCC + CNN/BiLSTM** + **KoBERT** 텍스트 분류 → 멀티모달 분류기
- **음성 합성/딥페이크 탐지**: YAMNet, RawNet 기반
- 한국어 데이터셋: **KorCCVi**

#### B. 통화 패턴 LLM 분석
- **GPT-4o로 보이스피싱 시나리오 데이터 증강** (IEEE 2026 논문)
  - 금감원 사례 보고서 + KorCCVi → 한국어 시나리오 자동 생성
  - 미확보 사기 패턴까지 학습 (non-phishing 변형 생성)
- 통화 중 키워드(검찰/금감원/대포통장/원격제어/USDT/캄보디아) 실시간 트래킹

#### C. 온디바이스 LLM (개인정보 보호 + 실시간성)
- **VishielDroid**: Android 온디바이스, F1=99.78%
- 폰에서 직접 처리 → 통신사 의존 없이 우리은행 앱이 자체 보호 가능
- 양자화(quantization)로 모바일 인퍼런스 시간 단축

#### D. FDS 차세대 — 행동 + 환경 + 거래 융합
- 기존: 거래 패턴 중심
- 진화: 인증 과정(SIM 변경 직후·새 단말·새 IP) + 이용 환경 + 거래 + **통화 패턴** 종합 분석
- 행동 바이오메트릭스 결합 (BioCatch, Sardine 모델)

#### E. AI 미끼봇 / 피싱 백신 (창의 영역)
- **미끼봇 (Honeybot)**: 의심 통화 감지 시 AI가 피해자 척하면서 사기범 시간 끌고 통신 패턴 수집
- **피싱 백신**: 동의한 사용자에게 우리은행이 가짜 피싱 전화 → 면역 훈련 + 한도 인센티브
- 합법성·윤리 답변 준비 필수

### 4.5 오픈소스·논문

#### 깃허브
- **Mrkomiljon/voiceguard** — RawNet 실시간 보이스피싱 탐지 (가장 적합)
- **Srujan-rai/Deepfake_voice_detection** — CNN 기반
- **Srujanrana07/DeepFake-Voice-Detection** — MFCC+CNN+RF+KNN, ~98% (SceneFake 데이터셋)
- **KaushiML3/Deepfake-voice-detection_Yamnet** — YAMNet 기반
- **zo9999/deepfake-audio-detector** — CNN 94%

#### 논문
- **IEEE 2026** — *Enhanced Voice Phishing Detection Using an LLM-Based Framework for Data Augmentation and Classification* (GPT-4o + KorCCVi)
- **MDPI 15(20):11170** — *Multimodal Voice Phishing Detection System Integrating Text and Audio Analysis* (KoBERT + MFCC + CNN-BiLSTM)
- **Springer J. Ambient Intelligence (2021)** — *Real-time Korean voice phishing detection based on ML*
- **ScienceDirect S0167404825000537** — *The silence of the phishers: Early-stage voice phishing detection with runtime permission requests*
- **arxiv 2409.06348** — *VoiceWukong: Benchmarking Deepfake Voice Detection*

#### 데이터셋
- **KorCCVi** — 한국어 보이스피싱 통화 전사 (가장 핵심)
- **SceneFake** — 합성 음성
- 금감원 사기 사례 보고서 (공개)

### 4.6 아이디어 후보

| # | 한 줄 컨셉 | AI 활용 핵심 | 차별화 |
|---|------------|---------------|--------|
| 4-A | **송금 90초 시뮬레이션** — 이 돈이 어디로 가는지 영상으로 | Remotion + LLM + TTS + 위험점수 | 가장 시각적 임팩트 |
| 4-B | **피싱 백신** — 우리은행이 거는 가짜 피싱 + 한도 인센티브 | LLM 시나리오 + TTS + 게이미피케이션 | 면역 메타포 신선 |
| 4-C | **온디바이스 미니 LLM** — 통신사 의존 없이 우리은행 앱이 직접 통화 분석 | VishielDroid·voiceguard 응용 + 양자화 | KB는 통신사 의존, 우리는 자립 |
| 4-D | **AI 미끼봇** — 피해자 척하며 사기범 시간 끌고 콜센터 역추적 | LLM 페르소나 + 음성 합성 + 통화 분석 | 방어→역공, 법적 답변 필수 |
| 4-E | **시니어 가족 워치** — 부모 통화 의심 키워드 자녀에 실시간 알림 | 온디바이스 STT + 키워드 분류 | 1분야와 융합 가능 |
| 4-F | **자립준비청년 전용 사기 면역앱** — 우리금융 6월 행사 직격 | LLM 시나리오 + 청년 톤 매니지 | 우리은행 직접 발표한 우선순위 |

---

## 5. 4개 분야 종합 평가 매트릭스

### 5.1 분야별 핵심 지표

| 평가 항목 | 1.취약계층 | 2.불완전판매 | 3.민원 | 4.보이스피싱 |
|-----------|:-:|:-:|:-:|:-:|
| 사회적 절박감 | ★★★★★ (172조) | ★★★★ (1.4조 과징금) | ★★★ (만성) | ★★★★★ (3,116억 1Q) |
| 우리은행 약점 직격 | ★★★★ | ★★★★★ (ELS 과징금) | ★★★ | ★★★★ (자산 부족) |
| 우리은행 명시 우선순위 | ★★★★★ (하반기 핵심) | ★★★ | ★★ | ★★★★★ (현재 1순위) |
| 경쟁사 진입도 | ★★★ (KB만 앞섬) | ★★★★ (신한 선점) | ★★★★★ (포화) | ★★★★★ (레드오션) |
| AI 기술 신선도 | ★★★★ | ★★★ | ★★ | ★★★ |
| 차별화 여지 | ★★★★ | ★★★ | ★★ | ★★★ |
| 데모 임팩트 가능성 | ★★★★ | ★★★★ | ★★ | ★★★★★ |
| 기술 구현 난이도(낮을수록↑) | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| Q&A 위험 (낮을수록↑) | ★★ (의료·윤리) | ★★★★ | ★★★★ | ★★★ (윤리) |
| **종합 1등 확률** | **★★★★** | **★★★★** | **★★** | **★★★** |

### 5.2 한 줄 평

| 분야 | 한 줄 |
|------|------|
| 1. 취약계층 | **시장 거대·우리은행 하반기 핵심·KB 외 공백** — 가장 균형 잡힌 한방 |
| 2. 불완전판매 | **우리은행 약점 직격·시의성 폭발** — 단, 신한 AI 스크립트와 정면 충돌 |
| 3. 민원 | **AI 챗봇 시장 포화·신선도 부족** — 평범한 선택 |
| 4. 보이스피싱 | **사회적 절박감 최고·경쟁사 즐비** — 차별화 못 하면 광탈 |

---

## 6. 기술 스택 카탈로그 (구현 단계 참고)

### 6.1 LLM/RAG 스택

| 컴포넌트 | 후보 |
|----------|------|
| 베이스 모델 | Claude (claude-sonnet-4-6 / claude-opus-4-7), GPT-4o, Gemini, Llama 3.1, EXAONE 3.5 (한국어) |
| 한국어 특화 | EXAONE 3.5 (LG AI Research), KoBERT, KoGPT, Polyglot-Ko |
| 벡터DB | Chroma, Pinecone, Weaviate, MongoDB Atlas Vector, pgvector |
| 프레임워크 | LangChain, LlamaIndex, Haystack |
| 평가 | RAGAS, TruLens |

### 6.2 음성 처리

| 작업 | 도구 |
|------|------|
| STT | Whisper, Clova Speech, Google STT |
| TTS | ElevenLabs, OpenAI TTS, Clova Voice, Naver Voice |
| 음성 인증/탐지 | YAMNet, RawNet, Wav2Vec2, MFCC |
| 딥페이크 탐지 깃허브 | voiceguard, DeepFake-Voice-Detection, deepfake-audio-detector |

### 6.3 영상/시각화 (PT 데모용)

| 도구 | 용도 |
|------|------|
| **Remotion** (React) | 동적 데이터 → 영상 (SSAFY 친화) |
| Lottie | 무료 애니메이션 템플릿 + 데이터 주입 |
| D3.js | 거래 패턴 시각화 |
| Three.js | 3D 시나리오 |
| Recharts/Chart.js | 손익 시뮬레이션 차트 |

### 6.4 ML/FDS

| 작업 | 도구 |
|------|------|
| 이상거래 탐지 | XGBoost, LightGBM, Isolation Forest, LSTM Autoencoder |
| 행동 바이오메트릭스 | 자체 구현 (BioCatch/Sardine은 상용) |
| 시계열 | Prophet, NeuralProphet, sktime |
| Drift 감지 | Evidently AI, river |

### 6.5 백엔드/프론트엔드 (SSAFY 친화)

| 영역 | 후보 |
|------|------|
| 백엔드 | Spring Boot, FastAPI, Node.js |
| 프론트 | React, Vue, Flutter, Next.js |
| 모바일 데모 | React Native, Flutter, Expo |
| 인프라 | Docker, AWS Lambda, Vercel, Hugging Face Spaces |

---

## 7. 데이터셋·참고자료 정리

### 7.1 공개 데이터셋
- **KorCCVi** — 한국어 보이스피싱 통화 (보이스피싱 분야 필수)
- **SceneFake** — 합성 음성 데이터셋
- **금감원 보이스피싱 사례 보고서** — 공개 자료
- **Kaggle Bank Customer Churn Modeling** — 민원 예측 base
- **PhonePe transactions** — 시계열 거래 패턴 예제
- **금감원 분쟁조정사례** — 민원 NLP 학습용

### 7.2 핵심 논문 (PT 인용용)
1. IEEE 2026 — LLM voice phishing detection (GPT-4o + KorCCVi)
2. MDPI 2024 — Multimodal Korean voice phishing (KoBERT+MFCC)
3. ScienceDirect 2026.04 — Cognitive liquidity trap (38% 사기 감소)
4. PMC8721598 — Mild Cognitive Decline as Scam Vulnerability
5. arxiv 2505.02519 — Deaf in AI: linguistic rights
6. EU AI Act 2026.08.02 — 고위험 금융 의무 (인용하면 가산점)

### 7.3 깃허브 시작점 (Top 7)
1. **Mrkomiljon/voiceguard** — 보이스피싱 (RawNet)
2. **mburaksayici/FinancialAdvisorGPT** — RAG 보일러플레이트
3. **iusztinpaul/hands-on-llms** — LLMOps 학습용
4. **Srujanrana07/DeepFake-Voice-Detection** — 98% 정확도 디포 탐지
5. **zunicd/Bank-Churn-Prediction** — 7개 ML 모델 대시보드
6. **kennethleungty/Finance-LLMs** — 금융 LLM 도입 사례
7. **simranjeet97/LLM-RAG_Finance_UseCases** — GenAI 금융 케이스

### 7.4 우리은행 PT 인용용 외부 사실
- 신한 그룹 FDS 2주에 8억 피해 예방 (2026.05.06)
- 인뱅 3사 6월 AI 연합 FDS
- 갤럭시 S26 익시오 2.0 온디바이스 보이스피싱
- 케뱅·카뱅 통신사 협업 모델
- 우리금융 2026년 1차 소비자보호 세미나 우선순위

---

## 8. 결론: 1등 후보 주제 압축

### 8.1 Top 3 추천

#### 🥇 후보 1. **시니어 인지케어 + 보이스피싱 융합** (1분야 메인 + 4분야 흡수)
- **핵심:** "엄마 안심 금고 (Family Consent Vault)" + AI 인지 트래커 + 자녀 알림
- **차별화:** KB 인지검사(일회성)·휴머노이드(돌봄)와 다른 **연속 모니터링 + 사전합의 게이트**
- **AI 활용:** LSTM Autoencoder + 우리GPT + STT + RAG
- **데모:** 시니어 페르소나 + 거래 drift 시각화 + 가족 인증 화면
- **위험:** 의료기기 규제 답변, "치매 진단 아닌 위험 알림" 프레이밍

#### 🥈 후보 2. **AI 적합성 디스클로저 + 가입 후 LLM 역검증** (2분야)
- **핵심:** 가입 직전 본인 데이터 시뮬레이션 + 평어 3줄 + 24h 후 LLM이 이해도 채점
- **차별화:** 신한 AI 스크립트(가입 시점) 약점인 **사후 검증·미래 시각화**
- **AI 활용:** RAG (상품 약관) + LLM 시뮬레이션 + Remotion 영상 + STT 채점
- **시의성:** 국민성장펀드 5/22 출시 + EU AI Act 8/2 발효 + 우리은행 ELS 과징금
- **위험:** 비교 대상이 신한 → 차별화 명확해야

#### 🥉 후보 3. **송금 90초 시뮬레이션** (4분야 메인 + 1·2분야 흡수)
- **핵심:** 일정 금액 이상 송금·상품 가입 직전 AI가 90초 시나리오 영상 즉석 생성
- **차별화:** 모든 경쟁사가 "막기"인데 우리는 "보여주기" (행동경제학)
- **AI 활용:** Remotion + LLM + TTS + 위험점수
- **데모 임팩트:** 무대에서 즉석 생성 시연 가능
- **위험:** "Sora급 즉석 생성" 약속 금지 → **하이브리드 동적 합성**으로 정직하게 포지셔닝

### 8.2 다음 단계
이 리서치 기반으로 사용자가 1개 후보를 골라야 합니다. 선택 후:
1. 문제정의 → 데이터셋·아키텍처 확정
2. 15쪽 PPT 목차 + 한 줄 슬로건
3. 데모 시나리오 3개 (청년/시니어/직장인)
4. Q&A 예상 질문 10개 + 답변
5. 5/25 응모용 PPT → 6/5 라이브 데모

---

## 참고 출처

### 한국 뉴스 (Naver, 2026.05 기준 핵심)
- 우리금융 2026.05.14 제1차 금융소비자보호 세미나 (아시아 etc)
- 신한금융 그룹 FDS 8억 피해 예방 (글로벌이코노믹 2026.05.06)
- 인뱅 3사 AI 연합 모델 6월 적용 (헤럴드 2026.04.07)
- KB통신사 협업 보이스피싱 실시간 탐지 (시사저널e 2026.04.06)
- SK텔레콤 익시오 2.0 온디바이스 (뉴스웍스 2026.03.06)
- 치매머니 172조 (서울경제 등 다수)
- 우리은행 4대 공적연금 비대면 (한국일보 2026.05.13)

### 해외/학술
- [IEEE 2026 — LLM Voice Phishing Detection](https://ieeexplore.ieee.org/document/11142247/)
- [MDPI — Multimodal Korean Voice Phishing](https://www.mdpi.com/2076-3417/15/20/11170)
- [ScienceDirect 2026.04 — Cognitive liquidity trap](https://www.sciencedirect.com/science/article/pii/S2451958826001296)
- [Springer — Korean Voice Phishing ML](https://link.springer.com/article/10.1007/s12652-021-03587-x)
- [PMC10913197 — AI for neurocognitive disorders](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10913197/)
- [PMC8721598 — Cognitive Decline & Scam](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8721598/)
- [arxiv VoiceWukong](https://arxiv.org/pdf/2409.06348)
- [Signapse — Deaf telephone banking](https://www.signapse.ai/post/end-of-telephone-banking-and-what-it-means-for-deaf-people)
- [Alkami — AI-Driven Elder Scams](https://www.alkami.com/blog/banking-fraud-prevention-in-the-age-of-ai-driven-elder-scams/)
- [BioCatch](https://www.biocatch.com/)
- [EU AI Act Aug 2026](https://artificialintelligenceact.eu/)

### 깃허브
- [Mrkomiljon/voiceguard](https://github.com/Mrkomiljon/voiceguard)
- [Srujanrana07/DeepFake-Voice-Detection](https://github.com/Srujanrana07/DeepFake-Voice-Detection)
- [KaushiML3/Deepfake-voice-detection_Yamnet](https://github.com/KaushiML3/Deepfake-voice-detection_Yamnet)
- [mburaksayici/FinancialAdvisorGPT](https://github.com/mburaksayici/FinancialAdvisorGPT)
- [iusztinpaul/hands-on-llms](https://github.com/iusztinpaul/hands-on-llms)
- [kennethleungty/Finance-LLMs](https://github.com/kennethleungty/Finance-LLMs)
- [zunicd/Bank-Churn-Prediction](https://github.com/zunicd/Bank-Churn-Prediction)
