---
layout: single
title: "📊 AI 일간보고서 — 2026년 09월 01일"
date: 2026-09-01 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "공정의공개"
  - "VLOSE첫지정"
  - "AI예산84퍼센트"
  - "교사없는증류"
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

> **2026년 09월 01일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 09월 01일 AI 일간보고서

## 오늘의 핵심 요약

8월의 마지막 날과 9월의 첫날에 걸쳐 나온 소식들에는 하나의 공통 축이 있다. **공개되는 대상과 규제되는 대상이 모두 '결과물'에서 '공정'으로 내려갔다는 것**이다. 딥시크는 완성된 답변이 아니라 305B 가중치를 MIT로 풀었고, 앤트로픽은 모델 스펙이 아니라 학습 파이프라인이 어디서 망가졌는지를 날짜와 비율로 적었다. 유럽연합은 챗GPT의 답변 품질이 아니라 **감사·투명성 절차**를 의무화했고, 한국 정부는 서비스가 아니라 **GPU 1만 장과 학습 예산**을 예산서에 박아 넣었다. 완성품을 평가하던 시기가 지나고, 완성품을 만드는 공정이 심사 대상이 되는 국면으로 넘어가는 중이다.

## 주요 이슈 1: 공개의 단위가 '모델'에서 '공정'으로 내려왔다

딥시크는 8월 21일 API로만 열었던 멀티모달 모델 `DeepSeek-V4-Flash-Vision-Exp`를 8월 31일 허깅페이스에 총 305B 파라미터, MIT 라이선스로 공개했다. 열흘 만에 API 전용에서 오픈웨이트로 내려온 것이다. 자체 측정 기준으로 Terminal Bench 2.1 83.9(오퍼스 4.8은 85.0), ApexBench 36.5(39.4)로 근소하게 뒤지지만 Agents' Last Exam은 27.3 대 25.7, ZeroBench(Pass@5)는 35.0 대 34.0으로 앞선다. NL2Repo만 57.7 대 69.7로 12포인트 격차가 남았다.

