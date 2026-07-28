---
layout: single
title: "📊 AI 일간보고서 — 2026년 07월 28일"
date: 2026-07-28 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "오픈웨이트"
  - "그록4.6"
  - "에이전틱보안"
  - "AI검색"
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

> **2026년 07월 28일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 07월 28일 AI 일간보고서

## 오늘의 핵심 요약

지난 금요일(7월 24일) 엔비디아·메타·마이크로소프트·미스트랄·허깅페이스가 오픈웨이트 규제에 반대하는 공개서한을 낸 뒤 나흘, 그 논쟁이 말에서 조직과 제도로 굳어졌습니다. 엔비디아는 40개사 규모의 상설 보안 연합을 띄웠고, 앤트로픽 CEO는 자신의 입장이 오도됐다며 쟁점을 다시 규정했으며, 한국 정부는 국산 모델 평가에 일반 국민 200명을 끌어들였습니다. 같은 기간 xAI는 4주 간격으로 두 개의 프런티어 모델을 예고했고, 마이크로소프트는 보안 자체를 에이전트 제품으로 내놨습니다. 오늘의 공통 축은 하나입니다 — **누가 모델을 만드느냐에서, 누가 그 모델을 검증하고 방어하느냐로 산업의 무게중심이 옮겨가고 있다**는 것.

## 주요 이슈 1: 오픈웨이트 논쟁, 연합체와 반박문으로 구체화

