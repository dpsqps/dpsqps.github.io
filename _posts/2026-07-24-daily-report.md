---
layout: single
title: "📊 AI 일간보고서 — 2026년 07월 24일"
date: 2026-07-24 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "딥시크"
  - "AI인프라"
  - "에이전트안전성"
  - "의료AI"
  - "2026"
author_profile: false
read_time: true
toc: true
toc_label: "목차"
toc_sticky: true
header:
  overlay_image: "https://picsum.photos/seed/daily-ai-report/1600/500"
  overlay_filter: "0.6"
---

> **2026년 07월 24일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 07월 24일 AI 일간보고서

## 오늘의 핵심 요약

오늘의 소식에는 새 프런티어 모델 발표가 없습니다. 대신 **마감일, 공시, 제휴, 벤치마크 점수**가 자리를 채웠습니다. 딥시크는 오늘 15:59(UTC) 구형 API 별칭을 완전히 닫고, SK텔레콤은 7,500억원짜리 AI 데이터센터 자회사를 공시했으며, AMD와 세레브라스는 추론 파이프라인을 두 종류의 실리콘으로 쪼개는 제휴를 내놨습니다. 그 사이 arXiv에는 자율 에이전트의 정확도 천장이 **74.8%**라는 계량 결과가 올라왔습니다.

이 조합이 말해주는 것은 산업의 무게중심이 '무엇을 새로 만들었나'에서 **'만든 것을 어떻게 운영하고, 어디서 깨지는지 아는가'**로 넘어갔다는 사실입니다. 모델 출시 캘린더가 잠시 비면 그 자리에 운영·설비·검증의 청구서가 드러납니다. 오늘이 정확히 그런 날이었습니다.

## 주요 이슈 1: 신모델이 아니라 '별칭 폐기'가 오늘의 모델 뉴스다

딥시크는 공식 API 문서에서 `deepseek-chat`과 `deepseek-reasoner`가 **2026년 7월 24일 15:59(UTC) 이후 완전히 폐기되어 접근 불가**가 된다고 못박았습니다. 두 별칭은 현재 신형 **V4-Flash**로 라우팅되고 있어, 호출부에 모델명을 고정해두지 않은 서비스는 오늘을 기점으로 끊깁니다. 새로 표준이 되는 V4 계열은 **V4-Pro가 총 1.6조·활성 490억**, **V4-Flash가 총 2,840억·활성 130억** 파라미터의 MoE 구성이고, 컨텍스트는 모든 공식 서비스에서 **100만 토큰이 기본값**입니다.

