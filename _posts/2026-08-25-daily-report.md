---
layout: single
title: "📊 AI 일간보고서 — 2026년 08월 25일"
date: 2026-08-25 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "오픈웨이트전쟁"
  - "에이전트권한"
  - "피지컬AI자본"
  - "라우팅경제학"
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

> **2026년 08월 25일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 08월 25일 AI 일간보고서

## 오늘의 핵심 요약

오늘은 '오픈웨이트'라는 단어가 세 가지 전혀 다른 맥락에서 동시에 등장한 날이다. 엔비디아는 오픈웨이트 모델을 만들 인력과 파이프라인을 확보하는 데 60억 달러를 썼고, 오르니스는 397B 오픈웨이트를 실제로 내놨으며, 어느 커뮤니티 개발자는 오픈웨이트 27B의 안전 정렬을 벗겨내 맥북에서 돌렸다. 하나의 단어가 전략, 성과, 리스크라는 세 얼굴을 하루에 다 보여준 셈이다.

두 번째 축은 자본의 이동 방향이다. 알리바바는 순이익 75% 감소를 감수하며 102억 달러를 조달했고, 게임 영상으로 로봇 정책을 학습하는 스타트업은 몇 주 만에 기업가치가 23억에서 60억 달러로 뛰었다. 텍스트 모델 경쟁이 가격으로 수렴하는 동안, 프리미엄은 영상·로보틱스 같은 '아직 안 풀린 모달리티'로 옮겨가고 있다.

세 번째 축은 권한이다. 개인 비서 에이전트의 약관과 메타의 하드웨어 킬 스위치 특허가 같은 날 나왔다. 에이전트에게 무엇을 맡길지가 아니라, 맡긴 뒤 어떻게 되돌릴지가 논쟁의 중심으로 이동했다.

## 주요 이슈 1: 엔비디아의 60억 달러 — 오픈웨이트는 이제 조달의 문제다

어제 엔비디아가 차세대 네모트론에 1조 파라미터를 조준한다고 밝혔을 때 비어 있던 칸은 실행 주체였다. 오늘 그 칸이 채워졌다. 엔비디아는 풀사이드의 모델 소프트웨어 라이선스에 60억 달러를 지불하고, 프리머니 120억 달러 밸류에 10억 달러를 추가 투자하며, 엔지니어 100명 이상을 네모트론 팀으로 흡수한다([Quartz](https://qz.com/nvidia-poolside-6-billion-license-ai-model-082426)).

이 거래에서 읽어야 할 것은 금액이 아니라 방향성이다. 첫째, 인수가 아니라 '라이선스 + 인력 이동' 구조다. 둘째, 풀사이드가 이 길을 택한 이유는 20억 달러 조달을 6주 안에 마치지 못했기 때문이다. 프런티어 경쟁의 진입 조건이 이제 모델 품질이 아니라 컴퓨팅 조달 능력이라는 사실이, 실패 사례를 통해 확인됐다. 셋째, 명시적 표적이 딥시크·키미 K3·큐원 등 중국발 오픈웨이트다([Tech Startups](https://techstartups.com/2026/08/24/nvidia-to-invest-6-billion-to-build-u-s-open-weight-ai-model-alternative-to-chinas-deepseek-kimi-k3-and-qwen/)). GPU를 파는 회사가 GPU 수요를 만드는 모델까지 직접 만드는 구조는 어제 언급된 수직화의 연장이지만, 오늘 붙은 가격표는 그 의지가 선언 수준이 아님을 보여준다.

## 주요 이슈 2: 오르니스-1.5와 무삭제 큐원 — 오픈웨이트의 성과와 청구서

같은 날 오픈웨이트의 두 얼굴이 나란히 도착했다. 오르니스-1.5는 모델이 스스로 학습 과제를 만들고 전략을 설계한 뒤 강화학습으로 되먹이는 '셀프 스캐폴딩' 구조로, 397B MoE가 터미널-벤치 2.1에서 86.1점을 기록해 클로드 오퍼스 4.8(85.0점)을 앞섰다. 다만 딥SWE는 56.0점으로 오퍼스 4.8(59.0점)에 뒤진다. 종목별로 순위가 갈린다는 것 자체가 이제 '프런티어'가 단일 서열이 아니라는 뜻이다. 실무적으로 더 중요한 수치는 하단이다. 9B 덴스 모델이 SWE-벤치 베리파이드 70.6점을 낸다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214261)).

그리고 청구서. 커뮤니티 개발자가 큐원 3.8 27B의 안전 정렬을 제거한 버전을 공개했고, 유해 프롬프트 100개에 대한 거부 반응은 원본의 98회에서 12회로 떨어졌다. 이 모델은 통합 메모리 16GB 이상의 애플 실리콘 맥에서 GPU도 클라우드도 없이 돌아간다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214299)). 가중치를 공개하는 순간 정렬은 서버 측 정책이 아니라 로컬에서 벗겨낼 수 있는 층이 된다는 것을 98 → 12라는 숫자가 정량화했다. 엔비디아가 60억 달러를 들여 미국산 오픈웨이트를 만들겠다고 한 바로 그날 이 수치가 나온 것은 우연이지만, 오픈웨이트 전략을 밀어붙일 모든 조직이 함께 받아들 문제이기도 하다.

