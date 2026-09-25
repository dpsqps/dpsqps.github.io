---
layout: single
title: "📊 AI 일간보고서 — 2026년 09월 25일"
date: 2026-09-25 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "앤트로픽"
  - "구글딥마인드"
  - "AI거버넌스"
  - "에이전트"
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

> **2026년 09월 25일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 09월 25일 AI 일간보고서

## 오늘의 핵심 요약

전날부터 이어진 소식들을 한 줄로 묶으면 **"에이전트가 실제 시스템을 만지기 시작했고, 그 대가로 자본과 규범이 동시에 움직였다"**로 정리된다. 앤트로픽은 아카마이와 7년 **116억 달러** 클라우드 계약을 맺고 최대 5% 지분 워런트까지 챙겼으며, 같은 날 자사 클로드가 박테리오파지에서 새로운 효소 시스템 후보를 찾아냈다고 발표했다. 아마존은 셀러센트럴 API를 외부 AI에 열어 클로드가 재고와 가격을 실제로 바꿀 수 있게 했고, 오픈AI는 같은 성격의 작업을 음성으로 모바일에서 실행하게 했다. 구글은 97개 언어 립싱크 아바타를 기업용으로 내놓으면서 제미나이 4의 출시를 앞당기겠다고 밝혔다. 그리고 이 회사들의 CEO들은 유엔 안보리에서 국제 규제를 요청했다. 기술 확산 속도와 거버넌스 공백이 같은 24시간 안에 나란히 드러난 날이다.

## 주요 이슈 1: 컴퓨트 계약이 지분 계약으로 — 앤트로픽·아카마이 116억 달러

