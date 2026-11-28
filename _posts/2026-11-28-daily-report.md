---
layout: single
title: "📊 AI 일간보고서 — 2026년 11월 28일"
date: 2026-11-28 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "AI인프라"
  - "동해AI데이터센터"
  - "수출통제"
  - "AI검증"
  - "AI수학"
  - "AI보안"
  - "오픈웨이트"
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

> **2026년 11월 28일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 11월 28일 AI 일간보고서

## 오늘의 핵심 요약

미국 추수감사절 연휴로 빅테크의 신제품 발표는 드물었지만, 그 빈자리에서 AI 산업의 구조적 조건이 선명하게 드러났습니다. 첫째, 연산 인프라가 곧 경쟁력이라는 점입니다. 한국은 GW급 AI 데이터센터의 첫 삽을 떴고, 중국 연구소들은 해외 연산 접근이 막히며 플래그십 출시를 미루고 있습니다. 둘째, AI가 수학·물리·신약 분야에서 결과를 쏟아내는 속도가 사람의 검증 속도를 앞지르기 시작했다는 점입니다. 셋째, AI 에이전트가 공격 도구이자 감사 도구로 동시에 쓰이면서 '경계 설정'이 제품·보안·플랫폼 정책의 공통 과제가 됐다는 점입니다.

## 주요 이슈 1: 연산의 지정학 — 동해에서는 착공, 베이징에서는 지연

11월 28일 강원 동해에서 GS의 AI 데이터센터가 착공했습니다. 100MW로 시작해 2028년부터 순차 준공하고 2029년까지 1단계 1.2GW, 최종 최대 2.4GW 규모로, 지난 6월 29일 정부가 발표한 GW급 메가프로젝트 가운데 첫 착공입니다([아주경제](https://www.ajunews.com/view/20261128114112735)). 대통령이 일주일 사이 울산(21일)과 동해(28일) 데이터센터 현장을 연달아 찾은 것은, 정부가 2030년 아시아·태평양 최대 AI 인프라 허브라는 목표를 전력·부지가 확보된 지역 거점 중심으로 밀어붙이고 있음을 보여줍니다([이투데이](https://www.etoday.co.kr/news/view/2654174)).

같은 시기 중국에서는 반대 상황이 벌어지고 있습니다. 11월 19일 발효된 미 상무부 규칙은 해외 데이터센터에서 H100 약 750개 상당 이상의 연산을 쓰는 중국 기업에 라이선스를 요구합니다. 로이터에 따르면 즈푸AI는 약 3조 파라미터 규모의 'GLM-5.5'를 이달 출시하지 못했고 내년 1분기 이후로 밀릴 수 있으며, 문샷AI는 주요 모델 출시 간격이 6개월에서 12개월 이상으로 늘어날 수 있다고 내부적으로 전망했습니다([타이베이타임스(로이터)](https://www.taipeitimes.com/News/biz/archives/2026/11/27/2003868457)). 전날 다룬 엔비디아의 동남아 4개국 출하 중단과 합치면, 미국의 규제가 칩 판매 단계를 넘어 '연산 임대' 단계까지 차단하면서 중국 모델의 출시 주기 자체를 늘리고 있다는 그림이 완성됩니다.

흥미로운 대비는 러시아 스베르의 'GigaChat 4'입니다. 총 7,080억 파라미터(활성 410억)의 MoE 모델을 MIT 라이선스로 공개했지만, 회사 자체 표에서도 장기 코딩 과제 DeepSWE 점수는 35.40%로 비교 대상 DeepSeek 모델(74.34%)의 절반에 못 미쳤습니다([Tech Times](https://www.techtimes.com/articles/331654/20261127/sber-releases-gigachat-4-1m-token-window-lists-35-coding-test-where-deepseek-gets-74.htm)). 파라미터 규모는 따라잡을 수 있어도, 장시간 에이전트 작업 성능은 연산과 데이터가 누적된 결과라는 점을 시사합니다.

## 주요 이슈 2: 생성은 폭발, 검증은 병목 — AI 과학 결과의 신뢰 문제

이번 주 AI가 만든 과학 결과가 연달아 발표됐습니다. 구글리서치는 제미나이 4 기반 에이전트 '코젠틱'이 사람 개입 없이 쓴 논문 6편(274쪽)을 공개하며 소인수분해의 이론적 복잡도 지수를 미증명 가정 없이 1/2에서 1/3로 낮췄다고 주장했습니다. 증명이 맞다면 34년 만의 기록 갱신이지만, Lean 4 형식 검증 코드는 아직 공개되지 않았습니다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217867)).

물리학에서는 검증의 어려움이 더 극명합니다. 스탠퍼드 물리학자가 'GPT-6 아스트라'와 약 4억 토큰을 주고받으며 쓴 양자중력 논문에 대해, UCL 오펜하임 교수는 클로드 에이전트로 난제 21개를 정리한 뒤 실제로 해결된 것은 1개뿐이라고 반박했습니다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217864)). AI 대 AI의 검증 구도가 등장한 셈이지만, 물리학에는 수학의 Lean 같은 형식 검증 도구가 없다는 한계가 남습니다.

반면 신약 분야는 '실험'이라는 외부 검증 루프가 있다는 점에서 다릅니다. 텐센트의 네이처 논문은 AI가 설계한 이중표적 펩타이드 후보 15개 중 1라운드 적중이 3개였지만, 실험 결과를 모델에 되먹인 3라운드에서는 15개 모두 적중했다고 보고했습니다. 최상위 항암 후보는 동물실험에서 종양 부피를 94.2% 줄였습니다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217890)). 생성과 검증이 같은 루프 안에서 돌 때 AI 성능이 빠르게 수렴한다는 사례입니다.

