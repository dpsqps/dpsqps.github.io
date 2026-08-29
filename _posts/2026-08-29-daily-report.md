---
layout: single
title: "📊 AI 일간보고서 — 2026년 08월 29일"
date: 2026-08-29 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "합성실패"
  - "물리계층자본"
  - "통제계층"
  - "사이버방어서한"
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

> **2026년 08월 29일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 08월 29일 AI 일간보고서

## 오늘의 핵심 요약

8월 28일을 관통한 주제는 **'조각은 잘하는데 이어붙이지 못한다'**였다. 구글의 새 영상 모델은 10초짜리 클립을 40초로 잇는 기능을 최대 성과로 내놨고, 오픈AI는 세션이 끝나면 죽어버리는 에이전트를 살려두는 모드를 시험 중이며, 같은 날 공개된 도시 스케일 벤치마크는 에이전트의 단거리 성공률이 최대 75%인데 장거리는 3.8%로 붕괴한다는 숫자를 내놨다. 세 사건은 서로 다른 레이어에서 같은 병목을 가리킨다 — **지속성(persistence)**이다.

두 번째 축은 자본과 규제가 동시에 물리 계층으로 내려온 것이다. a16z는 소프트웨어 배수 대신 칩·전력·로봇에 11억 달러를 걸었고, 시장은 마벨-구글의 1,200억 달러 계약에 '언제 매출이 되냐'를 물으며 주가를 8% 깎았으며, 호주 정부는 데이터센터에 재생에너지 조달 의무를 법제화하겠다고 확인했다. AI 산업의 채점표가 모델 성능에서 **전력·시점·회수 가능성**으로 이동하고 있다.

## 주요 이슈 1: 지속성이 새로운 경쟁 축이 됐다

가장 선명한 대비는 같은 날 나온 제품과 논문 사이에 있다. 구글 **Gemini Omni 1.1 Flash**는 직전 영상 10초를 문맥으로 읽어 10초 단위로 장면을 확장하고 최대 40초까지 일관성을 유지한다. 360p 드래프트 모드로 최대 60% 빠르게, 3분의 1 비용으로 미리보기를 만든 뒤 4K로 업스케일하는 2단계 워크플로도 함께 제시했다. 영상 생성의 진짜 병목이 한 컷의 화질이 아니라 **컷을 잇는 비용**이었다는 자백에 가깝다.

같은 주에 오픈AI는 Codex의 추론 강도 메뉴에 '퍼시스턴트 모드'를 추가하는 풀 리퀘스트를 8월 26일 머지했다. 사용자가 재울 때까지 종료되지 않고, 요청이 끝나면 스스로 후속 작업을 만들어 다음 세션까지 들고 간다. 회사는 즉시 출시 계획이 없다고 선을 그었지만, "작업을 끝내기도 전에 스스로 꺼진다"는 사용자 불만이 배경에 깔려 있다.

그리고 학계가 그 어려움의 크기를 숫자로 못 박았다. **UrbanGround**(arXiv:2608.27456)는 홍콩을 실제 스케일로 복제한 샌드박스에서 810개 검증 인스턴스로 10개 모델 버전을 평가했다. 시각 인식은 63.6~93.8%로 괜찮지만 방향 이해는 23.3~58.3%, 단거리 내비게이션 15.0~75.0%에 **장거리는 0.0~3.8%**다. 보행자 충돌률은 76.3~90.0%에 달했다. 요컨대 원자적 능력은 있으나 그것이 장시간 목표 지향 행동으로 **합성되지 않는다**. 제품이 40초를, 연구가 장거리 붕괴를 동시에 말한 것은 우연이 아니다.

## 주요 이슈 2: 자본과 규제가 같은 날 물리 계층에 도착했다