## 주요 이슈 3: 자본은 텍스트를 떠나 영상과 로봇으로 간다

알리바바는 신주 7억1000만주를 주당 112.7홍콩달러에 팔아 102억 달러를 조달했다. 4~6월 순이익이 전년 대비 75% 이상 줄고 분기 중 66억 달러의 잉여현금이 유출된 상태에서, 분기 자본지출 100억 달러와 3년간 75조 원 투자 계획을 유지하기 위한 조달이다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214284)). 같은 날 알리바바 클라우드는 30초 길이 영상을 만드는 '완 3.0'을 공개했다.

한편 제너럴 인튜이션은 프리머니 60억 달러를 인정받았다. 몇 주 전 23억 달러에 3억2000만 달러를 조달했으니 약 2.6배다. 이 회사의 자산은 모회사 메달에서 나온 수억 시간의 게임플레이 영상과 **액션 라벨** — 플레이어가 언제 어떤 버튼을 눌렀는지의 기록 — 이며, 이를 로보틱스용 라지 액션 모델 학습에 쓴다([TechCrunch](https://techcrunch.com/2026/08/24/valor-point72-back-general-intuition-at-6b-valuation-as-ai-startup-pushes-into-robotics/)). 텍스트 웹 데이터가 고갈 논쟁에 갇힌 사이, 시간축과 행동 라벨이 붙은 데이터가 새로운 희소 자산으로 값이 매겨지고 있다.

## 주요 이슈 4: 권한과 라우팅 — 배포 현실이 연구 주제를 바꾼다

인스팅트 AI 비서의 약관은 사용자 자료에 대해 영구적·취소불가 라이선스를 명시하고 화면·커서·키보드 입력까지 수집한다. 연결을 끊은 뒤에도 서버의 메일을 계속 요약했고, 확인 없이 메일을 발송해 투자자의 신뢰를 잃은 사례도 보고됐다([TechCrunch](https://techcrunch.com/2026/08/24/instincts-powerful-ai-assistant-is-raising-privacy-and-security-concerns/)). 반대편에서 메타는 소프트웨어 명령으로는 되돌릴 수 없는 하드웨어 회로 킬 스위치 특허를 공개했다([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214304)). 약관으로 권한을 최대화하는 설계와 회로로 권한 상한을 못 박는 설계가 정면으로 마주 선 하루였다.

연구 쪽도 같은 방향을 본다. 엔비디아의 'Cross-Model KV Cache Transfer'는 모델을 바꿀 때 캐시를 버리고 다시 프리필하는 낭비를, 헤드별 릿지 회귀라는 선형 연산과 500개 샘플만으로 해결해 정확도 73~98%를 유지하며 2.7~25배 속도를 냈다([arXiv](https://arxiv.org/pdf/2608.03893)). 노타는 MoE 양자화의 진짜 병목이 가중치 오차가 아니라 전문가 선택의 변형이라는 관점으로 EMNLP 2026에 논문 2편을 올렸다(메인 채택률 15.4%)([AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214318)). 두 연구 모두 단일 모델의 점수가 아니라 여러 모델을 갈아 끼우고 압축해 운영하는 시스템을 대상으로 한다.

## 오늘의 시사점

오늘 다섯 갈래 소식을 하나의 문장으로 묶으면 이렇다. **모델은 상품이 되었고, 경쟁은 그 주변 인프라로 옮겨갔다.**

근거는 서로 맞물린다. 엔비디아가 60억 달러를 쓴 대상은 모델 그 자체가 아니라 모델을 반복 생산하는 파이프라인과 그것을 아는 사람 100명이었다. 오르니스가 자랑한 것도 특정 점수보다 스스로 커리큘럼을 만드는 학습 루프다. 노타와 엔비디아 연구진이 붙든 문제는 모델을 더 똑똑하게 만드는 것이 아니라 여러 모델을 싸게 운영하는 것이다. 자본이 영상·로보틱스로 이동하는 이유도 텍스트 모델이 이미 대체 가능한 부품이 되었기 때문이다.

동시에 상품화에는 대가가 따른다. 27B 모델의 거부율이 98회에서 12회로 떨어지는 데 필요한 것은 프런티어 랩이 아니라 개발자 한 명과 16GB 맥이었다. 오픈웨이트를 국가·기업 전략으로 삼는 쪽은 배포 후 통제권이 사실상 0이라는 조건을 전제로 안전 설계를 다시 짜야 한다. 인스팅트와 메타 특허의 대비가 시사하는 바도 같다. 앞으로 신뢰의 근거는 "무엇을 안 하겠다는 약속"이 아니라 "구조적으로 할 수 없게 만든 설계"가 될 가능성이 높다. 국내 기업에는 좁지만 선명한 자리가 보인다. 위버스브레인의 6억8000만건 음성 데이터, 노타의 MoE 압축 논문처럼, 남들이 만든 모델을 실제 제품 제약 안에서 굴러가게 만드는 층위다.

---

## 📎 참고 자료

1. [Nvidia pays $6 billion to license Poolside AI model software — Quartz](https://qz.com/nvidia-poolside-6-billion-license-ai-model-082426)
2. [Nvidia to invest $6 billion to build U.S. open-weight AI model alternative — Tech Startups](https://techstartups.com/2026/08/24/nvidia-to-invest-6-billion-to-build-u-s-open-weight-ai-model-alternative-to-chinas-deepseek-kimi-k3-and-qwen/)
3. [스스로 문제 만들고 해결 전략까지 구축....오픈소스 '오르니스-1.5' 출시 — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214261)
4. [맥북에서 돌리는 '무삭제 큐원 3.8' 등장 — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214299)
5. [AI에 올인한 알리바바, 투자 위해 14조 대규모 증자 단행 — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214284)
6. [Valor, Point72 back General Intuition at $6B valuation — TechCrunch](https://techcrunch.com/2026/08/24/valor-point72-back-general-intuition-at-6b-valuation-as-ai-startup-pushes-into-robotics/)
7. [Instinct's powerful AI assistant is raising privacy and security concerns — TechCrunch](https://techcrunch.com/2026/08/24/instincts-powerful-ai-assistant-is-raising-privacy-and-security-concerns/)
8. [메타, 스마트 안경에 해킹 불가 '물리적 킬 스위치' 도입 — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214304)
9. [Cross-Model KV Cache Transfer — arXiv](https://arxiv.org/pdf/2608.03893)
10. [노타, EMNLP 논문 2편 채택..."MoE 양자화 난제 풀었다" — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214318)
11. [위버스브레인, 음성 AI로 SKT와 AI 에이전트 개발 협력 — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=214321)
