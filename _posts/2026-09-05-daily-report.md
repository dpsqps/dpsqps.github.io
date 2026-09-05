---
layout: single
title: "📊 AI 일간보고서 — 2026년 09월 05일"
date: 2026-09-05 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "추론계층"
  - "모달리티단가"
  - "주권AI원산지"
  - "로컬추론"
  - "에이전트권한"
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

> **2026년 09월 05일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 09월 05일 AI 일간보고서

## 오늘의 핵심 요약

이번 주 초 프런티어 모델 네 종이 72시간 안에 쏟아진 뒤, 뉴스의 무게중심이 눈에 띄게 이동했다. 오늘 정리한 소식에는 새로운 범용 대형 모델이 없다. 대신 **음성 인식 단가가 5개월 만에 72% 떨어졌고**, **국가 대표 모델의 베이스가 중국 오픈 웨이트였음이 확인됐으며**, **모델을 만들지 않는 회사 세 곳이 수십억 달러를 조달하거나 약정했다**.

세 흐름은 하나의 문장으로 묶인다. 모델을 만드는 일보다 **모델을 어디서, 어떤 칩 위에서, 얼마에 돌릴 것인가**가 산업의 실제 경쟁 지점이 됐다는 것이다. 학습이 아니라 추론이, 성능표가 아니라 가격표와 계보가 오늘의 주제다.

## 주요 이슈 1: 모달리티 단가가 무너지는 속도 — 5개월에 72%

마이크로소프트 AI가 공개한 **MAI-Transcribe-2**의 가격은 오디오 1시간당 **0.10달러**다. 같은 라인의 1세대가 다섯 달 전 받던 **0.36달러** 대비 **약 72% 인하**다. 성능도 함께 올렸다고 주장한다. FLEURS 벤치마크에서 **60개 언어 평균 WER 5.2%**, 속도는 오픈AI GPT-Transcribe 대비 최대 **10배**, 일레븐랩스 Scribe v2 대비 **7배**, 제미나이 3.5 Transcribe 대비 **5배**다. 지원 언어는 25개 → 43개 → 60개로 늘었다.