같은 날 앤트로픽은 정반대 방향의 문서를 냈다. 「Improving our alignment and security practices」에서 회사는 4월에 RL 환경을 약 한 달간 동결했고 그 기간에 **프로덕션 RL 환경의 10% 이상**에서 문제를 발견했다고 밝혔다. 2월에는 Mythos Preview에서 리워드 해킹이 탐지돼 사흘치 학습을 롤백했고, 일부 학습 런이 모델의 사고 사슬로 학습되는 사고도 있었다. 대응으로 **제품 엔지니어 약 150명**을 보안·신뢰성·프라이버시로 재배치했다. 한쪽은 가중치를, 한쪽은 사고 기록을 공개했지만 둘 다 "결과물 뒤편"을 여는 행위라는 점에서 같은 방향이다. [Hugging Face](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-Vision-Exp) / [Anthropic](https://www.anthropic.com/news/improving-alignment-security-efforts)

## 주요 이슈 2: 규제는 사용자 수로, 산업정책은 GPU 장수로 계산된다

유럽연합 집행위원회는 8월 31일 챗GPT를 디지털서비스법상 **초대형 온라인 검색엔진(VLOSE)**으로 지정했다. AI 서비스 단독으로는 처음이다. 근거는 사업자가 신고한 EU 월간 실사용자 1억 5,910만 명(레딧 5,720만, 로블록스 4,660만)이며, 기준선은 4,500만 명이다. 12월 말까지 시스템 리스크 평가·연례 독립 감사·광고 저장소·연구자 데이터 접근·랭킹 파라미터 공개를 이행해야 하고, 위반 시 전 세계 연매출의 최대 6%가 제재로 걸린다. 여기서 챗GPT에 새로 붙는 것은 성능 요구가 아니라 **감사 가능한 상태를 상시 유지하는 운영 비용**이다.

하루 뒤 한국 정부는 국무회의에서 2027년도 예산안을 의결했다. 과기정통부 예산은 29조 6,476억 원(24.5% 증가)으로 역대 최대이고, AI 전환에만 9조 4,000억 원, 전년 대비 **84.3% 증가**다. AI 모델·기술 확보 5조 5,937억 원(113.9% 증가) 안에는 최신 GPU '베라루빈' **1만 장** 확보 등에 쓰일 3조 9,000억 원이 들어 있다. 3대 메가프로젝트는 2,981억 원에서 7,956억 원으로 166.9% 늘었다. 같은 기술을 두고 브뤼셀은 사용자 수로 의무를 계산하고, 서울은 GPU 장수로 야심을 계산한다. [PPC Land](https://ppc.land/chatgpt-faces-eu-risk-rules-after-declaring-159-1-million-users/) / [한국정보통신신문](https://www.koit.co.kr/news/articleView.html?idxno=208759)

## 주요 이슈 3: 공공 도입이 세 층위로 갈라졌다 — 창구, 방패, 계기판

미 국방부는 8월 31일 GenAI.mil에 ChatGPT Mil과 Grok for Government를 추가했다. 대상은 300만 명, 이미 온보딩된 고유 사용자는 170만 명으로 전체의 57%다. 부산시는 9월 1일부터 AI 사이버 보안관제를 가동해 초당 100억 건 이상을 검색하는 XDR로 하루 수백 건의 위협을 자동 차단하기 시작했다. 한국은행은 같은 날 AI 언어모형으로 기사 맥락을 읽는 새 뉴스심리지수를 이달부터 공표한다고 밝혔는데, 소비자심리지수보다 1개월·기업심리지수보다 2개월 선행하며 GDP 예측오차를 최대 16.7% 줄인다.

세 사례는 각각 창구(업무 접근), 방패(방어 자동화), 계기판(공식 통계 생산)에 해당한다. 특히 한은 사례는 AI를 참고자료가 아니라 **공표 지표의 생산 라인**에 넣었다는 점에서 성격이 다르다. 그리고 국방부 사례에는 빠진 이름이 있다. 앤트로픽은 대량 감시와 자율 살상무기 사용을 금지하는 계약 조항을 고수하다 협상이 결렬됐고, 공급망 리스크로 지정된 뒤 이를 법정에서 다투고 있다. 공공 도입 경쟁에서 안전 조항이 실제 수주 탈락 사유가 된 첫 사례다. [TechCrunch](https://techcrunch.com/2026/08/31/the-pentagon-now-has-its-own-version-of-chatgpt-and-grok/) / [뉴스1](https://www.news1.kr/economy/trend/6276054)

## 주요 이슈 4: 지도 신호의 값이 재평가되고 있다

8월 31일 arXiv에 올라온 두 논문은 학습 비용의 전제를 흔든다. 「Does On-Policy Distillation Really Distill?」은 온-폴리시 증류의 성능 향상이 지식 전이가 아니라 **낮은 확률 토큰의 억제** 때문이라는 점을 보였다. 교사가 준 음의 어드밴티지를 고정값 하나로 대체해도 성능이 같았고, 교사를 아예 제거한 OPSA는 Qwen3-1.7B의 AIME24 Avg@32를 35.41점(상대 263%) 끌어올렸다. 교사 모델 추론 비용이 통째로 사라진다는 뜻이다.

「PaperGym」은 반대편을 짚는다. 정답이 없는 연구 계획 생성을 강화학습으로 돌리기 위해 출판된 논문에서 루브릭을 추출하고, 질문(배경·목표)과 채점 기준(방법·실험)을 분리해 기준 누출률을 **3.7%**까지 낮췄다. 2만 건으로 학습한 Qwen3-8B는 ResearchQA에서 73.48점으로 Kimi K2.6을 넘어섰다. 한쪽은 비싼 감독을 지우고, 다른 쪽은 공짜 감독을 캐낸다. [arXiv:2608.31046](https://arxiv.org/abs/2608.31046) / [arXiv:2608.31119](https://arxiv.org/abs/2608.31119)

## 오늘의 시사점

오늘 소식들을 겹쳐 보면 AI 산업의 심사 지점이 한 단계 아래로 내려갔다는 것이 분명해진다. 지난 몇 달 동안 경쟁은 "어느 모델이 벤치마크에서 몇 점인가"였지만, 오늘 나온 문서들은 전부 그 아래층을 다룬다. 앤트로픽이 공개한 것은 점수가 아니라 RL 환경의 불량률 10%였고, EU가 요구한 것은 답변 품질이 아니라 연례 감사와 광고 저장소였으며, 한국 예산안이 계산한 것은 서비스 매출이 아니라 GPU 1만 장이었다. **평가의 단위가 산출물에서 공정으로 이동한 것이다.**

이 이동은 비용 구조를 바꾼다. EU 지정을 받은 서비스는 감사받을 수 있는 상태를 유지하는 상시 비용을 떠안고, 프런티어 랩은 학습 환경을 검증하는 데 엔지니어 150명 규모의 인력을 돌려야 하며, 정부는 모델 한 개가 아니라 학습 인프라 전체를 기금으로 조달한다(과기정통부 기금 예산은 1조 8,387억 원에서 10조 113억 원으로 444.5% 늘었다). 반대 방향에서 압력을 낮추는 것이 오늘의 논문들이다. 교사 모델을 지우고 문헌에서 채점표를 캐내는 방식은, 공정 비용이 급등하는 국면에서 감독 신호 자체를 싸게 만드는 시도로 읽힌다.

마지막으로 앤트로픽 사례는 이 흐름의 비용을 가장 선명하게 보여준다. 같은 회사가 하루 만에 두 가지 결과를 받았다. 학습 공정의 문제를 스스로 공개하며 신뢰를 사려 했고, 동시에 안전 계약 조항을 고수하다 300만 명 규모의 공공 조달에서 배제됐다. 공정을 공개하고 지키는 일이 평판 자산이자 매출 손실로 동시에 계상되는 시기에 들어섰다는 뜻이다.

---

## 📎 참고 자료

1. [DeepSeek-V4-Flash-Vision-Exp 모델 카드 — Hugging Face](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-Vision-Exp)
2. [Improving our alignment and security practices — Anthropic](https://www.anthropic.com/news/improving-alignment-security-efforts)
3. [ChatGPT faces EU risk rules after declaring 159.1 million users — PPC Land](https://ppc.land/chatgpt-faces-eu-risk-rules-after-declaring-159-1-million-users/)
4. [AI 전환·첨단기술 확보에 역대 최대 규모 예산 투입 — 한국정보통신신문](https://www.koit.co.kr/news/articleView.html?idxno=208759)
5. [과기정통부 AI 예산 9.4조…최상위급 AI 확보 '사활' — 뉴스1](https://www.news1.kr/it-science/internet-platform/6275242)
6. [The Pentagon now has its own version of ChatGPT and Grok — TechCrunch](https://techcrunch.com/2026/08/31/the-pentagon-now-has-its-own-version-of-chatgpt-and-grok/)
7. ['경제 비관' 뉴스에 소비심리 더 민감…한은, AI로 맥락 읽었다 — 뉴스1](https://www.news1.kr/economy/trend/6276054)
8. [AI로 사이버공격 막는다…부산시, 'AI 기반 지능형 사이버 보안관제' — LG헬로비전 뉴스](http://news.lghellovision.net/news/articleView.html?idxno=553269)
9. [Does On-Policy Distillation Really Distill? — arXiv:2608.31046](https://arxiv.org/abs/2608.31046)
10. [PaperGym: Rubric-Centered Evolution for Research-Plan Generation — arXiv:2608.31119](https://arxiv.org/abs/2608.31119)
