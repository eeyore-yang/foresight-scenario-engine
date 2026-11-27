# AI 가속화 근거 묶음 v0.1
2026-11-27. 기존 116개 관측과 분리한 14개 근거 묶음. 재사용 자료(IEA, MIT 등) 및 복수 연구를 포함하므로 독립 신규 관측 14개로 합산하지 않는다. 현재 열람한 공개 HTML·연구 초록과 검색 결과 기반이며 원자료/첨부 PDF는 분석하지 않았다. 수치는 각 연구의 조건 안에서만 유효하다.

## A01 — 한국의 실제 도입과 업무시간
한국은행 이슈노트 2026-29, 2026-11-17 공식 요약: 근로자 업무용 생성형 AI 활용률 2025년 51.8%, 2026년 66.5%; 평균 업무시간 절감률 3.8%→9.2%(주40시간 환산 1.5→3.7시간). 핵심업무 활용 제한, 시간절감과 산출량·품질 개선의 약한 상관. 고학력·유료 구독자의 절감 효과가 상대적으로 큼.
출처: [한국은행 공식 요약](https://www.bok.or.kr/portal/bbs/P0002353/view.do?depth=200433&menuNo=200433&nttId=11066699&oldMenuNo=201150&programType=newsData&relate=Y).
유형: 대표 표본 설문/패널 분석 요약. 실측 노동시간 단축, GDP 향상, 인과효과로 해석하지 않음. 첨부 PDF 미검토. 연결 K01/K02/K05.

## A02 — 실제 업무 생산성 향상
2025 QJE 연구: 고객지원 직원 5,172명의 순차적 도입 자료. 시간당 해결 건수 평균 15% 증가, 근로자별 이질성.
출처: [QJE](https://doi.org/10.1093/qje/qjae044), [Stanford](https://digitaleconomy.stanford.edu/publication/generative-ai-at-work/).
유형: 현장 도입 연구. 단일 업무 환경, 전체 고용/임금/기업 조직 대체율 아님. 2023 working paper의 14%와 최종 15% 구별. 연결 K01/K05.

## A03 — 검증·통합 비용의 반례
METR 2025년 초 RCT: 숙련 오픈소스 개발자 16명, 246개 작업에서 AI 허용 시 완료 시간이 19% 증가. 2026-02-24 후속 발표는 2025년 말 도구로 속도 향상 가능성이 있지만 모집/작업 선택 편향으로 효과 크기를 정확히 추정하기 어렵다고 설명.
출처: [2025 초록](https://arxiv.org/abs/2507.09089), [2026 후속](https://metr.org/blog/2026-02-24-uplift-update/).
유형: 소규모 RCT 및 후속 실험 방법 논의. 현재 도구의 성능 수치로 사용 금지. 연결 K01/K09.

## A04 — 에이전트의 과업 시간과 현실 전이
METR의 task-completion horizon은 인간 전문가가 완료하는 데 걸리는 시간으로 과업 난도를 표현하고 특정 성공률에서의 과업 길이를 추정한다. 2026-11-20 업데이트는 R&D 관련 역량의 향상과 평가·실제 연구 사이의 한계(장기 맥락, 일반화, 전문가 검증, 평가 환경)를 설명한다.
출처: [METR 시간 지평](https://metr.org/time-horizons/), [2026-11 업데이트](https://metr.org/blog/2026-11-20-q4-2026-capability-update/).
유형: 벤치마크 및 평가기관 분석. 연속 자율 실행 시간, 사람 대체율, 실제 R&D 성장률이 아니다. 연결 K01/K09/K11.

## A05 — 학습 결과와 수행의 분리
2025 PNAS 고교 수학 현장 실험: 약 1천 학생 대상, 일반 GPT 도구와 학습 보호형 튜터를 구분. 도구 이용 중 수행 개선과 도구를 제거한 뒤 학습 결과 악화 가능성을 함께 발견하고 보호 설계의 중요성을 강조했다.
출처: [PNAS](https://doi.org/10.1073/pnas.2422633122), [Stanford SCALE](https://scale.stanford.edu/publications/generative-ai-can-harm-learning).
유형: 특정 학교/과목 실험, AI 전체가 학습을 해친다는 결론 아님. 연결 K01/K10.

## A06 — 로봇 보급과 물리적 자동화
IFR World Robotics 2026(2026-09-24 발표): 2025년 세계 산업용 로봇 운영 재고 약 508만대(+9%), 신규 설치 60.3만대(+11%).
출처: [IFR 발표](https://ifr.org/ifr-press-releases/news/five-million-robots-now-operate-in-factories-globally), [IFR 회장 보고](https://ifr.org/ifr-press-releases/news/presidents-report-by-jane-heffner-3-2026).
유형: 산업 통계. 모든 산업용 로봇이 생성형 AI 또는 범용 휴머노이드인 것은 아님. 서비스·가정·건설 현장으로 직접 외삽 금지. 연결 K01/K07.

## A07 — 노동소득과 자본소득
IMF 2024 분석은 AI와 고소득 노동의 보완성, 자본수익의 분배에 따른 불평등 경로를 제시한다. IMF 2025 working paper는 고소득 직업의 노출로 노동소득 격차가 줄 가능성도 자본수익 효과와 구별한다.
출처: [IMF 2024](https://www.imf.org/en/Publications/Staff-Discussion-Notes/Issues/2024/01/14/Gen-AI-Artificial-Intelligence-and-the-Future-of-Work-542379), [2025](https://www.imf.org/en/publications/wp/issues/2025/04/04/ai-adoption-and-inequality-565729).
유형: 모형/조건부 분석, 실제 AI에 의해 자산 격차가 늘어난 크기를 측정한 것이 아님. 연결 K02/K01.

## A08 — 컴퓨트의 지역·기업 집중
OECD 2026 Digital Economy and Society Outlook은 AI 가능 퍼블릭 클라우드 가용영역 추정에서 미국·중국 집중, 신흥경제 17%를 소개한다. 2026 AI markets는 칩·클라우드·데이터·에너지 등 공급 제약과 규모경제·전환비용을 다룬다.
출처: [OECD compute](https://www.oecd.org/en/publications/oecd-digital-economy-and-society-outlook-2026_022ed474-en/full-report/powering-ai-progress-the-future-of-compute_b4007d1b.html), [시장 보고](https://www.oecd.org/en/publications/artificial-intelligence-markets_d531d73f-en/full-report.html).
유형: 시장·인프라 분석. 가용영역 수는 FLOPS, 실제 사용량, 국가의 통제력과 다름. 연결 K02/K06/K11.

## A09 — 효율 개선과 총수요의 증가
IEA 2026-04-16 보고서: 세계 데이터센터 전력수요 2025년 17% 증가, AI 과업당 전력 소비는 빠르게 감소한다고 설명. 001-M04의 자료와 중복.
출처: [IEA 요약](https://www.iea.org/reports/key-questions-on-energy-and-ai/executive-summary), [발표](https://www.iea.org/news/data-centre-electricity-use-surged-in-2025-even-with-tightening-bottlenecks-driving-a-scramble-for-solutions).
유형: 집계 및 기술 분석. 데이터센터 전체 전력과 AI만의 전력 구분; 효율이 총수요 증가의 원인이라는 인과 추정 아님. 연결 K07/K06/K08.

## A10 — 과학적 탐색의 가속
2024 Nature AlphaFold 3 논문: 단백질·핵산·리간드 등 복합체 구조 예측 성능 향상 보고.
출처: [Nature](https://www.nature.com/articles/s41586-024-07487-w).
유형: 모델 개발 연구와 구조 예측 평가. 실제 임상 효과, 약물 개발 성공률·기간, 과학 전체 성장률과 다름. 실험 검증과 생산/허가 별도. 연결 K07/K04/K08.

## A11 — 실제 의료의 긍정적 효과
스웨덴 MASAI 무작위 검진 연구 2025 발표: AI 지원 유방촬영 검진의 암 발견 1천명당 6.4 대 5.0, 판독 작업량 44% 감소 및 유사한 위양성률. 2026년 간격암 평가도 별도 출판됨(이번에는 결과 수치 인용하지 않음).
출처: [2025 연구](https://doi.org/10.1016/s2589-7500%2824%2900267-x), [2026 연구](https://pubmed.ncbi.nlm.nih.gov/41620232/).
유형: 특정 검진 경로 RCT. 장기 사망률 감소, 전체 의료 대체, 모든 집단의 효과로 외삽 금지. 연결 K03/K04/K05.

## A12 — 인간과 AI의 정서적 관계
JCR 2026 권호 연구(2025 온라인 공개)는 일주일간 AI 동반자 사용 후 순간적 외로움 감소를 보고. 2026 Psychological Science 12개월 관찰(서구 4개국, 2천명 이상)에서는 일부 외로움 측정에서 AI 동반자 사용 증가와 이후 외로움 증가의 연관성이 나타났다. 001-U06의 MIT/OpenAI 4주 연구도 참조.
출처: [JCR](https://doi.org/10.1093/jcr/ucaf040), [12개월 연구](https://pubmed.ncbi.nlm.nih.gov/41870975/), [MIT](https://www.media.mit.edu/publications/how-ai-and-human-behaviors-shape-psychosocial-effects-of-chatbot-use-a-longitudinal-controlled-study/).
유형: 서로 다른 실험·관찰, 시간과 지표 차이. 관계의 장기 대체 또는 외로움의 인과를 단정하지 않는다. 연결 K05/K04/K10.

## A13 — AI의 행정적 활용
OECD 2025 Governing with AI는 11개 정부 기능의 200개 사례를 분석해 효율, 접근 및 운영·윤리·배제 위험을 함께 다룬다.
출처: [OECD](https://www.oecd.org/en/publications/governing-with-artificial-intelligence_795de142-en/full-report/trends-and-early-lessons-from-the-use-of-ai-across-functions-of-government_c4968cb1.html).
유형: 선별 사례 분석, 전체 정부의 보급률·효과나 정부 형태의 우열 측정 아님. 연결 K03/K09/K11/K08.

## A14 — 숙의의 긍정적 가능성
Science 2024 Habermas Machine 연구: 5,734명 참여, AI 중재자가 생성한 공동 의견문을 인간 중재자 작성문보다 선호하는 경향. 가상 시민의회에서 재현했다.
출처: [Science 초록](https://pubmed.ncbi.nlm.nih.gov/39418380/), [DOI](https://doi.org/10.1126/science.adq2852).
유형: 실험, 실제 정치 제도에서 합의가 지속된다는 증거 아님. 연구자 소속/모형 설계 고려. 소수자 권리와 단순 선호·합의율을 구분. 연결 K11/K09.

## 미해결
AI 에이전트의 실제 기업 재편, 물리 로봇의 비구조화 현장 실적, 검증 포함 완결 비용 장기 추세, 노동·자본 배분의 실측, AI 과학 연구의 실험→허가→보급 효과, 한국의 친밀성·문화 및 공공 AI 구제 성과는 추가 독립 조사 필요.
