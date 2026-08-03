---
layout: single
title: "📊 AI 일간보고서 — 2026년 08월 03일"
date: 2026-08-03 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "EU AI법"
  - "검증비용"
  - "데이터무결성"
  - "휴머노이드개방"
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

> **2026년 08월 03일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 08월 03일 AI 일간보고서

## 오늘의 핵심 요약

오늘 소식을 한 줄로 묶으면 "생성 비용이 0에 가까워지자, 청구서가 검증 쪽으로 옮겨 붙었다"이다. EU는 AI 생성물에 라벨을 붙이라는 의무를 8월 2일부로 발효시켰고, 애플은 AI가 써낸 취약점 제보가 밀려들자 제보 창구 자체에 상한을 걸었다. 가트너는 2029년이면 개인정보 사고 대부분이 유출이 아니라 AI의 추론에서 나올 것이라고 봤고, 실제로 AI 지원 코드가 DNA 증거 스캔 데이터를 흔적 없이 변조할 수 있다는 연구 결과가 나왔다. 네 건 모두 "AI가 무엇을 만들 수 있는가"가 아니라 "AI가 만든 것을 누가 어떻게 확인하는가"에 관한 뉴스다. 여기에 미국 주정부들의 데이터센터 세제 혜택 철회와 한국의 독자 파운데이션 모델 2차 평가 일정이 겹치면서, 규제·인프라·검증 비용이 같은 주에 동시에 올라갔다.

## 주요 이슈 1: 발효된 것은 라벨링 의무뿐이고, 무거운 쪽은 뒤로 밀렸다

유럽연합 집행위원회는 8월 2일 AI법 투명성 의무의 적용 개시를 공식화했다. 사용자가 챗봇·에이전트·아바타와 대화 중임을 고지할 것, AI 생성·조작 콘텐츠를 기계 판독 가능한 방식으로 표시할 것, 딥페이크와 감정 인식·생체 분류 결과에 라벨을 붙일 것. 위반 시 기업에는 최대 1,500만 유로 또는 전 세계 연매출 3%, EU 기관에는 최대 75만 유로가 부과된다.

