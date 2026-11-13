---
layout: single
title: "📊 AI 일간보고서 — 2026년 11월 13일"
date: 2026-11-13 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "엔비디아"
  - "제미나이4하이드로젠"
  - "AI안경"
  - "추론칩"
  - "온디바이스AI"
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

> **2026년 11월 13일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 11월 13일 AI 일간보고서

## 오늘의 핵심 요약

11월 12일(현지시간)은 AI 산업의 '정점'과 '확산'이 동시에 드러난 하루였습니다. 정점에서는 AI 반도체 시장을 지배해 온 엔비디아의 젠슨 황 CEO가 전격 사임하며 리더십 공백이 생겼고, 확산의 측면에서는 구글이 저가·고속 모델과 AI 안경을 동시에 내놓고, 오픈소스 진영은 1,450억 매개변수 모델을 노트북으로 끌어내렸습니다. 투자 자금은 엔비디아 이후를 겨냥한 추론 칩과 산업용 로봇으로 흘러가고 있습니다.

## 주요 이슈 1: 엔비디아 리더십 공백과 '포스트 엔비디아' 베팅

엔비디아는 젠슨 황의 사장·CEO·이사직 즉시 사임을 발표하고, 콜레트 크레스 CFO를 임시 CEO로, 하비 C. 존스를 회사 역사상 첫 이사회 의장으로 선임했습니다. CNBC에 따르면 주가는 이날 4.3% 하락했습니다([NVIDIA 뉴스룸](https://nvidianews.nvidia.com/news/nvidia-announces-ceo-transition) / [CNBC](https://cnbc.com/2026/11/12/nvidia-jensen-huang-ceo-live-updates.html)). 창업자가 33년간 이끌던 회사에서 CEO와 의장 역할이 처음 분리된 것은 지배구조 측면에서도 의미가 큽니다. 시장의 첫 시험대는 11월 17일 3분기 실적 발표입니다.

같은 날 자본은 엔비디아의 대안에 몰렸습니다. 영국 프랙타일은 7억 2,000만 달러 시리즈C로 6개월 만에 기업가치가 약 10억 달러에서 약 70억 달러(보도 기준)로 뛰었고([Tech Funding News](https://techfundingnews.com/fractile-720m-series-c-7b-valuation-ai-inference-chips)), CUDA 의존을 줄이는 추론 컴파일러 루미널은 2,300만 달러를 유치하며 월 45조 토큰 이상을 처리 중이라고 밝혔습니다([SiliconANGLE](https://siliconangle.com/2026/11/12/with-23m-in-funding-luminal-is-the-latest-startup-to-put-nvidias-cuda-moat-in-its-crosshairs)). 서울에서는 인텔이 HBM 대신 LPDDR5X를 쓰는 추론 GPU '크레센트 아일랜드'(기본 160GB, 350W)를 소개하며 국내 23개사와 얼라이언스를 꾸렸습니다([인공지능신문](https://www.aitimes.kr/news/articleView.html?idxno=42712)). 학습은 엔비디아, 추론은 다변화라는 구도가 굳어지는 모습입니다.

## 주요 이슈 2: 싸고 빠른 모델이 상위 모델을 넘어서다

구글 '제미나이 4 하이드로젠'은 입력 100만 토큰당 1.50달러의 고속 모델이면서 아티피셜 애널리시스 지능 지수 51점(xhigh 54점)으로 상위 모델 아르곤(50점)을 앞섰습니다. 이전 3.8 플래시 대비 2.5배 빠르고 터미널-벤치 4.1 점수는 18.2%에서 57%로 3배 넘게 뛰었습니다([Google 블로그](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/)). 안티그래비티에서 상위 모델 카본과 함께 오케스트레이터로 쓰면 할당량 24% 절감, 완료 속도 19% 향상을 제시한 점도 눈에 띕니다. '최상위 모델 하나'가 아니라 '고가 모델 + 저가 실행 모델' 조합이 에이전트 비용 구조의 표준이 되고 있습니다.

오픈소스에서는 Edge0가 전체 1,450억 매개변수 중 약 100억 개만 활성화하는 'Edge0-145B'를 최대 메모리 29GB, 디코딩 초당 80토큰 이상으로 로컬에서 돌린다고 발표했습니다([Edge0 블로그](https://edge0.ai/blog/introducing-edge0-145b-frontier-ai-capabilities-on-your-own-computer)). 회사 자체 평가라는 한계는 있지만, 프런티어급 점수를 개인 PC에서 노리는 시도가 구체적 수치와 함께 나왔다는 점에서 클라우드 토큰 가격 하락 압력은 더 커질 것입니다.

## 주요 이슈 3: AI가 얼굴 위로 — 삼성·구글 AI 안경 출시 확정

삼성전자와 구글은 젠틀몬스터·워비파커와 함께 만든 AI 안경 30종을 공개하고 12월 10일 한국·미국 출시를 확정했습니다. 국내 가격은 65만~70만 원, 무게 약 41g, 배터리 최대 9시간이며 제미나이로 70개 이상 언어 실시간 번역을 지원합니다([아주경제](https://www.ajunews.com/view/20261112154700790) / [Google 블로그](https://blog.google/innovation-and-ai/technology/xr-ar/google-intelligent-eyewear-collections-pre-order/)). 올해 상반기 출하 점유율 81.3%의 메타가 독주하던 시장에 안드로이드·아이폰 모두와 호환되는 대항마가 생긴 셈입니다.

## 주요 이슈 4: '실행하는 에이전트'와 '맞춤형 판단'의 평가

네이버는 쇼핑·예약·지도·페이에 직접 연결되는 개인형 AI 에이전트 앱을 연내 내놓겠다고 밝혔고([파이낸셜뉴스](https://www.fnnews.com/news/202611120921163938)), 찰스 슈왑은 클로드 사용자 일부에게 계좌 데이터를 MCP로 연결하는 시범 서비스를 시작했습니다([Investing.com](https://in.investing.com/news/stock-market-news/charles-schwab-launches-ai-tools-extends-options-trading-hours-93CH-5699723)). 에이전트가 실제 돈과 일정에 손을 대는 단계로 넘어가면서, '작업을 끝냈는가'보다 '그 사람에게 맞는 선택을 했는가'가 중요해집니다. ETRI의 '트리니티' 벤치마크가 151가지 사용자 조건으로 이 문제를 측정하고, 일부 LLM 에이전트가 채식 사용자에게 부적절한 음식을 고른 사례를 보고한 것은 바로 이 지점을 겨냥합니다([인공지능신문](https://www.aitimes.kr/news/articleView.html?idxno=42718)).

## 오늘의 시사점

첫째, AI 하드웨어 패권은 한 기업의 리더십 이슈와 무관하게 이미 분산되는 중입니다. 엔비디아의 CEO 공백은 단기 변동성을 키우겠지만, 프랙타일·루미널·인텔 사례처럼 추론 영역의 대안 투자는 그 이전부터 가속하고 있었습니다. 둘째, 모델 경쟁의 축이 '최고 점수'에서 '점수당 비용'으로 이동했습니다. 1.5달러짜리 모델이 상위 모델을 넘고, 29GB 메모리로 1,450억 매개변수 모델이 도는 상황에서 가격 경쟁력은 곧 배포 범위입니다. 셋째, AI의 접점이 안경·증권 계좌·생활 서비스로 넓어질수록 신뢰성 평가의 기준도 '정답률'에서 '개인 맥락에 맞는 판단'으로 바뀌어야 합니다. 이 세 흐름이 맞물리는 지점, 즉 값싼 모델이 개인 데이터에 접근해 실제 행동을 하는 영역이 2027년 AI 경쟁의 주무대가 될 가능성이 큽니다.

[NVIDIA 뉴스룸](https://nvidianews.nvidia.com/news/nvidia-announces-ceo-transition) / [Google 블로그](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/) / [Tech Funding News](https://techfundingnews.com/fractile-720m-series-c-7b-valuation-ai-inference-chips)

---

## 📎 참고 자료

1. [NVIDIA — NVIDIA Announces CEO Transition](https://nvidianews.nvidia.com/news/nvidia-announces-ceo-transition)
2. [CNBC — Nvidia CEO Jensen Huang resigns: Live updates](https://cnbc.com/2026/11/12/nvidia-jensen-huang-ceo-live-updates.html)
3. [Tech Funding News — Fractile raises $720M](https://techfundingnews.com/fractile-720m-series-c-7b-valuation-ai-inference-chips)
4. [SiliconANGLE — Luminal raises $23M](https://siliconangle.com/2026/11/12/with-23m-in-funding-luminal-is-the-latest-startup-to-put-nvidias-cuda-moat-in-its-crosshairs)
5. [인공지능신문 — 인텔, 차세대 추론 가속기 공개](https://www.aitimes.kr/news/articleView.html?idxno=42712)
6. [Google — Introducing Gemini 4 Hydrogen](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/)
7. [Edge0 — Introducing Edge0-145B](https://edge0.ai/blog/introducing-edge0-145b-frontier-ai-capabilities-on-your-own-computer)
8. [아주경제 — 삼성전자, 구글과 공동 개발한 첫 AI 글라스 내달 10일 출시](https://www.ajunews.com/view/20261112154700790)
9. [Google — Intelligent eyewear pre-order](https://blog.google/innovation-and-ai/technology/xr-ar/google-intelligent-eyewear-collections-pre-order/)
10. [파이낸셜뉴스 — 네이버 "연내 AI 에이전트 앱 출시"](https://www.fnnews.com/news/202611120921163938)
11. [Investing.com — Charles Schwab launches AI tools](https://in.investing.com/news/stock-market-news/charles-schwab-launches-ai-tools-extends-options-trading-hours-93CH-5699723)
12. [인공지능신문 — ETRI '트리니티' 공개](https://www.aitimes.kr/news/articleView.html?idxno=42718)