## 주요 이슈 3: 에이전트의 양면 — 침투 도구이자 감사 도구

SAP가 AI 에이전트 침투로 추정되는 보안 사고를 '프로젝트 그래니트'라는 이름으로 대응 중이라는 슈피겔 보도가 나왔습니다. 공격자는 직원 인증 토큰을 탈취한 뒤 깃허브의 SAP 관련 코드를 조작·복사한 것으로 알려졌고, 마이크로소프트는 이달 초 AI 침투테스트 도구 'Artex'를 악용한 깃허브 공격 증가를 경고했습니다([SBS](https://news.sbs.co.kr/english/article.do?news_id=N1008867320)). 아직 AI 에이전트 소행은 추정 단계지만, 토큰 하나로 대규모 코드 저장소에 접근할 수 있는 개발 인프라가 AI 자동화 공격의 주요 표적이 되고 있습니다.

방어 측에서도 에이전트가 쓰이기 시작했습니다. 앤스로픽의 뉴런 기반 해석가능성 연구에서, 숨은 행동을 심은 미세조정 모델 58개를 클로드가 감사했을 때 답변만 볼 경우 탐지율은 40%였지만 내부 뉴런 분석을 더하면 75%로 올랐습니다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217863)). 모델 출력만으로는 보이지 않는 위험을 내부 구조로 찾아내는 방식이 수치로 효과를 보이기 시작한 것입니다.

## 주요 이슈 4: 서비스 경계 — 로컬 샌드박스와 플랫폼 퇴출

AI 서비스 쪽에서는 '어디까지 허용할 것인가'가 제품 설계와 플랫폼 정책 양쪽에서 동시에 다뤄졌습니다. 래블업의 '에이아이고 2.0'은 언어·비전·이미지·음성 4종 로컬 모델과 에이전트를 PC 안에서 실행하되, 결제·전송·삭제는 매번 승인받고 코드 실행은 네트워크가 차단된 OS 샌드박스에 가뒀습니다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217872)). 반대로 애플은 월 이용자 약 1,100만 명, 2024년 미니맥스 매출의 63.7%를 차지했던 AI 동반자 앱 '토키'를 아동 안전 문제로 전 세계 앱스토어에서 삭제했습니다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217870)). 규제 당국보다 앱 플랫폼이 먼저 기준을 집행하는 구도가 굳어지고 있습니다.

