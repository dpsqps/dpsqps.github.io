---
layout: single
title: "📊 AI 일간보고서 — 2026년 08월 22일"
date: 2026-08-22 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "스캐폴딩의시대"
  - "멀티모달가격붕괴"
  - "카카오인적분할"
  - "엔비디아수직화"
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

> **2026년 08월 22일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 08월 22일 AI 일간보고서

## 오늘의 핵심 요약

새 파라미터를 늘려서 이긴 사례가 하나도 없는 하루였다. 엔비디아는 클로드 오퍼스 5를 그대로 쓰면서 ARC-AGI-3 점수를 30%에서 100%로 끌어올렸고, 구글 연구진은 모델 대신 학습 환경을 재설계해 held-out 성능 9.0점을 얻었다. 반대편에서는 딥시크가 이미지 1,000장 처리 비용을 1.15위안으로 내리고, 정체불명의 스텔스 모델이 100만 토큰 컨텍스트를 일주일 무료로 뿌렸다. 그리고 이 모든 기술 경쟁의 밑단에서, 카카오는 회사를 둘로 쪼갰고 엔비디아는 한국 NPU 설계사의 문을 두드렸으며 앤트로픽은 상장 신고서에 'AI에 대한 대중 반발'을 위험요인으로 적기 시작했다. 능력의 프런티어는 모델 안쪽에서 모델 바깥쪽으로, 그리고 조직도와 공시 문서로 옮겨가고 있다.

## 주요 이슈 1: 30%를 100%로 만든 것은 모델이 아니라 스캐폴딩이었다

