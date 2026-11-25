---
layout: single
title: "📊 AI 일간보고서 — 2026년 11월 25일"
date: 2026-11-25 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "델"
  - "JP모건"
  - "AI설비투자"
  - "뉴욕증시"
  - "앤스로픽"
  - "MCP"
  - "Muse"
  - "Hy-MT3"
  - "arXiv"
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

> **2026년 11월 25일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 11월 25일 AI 일간보고서

## 오늘의 핵심 요약

수요를 보여 주는 숫자와 가격을 보여 주는 숫자가 같은 날 반대 방향을 가리켰습니다. 델은 AI 서버 수주잔고 1,323억 달러를 발표했고 JP모건은 5대 빅테크의 내년 AI 자본지출을 1조 4,000억 달러로 내다봤지만, 뉴욕증시의 AI 반도체주는 전날 상승분을 되돌렸고 앤스로픽은 공모가 아래로 내려갔습니다. 제품 쪽에서는 에이전트가 외부 서비스와 연결되는 범위가 넓어졌고, 모델과 연구 쪽에서는 '평균 점수가 아니라 오류의 종류'를 따지는 흐름이 이어졌습니다.

## 주요 이슈 1: 수주는 사상 최대, 주가는 하루 만에 반납

델의 회계연도 2027년 3분기 매출은 549억 4,000만 달러로 전년 대비 두 배를 넘었고, AI 최적화 서버 매출은 220억 달러로 291% 늘었습니다. 다음 회계연도 AI 서버 매출 전망 780억 달러는 시장 예상 740억 달러를 웃돕니다. 수치만 보면 수요 둔화의 흔적은 없습니다.

그런데 같은 24일(현지시간) 나스닥은 1.48% 내렸고, 엔비디아는 5.86%, 마이크론은 10.97%, AMD는 8.86% 하락했습니다. 앤스로픽은 6.54% 내린 81.91달러로 공모가 83달러를 밑돌았습니다. 다우지수는 0.85% 올라 5만 선을 회복했으니 시장 전체가 무너진 것이 아니라 AI 반도체에서 자금이 빠진 것입니다.

