---
layout: single
title: "📊 AI 일간보고서 — 2026년 08월 07일"
date: 2026-08-07 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "추론비용"
  - "가격정책전환"
  - "온디바이스"
  - "에이전틱커머스"
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

> **2026년 08월 07일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 08월 07일 AI 일간보고서

## 오늘의 핵심 요약

오늘의 소식들을 하나로 묶는 단어는 **추론 비용**이다. 오픈AI는 주간 사용자 10억명 규모의 서비스에서 무료 사용자 텍스트 대화 한도를 없앴고, 딥시크는 정반대로 API 전체 가격 인상을 예고했다. 마이크로소프트는 사내 개발 도구의 기본 모델을 가성비 기준으로 갈아치웠고, 미렌딜은 시드 자금의 절반을 컴퓨트 계약 한 건에 투입했다. 같은 제약 조건 앞에서 확산·회수·최적화·선점이라는 네 가지 상반된 전략이 하루 사이에 동시에 나온 셈이다. 여기에 구글은 지도 안에 결제를 붙이며 '토큰을 태워 매출을 만드는' 경로를 제시했다.

## 주요 이슈 1: 무료 무제한과 가격 인상, 정반대로 갈린 두 회사

오픈AI는 8월 6일 챗GPT 무료·고 등급의 **텍스트 대화 한도를 폐지**하고 기본 모델을 GPT-5.5에서 **GPT-5.6 루나**로 교체했다. 자체 테스트 기준 사실 오류는 GPT-5.5-인스턴트 대비 루나 **62%**, 솔 **68%** 감소했고, 복잡한 질문용 'Think 버튼'과 플러스·프로용 추론 강도 슬라이더가 함께 붙는다. 주간 사용자 **10억명**을 넘긴 서비스에서 한도를 없앤다는 것은, 늘어나는 추론 원가를 감수하고 사용자 기반과 사용 습관을 우선 확보하겠다는 선언이다. [TechCrunch](https://techcrunch.com/2026/08/06/openai-brings-unlimited-chatgpt-text-chats-to-free-users/)

같은 날 딥시크는 반대로 움직였다. "가까운 시일 내에 API 서비스의 전체 가격을 인상할 계획이며 상당한 인상이 예상된다"고 공지한 것이다. 현재 딥시크-V4 플래시는 입력 100만 토큰당 **0.14달러**, 출력 **0.28달러**로 시장 최저가 구간을 형성해 왔다. 지난 몇 분기의 지배적 서사였던 '성능 수렴·가격 하락'을 만든 당사자가 먼저 방향을 튼 것은, 저가 공세가 무한정 지속될 수 없다는 신호에 가깝다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=213632)

두 결정은 모순이 아니라 자본 구조의 차이다. 손실을 감당할 자본이 있는 쪽은 무료화로 밀고, 그렇지 않은 쪽은 단가를 정상화한다.

## 주요 이슈 2: 최적화로 대응하는 쪽 — MS의 기본 모델 교체와 온디바이스 경량화

마이크로소프트는 8월 6일 깃허브 코파일럿·비주얼 스튜디오·VS 코드의 **기본 모델을 GPT-5.6 솔**로 지정했다. 이유는 성능이 아니라 효율이다. 주요 빅테크의 2026년 AI 인프라 지출이 **7000억 달러**를 넘어설 것으로 전망되는 상황에서, 전략이 '토큰 최대화'에서 가성비 최적화로 옮겨간 결과다. MS가 앤트로픽에 최대 **50억 달러**를 투자하고 앤트로픽이 애저에 **300억 달러** 지출을 약정한 관계임을 감안하면, 기본 모델 선택은 순수한 기술 판단이 아니라 파트너십 역학이기도 하다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=213604)

비용 문제를 아예 기기 쪽으로 옮기는 접근도 나왔다. 옵트에이아이는 8월 6일 온디바이스 특화 경량 모델 **옵트기어**를 **1B/270M/1M** 세 가지 크기의 오픈웨이트로 공개했다. MMLU **43.2점**, 한국어 상식 평가 HAERAE **44.2점**으로 절대 성능은 프런티어급이 아니지만, 스냅드래곤 8 Elite Gen5 NPU에서 입력 처리 **초당 7042토큰**(큐원 3-1.7B 대비 **2.9배**), 아이폰 17 프로 생성 속도가 엑사원 4.0-1.2B의 **4.9배**다. MCU에서까지 돌아간다는 점이 핵심으로, 클라우드 호출이 아예 발생하지 않는 워크로드를 겨냥한 설계다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=213630)

## 주요 이슈 3: 컴퓨트 선점 대 매출 증명 — 자금이 갈라진 지점