아카마이가 앤트로픽과 체결한 **7년 116억 달러** 계약은 규모보다 구조가 중요하다. 첫째, 용도가 학습용 GPU가 아니라 앤트로픽의 급증하는 **CPU 워크로드**다. 추론과 서비스 운영을 떠받치는 범용 컴퓨트 수요가 이미 조 단위 장기 약정을 낼 만큼 커졌다는 뜻이다. 둘째, 계약에 지분이 얽혔다. 앤트로픽은 시리즈 B 주식을 **주당 111.33달러**에 사들여 보통주 약 **770만 주**로 전환할 수 있는 워런트를 받았고, 이 중 약 **2%**는 이번 약정에, 나머지 **3%**는 최대 **90억 달러** 추가 확대에 연동된다. 전부 실행되면 총액은 **약 200억 달러**다. 고객이 공급사의 주주가 되는 이 구조는 올해 반복돼 온 패턴으로, 컴퓨트 확보 경쟁이 조달에서 지배구조 영역으로 옮겨가고 있음을 보여준다. 시장은 즉각 반응해 아카마이 주가가 시간외에서 **20% 이상** 뛰었다. ([SiliconANGLE](https://siliconangle.com/2026/09/24/akamai-shares-jump-more-than-20-on-11-6b-anthropic-computing-deal/))

## 주요 이슈 2: 에이전트가 백오피스 권한을 받았다 — 아마존·오픈AI

아마존은 Accelerate 행사에서 **셀러센트럴 API를 외부 AI 에이전트에 개방**했다. 미국 판매자는 클로드나 아마존 Quick을 통해 셀러센트럴에 들어가지 않고 재고·가격·리스팅·분석을 조회하고 **변경**할 수 있다. 연결에 **약 60초**가 걸리고 코딩은 필요 없으며, 안전장치는 접근 범위 제한과 **행동별 사람 승인**, 전체 감사 로그다. 흥미로운 경계선은 아마존이 판매자 백오피스는 열었지만 **소비자 스토어프런트는 닫아 뒀다**는 점이다. 같은 시기 오픈AI는 ChatGPT 모바일에 음성 기반 에이전트 기능을 추가해, 문서·이메일 작성과 **슬랙 요약**, 사이트·프레젠테이션 생성을 음성으로 실행하게 했다(Plus·Pro는 Work 탭 전체, Free·Go는 플러그인·연결 앱 한정). 두 발표를 함께 보면 이번 분기의 경쟁축은 모델 성능 지표가 아니라 **"에이전트가 어떤 시스템에 쓰기 권한을 갖는가"**다. ([API Evangelist](https://apievangelist.com/2026/09/24/amazon-opened-seller-central-to-agents-and-kept-the-storefront-closed/) / [Dataconomy](https://dataconomy.com/2026/09/24/openai-voice-power-work-features-chatgpt-mobile/))

## 주요 이슈 3: 구글은 '얼굴'과 '속도'로 응수 — 라이브 아바타와 제미나이 4

구글은 **Gemini 3.8 Live with Live Avatar**를 Gemini Enterprise에 출시했다. **97개 언어** 음성-대-음성 동기화, 대화 중 언어 전환에도 끊기지 않는 립싱크, 참조 사진 1장과 오디오 샘플 1개로 만드는 커스텀 페르소나, 대화 흐름을 유지한 채 백그라운드 조회를 수행하는 **비동기 도구 실행**, 모든 출력에 삽입되는 **SynthID 워터마크**가 특징이다. 동시에 딥마인드 신임 수장 코라이 카부크추오글루는 **제미나이 4가 포스트트레이닝 초기 단계**이며 출시가 "연말보다 훨씬 이르게" 이뤄질 것이라고 밝혔다. 그는 "AGI 달성 여부는 올바른 논의가 아니다, **신뢰할 수 있는 에이전트**를 만들 수 있느냐가 논의"라고 말했다. 배경에는 부담도 있다. 5월에 발표된 제미나이 3.5 프로는 세 차례 일정을 놓치고 출하되지 못했고, 딥마인드의 채용 대비 이탈 비율은 2023년 2분기 약 **12:1**에서 2026년 3분기 약 **2:1**로 악화됐다. ([Google 블로그](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-with-live-avatar/) / [The Decoder](https://the-decoder.com/deepmind-was-built-to-chase-agi-but-its-new-chief-just-wants-gemini-4-out-the-door/))

## 주요 이슈 4: 안보리의 규제 요청과 미국의 거부 — 그리고 과학 현장의 자율 탐색

**15개 이사국**의 유엔 안보리 회의에서 다리오 아모데이는 "관리가 잘못되면 AI가 인류 전체에 대한 위험이 될 수 있다"고 말했고, 샘 올트먼은 "가장 중요한 결정이 샌프란시스코의 연구소들만으로 이뤄질 수는 없다"고 했다. 반면 미국 측은 국제 기구의 **중앙집중 통제 시도를 전면 거부**했다. 규제 대상이 규제를 요청하고 최대 시장국이 거부하는 구도다. 한편 실제 연구 현장에서는 클로드가 **약 21시간·약 950개 에이전트·약 2억 1천만 토큰**을 써서 **20만 개 이상의 역전사효소**를 훑고 **약 3,500개 후보**를 거쳐 CRISPR 유사 반복 배열을 가진 효소 시스템 **ART**를 지목했다. 단 기능은 미규명이고, 실험은 **BSL-1/2 환경에서 인간 과학자만** 수행했다. ([Al Jazeera](https://www.aljazeera.com/news/2026/9/24/ai-corporate-leaders-tell-un-the-industry-needs-global-regulation) / [Anthropic](https://www.anthropic.com/news/claude-discovers-novel-enzyme-system))

## 오늘의 시사점

세 흐름이 서로를 설명한다. 첫째, **권한의 이동**이다. 아마존 API 개방과 ChatGPT 음성 에이전트는 AI의 가치가 "정답 생성"에서 "시스템 조작 권한"으로 옮겨갔음을 보여주고, 그래서 60초 연결·행동별 승인·감사 로그 같은 지루한 장치가 오히려 제품의 핵심 스펙이 됐다. 둘째, **비용 구조의 고착**이다. 116억 달러 CPU 약정과 최대 200억 달러 확장 옵션, 그리고 지분 워런트는 추론 비용이 장기 고정비가 되고 있다는 신호다. 같은 날 벤처 자금이 응용 서비스보다 브라우저 보안(Island 4억 달러), 신경 인터페이스(Precision Neuroscience 2억 5천만 달러), 독점적 생물학 데이터(Basecamp Research 1억 4천만 달러) 같은 **통제점**으로 간 것도 같은 논리다. 셋째, **검증의 병목**이다. ART 사례에서 AI는 후보를 만들었지만 기능은 아직 모르고 실험은 사람이 했다. 안보리에서 드러난 거버넌스 공백도 결국 같은 문제의 정책 버전이다 — 생성 속도는 올라갔고, 확인하는 쪽은 그대로다. 앞으로 볼 지표는 모델 벤치마크가 아니라 **쓰기 권한의 범위, 추론 비용의 구조, 검증 인프라의 속도** 세 가지다.

---

## 📎 참고 자료

1. [Akamai shares jump more than 20% on $11.6B Anthropic computing deal — SiliconANGLE (2026-09-24)](https://siliconangle.com/2026/09/24/akamai-shares-jump-more-than-20-on-11-6b-anthropic-computing-deal/)
2. [Amazon Opened Seller Central To Agents, And Kept The Storefront Closed — API Evangelist (2026-09-24)](https://apievangelist.com/2026/09/24/amazon-opened-seller-central-to-agents-and-kept-the-storefront-closed/)
3. [OpenAI brings voice-powered work features to ChatGPT mobile — Dataconomy (2026-09-24)](https://dataconomy.com/2026/09/24/openai-voice-power-work-features-chatgpt-mobile/)
4. [Introducing Gemini 3.8 Live with Live Avatar — Google 블로그 (2026-09-24)](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-with-live-avatar/)
5. [Deepmind was built to chase AGI, but its new chief just wants Gemini 4 out the door — The Decoder (2026-09-24)](https://the-decoder.com/deepmind-was-built-to-chase-agi-but-its-new-chief-just-wants-gemini-4-out-the-door/)
6. [OpenAI, Anthropic CEOs call for global AI regulation at UN — Al Jazeera (2026-09-24)](https://www.aljazeera.com/news/2026/9/24/ai-corporate-leaders-tell-un-the-industry-needs-global-regulation)
7. [Claude discovers a novel enzyme system — Anthropic (2026-09-23)](https://www.anthropic.com/news/claude-discovers-novel-enzyme-system)
8. [Venture Capital & Startup Funding Roundup, September 24, 2026 — Tech Startups (2026-09-24)](https://techstartups.com/2026/09/24/venture-capital-startup-funding-roundup-september-24-2026-ark-invest-evolution-equity-mirae-asset-capital-socratic-partners-more/)