a16z의 **11억 달러 'Machine Age Fund'**는 이 회사가 오래 유지해온 소프트웨어 편향을 스스로 깬 사건이다. 투자 범위는 칩·메모리·네트워킹·스토리지에서 데이터센터·로보틱스·가전까지다. 근거로 내세운 진단은 하드웨어 공급망 전 구간이 동시에 용량 제약에 걸렸다는 것. VMware 출신 마틴 카사도와 인텔 데이터센터 부문 전 CTO 귀도 아펜젤러가 참여한다는 인선이 이 진단의 진지함을 보여준다.

같은 날 시장은 반대 방향에서 같은 결론에 도달했다. **마벨** 주가는 장전 8.2% 하락한 222.51달러를 찍었다. 구글에 122억 달러 규모 워런트를 주고 회계연도 2033년까지 최대 1,200억 달러 기회로 제시된 계약이 있는데도 그렇다. 이유는 그 매출이 **회계연도 2029년**에야 본격화된다는 점이 드러났기 때문이다. AI 자본지출을 '야망의 신호'로 후하게 쳐주던 국면은 끝났고, 이제 시점과 귀속으로 채점된다.

인프라 확장 자체는 계속된다. **알리바바 클라우드**는 상파울루에 데이터센터 2개로 첫 남미 리전을 열어 31개 리전·106개 AZ 체제를 갖췄다. 530억 달러 AI 인프라 투자의 일부다. 반대편에서 **호주**는 8월 28일 데이터센터에 '파이어밍이 뒷받침된 100% 재생에너지' 조달 의무를 확인했다. AEMO는 데이터센터 전력 수요가 국가전력시장의 2%에서 2050년 10%로 오를 것으로 본다. 1,500억 호주달러 규모 파이프라인을 유치하려는 나라가 스스로 전력 조건을 법으로 묶는 셈이다. 전력이 AI 인프라의 실질적 인허가 관문이 됐다.

## 주요 이슈 3: 통제 계층이 제품과 제도로 동시에 굳었다

에이전트를 만드는 도구는 흔해졌고, 이번 주 신제품은 그 다음 질문에 답한다. **AccuKnox AgentZ**는 조직·워크스페이스·에이전트·워크플로·샌드박스 5계층 위에 역할 기반 접근 통제를 걸고, SaaS·온프레미스·에어갭 3가지 배포를 지원한다. 모델은 OpenAI·Claude·Grok을 가리지 않는다. 회사는 이를 "AI를 쓰는 보안 제품이 아니라 보안이 내장된 AI 플랫폼"으로 규정했다. 규제 산업에서 에이전트 도입을 막던 것이 성능이 아니라 감사 추적이었다는 진단이 제품 형태로 굳은 것이다.

하드웨어 쪽에서는 **메타**가 스마트글라스의 몰래 촬영 우회로를 닫았다. 이전에는 녹화 시작만 차단됐고 시작 후 LED를 덮는 방식은 통했는데, 이제 녹화 도중 LED가 가려지면 카메라가 즉시 멈춘다. Ray-Ban Meta·Oakley Meta·Meta AI glasses 3개 라인에 적용된다. 착용형 AI의 신뢰가 모델 성능이 아니라 **주변인이 확인 가능한 물리적 신호의 무결성**에 달려 있음을 인정한 조치다.