여기서 짚어야 할 사실관계가 하나 있습니다. 여러 요약 매체가 오늘을 'DeepSeek V4 정식(스테이블) 출시일'로 소개했지만, 공식 문서에 그런 표현은 없습니다. 문서에 존재하는 것은 **4월 24일자 'V4 프리뷰 릴리스' 공지**와 그 안의 별칭 폐기 시한뿐이며, GA 일정은 공개되지 않았습니다. 차이는 실무에서 큽니다. GA라면 버전 고정과 SLA가 따라오지만, 프리뷰 상태 모델로 트래픽이 강제 이관되는 상황에서는 응답 특성 변화에 대한 회귀 테스트를 서비스 측이 전부 떠안습니다. [DeepSeek API Docs](https://api-docs.deepseek.com/news/news260424/)

## 주요 이슈 2: 자본은 모델이 아니라 '모델을 굴리는 층'으로 갔다

7월 23일 하루에 인프라 쪽 결정이 세 건 겹쳤습니다. **SK텔레콤**은 AI 데이터센터 자회사 **에스케이하이퍼** 설립을 공시하며 **187만 5,000주·7,500억원** 취득을 밝혔습니다. 자기자본(12조 9,552억원) 대비 **5.79%** 규모인데, 눈여겨볼 대목은 집행 방식입니다. 7월 중 **3,300억원을 우선 출자**하고 잔여 **4,200억원**은 사업 경과에 따라 순차 납입하되 최종 기한을 **2030년 12월 31일**로 뒀습니다. 한 번에 쏟아붓는 대신 4년 반에 걸쳐 수요와 부지·전력 확보 속도에 맞춰 흘려보내는 구조입니다.

**AMD와 세레브라스**는 추론을 아예 둘로 쪼갰습니다. AMD **Helios** 랙스케일이 고처리량 프롬프트 처리를, 세레브라스 **웨이퍼 스케일 엔진**이 초저지연 디코드를 맡는 분리형 구조로, 양사는 **와트당 초당 토큰 최대 5배** 향상을 기대한다고 밝혔습니다. 다만 이 수치는 2026년 7월 자체 **모델링 결과이며 실측이 아니라는 점**이 발표문에 명시돼 있습니다. 결합 솔루션은 **2026년 하반기 세레브라스 클라우드**에 먼저 올라갑니다. 여기에 **마이크로소프트–데이터브릭스**가 협력을 **2030년대까지 연장**하며 데이터 계층을 묶었습니다(데이터브릭스 사용 조직 **2만 개 이상**, 포춘 500의 **70%**, 최대 **50%** 성능 향상을 내세운 Cobalt 200 도입 예정).

한편 응용 쪽에서는 로보틱스 스타트업 **제네시스 AI**가 **프리머니 30억 달러**에 **약 5억 달러** 조달을 협의 중이라는 보도가 나왔습니다. 2025년 7월 **1억 500만 달러** 시드로 스텔스를 벗은 지 1년 만입니다. [데이터투자](https://www.datatooza.com/article/20260723172603607852ef3a3fcc_80) / [AMD IR](https://ir.amd.com/news-events/press-releases/detail/1293/amd-and-cerebras-announce-industry-leading-ultra-low-latency-and-high-throughput-ai-inference-solution) / [Microsoft Source](https://news.microsoft.com/source/2026/07/23/databricks-and-microsoft-expand-partnership/) / [Bloomberg](https://www.bloomberg.com/news/articles/2026-07-23/robotics-startup-genesis-in-talks-to-raise-about-500-million)

## 주요 이슈 3: 에이전트 안전성의 천장이 숫자로 찍혔다 — 74.8%

7월 23일 arXiv에 오른 **GuardianAgentBench**는 자율 에이전트가 어디서 깨지는지를 **6개 도메인 580개 시나리오**로 측정했습니다. LangChain·LlamaIndex·Vectara 세 프레임워크 위에서 돌린 결과, 가장 강한 조합조차 **전체 정확도 74.8%**에 머물렀습니다. 실패 방식은 능력대별로 갈렸는데, 강한 모델은 **필요한 도구를 호출하지 않는** 쪽으로, 약한 모델은 **엉뚱한 도구를 과도하게 호출하는** 쪽으로 무너졌습니다. 도구 세트가 커지고 턴이 깊어질수록 성능은 일관되게 떨어졌습니다. 저자들의 실행 시점 가드레일은 **실패의 19.9%를 오탐률 0.5%로 복구**했습니다.

같은 날 공개된 **AREX**는 반대 방향의 시도입니다. 근거를 모아 잠정 답을 만드는 내부 루프와, 그 답을 제약 단위로 쪼개 감사하는 외부 루프를 번갈아 돌립니다. **4B 덴스**와 **122B-A10B MoE** 구성으로 BrowseComp·WideSearch·DeepSearchQA·HLE에서 동급 베이스라인을 크게 앞섰다고 보고했습니다. 두 논문을 겹쳐 읽으면 그림이 분명해집니다. **성능은 자기검증으로 밀어 올릴 수 있지만, 도구를 많이 쥐여줄수록 실패율은 구조적으로 올라간다**는 것입니다. [arXiv:2607.20982](https://arxiv.org/abs/2607.20982) / [arXiv:2607.21461](https://arxiv.org/abs/2607.21461)

## 주요 이슈 4: AI가 의료기록과 광고 화면이라는 '규제 지대'로 들어갔다

오픈AI는 7월 23일 **'Health in ChatGPT'**를 미국 사용자에게 열었습니다. 애플 헬스와 에픽·오라클 헬스 등 의료기록을 연결해 검사 수치 비교, 직전 진료 이후 변화 요약, 복약·수면·활동 추적을 대화창에서 처리합니다. 대상은 **미국 만 18세 이상**, 웹·iOS의 **Free·Go·Plus·Pro 전 요금제**이며, 연결된 의료 정보와 관련 대화는 **모델 학습·광고 타기팅에 사용되지 않고** 추가 암호화가 적용됩니다. 무료 요금제까지 한 번에 연 것은 의료 데이터 연동을 프리미엄이 아닌 기본기로 두겠다는 선택입니다.

반대편에서는 제약이 들어왔습니다. **아마존**은 같은 날 제3자 판매자에게 상품 이미지·영상 속 **'AI 생성 인물' 표시를 의무화**했습니다. 배경은 **6월 9일 발효된 뉴욕주 합성 출연자 공시법**으로, 위반 시 **1차 1,000달러, 이후 건당 5,000달러**의 과태료가 붙습니다. 다만 TV·게임·영화 캐릭터나 AI로 보정된 실존 인물은 대상에서 제외됐습니다. 주 하나의 광고법이 전국 마켓플레이스의 등록 규칙을 바꾼 사례입니다. [9to5Mac](https://9to5mac.com/2026/07/23/openai-relaunches-apple-health-connected-chatgpt-feature-with-expanded-access/) / [CNBC](https://www.cnbc.com/2026/07/23/amazon-makes-sellers-label-ai-generated-people-in-images-after-ny-law.html)

## 오늘의 시사점

오늘의 네 갈래를 한 줄로 꿰면 **"운영 비용이 청구되기 시작한 날"**입니다.

첫째, 딥시크의 별칭 폐기는 API 계층에도 **기술 부채의 만기일**이 존재한다는 것을 보여줍니다. 편의를 위해 별칭에 의존한 파이프라인일수록 오늘 대가를 치릅니다. 모델 선택을 추상화하는 대신 **버전을 고정하고 회귀 테스트를 붙이는 쪽**이 왜 비싼 보험이 아니라 필수 비용인지가 확인된 셈입니다.

둘째, 인프라 자본의 집행 방식이 달라졌습니다. SK텔레콤의 3,300억원 선출자 후 2030년까지 순차 납입, AMD·세레브라스의 프리필/디코드 분리, 마이크로소프트–데이터브릭스의 10년 단위 재계약은 모두 **"수요가 확인되는 만큼만 설비를 붙인다"**는 같은 문법을 씁니다. 무제한 선투자 국면이 조건부 분할 집행 국면으로 이동하고 있습니다.

셋째, 74.8%라는 숫자는 에이전트 도입 계획서에 그대로 옮겨 적을 만한 수치입니다. 도구를 많이 붙일수록 성능이 떨어진다는 관측은, 실무에서 **에이전트에게 쥐여줄 도구 수를 줄이고 턴 깊이를 제한하는 설계**가 안전성뿐 아니라 정확도에도 이롭다는 뜻입니다. 가드레일이 실패의 19.9%만 복구했다는 점도 함께 기억해야 합니다. 나머지는 여전히 사람이 감당할 몫입니다.

넷째, 의료기록 연동과 광고 라벨 의무화가 같은 날 나온 것은 우연이 아닙니다. AI 기능이 규제 밀도가 높은 영역으로 들어가는 순간, 제품 경쟁력의 절반은 **데이터 취급 방식과 공시 준수 여부**로 옮겨갑니다. 무료 요금제까지 의료 연동을 여는 결정과, 마켓플레이스 전체에 라벨 필드를 추가하는 결정은 방향이 달라 보여도 같은 규칙 아래 있습니다.

---

## 📎 참고 자료

1. [DeepSeek-V4 Preview Release — DeepSeek API Docs](https://api-docs.deepseek.com/news/news260424/)
2. [SK텔레콤, 에스케이하이퍼 설립 출자 공시 — 데이터투자](https://www.datatooza.com/article/20260723172603607852ef3a3fcc_80)
3. [AMD and Cerebras Announce Ultra-Low-Latency and High Throughput AI Inference Solution — AMD IR](https://ir.amd.com/news-events/press-releases/detail/1293/amd-and-cerebras-announce-industry-leading-ultra-low-latency-and-high-throughput-ai-inference-solution)
4. [Databricks and Microsoft expand partnership — Microsoft Source](https://news.microsoft.com/source/2026/07/23/databricks-and-microsoft-expand-partnership/)
5. [Robotics Startup Genesis in Talks to Raise About $500 Million — Bloomberg](https://www.bloomberg.com/news/articles/2026-07-23/robotics-startup-genesis-in-talks-to-raise-about-500-million)
6. [GuardianAgentBench: Where Agents Fail and How to Guard Them — arXiv:2607.20982](https://arxiv.org/abs/2607.20982)
7. [AREX: Towards a Recursively Self-Improving Agent for Deep Research — arXiv:2607.21461](https://arxiv.org/abs/2607.21461)
8. [OpenAI relaunches Apple Health-connected ChatGPT feature with expanded access — 9to5Mac](https://9to5mac.com/2026/07/23/openai-relaunches-apple-health-connected-chatgpt-feature-with-expanded-access/)
9. [Amazon makes sellers label AI-generated people in images after NY law — CNBC](https://www.cnbc.com/2026/07/23/amazon-makes-sellers-label-ai-generated-people-in-images-after-ny-law.html)