엔비디아는 7월 28일 약 40개사가 참여하는 '오픈 시큐어 AI 얼라이언스'를 출범시켰습니다. 마이크로소프트·IBM·팔란티어·세일즈포스가 창립 파트너이고, 한국에서는 네이버와 SK텔레콤이 이름을 올렸습니다. 엔비디아는 오픈소스 연구 프로젝트 'NOOA'를 함께 공개하며 "최첨단 개방형 AI 시스템을 일괄 제한하면 오히려 방어 역량이 약해진다"고 주장했습니다 [(AI타임스)](https://www.aitimes.com/news/articleView.html?idxno=213231).

다리오 아모데이 앤트로픽 CEO는 7월 27일 반박문으로 응수했습니다. "앤트로픽은 오픈웨이트 모델 금지를 주장한 적이 없다"며, 위험 역량이 없는 오픈 모델은 "구동 컴퓨트 외에 아무 비용도 들지 않는 공공재"라고 규정했습니다. 그가 실제로 겨냥한 것은 개방 여부가 아니라 권위주의 정부의 "영구적 군사 우위" 확보 시나리오였고, 해법으로는 원산지와 개방·폐쇄 여부에 무관하게 전 세계에 동일 적용되는 모델 안전성 시험 기구를 제안했습니다 [(TechCrunch)](https://techcrunch.com/2026/07/27/anthropics-dario-amodei-responds-doesnt-oppose-open-weight-models-but-fears-chinese-ai/).

주목할 점은 양측의 결론이 생각보다 가깝다는 것입니다. 엔비디아 연합의 '공동 방어 인프라'와 아모데이의 '글로벌 시험 기구'는 둘 다 개별 기업이 아닌 산업 공통 계층에 검증 책임을 놓자는 제안입니다. 대립 구도로 보도되지만, 실제로는 규제의 형태를 놓고 벌이는 선점 경쟁에 가깝습니다.

## 주요 이슈 2: 파라미터 2조 대 2,500억 — 규모와 효율이 같은 주에 지표를 냈다

일론 머스크는 그록 4.6을 2주 내, 4.7을 4주 내 출시한다고 밝혔습니다. 4.6의 매개변수는 2조 개로 현행 1.5조 대비 33% 증가한 규모이며, 그록 4.5 수준의 속도(초당 약 80토큰)와 약 2배의 토큰 효율을 유지하는 것이 목표입니다. 다만 2조 개는 키미 K3(2.8조)와 큐원 3.8(2.4조)에 이은 3위권이고, 4.7은 4조~6조 개가 거론됩니다 [(AI타임스)](https://www.aitimes.com/news/articleView.html?idxno=213211).

반대편에서는 업스테이지의 솔라 오픈 2가 2,500억 파라미터로 허깅페이스 글로벌 주간 트렌딩 3위에 올랐습니다. 누적 다운로드 3,300회 이상, 라이크 600개 이상이며 에포크AI '주목할 만한 모델'에도 등재됐습니다 [(AI타임스)](https://www.aitimes.com/news/articleView.html?idxno=213222). 그록 4.6과는 8배 격차지만, 순위를 만든 변수는 규모가 아니라 배치 비용이었습니다. 어제 다룬 키미 K3의 '가중치는 공개됐지만 1.4TB를 돌릴 인프라가 없다'는 문제의 정확한 반대편 답안이기도 합니다.

## 주요 이슈 3: 보안이 상품이 된 날, 보안 사고가 난 날

마이크로소프트는 7월 27일 첫 사이버보안 전용 모델 MAI-Cyber-1-Flash를 공개하고 즉시 프로덕션에 투입했습니다. 사티아 나델라 CEO는 사이버 짐 벤치마크에서 제미나이·GPT-5.5 Cyber·GPT-5.6 Sol·미토스 5 등 4개 모델을 앞선다고 밝혔습니다. 함께 나온 '퍼셉션' 플랫폼은 레드팀(공격)·블루팀(탐지)·그린팀(조치)으로 역할을 나눈 에이전트 조직을 구성해, 수 시간짜리 수작업 보안 워크플로를 수 분으로 줄이는 것을 목표로 합니다 [(TechCrunch)](https://techcrunch.com/2026/07/27/microsoft-launches-its-first-cyber-model-and-a-new-agentic-cybersecurity-system/).

같은 날, 앤트로픽 클로드의 공유 링크와 아티팩트가 구글에 색인된 사실이 보도됐습니다. `site:claude.ai/share` 검색만으로 임상시험 데이터, 환자 이름, 아동 연락처, 기업 내부 문서가 노출된 상태였고, 지난해 유사 사고에서는 약 600건이 색인된 바 있습니다. 앤트로픽은 검색엔진에 디렉터리나 사이트맵을 제공하지 않는다며 사용자 게시 경로를 원인으로 지목했습니다 [(TechCrunch)](https://techcrunch.com/2026/07/27/psa-your-claude-shared-chats-and-artifacts-may-have-ended-up-on-google/). 벤치마크에서 취약점을 찾는 모델과, 공유 버튼 하나로 새는 데이터가 같은 24시간 안에 놓였다는 점이 오늘의 아이러니입니다.

## 주요 이슈 4: 한국, 모델 평가에 일반 국민 200명을 넣다

과학기술정보통신부는 독자 AI 파운데이션 모델 2차 평가에 국민 평가단 200명을 투입합니다. 8월 4일 오후 6시 모집 마감, 8월 8~11일 평가이며 LG AI연구원·SK텔레콤·업스테이지·모티프테크놀로지스의 모델이 대상입니다. 성별·연령대별로 선발된 평가단이 직접 사용 후 매긴 절대평가 점수가 공식 평가에 반영되고, 세부 기준과 결과는 8월 중 공개됩니다 [(AI타임스)](https://www.aitimes.com/news/articleView.html?idxno=213239).

벤치마크와 전문가 심사만으로 국가 예산 배분을 결정하던 방식에 체감 지표를 정식으로 끼워 넣는 시도입니다. 벤치마크 점수와 실사용 만족도가 갈리는 사례가 누적된 상황에서, 평가 기준 자체를 다변화하는 방향으로 읽힙니다.

## 오늘의 시사점

오늘 네 갈래 소식은 한 문장으로 수렴합니다. **모델을 만드는 능력은 이미 여러 곳에 분산됐고, 이제 경쟁은 그 모델을 누가 검증하고 방어하느냐로 이동했습니다.** 엔비디아의 40개사 연합도, 아모데이의 글로벌 시험 기구 제안도, 과기정통부의 국민 평가단도 형식은 다르지만 모두 '검증 계층을 누가 설계하느냐'를 놓고 벌이는 포지셔닝입니다.

두 번째 축은 비용입니다. 그록 4.6의 2조 파라미터와 솔라 오픈 2의 2,500억 파라미터가 같은 주에 각자의 지표를 세운 것은, 시장이 하나의 축으로 줄 세워지지 않는다는 뜻입니다. 사티아 나델라가 같은 날 "하나의 AI에만 의존하는 기업은 살아남지 못할 수 있다"고 말한 것도 같은 맥락에 있습니다 [(TechCrunch)](https://techcrunch.com/2026/07/27/satya-nadella-says-companies-that-trust-one-ai-for-everything-may-not-survive/).

세 번째는 소비 인터페이스의 변화입니다. 구글 AI 개요는 1년 만에 검색의 15%에서 43%로, AI 모드 방문은 1억 2,600만 건에서 2억 7,900만 건으로 늘었습니다. 반면 미국 챗GPT 데스크톱 질의 중 인용이 붙은 비율은 6.8%에 그칩니다 [(TechCrunch)](https://techcrunch.com/2026/07/27/googles-ai-search-is-rapidly-becoming-the-default-new-data-shows/). AI 검색이 기본값이 되는 속도는 출처 표기가 정착되는 속도보다 훨씬 빠릅니다. 검증 계층을 만들자는 오늘의 논의가 모델뿐 아니라 그 출력이 소비되는 지점에서도 필요하다는 신호입니다.

---

## 📎 참고 자료

1. [AI타임스 — 엔비디아, 네이버·SKT 등 40곳 참여 개방형 AI 보안 연합 출범](https://www.aitimes.com/news/articleView.html?idxno=213231)
2. [TechCrunch — Anthropic's Dario Amodei responds: doesn't oppose open-weight models, but fears Chinese AI](https://techcrunch.com/2026/07/27/anthropics-dario-amodei-responds-doesnt-oppose-open-weight-models-but-fears-chinese-ai/)
3. [AI타임스 — 머스크 "그록 4.6은 2주 내, 4.7은 4주 내 출시"](https://www.aitimes.com/news/articleView.html?idxno=213211)
4. [AI타임스 — 업스테이지 솔라 오픈 2, 허깅페이스 트렌딩 3위](https://www.aitimes.com/news/articleView.html?idxno=213222)
5. [TechCrunch — Microsoft launches its first cybersecurity model, plus a new agentic cybersecurity system](https://techcrunch.com/2026/07/27/microsoft-launches-its-first-cyber-model-and-a-new-agentic-cybersecurity-system/)
6. [TechCrunch — PSA: Your Claude shared chats and Artifacts may have ended up on Google](https://techcrunch.com/2026/07/27/psa-your-claude-shared-chats-and-artifacts-may-have-ended-up-on-google/)
7. [AI타임스 — 국민이 직접 국산 AI 모델 평가한다…평가단 200명 모집](https://www.aitimes.com/news/articleView.html?idxno=213239)
8. [TechCrunch — Google's AI search is rapidly becoming the default, new data shows](https://techcrunch.com/2026/07/27/googles-ai-search-is-rapidly-becoming-the-default-new-data-shows/)
9. [TechCrunch — Satya Nadella says companies that trust one AI for everything may not survive](https://techcrunch.com/2026/07/27/satya-nadella-says-companies-that-trust-one-ai-for-everything-may-not-survive/)