제도 차원에서는 오픈AI·앤트로픽·구글·마이크로소프트·아마존을 포함한 **116개 기업**이 AI 기반 사이버공격 급증에 대비한 '방어 서지(defensive surge)'를 촉구하는 공동 서한을 냈다. 서명 기업에는 캐피털원·마스터카드·비자·GM·쇼피파이 등 비테크 기업도 포함됐다. 권고는 조직·보안기업·정부·프런티어 AI 기업 네 그룹으로 나뉘고, 각 사는 방어용 프런티어 모델 프로그램(오픈AI Daybreak, 앤트로픽 Mythos, 마이크로소프트 Perception)을 함께 제시했다. 경쟁사끼리 방어 인프라만 따로 떼어 공동 전선을 만든 형태다. [Business Standard](https://www.business-standard.com/technology/artificial-intelligence/collective-cyber-defence-openai-100-companies-ai-cyber-threats-126082800477_1.html) / [TechCrunch](https://techcrunch.com/2026/08/27/openai-anthropic-google-and-100-other-companies-call-for-action-to-defend-against-rogue-ai/)

## 오늘의 시사점

세 갈래 소식을 겹쳐 놓으면 하나의 그림이 나온다. **능력의 한계가 아니라 지속의 한계**가 지금의 병목이다. 모델은 10초를 잘 만들고, 단거리를 잘 걷고, 한 번의 요청을 잘 처리한다. 문제는 40초, 장거리, 다음 세션이다. 구글이 씬 확장을, 오픈AI가 퍼시스턴트 모드를, UrbanGround가 합성 실패를 같은 주에 말한 것은 업계가 동일한 벽 앞에 서 있다는 뜻이다.

그리고 그 벽을 넘는 비용은 물리적이다. 지속하려면 더 오래 연산해야 하고, 더 오래 연산하려면 칩과 전력이 필요하다. a16z가 하드웨어 펀드를 만들고 호주가 전력 조달을 법으로 묶은 것은 이 인과의 양쪽 끝이다. 마벨 사례는 그 사이에 놓인 시차의 가격표다 — 1,200억 달러라도 2029년에 오면 오늘의 주가는 8% 빠진다.

마지막으로, 오래 도는 에이전트는 오래 감시받아야 한다. AgentZ의 샌드박스와 감사 추적, 메타의 LED 강제 종료, 116개사의 사이버 방어 서한은 모두 같은 논리의 산물이다. **자율성을 늘리는 기능과 그것을 되감을 수 있는 장치가 같은 속도로 출시되는지**가, 앞으로 이 산업의 성숙도를 재는 실질적 지표가 될 것이다.

---

## 📎 참고 자료

1. [Build with Gemini Omni 1.1 Flash — Google Blog](https://blog.google/innovation-and-ai/technology/developers-tools/build-with-gemini-omni-1-1-flash/)
2. [Nevertheless, OpenAI Persists With New Always-On Agent — Gizmodo](https://gizmodo.com/nevertheless-openai-persists-with-new-always-on-agent-2000804088)
3. [UrbanGround — arXiv:2608.27456](https://arxiv.org/abs/2608.27456)
4. [a16z creates a $1.1B 'Machine Age' fund — TechCrunch](https://techcrunch.com/2026/08/28/a16z-creates-a-1-1b-machine-age-fund-to-accelerate-the-physical-buildout-of-ai/)
5. [Marvell Drops 8% as Google's $120 Billion Promise Arrives Too Late — Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/marvell-drops-8-googles-120-171726121.html)
6. [Alibaba pushes into South America's AI market — South China Morning Post](https://www.scmp.com/tech/big-tech/article/3365491/alibaba-pushes-south-americas-ai-market-launch-brazil-data-centres)
7. [Australia's Bowen warns on data centres — PV Tech](https://www.pv-tech.org/states-will-be-free-to-add-more-rigorous-requirements-but-not-to-water-them-down-australias-bowen-warns-on-data-centres/)
8. [AccuKnox Launches AgentZ — GlobeNewswire](https://www.globenewswire.com/news-release/2026/08/27/3351759/0/en/accuknox-launches-agentz-to-help-enterprises-build-run-and-govern-ai-agents-at-scale.html)
9. [Meta Ray-Ban smart glasses privacy LED loophole update — 9to5Google](https://9to5google.com/2026/08/28/meta-ray-ban-smart-glasses-privacy-led-loophole-update/)
10. [Collective cyber defence: OpenAI, 100+ companies — Business Standard](https://www.business-standard.com/technology/artificial-intelligence/collective-cyber-defence-openai-100-companies-ai-cyber-threats-126082800477_1.html)
11. [OpenAI, Anthropic, Google and 100 other companies call for action — TechCrunch](https://techcrunch.com/2026/08/27/openai-anthropic-google-and-100-other-companies-call-for-action-to-defend-against-rogue-ai/)
