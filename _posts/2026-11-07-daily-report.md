---
layout: single
title: "📊 AI 일간보고서 — 2026년 11월 07일"
date: 2026-11-07 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "일간보고서"
  - "오픈웨이트"
  - "기업가치"
  - "데이터센터"
  - "에이전트평가"
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

> **2026년 11월 07일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 11월 07일 AI 일간보고서

## 오늘의 핵심 요약

기술주가 폭락한 다음 날, AI 업계는 모든 것을 '효율'의 관점에서 다시 계산하기 시작했습니다. 모델 쪽에서는 전체는 크고 활성 매개변수는 작은 오픈웨이트 모델이 잇따라 나왔습니다. 자본 쪽에서는 오픈AI와 앤트로픽이 목표 몸값을 낮췄습니다. 인프라 쪽에서는 구형 GPU 임대를 정리하고 기존 건물을 데이터센터로 바꾸는 방안이 나왔습니다. 연구계는 모델이 아니라 환경과 평가 방식을 바꿔야 한다는 결과를 내놓았습니다.

## 주요 이슈 1: 오픈웨이트 경쟁, '활성 매개변수' 숫자가 핵심이 되다

씽킹 머신즈 랩의 '잉클링 2 스몰'은 전체 5,940억 개 매개변수 가운데 170억 개만 활성화하는 MoE 모델입니다. 외부 안전성 시험을 마친 뒤 아파치 2.0으로 가중치를 공개할 예정입니다. [Thinking Machines Lab](https://thinkingmachines.ai/news/inkling-2-small/) 바이두 '어니 5.5 플래시 베이스'는 2,800억 개 중 140억 개를 쓰는 구조로, 지시 미세조정을 하지 않은 베이스 모델 그대로 가중치를 풀었습니다. [The Decoder](https://the-decoder.com/baidu-releases-ernie-5-5-flash-base-with-280-billion-parameters-as-an-open-source-foundation-model/) 반대 방향의 사례도 있습니다. 리커시브 인텔리전스의 650억 매개변수 밀집 모델 '리플-65B'는 회사 측 수치로 터미널벤치 2.1에서 80.52점을 받아 5,010억 규모 모델보다 높았고, 개발비는 3,200만 달러라고 밝혔습니다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217107)

세 모델 모두 '얼마나 큰가'보다 '실행할 때 얼마나 싼가'를 내세웁니다. 국내 카카오 '카나나-2-v-디사이드'가 H200 1장에서 0.04초 응답을 강조한 것도 같은 흐름입니다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217087) 영상 분야에서도 구글이 제미나이 옴니 1.2 플래시 가격을 30% 내려 720p 초당 0.07달러로 맞췄습니다. 추론 단가가 경쟁의 기준이 되고 있습니다. [Google 블로그](https://blog.google/innovation-and-ai/technology/developers-tools/introducing-gemini-omni-1-2-flash/)

## 주요 이슈 2: 폭락 이후 몸값 재조정, 성장률 둔화가 숫자로 확인되다

전날 급락의 첫 후속 결과는 기업가치였습니다. 오픈AI는 1조2,500억 달러 가치로 110억 달러를 새로 받았지만, 300억 달러 이상이던 모집 목표는 최대 200억 달러 수준으로 내려갔습니다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217117) 앤트로픽의 상장 기대 몸값은 1조1,000억~1조3,000억 달러로, 한때 거론된 2조 달러보다 최대 45% 낮아졌습니다. 3분기 매출은 169억6,000만 달러로 47% 늘었지만 2분기 성장률 144%보다 크게 느려졌습니다. 장기 컴퓨팅 약정 8,954억 달러는 그대로입니다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217122)

매출은 여전히 빠르게 늘지만, 투자자들은 이제 성장률이 얼마나 빨리 꺾이는지와 고정비가 얼마나 무거운지를 함께 봅니다. 모델 가격 인하가 매출을 약 6억 달러 줄였다는 앤트로픽의 설명은 이슈 1의 가격 경쟁이 공급자에게 어떤 부담이 되는지 보여 줍니다.

## 주요 이슈 3: 컴퓨팅 재배치, 낡은 GPU는 정리하고 낡은 건물은 다시 쓴다

마이크로소프트는 오라클과의 AI 서버 임대 계약을 갱신하지 않기로 했고, 엔스케일 텍사스 데이터센터의 추가 용량도 포기했습니다. 오라클이 9월 4년 된 GPU 임대를 20% 비싸게 갱신했던 것과 반대되는 판단입니다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217120) 엔비디아는 20개 주에 흩어진 브라이트스피드 전화국 130여 곳, 약 1GW 규모 전력을 AI 데이터센터로 바꾸는 방안을 아폴로와 논의 중입니다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217096) 중국에서는 미국이 판매를 승인한 H200 약 60만 개가 반입 제한으로 홍콩에 묶여 있고, H200 8개짜리 서버 가격은 1년 새 약 3배로 뛰었습니다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217106)