## 오늘의 시사점

오늘 소식들을 관통하는 키워드는 '제약'입니다. 연산 제약은 중국 연구소의 출시 주기를 늘리고, 반대로 이를 확보한 국가와 기업에는 경쟁 우위가 됩니다. 한국이 GW급 데이터센터 착공을 서두르는 이유도 여기에 있습니다. 검증 제약은 AI 과학의 다음 병목입니다. 수학은 Lean 같은 형식 검증으로, 신약은 실험 피드백 루프로 이 문제를 풀고 있지만, 물리학처럼 검증 도구가 없는 분야에서는 AI가 만든 '그럴듯한 결과'가 혼란을 키울 수 있습니다. 마지막으로 행동 제약, 즉 에이전트가 할 수 있는 일의 경계가 보안 사고·제품 설계·플랫폼 정책 모두에서 핵심 설계 변수가 됐습니다. 스위스 nextesy가 회계·급여 자동화 에이전트로 1,040만 달러를 유치하고 고객 2,000곳 이상을 확보한 것처럼([TechStartups](https://techstartups.com/2026/11/27/swiss-ai-startup-nextesy-raises-10-4m-to-automate-accounting-payroll-and-business-administration-with-ai-agents/)), 범위가 명확히 제한된 에이전트가 오히려 먼저 상업적 성과를 내는 흐름도 같은 맥락으로 읽힙니다.

[아주경제](https://www.ajunews.com/view/20261128114112735) / [타이베이타임스(로이터)](https://www.taipeitimes.com/News/biz/archives/2026/11/27/2003868457) / [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=217867)

---

## 📎 참고 자료

1. [아주경제 — 李대통령, 동해 GS AI 데이터센터 착공식 참석…강원 메가프로젝트 첫 삽](https://www.ajunews.com/view/20261128114112735)
2. [이투데이 — 李대통령, 동해 GS AI데이터센터 착공식 참석](https://www.etoday.co.kr/news/view/2654174)
3. [Taipei Times (Reuters) — US chip curbs, distillation crackdown threaten Chinese AI model development](https://www.taipeitimes.com/News/biz/archives/2026/11/27/2003868457)
4. [Tech Times — Sber Releases GigaChat 4 With 1M-Token Window](https://www.techtimes.com/articles/331654/20261127/sber-releases-gigachat-4-1m-token-window-lists-35-coding-test-where-deepseek-gets-74.htm)
5. [AI타임스 — 구글도 AI 수학 연구 경쟁 가세…소인수분해 34년 기록 경신 주장](https://www.aitimes.com/news/articleView.html?idxno=217867)
6. [AI타임스 — 'GPT-6 아스트라'로 양자 중력 이론 제안…'클로드'로 반박도 등장](https://www.aitimes.com/news/articleView.html?idxno=217864)
7. [AI타임스 — 텐센트, AI로 비만·암 치료 후보물질 설계…네이처에 연구 성과](https://www.aitimes.com/news/articleView.html?idxno=217890)
8. [SBS — Europe's Top Software Firm SAP Hit by Security Incident Suspected to Involve AI](https://news.sbs.co.kr/english/article.do?news_id=N1008867320)
9. [AI타임스 — 앤트로픽, AI 내부 뉴런 직접 분석…숨겨진 위험 행동 탐지 기술 연구](https://www.aitimes.com/news/articleView.html?idxno=217863)
10. [AI타임스 — 래블업, 로컬AI PC 앱 '에이아이고 2.0' 출시](https://www.aitimes.com/news/articleView.html?idxno=217872)
11. [AI타임스 — 애플, 미니맥스 AI 동반자 '토키' 앱스토어에서 삭제](https://www.aitimes.com/news/articleView.html?idxno=217870)
12. [TechStartups — Swiss AI startup nextesy raises $10.4M](https://techstartups.com/2026/11/27/swiss-ai-startup-nextesy-raises-10-4m-to-automate-accounting-payroll-and-business-administration-with-ai-agents/)