미렌딜은 8월 6일 구글 클라우드와 **1억 달러 이상** 다년 계약을 맺고 TPU와 엔비디아 GPU, 관리형 학습 클러스터를 확보했다. 6월 말 **10억 달러 기업가치**에 **2억 달러** 시드를 조달한 회사가 그 절반을 컴퓨트 한 건에 묶은 것이다. 프런티어 랩에게 펀드레이징과 컴퓨트 확보가 사실상 같은 행위가 됐다는 뜻이다. [TechCrunch](https://techcrunch.com/2026/08/06/exclusive-mirendil-inks-100m-google-cloud-deal-to-scale-self-improving-ai/)

정반대 근거로 자금을 받은 사례도 같은 날 나왔다. 2002년 설립된 상담 자동화 기업 오밀리아는 **6700만 달러 시리즈 B**를 유치했는데, 근거는 서사가 아니라 ARR **6000만 달러**(2020년 대비 **10배**)와 타코벨 **1000개 이상 매장** 같은 실제 배포 실적이었다. 누적 조달액은 **8700만 달러**로, 누적 조달보다 연 매출이 더 큰 구조다. CEO가 "링크드인에서 일레븐랩스나 시에라만큼 섹시하지 않아도 개의치 않는다"고 말한 대목이 지금 시장의 두 트랙을 정확히 요약한다. [TechCrunch](https://techcrunch.com/2026/08/06/omilia-raises-67m-to-scale-its-customer-support-platform/)

## 주요 이슈 4: 토큰을 매출로 바꾸는 경로 — 지도 안으로 들어간 결제

구글은 8월 6일 '애스크 맵스'에 음식 주문·호텔 예약·공연 티켓 구매를 붙였다. 주문은 **스퀘어·토스트·우버이츠**와 연동되고, 지메일·캘린더를 참조하는 퍼스널 인텔리전스는 **기본 비활성화**로 제공된다. 거래 기능은 **미국**부터 순차 적용된다. 검색창이 아니라 지도에서 결제가 일어나면, 추론 비용이 광고가 아닌 거래 수수료로 회수된다. [TechCrunch](https://techcrunch.com/2026/08/06/google-maps-adds-agentic-features-including-food-ordering-and-hotel-bookings/)

반대편에서는 생성물에 대한 책임 비용도 드러났다. 수노는 같은 날 뮤직매치의 **센티넬** 시스템을 이용한 워터마킹·핑거프린팅 도입을 발표했다. 유니버설·소니 소송과 독일 법원 판결, **5500만명** 규모 데이터 유출로 인한 집단소송이 겹친 상태이며, 회사는 6월 **4억 달러** 시리즈 D를 유치한 바 있다. 확산 이후에 청구되는 비용이 무엇인지 보여주는 사례다. [TechCrunch](https://techcrunch.com/2026/08/06/amid-legal-battles-suno-says-it-will-start-watermarking-songs/)

## 오늘의 시사점

오늘 하루의 뉴스를 관통하는 것은 **추론 원가를 누가, 어떤 방식으로 부담하는가**라는 질문이다. 오픈AI는 무료화로 원가를 스스로 떠안았고, 딥시크는 사용자에게 넘겼으며, MS는 모델 교체로 줄였고, 옵트에이아이는 아예 기기로 옮겼다. 구글은 거래 수수료로 회수하는 길을 열었다. 지난 2년간 이 질문은 '언젠가 하드웨어가 싸지면 해결될 문제'로 미뤄져 왔지만, 2026년 인프라 지출 **7000억 달러** 전망 앞에서 각 사업자는 더 이상 미룰 수 없는 선택을 하고 있다.

여기서 구조적으로 유리한 위치가 드러난다. 모건스탠리는 8월 7일 보고서에서 AI의 미래를 폐쇄형 독점, 폐쇄형·오픈소스 공존, 오픈소스 범용화의 세 갈래로 나눈 뒤, 세 시나리오 모두에서 공통 승자로 **컴퓨팅 인프라를 공급하는 엔비디아와 이를 운영하는 대형 클라우드 사업자**를 지목했다. 미렌딜이 시드의 절반을 구글 클라우드에 넣고, MS가 자사 개발 도구의 기본 모델을 바꾸며, 앤트로픽이 애저에 300억 달러를 약정하는 그림은 이 진단과 정확히 겹친다. 모델 계층에서 누가 이기든 비용은 인프라 계층을 통과한다. [AI타임스](https://www.aitimes.com/news/articleView.html?idxno=213601)

응용 계층에 주는 함의는 더 실용적이다. 옵트기어의 MMLU 43.2점은 프런티어 모델과 비교할 수준이 아니지만, 초당 7042토큰과 MCU 구동은 다른 종류의 경쟁력이다. 오밀리아가 생성 AI 단독이 아니라 과업별 도구 조합으로 ARR 6000만 달러를 만든 것도 같은 맥락이다. 최고 성능 모델을 쓰는 것과 문제를 푸는 것이 분리되기 시작했고, 그 분리가 실제 자금 조달로 확인되고 있다.

---

## 📎 참고 자료

1. [ChatGPT brings unlimited text chats to free users — TechCrunch](https://techcrunch.com/2026/08/06/openai-brings-unlimited-chatgpt-text-chats-to-free-users/)
2. [딥시크, 초저가 정책 접나…AI 서비스 가격 '대폭' 인상 예고 — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=213632)
3. [MS, 사내 개발자 기본 모델로 'GPT-5.6 솔' 지정..."효율 최우선" — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=213604)
4. [옵트에이아이, 온디바이스 특화 자체 경량 AI 모델 '옵트기어' 공개 — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=213630)
5. [Exclusive: Mirendil inks $100M+ Google Cloud deal to scale self-improving AI — TechCrunch](https://techcrunch.com/2026/08/06/exclusive-mirendil-inks-100m-google-cloud-deal-to-scale-self-improving-ai/)
6. [Omilia raises $67M to scale its customer support platform — TechCrunch](https://techcrunch.com/2026/08/06/omilia-raises-67m-to-scale-its-customer-support-platform/)
7. [Google Maps adds agentic features, including food ordering and hotel bookings — TechCrunch](https://techcrunch.com/2026/08/06/google-maps-adds-agentic-features-including-food-ordering-and-hotel-bookings/)
8. [Amid legal battles, Suno says it will start watermarking songs — TechCrunch](https://techcrunch.com/2026/08/06/amid-legal-battles-suno-says-it-will-start-watermarking-songs/)
9. ["AI의 미래는 셋으로 갈리지만"...모건스탠리가 지목한 공통 승자는 — AI타임스](https://www.aitimes.com/news/articleView.html?idxno=213601)