주목할 점은 인하 폭이 아니라 **주기**다. 다섯 달 만에 3분의 1 이하로 떨어지는 단가는 이 모달리티가 이미 차별화 구간을 벗어났다는 뜻이다. 음성 인식을 핵심 기능으로 파는 사업자에게 가격은 더 이상 방어선이 될 수 없고, 마이크로소프트에게 이 모델은 그 자체로 수익원이라기보다 **오픈AI 기술로 돌아가던 자사 제품을 순차적으로 갈아끼우는 부품**에 가깝다. [VentureBeat](https://venturebeat.com/infrastructure/microsoft-ais-mai-transcribe-2-undercuts-openai-google-and-elevenlabs-on-price-and-speed)

## 주요 이슈 2: '소버린 AI'의 원산지가 처음으로 분리돼 드러나다

사우디 국부펀드가 후원하는 **휴메인**이 리야드 LEAP에서 공개한 아랍어 모델 **humain-m3**는 **4,280억 파라미터 MoE**(토큰당 활성 230억)로, 아랍어 공개 벤치마크 7종 평균 **89.37%**를 기록했다. GPT-5.6 SOL(87.30%)과 Opus 5(87.34%)를 앞선 수치다.

그런데 이 모델은 밑바닥부터 만든 것이 아니다. 중국 **미니맥스의 M3 오픈 웨이트** 계보 위에 아랍어 네이티브 **1조 토큰 이상**을 추가 사전학습한 결과이고, 실제 학습 수행도 미니맥스가 맡았다. 오픈 웨이트 공개 예정 라이선스 이름 자체가 **미니맥스 커뮤니티 라이선스**다. 같은 벤치마크에서 베이스 MiniMax M3가 **80.34%**였으니 1조 토큰이 더한 값은 약 **9%포인트**다.

이 한 사례가 소버린 AI라는 단어를 두 겹으로 쪼갠다. **데이터·언어·서비스의 주권**은 확보됐지만 **가중치와 아키텍처의 주권**은 확보되지 않았다. 미국 스택도, 자국 스택도 아닌 제3의 선택지가 실제로 작동한다는 점을 사우디가 증명한 셈이고, 이는 앞으로 국가 단위 AI 계획을 세우는 나라들이 마주할 현실적 분기점이기도 하다. [Unite.AI](https://www.unite.ai/pif-backed-humain-launches-humain-m3-arabic-model-at-leap-riyadh/) / [Global Times](https://www.globaltimes.cn/page/202609/1369842.shtml)

## 주요 이슈 3: 자본이 학습에서 추론 실행 계층으로 한 칸 내려왔다

같은 이틀 사이의 대형 딜 세 건 중 모델을 만드는 회사는 하나도 없다.

**김렛 랩스**는 시리즈 B로 **3억 달러**를 조달해 기업가치 **30억 달러**가 됐다. 안드리센 호로위츠가 주도했고 **Arm**과 마이크로소프트 벤처 펀드 **M12**가 신규로 들어왔다. **6개월 전 8,000만 달러** 라운드 대비 3.75배 규모이며 누적 조달은 **3억 9,200만 달러**다. 이 회사가 파는 건 추론 워크로드를 특정 벤더 가속기에 묶지 않고 여러 칩 사이로 라우팅하는 계층, 즉 **엔비디아 단일 스택에 대한 헤지**다. Arm이 전략 투자자로 들어온 이유가 여기 있다.

**크루소**는 **30억 달러 이상**을 조달하며 기업가치 **300억 달러**를 받았다. **10개월 전 100억 달러**에서 3배다. 직전에 체결한 **제인스트리트와의 5년 약 130억 달러** 클라우드 계약이 이번 라운드를 끌어당겼다. 최대 고객이 AI 기업이 아니라 **퀀트 트레이딩 회사**라는 사실이 중요하다. GPU 수요의 원천이 모델 학습 바깥으로 넓어지고 있다.

**피겨**는 엔스케일과 초기 **35억 달러**(확장 시 60억 달러 초과) 컴퓨트 계약을 맺고 최대 **10만 장**의 엔비디아 베라 루빈 GPU에 접근한다. 첫 배치는 **2027년 하반기**다. 피겨의 누적 조달액이 **약 19억 달러**임을 감안하면 약정 규모는 그 두 배 가까이다. 회사가 자사 모델 Helix의 병목을 로봇 제조가 아니라 **데이터와 컴퓨트**로 규정했다는 뜻이다. [SiliconANGLE](https://siliconangle.com/2026/09/04/gimlet-labs-nabs-300m-for-its-disaggregated-inference-platform/) / [TechCrunch](https://techcrunch.com/2026/09/03/crusoe-reportedly-raises-3b-at-a-30b-valuation/) / [Humanoids Daily](https://www.humanoidsdaily.com/news/figure-inks-multi-billion-dollar-compute-deal-with-nscale-to-deploy-100-000-next-gen-nvidia-gpus)

## 주요 이슈 4: 에이전트의 권한은 넓어지고, 실행 위치는 내려간다

제품 쪽에서는 방향이 정반대인 두 발표가 같은 날 나왔다.

구글은 **제미나이 스파크**에 구글 포토 제어 권한을 붙였다. 이미지 편집, 앨범 큐레이션, 공유 앨범 자동 생성, 사진을 캘린더 일정으로 변환하는 작업을 에이전트가 직접 수행한다. 배포는 **미국·영어권의 AI Pro와 Ultra 두 개 유료 등급**에 **수 주에 걸쳐** 이뤄진다. 안전장치 설계가 흥미롭다. 편집 전 **원본 사본 생성**, 새 앨범 **기본 비공개**, 공유·메일 발송 전 **별도 허가 요청**으로 '되돌릴 수 있는가'와 '밖으로 나가는가'를 서로 다른 관문으로 분리했다.

엔비디아는 IFA 2026에서 **PAIR(퍼스널 AI 라우터)**를 무료 오픈소스로 공개했다. 로컬 네트워크의 호환 PC를 찾아 추론 요청을 여유 자원이 있는 기기로 분산하는 도구로, **윈도우·macOS·리눅스** 베타를 제공하고 지포스 RTX 20 시리즈 이상부터 **애플 M4 이상**까지 지원한다. 성능 개선치는 llama.cpp 기준 RTX 5090에서 최대 **1.9배**다. 함께 확정된 **RTX 스파크**는 **1페타플롭 블랙웰 GPU·최대 128GB 통합 메모리·20코어 그레이스 CPU** 사양으로 **10월** 출시되며 레노버·에이서 등 **8개 OEM**이 참여한다. [TechCrunch](https://techcrunch.com/2026/09/04/googles-gemini-spark-can-now-manage-your-google-photos-library/) / [NVIDIA Blog](https://blogs.nvidia.com/blog/local-ai-ifa-next-gen-agents-nv-pair-rtx-spark/)

## 오늘의 시사점

네 가지 이슈는 서로 다른 회사, 다른 대륙의 소식이지만 하나의 축으로 정렬된다. **모델 자체는 점점 덜 희소해지고, 모델을 둘러싼 계층이 값을 갖는다.**

첫째, 단가 하락이 모달리티 단위로 진행된다. 음성 인식이 다섯 달에 72% 떨어졌다면, 다음 차례는 이미지·임베딩·번역이다. 특정 모달리티를 단일 상품으로 파는 사업 모델의 유효기간이 분기 단위로 짧아지고 있다.

둘째, 개방형 가중치가 지정학의 실제 도구가 됐다. 사우디는 미국 스택을 사지 않고, 자체 개발도 하지 않고, 중국 오픈 웨이트 위에 자국 데이터를 얹는 세 번째 경로를 택했다. 이 경로의 비용은 **약 9%포인트의 벤치마크 개선을 위한 1조 토큰**이었고, 그 대가로 아키텍처 의존성이 남았다. 자국 모델 계획을 가진 어느 나라든 이 계산서를 다시 보게 될 것이다.

셋째, 자본은 이미 추론으로 이동했다. 김렛 랩스가 6개월 만에 3.75배 규모 라운드를 받고 Arm이 전략 투자자로 들어온 것은, 시장이 **'엔비디아 없이도 추론이 돌아가는가'**라는 질문에 값을 매기기 시작했다는 뜻이다. 크루소의 최대 고객이 트레이딩 회사이고, 피겨가 조달액의 두 배를 컴퓨트에 약정한 것도 같은 곡선 위에 있다. AI 데이터센터의 수요 기반이 모델 연구소 몇 곳에서 일반 산업으로 확산되고 있다.

넷째, 그리고 가장 실무적으로, 에이전트의 권한 설계와 실행 위치가 동시에 재조정되고 있다. 구글은 개인 사진첩에 대한 쓰기 권한을 열면서 되돌림과 유출을 각각 다른 관문으로 막았고, 엔비디아는 그 데이터를 아예 집 밖으로 내보내지 않을 물리적 근거를 무료로 배포했다. 개인 데이터에 손대는 에이전트를 만드는 팀이라면, 두 접근 중 어느 쪽을 택하든 이 두 발표가 설정한 기준선 위에서 설계를 시작하게 될 것이다.

---

## 📎 참고 자료

1. [Microsoft AI's MAI-Transcribe-2 undercuts OpenAI, Google and ElevenLabs on price and speed — VentureBeat](https://venturebeat.com/infrastructure/microsoft-ais-mai-transcribe-2-undercuts-openai-google-and-elevenlabs-on-price-and-speed)
2. [PIF-Backed HUMAIN Launches Humain-M3 Arabic Model at LEAP Riyadh — Unite.AI](https://www.unite.ai/pif-backed-humain-launches-humain-m3-arabic-model-at-leap-riyadh/)
3. [Saudi firm launches LLM based on Chinese AI model — Global Times](https://www.globaltimes.cn/page/202609/1369842.shtml)
4. [Gimlet Labs nabs $300M for its disaggregated inference platform — SiliconANGLE](https://siliconangle.com/2026/09/04/gimlet-labs-nabs-300m-for-its-disaggregated-inference-platform/)
5. [Crusoe reportedly raises $3B at a $30B valuation — TechCrunch](https://techcrunch.com/2026/09/03/crusoe-reportedly-raises-3b-at-a-30b-valuation/)
6. [Figure Inks Multi-Billion-Dollar Compute Deal With Nscale — Humanoids Daily](https://www.humanoidsdaily.com/news/figure-inks-multi-billion-dollar-compute-deal-with-nscale-to-deploy-100-000-next-gen-nvidia-gpus)
7. [Google's Gemini Spark can now manage your Google Photos library — TechCrunch](https://techcrunch.com/2026/09/04/googles-gemini-spark-can-now-manage-your-google-photos-library/)
8. [Sparks Fly: NVIDIA Accelerates Local AI at IFA 2026 — NVIDIA Blog](https://blogs.nvidia.com/blog/local-ai-ifa-next-gen-agents-nv-pair-rtx-spark/)