주목할 대목은 오히려 발효되지 '않은' 쪽이다. 7월 8일 서명된 디지털 옴니버스로 부속서 III 단독형 고위험 시스템 의무는 2027년 12월 2일로, 규제 제품 내장형 AI는 2028년 8월 2일로 밀렸다. 기존 시스템의 워터마킹 의무도 2026년 12월 2일까지 유예됐다. 즉 EU는 "무엇을 만들 수 있는가"를 제한하는 조항은 미루고, "만든 것에 표식을 남기라"는 조항만 먼저 켰다. 규제의 무게중심이 능력 통제에서 출처 추적으로 이동한 것이며, 이는 뒤에 나올 세 이슈와 정확히 같은 방향이다. [European Commission](https://commission.europa.eu/news-and-media/news/safer-and-more-transparent-ai-2026-08-02_en) / [Technology.org](https://www.technology.org/2026/07/17/eu-ai-act-what-actually-applies-on-2-august-2026/)

## 주요 이슈 2: 제보는 공짜가 됐고, 검증은 그대로다 — 애플이 창구를 좁힌 이유

애플은 보안 연구자의 취약점 제보 건수에 상한을 두고 30일 냉각 기간을 도입했다. 이유는 AI가 거들어 작성된 저품질 제보의 홍수였다. 존재하지 않는 취약점을 그럴듯하게 서술한 리포트가 쌓이면서 검토 파이프라인이 막혔다는 것이다.

부작용은 즉시 나타났다. 이탈리아 스타트업 바이나리오는 ChatGPT로 기기 완전 장악이 가능한 macOS 취약점을 찾았지만 제출이 막혀 신고하지 못했다. CEO는 이 결함의 암시장 가치를 10만~20만 달러로 추산했다. 애플이 최고 포상금을 200만 달러로 올린 시점에 벌어진 일이다. 소포스의 라페 필링은 "버그바운티가 취약점을 찾는 일에서 기계 속도로 검증하는 일로 옮겨갔다"고 요약했다.

구조를 뜯어보면 단순하다. 제보 생성 비용은 AI 덕분에 사실상 0이 됐지만, 제보 검증 비용은 여전히 사람 시간에 묶여 있다. 입력이 1,000배 늘고 처리량이 그대로면 남는 선택지는 입구를 좁히는 것뿐이고, 그 대가로 진짜 취약점이 밖에 남는다. 어제자 소식에서 애플의 최신 업데이트가 평소의 5배에 달하는 수정 건수를 담았다는 점을 고려하면, 이 병목은 이론이 아니라 이미 청구서다. [the-decoder](https://the-decoder.com/a-real-macos-flaw-worth-200k-went-unreported-because-apples-bug-bounty-inbox-was-full-of-ai-slop/) / [Financial Times](https://www.ft.com/content/4532122d-90f2-4433-9df6-ca99d8a141d2)

## 주요 이슈 3: 지켜야 할 대상이 '유출'에서 '해석'과 '무결성'으로 옮겨간다

가트너는 2029년까지 대부분의 개인정보 침해 사고가 PII의 직접 유출이 아니라 AI가 생성한 추론에서 비롯될 것으로 전망했다. 공개 정보와 비식별 데이터, AI 분석을 조합하면 원본 기록을 훔치지 않고도 개인의 건강 상태를 알아낼 수 있고, 그렇게 만들어진 정보는 원본이 아니기 때문에 기존 유출 탐지 체계에 걸리지 않는다. 바트 빌렘센 수석 애널리스트의 표현대로 "데이터 유출에서 인사이트 유출로" 사고 유형이 바뀌는 것이다. 가트너는 2028년까지 데이터 무결성 보호 지출이 기밀성 보호 투자와 비슷한 수준에 도달할 것으로 봤다.

같은 날 월스트리트저널이 전한 연구 결과는 이 전망의 극단적 사례다. 연구자들이 AI 지원 코드로 범죄 수사 연구소 표준 장비가 만든 DNA 증거 스캔 데이터를 흔적 없이 변조하는 데 성공했고, 사정권에 든 증거는 약 30년치다. DNA 증거의 법정 지위는 "원 데이터는 조작되지 않는다"는 전제 위에 서 있었는데, 그 계층이 조용히 바뀔 수 있다면 무결성 검증은 분석 단계가 아니라 장비 출력 단계로 내려가야 한다. 예산이 기밀성에서 무결성으로 절반쯤 이동할 것이라는 예측은, 이런 사례가 몇 건만 더 나오면 전망이 아니라 사후 대응이 된다. [ZDNet코리아](https://zdnet.co.kr/view/?no=20260803093811) / [The Wall Street Journal](https://www.wsj.com/tech/cybersecurity/security-flaw-placed-30-years-of-dna-evidence-at-risk-of-hacking-1932775a)

## 주요 이슈 4: 비용은 오르고, 경쟁은 개방과 국가 평가로 갈린다

인프라 쪽에서는 반대 방향의 압력이 확인됐다. 디인포메이션은 8월 2일 미국에서 4개 주가 데이터센터 세제 혜택을 되돌렸고 9개 주가 폐지를 검토 중이며, 감면이 사라지면 장비 비용이 최대 7% 오를 수 있다고 보도했다. 모델 추론 단가가 계속 내려가는 흐름과 정면으로 부딪히는 변수다.

경쟁 전선에서는 두 갈래가 뚜렷했다. 로보티즈는 8월 3일 휴머노이드 'AI 사피엔스'의 보행·균형 제어 코드 전체와 Sim2Real 도구, 강화학습 워크플로를 상업 이용 제약이 최소화된 라이선스로 공개했다. 기술 내재화율 97%의 자체 액추에이터로 만든 기체의 가장 값비싼 노하우를 그대로 내놓은 셈이다. 반면 한국 정부의 독자 파운데이션 모델 사업은 8월 8~11일 200명 규모 국민평가를 거쳐 LG AI연구원·SK텔레콤·업스테이지·모티프테크놀로지스 4팀 중 3팀만 남기고, 최종적으로는 2팀을 선정한다. 한쪽은 생태계를 열어 표준을 잡으려 하고, 다른 쪽은 자원을 좁혀 전력을 집중한다. [The Information](https://www.theinformation.com/articles/exclusive-data-center-costs-set-rise-u-s-states-move-repeal-tax-breaks) / [ZDNet코리아](https://zdnet.co.kr/view/?no=20260803091554) / [헤럴드경제](https://biz.heraldcorp.com/article/10828634)

## 오늘의 시사점

오늘 나온 소식들을 관통하는 수치는 7%, 3%, 30일, 30년처럼 서로 무관해 보이지만 모두 같은 지점을 가리킨다. AI가 무언가를 만들어내는 비용은 계속 떨어지는데, 그 산출물이 진짜인지 확인하는 비용은 떨어지지 않았다는 것이다.

사이언티픽 아메리칸이 전한 암호학 사례는 이 비대칭을 가장 선명하게 보여준다. 두 연구팀이 같은 미해결 문제를 같은 모델로 풀어 3시간 18분 간격으로 논문을 제출했다. 결과 자체는 훌륭하지만, 우선권과 검증이라는 학계의 사회적 절차는 몇 시간 단위 해상도로 설계된 적이 없다. 애플의 버그바운티에서 벌어진 일도, EU가 라벨링부터 켠 것도, 가트너가 무결성 예산을 지목한 것도 결국 같은 문제의 다른 얼굴이다.

실무적으로 정리하면 세 가지다. 첫째, EU 시장에 닿는 제품이라면 챗봇 고지와 생성물 표시를 지금 점검해야 한다. 유예된 건 고위험 의무이지 투명성 의무가 아니다. 둘째, AI 산출물을 외부에서 받아들이는 창구(제보, 지원서, 리뷰, 리서치)를 가진 조직은 유입량이 아니라 검증 처리량을 기준으로 용량을 다시 계산해야 한다. 셋째, 보안 예산을 "새어 나가지 않게 하는" 항목에만 배치해 두었다면, 상당 부분을 "잘못 해석되거나 조용히 바뀌지 않게 하는" 항목으로 옮길 준비를 시작할 때다.

[Scientific American](https://www.scientificamerican.com/article/ai-helped-produce-two-proofs-for-the-same-cryptography-problem/) / [European Commission](https://commission.europa.eu/news-and-media/news/safer-and-more-transparent-ai-2026-08-02_en)

---

## 📎 참고 자료

1. [Safer and more transparent AI — European Commission](https://commission.europa.eu/news-and-media/news/safer-and-more-transparent-ai-2026-08-02_en)
2. [EU AI Act: What Actually Applies on 2 August 2026 — Technology.org](https://www.technology.org/2026/07/17/eu-ai-act-what-actually-applies-on-2-august-2026/)
3. [A real macOS flaw worth $200K went unreported because Apple's bug bounty inbox was full of AI slop — the-decoder](https://the-decoder.com/a-real-macos-flaw-worth-200k-went-unreported-because-apples-bug-bounty-inbox-was-full-of-ai-slop/)
4. [Apple caps bug report submissions citing deluge of AI-assisted reports — Financial Times](https://www.ft.com/content/4532122d-90f2-4433-9df6-ca99d8a141d2)
5. [이름·연락처 없어도 건강 상태 안다…AI 개인정보 침해 '비상' — ZDNet코리아](https://zdnet.co.kr/view/?no=20260803093811)
6. [Security Flaw Placed 30 Years of DNA Evidence at Risk of Hacking — The Wall Street Journal](https://www.wsj.com/tech/cybersecurity/security-flaw-placed-30-years-of-dna-evidence-at-risk-of-hacking-1932775a)
7. [Data Center Costs Set to Rise as U.S. States Move to Repeal Tax Breaks — The Information](https://www.theinformation.com/articles/exclusive-data-center-costs-set-rise-u-s-states-move-repeal-tax-breaks)
8. [로보티즈, 휴머노이드 'AI 사피엔스' 코드 전체 공개 — ZDNet코리아](https://zdnet.co.kr/view/?no=20260803091554)
9. [윤곽 드러나는 국가대표AI…독파모 2차 평가 '결전의 달' — 헤럴드경제](https://biz.heraldcorp.com/article/10828634)
10. [AI helped produce two proofs for the same cryptography problem — Scientific American](https://www.scientificamerican.com/article/ai-helped-produce-two-proofs-for-the-same-cryptography-problem/)
