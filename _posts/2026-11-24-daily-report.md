---
layout: single
title: "📊 AI 일간보고서 — 2026년 11월 24일"
date: 2026-11-24 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "AI에이전트"
  - "추론인프라"
  - "AI보안"
  - "온디바이스AI"
  - "국산NPU"
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

> **2026년 11월 24일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 11월 24일 AI 일간보고서

## 오늘의 핵심 요약

지난주 나스닥 급락과 아시아 증시 하락으로 'AI 재평가' 분위기가 짙었지만, 23일(현지시간)에는 사모·벤처 시장에서 대형 거래가 잇따랐습니다. 하나로 묶으면 **'에이전트를 실제로 굴리는 데 필요한 것'에 돈이 몰렸다**는 것입니다. 에이전트로 성과를 파는 회사(시에라), 에이전트가 쓰는 추론을 더 싸게 공급하는 회사(말로우), 에이전트를 지키는 보안 회사(크라우드스트라이크)가 같은 날 숫자를 내놓았습니다. 모델 쪽에서도 새 모델 경쟁보다 기존 모델을 쓰임새와 장비에 맞게 다시 조정하는 작업(GPT-6.2 Sol 채팅용 버전, 노타의 알파마요 최적화)이 중심이었습니다.

## 주요 이슈 1: 거품 논란 속에서도 에이전트 기업 가치는 반년 만에 두 배