세 소식은 공통점이 있습니다. 새 데이터센터 부지와 전력을 확보하기 어려워지면서, 이미 있는 자원을 얼마나 잘 쓰느냐가 경쟁력이 되고 있습니다. 같은 칩이라도 어느 나라 정책 아래 있느냐에 따라 값이 크게 달라진다는 점도 드러났습니다.

## 주요 이슈 4: 연구계의 지적, 바꿔야 할 것은 모델이 아니라 환경과 평가

EnvOpt 논문은 모델은 그대로 두고 에이전트 환경만 최적화해 클로드 하이쿠 4.5 비용을 72.7% 줄이고 통과율을 14.34% 높였다고 보고했습니다. [arXiv:2611.07372](https://arxiv.org/abs/2611.07372) 반면 금융 실무 평가 FINCOSMOS에서는 에이전트 150세션 중 전문가가 받아들인 결과가 하나도 없었습니다. [arXiv:2611.07464](https://arxiv.org/abs/2611.07464) LLM으로 임상시험 문서를 대프니로 형식화한 연구에서는 독립 재추출 결과가 59.3%만 일치했습니다. 검증을 통과해도 원문 뜻과 맞는다고 볼 수 없다는 뜻입니다. [arXiv:2611.07073](https://arxiv.org/abs/2611.07073)

## 오늘의 시사점

오늘 소식은 모두 '같은 결과를 더 적은 자원으로'라는 방향을 가리킵니다. 모델은 활성 매개변수를 줄이고, 클라우드는 구형 GPU를 정리하고, 연구는 실행 환경을 다듬어 비용을 깎습니다. 이 효율화는 공급자의 마진을 압박합니다. 앤트로픽이 밝힌 가격 인하에 따른 매출 감소와 성장률 둔화가 그 예입니다. FINCOSMOS의 0건과 대프니 연구의 59.3%는 비용이 내려가도 실무에서 받아들일 만한 품질은 아직 확보되지 않았다는 점을 보여 줍니다. 앞으로 투자자와 기업 고객은 '토큰당 가격'보다 '받아들일 수 있는 결과 한 건당 비용'을 더 중요하게 볼 가능성이 큽니다. 다음 주로 예정된 앤트로픽 로드쇼는 이런 효율 중심 평가가 시장에서 처음 시험받는 자리가 될 것입니다.

[AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217122) / [arXiv:2611.07464](https://arxiv.org/abs/2611.07464)

---

## 📎 참고 자료

1. [Thinking Machines Lab — Introducing Inkling 2 Small](https://thinkingmachines.ai/news/inkling-2-small/)
2. [The Decoder — Baidu releases ERNIE 5.5 Flash Base](https://the-decoder.com/baidu-releases-ernie-5-5-flash-base-with-280-billion-parameters-as-an-open-source-foundation-model/)
3. [AI타임스 — 구글 출신 연구진, 65B 모델로 8배 큰 AI 코딩 성능 추월](https://www.aitimes.com/news/articleView.html?idxno=217107)
4. [AI타임스 — 카카오, 의사결정 모델 '카나나-2-v-디사이드' 공개](https://www.aitimes.com/news/articleView.html?idxno=217087)
5. [Google 블로그 — Gemini Omni 1.2 Flash](https://blog.google/innovation-and-ai/technology/developers-tools/introducing-gemini-omni-1-2-flash/)
6. [AI타임스 — 오픈AI, 15조 투자 유치…목표는 41조→27조로 축소](https://www.aitimes.com/news/articleView.html?idxno=217117)
7. [AI타임스 — 앤트로픽 IPO 예상 몸값 2조→1.1조달러](https://www.aitimes.com/news/articleView.html?idxno=217122)
8. [AI타임스 — MS, 오라클 AI 서버 임대 계약 종료](https://www.aitimes.com/news/articleView.html?idxno=217120)
9. [AI타임스 — 엔비디아, 미국 노후 전화국 130곳 AI 데이터센터로 전환 추진](https://www.aitimes.com/news/articleView.html?idxno=217096)
10. [AI타임스 — 중국, 엔비디아 H200 수입 제한](https://www.aitimes.com/news/articleView.html?idxno=217106)
11. [arXiv:2611.07372 — EnvOpt](https://arxiv.org/abs/2611.07372)
12. [arXiv:2611.07464 — FINCOSMOS](https://arxiv.org/abs/2611.07464)
13. [arXiv:2611.07073 — When Verification Is Not Agreement](https://arxiv.org/abs/2611.07073)