두 사실을 함께 놓고 보면, 지금 시장이 묻는 것은 '주문이 있는가'가 아니라 '그 주문이 대금으로 회수되는가'입니다. 델의 제프 클라크 부회장이 모든 AI 주문을 자금 조달 능력과 전력·부지 확보 여부까지 심사한다고 굳이 설명한 것은, 그 질문을 회사가 알고 있다는 뜻입니다. 수주잔고의 크기보다 수주잔고의 질을 설명해야 하는 국면입니다. [CNBC](https://www.cnbc.com/2026/11/24/dell-earnings-report-q3-2027.html) / [파이낸셜뉴스](https://www.fnnews.com/news/202611250626366579)

## 주요 이슈 2: 내년 1조 4,000억 달러, 그리고 2028년이라는 단서

JP모건 전망의 앞부분은 낙관적입니다. 알파벳·마이크로소프트·아마존·메타·오라클의 내년 AI 자본지출이 1조 4,000억 달러(약 1,884조 원)로, 올해 전망치 7,360억 달러의 두 배에 가깝습니다. 골드만삭스(1조 2,000억 달러)와 모건스탠리(리스 포함 1조 6,000억 달러)도 방향은 같습니다.

뒷부분에는 단서가 붙습니다. 증가세가 2028년부터 크게 꺾이고, 2028년 증가율 전망은 12~14% 수준입니다. JP모건 수석 이코노미스트는 총수요 기준으로 AI 투자의 정점이 올해일 수 있다고 봤고, 투자 재원이 현금에서 회사채·주식 발행으로 옮겨가고 있다고 지적했습니다. 자기 돈으로 하던 투자가 빌린 돈으로 하는 투자로 바뀌면, 금리와 신용 여건이 투자 속도를 좌우하는 변수가 됩니다.

한국에는 기회와 시한이 함께 주어진 셈입니다. KB증권은 내년 D램 수요 증가율(25%)이 공급 증가율(18%)을 웃돌 것으로, 트렌드포스는 HBM 평균판매가격이 122% 오를 것으로 봤습니다. 내년까지의 가시성은 높지만, 증설 결정은 2028년 이후의 수요를 보고 내려야 한다는 점이 부담입니다. [마켓잉크](https://www.market-ink.co.kr/news/articleView.html?idxno=15807) / [서울신문](https://www.seoul.co.kr/news/economy/industry/2026/11/25/20261125004004)

## 주요 이슈 3: 에이전트의 '연결'이 규격과 매장 양쪽에서 넓어졌다

앤스로픽은 Claude의 MCP 기능을 확장해, 외부 서비스 서버가 도구와 함께 사용 절차(스킬)를 배포할 수 있게 했습니다(공개 베타). 오래 걸리는 작업을 서버에 맡기는 Tasks와, 작업 도중 사용자 입력을 받는 Elicitation은 정식 출시됐습니다. MCP SDK 월간 다운로드 7억 회, Claude용 커넥터 1만 개라는 수치는 이 규격이 이미 사실상의 표준 접점이 됐음을 보여 줍니다.

메타는 개인 에이전트 Muse를 영국에 출시하며 Sainsbury's, Argos, M&S, easyJet 등을 연결했고, Argos는 15만 개 이상의 상품을 연결했습니다. 결제는 Stripe의 에이전트용 지갑을 거치되 구매마다 사용자 승인을 받습니다.

두 소식을 나란히 보면 역할 분담이 드러납니다. 서비스 제공사는 '우리 도구를 이렇게 쓰라'는 절차를 직접 정의하기 시작했고, 에이전트 운영사는 돈이 나가는 순간에 사람의 확인을 넣습니다. 영국 금융감독청이 출시 당일 에이전트형 AI에 대한 기대 사항을 내놓은 것처럼, 규제도 이 승인 단계를 중심으로 짜일 가능성이 높습니다. [Claude 공식 블로그](https://claude.com/resources/articles/skills-over-mcp-tasks-and-more) / [TNW](https://thenextweb.com/news/meta-muse-uk-launch)

## 주요 이슈 4: 평균 점수 대신 '어떤 오류가 얼마나'를 묻는다

텐센트의 오픈소스 번역 모델 Hy-MT3는 지원 언어를 38개에서 102개로 늘리면서, 성능을 종합 점수가 아니라 오류 유형별로 제시했습니다. 5,000개 실사용 표본에서 오역 포함 비율이 56.0%에서 31.8%로, 누락·추가 오류가 21.2%에서 5.5%로 줄었다는 식입니다. 자체 평가라는 한계는 있지만, 사용자가 실제로 겪는 문제 단위로 성능을 말했다는 점은 눈여겨볼 만합니다.

arXiv 논문들도 같은 방향입니다. 'Exact on Paper'는 서빙 최적화가 평균 정확도를 유지하면서도 개별 답을 뒤집는 비율을 쟀고, FP8 KV 캐시 설정이 요청의 3.36%에서 채점 결과를 바꾼다고 보고했습니다. ComplexIF는 14개 모델 중 최고 모델도 여러 제약을 전부 지키는 비율이 절반에 못 미친다고 밝혔습니다. 평균이 같아도 내용이 다를 수 있고, 조건 하나하나는 지켜도 전부는 못 지킬 수 있다는 이야기입니다. [인공지능신문](https://www.aitimes.kr/news/articleView.html?idxno=42880) / [arXiv:2611.29663](https://arxiv.org/abs/2611.29663) / [arXiv:2611.29775](https://arxiv.org/abs/2611.29775)

## 오늘의 시사점

오늘 뉴스를 하나로 묶으면 '총량에서 내역으로'입니다. 자본시장은 수주잔고 총액보다 그 주문의 회수 가능성을 묻고, 증권사 전망은 내년 총액과 함께 2028년의 둔화를 적어 넣었습니다. 에이전트 제품은 '무엇이든 연결된다'에서 '어느 단계에서 사람이 승인하는가'로 설계의 초점이 옮겨갔고, 모델 평가는 평균 점수에서 오류 유형과 개별 답의 변동으로 내려갔습니다.

실무자에게 주는 함의는 분명합니다. AI 인프라에 기대는 사업 계획이라면 2027년까지의 수요와 2028년 이후의 수요를 분리해서 가정해야 합니다. 에이전트를 도입하는 조직은 연결 가능한 서비스 수보다 승인·감사 지점을 먼저 정해야 합니다. 그리고 모델이나 서빙 설정을 바꿀 때는 평균 점수가 유지됐다는 사실만으로 '달라진 것이 없다'고 결론 내려서는 안 됩니다.

[CNBC](https://www.cnbc.com/2026/11/24/dell-earnings-report-q3-2027.html) / [마켓잉크](https://www.market-ink.co.kr/news/articleView.html?idxno=15807) / [Claude 공식 블로그](https://claude.com/resources/articles/skills-over-mcp-tasks-and-more) / [인공지능신문](https://www.aitimes.kr/news/articleView.html?idxno=42880)

---

## 📎 참고 자료

1. [CNBC — Dell earnings beat on AI strength, company authorizes $25 billion buyback](https://www.cnbc.com/2026/11/24/dell-earnings-report-q3-2027.html)
2. [파이낸셜뉴스 — 뉴욕증시: 엔비디아 약세 속 기술주 후퇴…앤스로픽, 공모가 붕괴](https://www.fnnews.com/news/202611250626366579)
3. [마켓잉크 — 빅테크 5곳, 내년 AI에 1조4천억달러 쏟는다…JP모건 "2028년부터 증가세 둔화"](https://www.market-ink.co.kr/news/articleView.html?idxno=15807)
4. [서울신문 — 내년 AI 설비투자 1900조원 육박… '삼전닉스' 메모리 슈퍼사이클 탄력](https://www.seoul.co.kr/news/economy/industry/2026/11/25/20261125004004)
5. [Claude 공식 블로그 — MCP servers can now ship skills, run tasks, and more with Claude](https://claude.com/resources/articles/skills-over-mcp-tasks-and-more)
6. [TNW — Meta's AI agent Muse lands in the UK in time for Christmas shopping](https://thenextweb.com/news/meta-muse-uk-launch)
7. [인공지능신문 — 텐센트, 한국어 등 102개 언어 지원 오픈소스 번역 AI '하이 MT3' 공개](https://www.aitimes.kr/news/articleView.html?idxno=42880)
8. [arXiv:2611.29663 — Exact on Paper](https://arxiv.org/abs/2611.29663)
9. [arXiv:2611.29775 — ComplexIF](https://arxiv.org/abs/2611.29775)
