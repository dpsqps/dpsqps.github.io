---
layout: single
title: "📊 AI 일간보고서 — 2026년 11월 12일"
date: 2026-11-12 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "일간보고서"
  - "오픈AI"
  - "코어위브"
  - "앤트로픽"
  - "제미나이디시전API"
  - "알파게놈2"
  - "K온디바이스"
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

> **2026년 11월 12일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 11월 12일 AI 일간보고서

## 오늘의 핵심 요약

AI 기업의 매출은 빠르게 늘고 있지만, 그 성장을 떠받치는 자금 조달은 더 까다로워졌다. 오픈AI의 분기 매출 100억 달러 돌파 보도가 나온 날, 코어위브는 고객 선급금에 기대기 시작했고 연준 이사는 AI 부채를 경고했다. 제품 쪽에서는 범용 모델 하나로 모든 일을 처리하던 방식에서 벗어나 판단 전용 모델, 세포 단위 유전체 모델처럼 용도를 좁힌 모델이 나왔다. 한국 정부는 온디바이스 AI반도체 10종의 개발 일정을 확정했다.

## 주요 이슈 1: 매출 100억 달러와 선급금 90억 달러

테크크런치가 블룸버그를 인용해 전한 바에 따르면 오픈AI의 3분기 매출은 처음으로 100억 달러를 넘었다. 2분기 67억 달러에서 약 50% 늘었고, 조정 영업이익률은 -150%에서 -109%로 개선됐다. 적자는 여전하지만 매출이 비용보다 빨리 늘고 있다는 신호다. [TechCrunch](https://techcrunch.com/2026/11/11/openais-quarterly-revenue-reportedly-crosses-10b-for-the-first-time/)

그 매출을 만들어내는 연산 자원의 공급 쪽 사정은 다르다. 코어위브는 3분기 매출이 36억 6,000만 달러로 168% 늘었는데도 순손실 7억 900만 달러를 냈고, 분기 이자 비용이 8억 4,600만 달러였다. 회사는 앞으로 3개월간 고객 선급금과 예치금 약 90억 달러를 받을 계획이다. 단기 용량 가격은 메가와트당 연 4,000만 달러 이상으로, 4~5년 장기 계약 가격(2,000만~2,500만 달러)의 두 배에 가깝다. 연산 자원이 부족한 동안에는 공급자가 가격과 결제 조건을 정할 수 있고, 그 부담은 모델 기업과 최종 고객에게 넘어간다. [TechCrunch](https://techcrunch.com/2026/11/11/coreweave-turns-to-customer-prepayments-shorter-contracts-to-fund-ai-growth/)

## 주요 이슈 2: 앤트로픽 상장을 앞두고 나온 연준의 경고

앤트로픽 상장에는 구글, 엔비디아, 마이크로소프트 등 기술 기업 7곳이 260억 달러 규모 사모로 참여한다. 공모와 사모를 합치면 희망가 상단 기준 903억 5,000만 달러이고, 가격 결정은 11월 18일로 예상된다. 칩과 클라우드를 파는 회사들이 그 고객인 모델 기업의 주주가 되는 구조다. [Open Magazine](https://openthemagazine.com/business/google-nvidia-and-microsoft-join-26-billion-anthropic-deal-ahead-of-ipo)

미셸 보먼 연준 이사는 바로 이런 구조를 위험 요인으로 꼽았다. 그는 AI 관련 부채 8,000억 달러와 부외 부채, 순환 금융을 근거로, AI 수익이 기대에 못 미치면 주가가 "큰 조정"을 받고 인프라 구축이 느려질 수 있다고 말했다. [Semafor](https://www.semafor.com/article/11/11/2026/anthropic-ipo-could-lead-to-large-correction-in-markets-fed-official-says) 수요 쪽 데이터도 속도 조절을 보여준다. 램프 AI 지수에 따르면 10월 미국 기업의 AI 지출은 사상 최고였지만 전월 대비 증가율은 1.65%에 그쳤고, 상위 1% 기업이 오픈AI와 앤트로픽 매출의 80%를 차지했다. 매출이 소수 대형 고객에 몰려 있다는 점은 이슈 1의 성장 수치를 읽을 때 함께 봐야 한다. [The Decoder](https://the-decoder.com/us-corporate-ai-spending-hits-a-new-high-in-october-but-growth-slows-to-1-65-percent/)

## 주요 이슈 3: 범용 모델에서 용도별 모델로

구글의 제미나이 디시전 API는 문장을 생성하지 않고 예/아니오, 객관식, 채점만 한다. 요청 하나에 질문 1,000개를 처리하고 입력 100만 토큰당 0.10달러, 출력은 무료다. 에이전트가 하루에 수천 번 내리는 분류·라우팅 판단을 비싼 생성형 모델에서 분리하는 설계다. [Google 블로그](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/) 딥마인드의 알파게놈 2는 반대 방향의 특화다. 1억 개 이상의 세포 프로파일로 학습해, 면역세포 평가에서 원인 변이 식별률을 16%에서 30%로 끌어올렸다. [Google DeepMind](https://deepmind.google/blog/alphagenome-2-deciphering-how-cells-read-dna-to-better-understand-disease/)

범용 플래그십 경쟁도 계속된다. 알리바바는 컨텍스트 100만 토큰의 큐원4-맥스-프리뷰를 11월 25일까지 2주 한정으로 열었다. [큐원클라우드 문서](https://docs.qwencloud.com/developer-guides/getting-started/latest-model) 에이전트 운영 도구도 함께 늘었다. 데이터브릭스는 백그라운드에서 상시 가동하는 지니를 내놨고 [TechCrunch](https://techcrunch.com/2026/11/11/databricks-new-ai-agent-tells-ceo-ali-ghodsi-the-unvarnished-truth/), 플루라이는 출시 전 에이전트를 가상 사용자로 시험하는 플랫폼을 정식 출시하며 1,300만 달러를 유치했다. [PR Newswire](https://prnewswire.com/news-releases/plurai-raises-13m-to-build-the-simulation-infrastructure-for-trustworthy-self-improving-ai-agents-302936422.html) 에이전트가 사람의 지시 없이 돌아가는 시간이 길어질수록 판단 비용과 사전 검증이 별도 제품으로 분리되고 있다.

## 주요 이슈 4: 한국, 8,002억 원 온디바이스 AI반도체 일정 확정

산업통상부는 11월 12일 K-온디바이스 AI반도체 프로젝트 로드맵을 공개했다. 2030년까지 자율주행차용 1종, 스마트가전용 3종, 로봇·드론용 4종, 설계자산 2종 등 10종을 개발한다. 가전용 칩 1종은 제조 시점을 1년 이상 앞당기고, 삼성전자 파운드리는 2027년 21회의 시제품 제작 수요를 미리 반영한다. 데이터센터용 GPU 경쟁에 뛰어드는 대신, 한국이 완제품 경쟁력을 가진 자동차·가전·로봇에 들어갈 칩을 수요기업과 함께 설계하는 전략이다. [ZDNet 코리아](https://zdnet.co.kr/view/?no=20261112092039) / [이투데이](https://www.etoday.co.kr/news/view/2647280)

## 오늘의 시사점

오늘 소식에서 공통으로 드러나는 것은 겉으로 보이는 지표와 실제 상태의 차이다. 오픈AI의 매출 100억 달러는 조정 영업이익률 -109%와 함께 읽어야 하고, 코어위브의 168% 성장은 분기 이자 8억 4,600만 달러와 함께 읽어야 한다. 연구 쪽에서도 같은 문제가 다뤄졌다. 4비트 사전학습은 검증 손실 차이가 0.5~2%에 불과하지만 희귀한 사실을 익히는 데는 노출이 1.32~1.52배 필요했다. AI 논문 심사 벤치마크에서는 최고 시스템이 오류 100개 중 71개를 잡았지만 '빠진 내용'은 어떤 시스템도 찾지 못했다.

투자 판단에서도 제품 평가에서도 대표 지표 하나만 보면 놓치는 부분이 생긴다. 다음 주 11월 18일로 예상되는 앤트로픽 공모가 결정은 시장이 AI 기업의 매출 성장과 부채 구조 중 어느 쪽에 더 무게를 두는지 보여줄 것이다.

[arXiv:2611.12832](https://arxiv.org/abs/2611.12832) / [arXiv:2611.12820](https://arxiv.org/abs/2611.12820)

---

## 📎 참고 자료

1. [OpenAI's quarterly revenue reportedly crosses $10B for the first time — TechCrunch](https://techcrunch.com/2026/11/11/openais-quarterly-revenue-reportedly-crosses-10b-for-the-first-time/)
2. [CoreWeave turns to customer prepayments, shorter contracts to fund AI growth — TechCrunch](https://techcrunch.com/2026/11/11/coreweave-turns-to-customer-prepayments-shorter-contracts-to-fund-ai-growth/)
3. [Google, Nvidia, Microsoft Lead $26 Billion Anthropic Investment Ahead of IPO — Open Magazine](https://openthemagazine.com/business/google-nvidia-and-microsoft-join-26-billion-anthropic-deal-ahead-of-ipo)
4. [Anthropic IPO could lead to 'large correction' in markets, Fed official says — Semafor](https://www.semafor.com/article/11/11/2026/anthropic-ipo-could-lead-to-large-correction-in-markets-fed-official-says)
5. [US corporate AI spending hits a new high in October, but growth slows to 1.65 percent — The Decoder](https://the-decoder.com/us-corporate-ai-spending-hits-a-new-high-in-october-but-growth-slows-to-1-65-percent/)
6. [Gemini Decisions API — Google 블로그](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/)
7. [AlphaGenome 2 — Google DeepMind](https://deepmind.google/blog/alphagenome-2-deciphering-how-cells-read-dna-to-better-understand-disease/)
8. [Qwen4-Max-Preview — QwenCloud 개발자 문서](https://docs.qwencloud.com/developer-guides/getting-started/latest-model)
9. [Databricks' new AI agent tells CEO Ali Ghodsi the unvarnished truth — TechCrunch](https://techcrunch.com/2026/11/11/databricks-new-ai-agent-tells-ceo-ali-ghodsi-the-unvarnished-truth/)
10. [Plurai raises $13M — PR Newswire](https://prnewswire.com/news-releases/plurai-raises-13m-to-build-the-simulation-infrastructure-for-trustworthy-self-improving-ai-agents-302936422.html)
11. [K-온디바이스, 2030년까지 자율주행 AI칩 등 10종 개발 — ZDNet 코리아](https://zdnet.co.kr/view/?no=20261112092039)
12. [정부, 8000억 규모 'K-온디바이스 AI칩' 로드맵 확정 — 이투데이](https://www.etoday.co.kr/news/view/2647280)
13. [What the Loss Curve Misses: FP4 Pretraining Slows the Acquisition of Rare Facts — arXiv:2611.12832](https://arxiv.org/abs/2611.12832)
14. [How Well Does AI Peer Review Work? — arXiv:2611.12820](https://arxiv.org/abs/2611.12820)