오늘 가장 선명한 수치는 엔비디아 AVO의 ARC-AGI-3 100%다. 25개 공개 환경의 183개 레벨 전부를, 지시문도 규칙도 목표도 없는 상태에서 통과했다. 그런데 진짜 숫자는 옆에 있다. AVO를 구동한 모델은 앤트로픽 클로드 오퍼스 5이고, 같은 모델을 단독으로 돌리면 같은 벤치마크에서 약 30%다. 지속 메모리, 점검-계획-구현-평가 반복 루프, 막혔을 때 경로를 되돌리는 감독 모듈. 이 세 가지가 70%포인트를 만들었다. [The New Stack](https://thenewstack.io/nvidia-avo-arcagi3-benchmark/)

같은 논리가 연구 쪽에서도 나왔다. 구글 연구진의 EnvHarness는 환경의 내부 로직을 전혀 수정하지 않고 그 위에 플러그인 층을 얹어 환경 행동을 재구성하는데, 4개 도메인 5개 벤치마크에서 held-out 성능 최대 9.0점 향상과 실행 단계 9.8% 감소를 동시에 얻었다. 저자들의 문제의식은 "손으로 만든 정적 환경은 에이전트의 약점을 모른다"는 것이다. 모델을 더 크게 만드는 대신 모델이 배우는 무대를 손보는 쪽이다. [arXiv:2608.19880](https://arxiv.org/abs/2608.19880)

주의할 대목도 같이 봐야 한다. AVO의 100%는 엔비디아가 자체 재구현한 과제 인터페이스에서 자체 측정한 값이고 ARC Prize 공식 리더보드의 독립 검증을 거치지 않았다. 딥시크의 벤치마크도 자사 환경 측정치다. 스캐폴딩이 점수를 만든다는 명제가 참일수록, '누가 어떤 하네스로 쟀는가'가 점수의 일부가 된다. 어제 이 블로그가 다룬 신뢰성 갭 — 한 번의 성공이 반복 성공을 보장하지 않는다는 문제 — 과 정확히 같은 자리에서 만나는 이야기다.

## 주요 이슈 2: 기억을 붙이면 좋아진다는 전제가 반증되고 있다

스캐폴딩이 만능이 아니라는 반례도 같은 날 나왔다. ZJUNLP의 MemTrapBench는 '얼마나 잘 저장하고 정확히 꺼내는가' 대신 '꺼내온 기억이 추론을 얼마나 망치는가'를 측정했다. 두 모델 계열에 다섯 가지 메모리 프레임워크를 붙인 결과, 평가한 모든 메모리 전략이 메모리를 쓰지 않은 설정보다 낮은 점수를 냈고 가장 강한 방법조차 10% 이상 하락했다. 저자들은 실패를 추론 고착과 신념 왜곡 두 유형으로 분류했다. [arXiv:2608.20202](https://arxiv.org/abs/2608.20202)

이건 이슈 1의 반대편 얼굴이다. AVO의 성공 요소 목록 첫 줄에도 '지속 메모리'가 있었다. 같은 부품이 한쪽에서는 70%포인트를 만들고 다른 쪽에서는 10%포인트를 깎는다. 차이는 부품 자체가 아니라 그 부품을 언제 신뢰하고 언제 버릴지를 정하는 제어 로직에 있다. MemTrapBench가 제안한 AdaptiveMem이 결국 "메모리 함정을 피하라"는 추론 시점 지시라는 점도 같은 방향을 가리킨다. 에이전트 엔지니어링의 다음 난제는 무엇을 붙일까가 아니라 무엇을 무시할까다.

## 주요 이슈 3: 멀티모달 단가가 무너지는 방식 — 토큰 환산과 무료 배포

딥시크는 8월 21일 V4-Flash-Vision-Exp를 열면서 이미지를 장당 최대 384토큰으로 환산해 기존 텍스트 모델과 동일 단가로 과금하는 구조를 택했다. 별도 비전 할증이 없다. 결과적으로 이미지 1,000장 처리에 약 1.15위안(약 0.17달러), 오프피크에는 0.6위안 아래다. 성능은 자체 측정 기준 Agents' Last Exam 27.3점, ZeroBench pass@5 35.0점으로 오퍼스 4.8의 25.7점·34.0점을 앞섰고, NL2Repo는 57.7점 대 69.7점으로 뒤졌다. 전 영역 우위가 아니라 특정 용도에서의 가격 대비 우위를 노린 배치다. [DeepSeek API Docs](https://api-docs.deepseek.com/news/news260821/)

같은 시기 정체불명의 스텔스 모델 Ox Alpha가 오픈라우터와 OpenCode에 등장해 1,048,576토큰 컨텍스트와 131,072토큰 출력, 텍스트·이미지·영상 입력을 일주일간 무료로 열었다. OpenCode 측은 데이터 무보관에 하루 100조 토큰 처리 용량을 언급했다. 어느 랩이 만들었는지는 확인되지 않았다. [OfficeChai](https://officechai.com/ai/stealth-model-ox-alpha-available-for-free-for-a-week-on-openrouter-and-opencode/)

어제 이 블로그는 '단가는 그대로인데 태스크당 비용은 오른다'는 출력 길이 착시를 다뤘다. 오늘 소식은 그 반대편 압력이다. 과금 단위 자체를 재정의하거나(이미지→384토큰), 아예 한시적으로 0으로 만들어 사용 데이터를 확보하는 방식. 두 흐름이 동시에 작동하면 공표 단가는 갈수록 의미 없는 비교 지표가 된다.

## 주요 이슈 4: 기술이 아니라 법인·지분·공시가 움직인 날

카카오는 8월 21일 이사회에서 신설법인 카카오AI와 존속법인 카카오X로의 인적분할을 결의했다. 순자산 장부가액 기준 분할비율은 0.36 대 0.64. 카카오AI는 약 5,000만 이용자의 카카오톡을 에이전틱 AI 인터페이스로 바꾸는 데 집중하고, 카카오X는 카카오뱅크·카카오페이·카카오모빌리티 등 자회사를 맡는다. 주주환원 재원도 카카오AI는 조정 FCF의 20~35%, 카카오X는 자회사 배당금의 30%와 투자차익의 30%로 성격을 갈랐다. 12월 17일 임시주총, 2027년 1월 1일 분할 완료, 1월 27일 재상장·변경상장 일정이다. [ZDNet Korea](https://zdnet.co.kr/view/?no=20260821102850) / [카카오](https://www.kakaocorp.com/page/detail/12116)

엔비디아는 다른 방식으로 경계를 넓혔다. 블룸버그는 8월 21일 젠슨 황 CEO가 산타클라라 본사에서 리벨리온 박성현 대표를 만나 기술 파트너십·투자·인수까지 포함한 초기 논의를 했다고 보도했다. 리벨리온은 SK하이닉스·삼성벤처투자·Arm 등에서 약 8억 5,000만 달러를 조달했고 기업가치는 약 23억 달러다. 하루 앞선 8월 20일에는 풀사이드의 모델 팩토리를 60억 달러에 비독점 라이선스하고 10억 달러를 추가 투자하는 구조가 공개됐다. 인수 대신 라이선스와 지분으로 흡수하는 패턴이 반복된다. [Bloomberg](https://www.bloomberg.com/news/articles/2026-08-21/nvidia-in-talks-with-chip-startup-rebellions-for-potential-deal)

그리고 앤트로픽의 IPO 신고서에는 'AI에 대한 대중 반발'이 위험요인으로 들어갈 예정이라고 CNBC가 전했다. 데이터센터 확산에 대한 지역사회 우려, 일자리 대체 불안 같은 항목이다. 연환산 매출은 7월 말 기준 약 650억 달러 수준으로 전해진다. [CNBC](https://www.cnbc.com/2026/08/21/-anthropic-ipo-filing-will-show-ai-backlash-as-risk-sources-say.html)

## 오늘의 시사점

세 갈래 소식이 하나의 문장으로 모인다. **AI의 경쟁 지점이 모델 내부에서 모델을 둘러싼 구조로 이동했다.**

기술적으로는 스캐폴딩이다. 같은 오퍼스 5가 하네스에 따라 30%도 되고 100%도 되며, 같은 메모리 모듈이 어디서는 성능을 만들고 어디서는 10%를 깎는다. 이는 모델 벤더의 해자가 얇아진다는 뜻이 아니라, 해자가 한 겹 더 생겼다는 뜻에 가깝다. 문제는 이 층이 대부분 자체 측정으로 보고된다는 점이다. 오늘 인용한 세 건의 인상적 수치 — AVO 100%, 딥시크의 벤치마크 표, EnvHarness의 9.0점 — 중 독립 검증을 거친 것은 없다.

경제적으로는 과금 단위의 재정의다. 이미지를 384토큰으로 환산하거나 100만 컨텍스트를 무료로 여는 선택은 가격 인하가 아니라 비교 자체를 무력화하는 전략이다. 구매자 입장에서 유일하게 의미 있는 지표는 '내 워크로드를 끝까지 돌렸을 때의 총비용'으로 좁혀지고 있다.

조직적으로는 분리다. 카카오가 AI 사업의 실행 속도와 자본배분 체계를 기존 법인 안에서 확보하기 어렵다고 판단해 회사를 쪼갠 것, 엔비디아가 인수 대신 라이선스와 지분으로 역량을 흡수하는 것, 앤트로픽이 사회적 수용성을 상장 문서의 계량 항목으로 올린 것. 셋 다 AI 역량을 기존 구조 안에 담을 수 없어 구조를 바꾸는 사례다. 모델이 좋아지는 속도보다 그것을 담을 그릇을 다시 만드는 속도가 지금 더 큰 변수다.

---

## 📎 참고 자료

1. [Claude Opus 5 scored 30% on ARC-AGI-3. Wrapped in Nvidia's AVO, it hit 100% — The New Stack](https://thenewstack.io/nvidia-avo-arcagi3-benchmark/)
2. [NVIDIA AVO Reaches 100% on ARC-AGI-3 — NVIDIA Technical Blog](https://developer.nvidia.com/blog/nvidia-avo-reaches-100-on-arc-agi-3-demonstrating-a-frontier-level-general-purpose-architecture-for-long-horizon-autonomous-agents/)
3. [EnvHarness: Awakening Static Worlds for Agent Learning — arXiv:2608.19880](https://arxiv.org/abs/2608.19880)
4. [MemTrapBench: Benchmarking Cognitive Traps in LLM Memory Use — arXiv:2608.20202](https://arxiv.org/abs/2608.20202)
5. [DeepSeek-V4-Flash-Vision-Exp Release: Multimodal API Now Live — DeepSeek API Docs](https://api-docs.deepseek.com/news/news260821/)
6. [DeepSeek Releases V4-Flash-Vision-Exp, Matches Opus 4.8 On Some Multimodal Benchmarks — OfficeChai](https://officechai.com/ai/deepseek-releases-v4-flash-vision-exp-matches-opus-4-8-on-some-multimodal-benchmarks/)
7. [Stealth Model Ox Alpha Available For Free For A Week On OpenRouter And OpenCode — OfficeChai](https://officechai.com/ai/stealth-model-ox-alpha-available-for-free-for-a-week-on-openrouter-and-opencode/)
8. [카카오, 2개 회사로 나뉜다…카카오AI-카카오X로 성장 재설계 — ZDNet Korea](https://zdnet.co.kr/view/?no=20260821102850)
9. [카카오, 인적분할 결의 — 카카오](https://www.kakaocorp.com/page/detail/12116)
10. [Nvidia in Talks With Chip Startup Rebellions for Potential Deal — Bloomberg](https://www.bloomberg.com/news/articles/2026-08-21/nvidia-in-talks-with-chip-startup-rebellions-for-potential-deal)
11. [Anthropic IPO filing will show AI backlash as a risk factor, sources say — CNBC](https://www.cnbc.com/2026/08/21/-anthropic-ipo-filing-will-show-ai-backlash-as-risk-sources-say.html)