시에라는 기업가치 300억 달러에 17억 5,000만 달러를 유치한다고 밝혔습니다. 5월 시리즈 E 때 기업가치가 150억 달러를 조금 넘었으니, 6개월 만에 약 두 배가 된 셈입니다. 이를 받쳐 주는 숫자는 매출 증가 속도입니다. 시에라는 ARR 4억 달러를 넘었고 3분기에만 1억 5,000만 달러 넘게 늘었다고 밝혔습니다. 대략 ARR의 75배에 기업가치가 매겨진 것으로, 상장사 기준으로 보면 공격적인 수준입니다. 시에라도 블로그에서 시장의 거품 우려를 직접 언급했습니다. 그런데도 투자자들이 이 가격을 받아들인 이유는 과금 방식에 있다고 봅니다. 시에라는 토큰이나 사용량이 아니라 '해결한 결과'에 요금을 받습니다. 모델 단가가 계속 떨어져도 매출이 함께 줄지 않는 구조입니다. 지난주 시장이 걱정한 것이 'AI 단가 하락이 매출을 깎는다'는 점이었다면, 시에라는 그 걱정을 피해 가는 사업 모델의 사례입니다. [Sierra 블로그](https://sierra.ai/blog/series-f-30b) / [CMSWire](https://www.cmswire.com/contact-center/sierra-hits-30b-valuation-on-175b-series-f/)

## 주요 이슈 2: 추론 인프라, '엔비디아 밖'이 하나의 투자 분야가 되다

창업 6개월 된 말로우가 시드 라운드에서 2억 7,700만 달러(기업가치 11억 5,000만 달러)를 받았습니다. 첫 데이터센터는 Etched 칩, 두 번째는 AMD Helios 랙으로 짓습니다. 회사가 내세우는 근거는 성능과 비용에서 2~3배 낫다는 것입니다. 아직 가동 중인 시설도 공개된 매출도 없는데 이 정도 시드 투자를 받았다는 것은, 투자자들이 '학습은 엔비디아, 추론은 여러 칩'으로 시장이 나뉘는 쪽에 베팅하고 있다는 뜻입니다. 첫 고객이 대형 AI 코딩 기업이라는 점도 중요합니다. 코딩 에이전트는 한 번 작업할 때 수많은 토큰을 쓰기 때문에 추론 단가에 가장 민감한 고객입니다. 같은 날 국내에서는 리벨리온이 SK텔레콤에 NPU 서버 약 40대(200억 원대)를 공급한다는 보도가 나왔습니다. 과기정통부 간담회에서는 HBM·LPDDR 공급 부족이 주요 의제였습니다. 엔비디아가 아닌 칩 진영이 커지려면 칩 성능만큼 메모리 공급이 받쳐 줘야 한다는 점을 보여 줍니다. [The Next Web](https://thenextweb.com/news/marlowe-277m-seed-multi-silicon-ai-inference-factories) / [한국경제](https://www.hankyung.com/article/2026112349541) / [정책브리핑 재게재](https://dazabi.com/insurance_magazine/article.php?id=48028)

## 주요 이슈 3: '에이전트 시대의 보안'을 명분으로 한 439억 달러 인수

크라우드스트라이크는 지스케일러를 약 439억 달러에 전액 주식으로 인수하기로 했습니다(지스케일러 1주당 1.135주). 엔드포인트 보안 1위 기업이 네트워크 보안의 대표 기업을 사들이는 것으로, 보안 업계 최대 규모의 거래 중 하나입니다. 회사는 인수 이유를 AI에서 찾았습니다. AI 에이전트 보호 제품 'Falcon Guardian'이 출시 첫해에 ARR 1억 달러를 넘었다며, Falcon을 '에이전트 시대의 보안 운영체제'로 소개했습니다. 에이전트가 사내 시스템과 외부 API를 마음대로 오가기 시작하면, 단말기를 지키는 보안과 네트워크를 지키는 보안을 따로 운영하기 어려워집니다. 같은 날 실적도 좋았습니다. 기말 ARR 62억 6,000만 달러(전년 대비 27% 증가), 순신규 ARR 사상 최대 4억 1,900만 달러였습니다. 에이전트 확산이 보안 업계에서는 이미 매출로 나타나고 있다는 근거입니다. [CrowdStrike 보도자료(SEC)](https://www.sec.gov/Archives/edgar/data/0001535527/000153552726000035/crwd-20261123xex991.htm)

## 주요 이슈 4: 모델은 '용도별·장비별 재조정'의 시대로

OpenAI는 Work·Codex용으로 먼저 낸 GPT-6.2 Sol을 일주일 뒤 채팅 탭용으로 따로 조정해 유료 요금제에 배포했습니다. 까다로운 대화에서 안전 정책을 지키는 비율은 91~94%로, GPT-6(77~80%)보다 높아졌다고 밝혔습니다. 국내 노타는 엔비디아 '알파마요 2 엣지'를 다시 학습시키지 않고 소프트웨어 최적화만으로 젯슨 AGX 토르에서 15배 빠르게 만들었습니다. 경로 생성까지 76ms로, 실시간 주행에 필요한 100ms 기준을 맞췄다는 설명입니다(노타 자체 측정). 연구 쪽에서도 같은 흐름이 보입니다. 모바일 NPU에서 에너지당 토큰을 최대 4.3배 늘린 MixFold, 토큰당 4% 미만의 추가 지연으로 안전 검사를 함께 하는 ToRA처럼 '이미 있는 모델을 더 싸고 안전하게 돌리는' 논문이 많았습니다. [MacRumors](https://www.macrumors.com/2026/11/23/openai-gpt-6-2-sol-chatgpt/) / [뉴스핌](https://www.newspim.com/news/view/20261124000464) / [arXiv 2611.26976](https://arxiv.org/abs/2611.26976) / [arXiv 2611.26975](https://arxiv.org/abs/2611.26975)

## 오늘의 시사점

첫째, **AI의 가치가 '모델'에서 '실행과 결과'로 옮겨 가고 있습니다.** 지난주 시장은 AI 단가가 떨어지면 매출도 줄어든다는 걱정에 흔들렸습니다. 그런데 오늘 큰돈을 받은 곳은 그 단가 하락을 오히려 이용하는 회사들이었습니다. 결과에 요금을 받는 시에라, 단가를 더 낮추는 말로우, 에이전트가 늘수록 보호할 대상이 늘어나는 크라우드스트라이크입니다.

둘째, **추론 단가를 낮추는 일이 하드웨어(말로우·리벨리온), 소프트웨어(노타), 연구(MixFold) 세 층에서 동시에 진행되고 있습니다.** 코딩 에이전트처럼 토큰을 많이 쓰는 서비스가 커질수록 이 세 층의 경쟁이 더 중요해집니다. 다만 국산 NPU와 엔비디아가 아닌 칩 진영 모두 메모리 공급이라는 같은 병목을 안고 있습니다.

셋째, **수치를 읽을 때 조심해야 합니다.** 시에라의 기업가치는 매출의 약 75배 수준입니다. 말로우의 '2~3배' 우위와 노타의 '15배' 가속은 모두 회사가 직접 측정한 값이며, 측정 조건이 공식 기준과 다릅니다. 투자 열기가 다시 붙은 날일수록 회사가 발표한 숫자와 독립적으로 검증된 숫자를 나눠 봐야 합니다.

[Sierra](https://sierra.ai/blog/series-f-30b) / [The Next Web](https://thenextweb.com/news/marlowe-277m-seed-multi-silicon-ai-inference-factories) / [CrowdStrike(SEC)](https://www.sec.gov/Archives/edgar/data/0001535527/000153552726000035/crwd-20261123xex991.htm)

---

## 📎 참고 자료

1. [Sierra — Building the digital front door (Series F)](https://sierra.ai/blog/series-f-30b)
2. [CMSWire — Sierra Hits $30B Valuation on $1.75B Series F](https://www.cmswire.com/contact-center/sierra-hits-30b-valuation-on-175b-series-f/)
3. [The Next Web — Marlowe raises a $277M seed](https://thenextweb.com/news/marlowe-277m-seed-multi-silicon-ai-inference-factories)
4. [CrowdStrike — Q3 FY2027 실적 및 지스케일러 인수 (SEC EX-99.1)](https://www.sec.gov/Archives/edgar/data/0001535527/000153552726000035/crwd-20261123xex991.htm)
5. [한국경제 — 신제품 앞세운 국산 AI칩, 글로벌 시장 도전장](https://www.hankyung.com/article/2026112349541)
6. [과기정통부 AI 반도체 업계 간담회 (정책브리핑 재게재)](https://dazabi.com/insurance_magazine/article.php?id=48028)
7. [MacRumors — OpenAI Brings GPT-6.2 Sol to ChatGPT's Chat Tab](https://www.macrumors.com/2026/11/23/openai-gpt-6-2-sol-chatgpt/)
8. [뉴스핌 — 노타, 엔비디아 자율주행 AI 추론 속도 15배 향상](https://www.newspim.com/news/view/20261124000464)
9. [arXiv 2611.26976 — MixFold](https://arxiv.org/abs/2611.26976)
10. [arXiv 2611.26975 — Run One, Get Two](https://arxiv.org/abs/2611.26975)
