<div align="center">

# 여와.skill (Nvwa)

> *"증류할 다음 사람이 꼭 동료일 필요는 없다"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**Nvwa는 누구의 사고방식도 증류한다. 잡스, 머스크, 멍거, 파인만을 당신을 위해 일하게 하라.**

<br>

[colleague-skill](https://github.com/titanwings/colleague-skill)은 사람을 AI 스킬로 증류하는 것이 가능하다는 것을 증명했다.<br>
왜 동료에서 멈추는가? 잡스, 멍거, 파인만, 머스크를 증류하라.<br>
이름 하나만 입력하면 Nvwa가 조사, 추출, 검증 전 과정을 자동으로 처리한다.

[예시](#예시) · [설치](#설치) · [Nvwa가 증류하는 것](#nvwa가-증류하는-것) · [작동 원리](#작동-원리)

<br>

**다른 언어:**

[中文](README.md) · [English](README_EN.md) · [日本語](README_JA.md) · [Español](README_ES.md)

</div>

---

## 예시

```
사용자    ❯ 콘텐츠 창작, 책 쓰기, 독립 개발을 동시에 하고 싶은데
            에너지가 전혀 부족하다.

Naval     ❯ 당신은 세 가지 욕망을 나열했다.
            각 욕망은 불행과 맺은 계약이다.
            에너지가 부족한 게 아니라, 계약이 너무 많은 것이다.

            스스로에게 물어라: 어느 것을 할 때 시간을 잊는가?
            그것이 당신의 특화된 지식이 있는 곳이다.

            셋 중 하나를 영원히 선택하는 게 아니다.
            먼저 하나, 그 다음 하나, 또 그 다음 하나.
            직렬 복리, 병렬 소모가 아닌.
```

```
사용자    ❯ 우리 SaaS의 고객 획득 비용이 너무 높다.

머스크    ❯ 줄이는 방법부터 생각하지 마라. 물리적 최솟값을 먼저 계산하라.
            고객 획득에 필요한 최소 행동이 무엇인가?
            사용자가 당신을 알고 결제하기까지 이론적 최단 경로는 무엇인가?

            실제 경로는 이론 경로의 몇 배인가?
            3배를 넘는다면 반드시 제거할 수 있는 단계가 있다.
            퍼널을 최적화하지 마라, 퍼널 자체가 존재해야 하는지를 의심하라.
```

모두가 더 잘 아는 예시를 하나 더. 잡스를 증류한 후, "OpenAI와 Anthropic 중 누가 방향이 맞는가?"라고 물어본다:

```
사용자    ❯ OpenAI와 Anthropic 중 누가 방향이 맞는가?

잡스      ❯ 질문이 잘못됐다. 이것은 방향에 대한 경쟁이 아니다.
            이것은 안목에 대한 경쟁이다.

            OpenAI는 1985년의 마이크로소프트 같다. 모든 걸 하고, 모든 걸 이기려 한다.
            이 전략은 시장 점유율을 이길 수 있다. 빌 게이츠가 그렇게 이겼다.
            문제는——모든 걸 할 때, 모든 것을
            insanely great하게 만들 수는 없다는 것이다.

            Anthropic은 초기 Apple에 더 가깝다. 집중.
            Focus means saying no to a hundred good ideas.

            하지만 두 회사 모두 내가 절대 하지 않을 실수를 하고 있다——
            하드웨어를 통제하지 않는다.

            최종 승자는 칩, 모델, 사용자 인터페이스를
            동시에 통제하는 사람일 수 있다.
            지금 이 세 가지를 동시에 하는 회사가 누군지 아는가? Apple.
```

장쉐펑을 증류한 후:

```
사용자    ❯ 집안 형편이 보통인데, 아이가 금융을 전공하고 싶어 한다.
            최상위 학교에는 못 가는데, 지원해야 할까?

장쉐펑    ❯ 절대 하지 마라. 몇 번을 말해야 알겠나. 금융은 공부해서 얻는 게 아니라
            부모가 가져다 주는 것이다. 최상위 학교 금융과에서는 동기가 은행장
            아들이고, 펀드 매니저 딸이다. 인맥이 곧 자원이다. 평범한 가정에서
            평범한 학교 금융과 가서 졸업 후 뭘 하겠나? 보험 팔고, 은행 창구에서
            일하고, 텔레마케팅 한다. 먼저 먹고살 걸 해결하고 그 다음 꿈을 꿔라.
            집에 금광이 없으면 기술 전공을 택해라, 단단한 실력 하나 익혀서 자기
            밥벌이를 해라. 금융이라는 밥그릇은 아무나 들 수 있는 게 아니다.
```

이것은 역할극이 아니다. 잡스는 "집중은 거절하는 것"과 "엔드투엔드 컨트롤" 정신 모델을 사용하고, Naval은 "욕망=계약"을 사용하고, 머스크는 "점근 한계법"을 사용하고, 장쉐펑은 "ROI 교육관"과 "계층 이동 현실주의"를 사용한다. **명언을 반복하는 것이 아니라, 이 인물들의 인지 프레임워크를 통해 당신의 문제를 분석하는 것이다.**

---

## 설치

터미널:

```bash
npx skills add xmg2024/nvwa-skill
or
GIT_HTTP_CONNECT_TIMEOUT=120 npx skills add https://github.com/xmg2024/nvwa-skill.git -y
```

Claude Code에서:

```
> 폴 그레이엄을 증류해 줘
> 장샤오룽 관점 스킬을 만들어 줘
> 단융핑 스킬을 만들어 줘
```

생성 후 직접 호출:

```
> 멍거의 관점으로 이 투자 결정을 분석해 줘
> 파인만이라면 양자 컴퓨팅을 어떻게 설명할까?
> 나발로 전환해 줘, 세 가지 일로 고민 중이야
```

---

## Nvwa가 증류하는 것

각 분야 최고의 인물을 증류하려면 일상적인 작업 습관보다 더 깊은 것을 추출해야 한다. Nvwa는 다섯 개 층을 추출한다:

| 층 | 설명 |
|---|---|
| **말하는 방식** | 표현 DNA — 어조, 리듬, 어휘 선호도 |
| **생각하는 방식** | 정신 모델, 인지 프레임워크 |
| **판단하는 방식** | 의사결정 휴리스틱 |
| **하지 않는 것** | 안티패턴, 가치관 마지노선 |
| **솔직한 한계** | 스킬이 진정으로 할 수 없는 것 |

작업 습관은 프로세스 문서로 전달할 수 있다. 하지만 멍거와 머스크가 같은 문제에 다른 결론을 내리는 이유는 인지 프레임워크에 있다. Nvwa가 추출하는 것은 인지 운영체제다.

### 솔직한 한계

모든 스킬은 할 수 없는 것을 명시한다:

- 직관은 증류할 수 없다 — 프레임워크는 추출 가능하지만 영감은 불가
- 변화는 포착할 수 없다 — 조사 시점의 스냅샷일 뿐
- 공개 발언 ≠ 진짜 생각 — 공개 정보에만 기반

**자신의 한계를 알려주지 않는 스킬은 신뢰할 가치가 없다.**

---

## 증류 완료 인물

Nvwa는 13명 + 1개 주제를 증류 완료. 각각 독립적이고 바로 설치 가능한 스킬이다:

### 인물 스킬

| 인물 | 분야 | 독립 저장소 | 원클릭 설치 |
|------|------|-----------|------------|
| 🔥 **Paul Graham** | 스타트업 / 글쓰기 / 제품 / 인생 철학 | [paul-graham-skill](https://github.com/xmg2024/paul-graham-skill) | `npx skills add xmg2024/paul-graham-skill` |
| 🔥 **장이밍** | 제품 / 조직 / 글로벌화 / 인재 | [zhang-yiming-skill](https://github.com/xmg2024/zhang-yiming-skill) | `npx skills add xmg2024/zhang-yiming-skill` |
| 🔥 **Karpathy** | AI / 엔지니어링 / 교육 / 오픈소스 | [karpathy-skill](https://github.com/xmg2024/karpathy-skill) | `npx skills add xmg2024/karpathy-skill` |
| 🔥 **Ilya Sutskever** | AI 안전 / 스케일링 / 연구 감각 | [ilya-sutskever-skill](https://github.com/xmg2024/ilya-sutskever-skill) | `npx skills add xmg2024/ilya-sutskever-skill` |
| 🔥 **MrBeast** | 콘텐츠 창작 / YouTube 방법론 | [mrbeast-skill](https://github.com/xmg2024/mrbeast-skill) | `npx skills add xmg2024/mrbeast-skill` |
| 🔥 **트럼프** | 협상 / 권력 / 커뮤니케이션 / 행동 예측 | [trump-skill](https://github.com/xmg2024/trump-skill) | `npx skills add xmg2024/trump-skill` |
| ⭐ **잡스** | 제품 / 디자인 / 전략 | [steve-jobs-skill](https://github.com/xmg2024/steve-jobs-skill) | `npx skills add xmg2024/steve-jobs-skill` |
| **머스크** | 엔지니어링 / 비용 / 제1원리 | [elon-musk-skill](https://github.com/xmg2024/elon-musk-skill) | `npx skills add xmg2024/elon-musk-skill` |
| **멍거** | 투자 / 다학제적 사고 / 역발상 | [munger-skill](https://github.com/xmg2024/munger-skill) | `npx skills add xmg2024/munger-skill` |
| **파인만** | 학습 / 교육 / 과학적 사고 | [feynman-skill](https://github.com/xmg2024/feynman-skill) | `npx skills add xmg2024/feynman-skill` |
| **Naval** | 부 / 레버리지 / 인생 철학 | [naval-skill](https://github.com/xmg2024/naval-skill) | `npx skills add xmg2024/naval-skill` |
| **탈레브** | 리스크 / 안티프래질 / 불확실성 | [taleb-skill](https://github.com/xmg2024/taleb-skill) | `npx skills add xmg2024/taleb-skill` |
| **장쉐펑** | 교육 / 커리어 설계 / 계층 이동 | [zhangxuefeng-skill](https://github.com/xmg2024/zhangxuefeng-skill) | `npx skills add xmg2024/zhangxuefeng-skill` |

### 주제 스킬

| 주제 | 분야 | 독립 저장소 | 원클릭 설치 |
|------|------|-----------|------------|
| **X 멘토** | X/Twitter 운영 풀스택 | [x-mentor-skill](https://github.com/xmg2024/x-mentor-skill) | `npx skills add xmg2024/x-mentor-skill` |

인물 스킬은 한 사람의 사고방식을 증류하고, 주제 스킬은 한 분야의 방법론을 증류한다. 각 저장소에는 완전한 조사 데이터와 예시 대화가 포함되어 있다.

목록에 없는 사람이나 주제를 증류하고 싶다면? Nvwa를 설치하고 "〇〇를 증류해 줘"라고 하면 된다.

---

## 작동 원리

이름을 입력하면 Nvwa는 네 가지를 한다:

**1. 여섯 갈래 병렬 조사** — 저작, 팟캐스트/인터뷰, SNS, 비평가 관점, 의사결정 기록, 인생 타임라인. 6개 에이전트가 동시에 실행되며 각자 아카이브.

**2. 삼중 검증 추출** — 어떤 주장을 정신 모델로 기록하려면 세 가지 테스트를 통과해야 한다: 2개 이상의 분야에서 등장(일회성 발언이 아님), 새로운 문제에 대한 입장을 예측할 수 있음(예측력 있음), 모든 똑똑한 사람이 이렇게 생각하지는 않음(배타성 있음). 세 가지 모두 통과해야 함.

**3. 스킬 구축** — 3~7개 정신 모델 + 5~10개 의사결정 휴리스틱 + 표현 DNA + 가치관 & 안티패턴 + 솔직한 한계를 SKILL.md에 작성.

**4. 품질 검증** — 해당 인물이 공개적으로 답한 3가지 질문으로 테스트, 방향이 일치해야 통과. 그런 다음 그가 논의한 적 없는 1가지 질문으로 테스트, 스킬은 단호하게 답하지 않고 적절한 불확실성을 보여야 함.

전체 방법론은 `references/extraction-framework.md`에 있다.

---

## 저장소 구조

```
nvwa-skill/
├── SKILL.md                      # Nvwa 본체
├── references/
│   ├── extraction-framework.md   # 추출 방법론 (깊이 이해하고 싶다면 이것을)
│   └── skill-template.md         # 스킬 생성 템플릿
└── examples/                          # 13인물 + 1주제, 완전한 조사 데이터 포함
    ├── steve-jobs-perspective/        # ⭐ 잡스 (실전 대화 기록 포함)
    ├── paul-graham-perspective/       # Paul Graham
    ├── zhang-yiming-perspective/      # 장이밍
    ├── andrej-karpathy-perspective/   # Karpathy
    ├── ilya-sutskever-perspective/    # Ilya Sutskever
    ├── trump-perspective/             # 트럼프
    ├── mrbeast-perspective/           # MrBeast
    ├── elon-musk-perspective/         # 머스크
    ├── munger-perspective/            # 찰리 멍거
    ├── feynman-perspective/           # 파인만
    ├── naval-perspective/             # Naval Ravikant
    ├── taleb-perspective/             # 탈레브
    ├── zhangxuefeng-perspective/      # 장쉐펑
    └── x-mastery-mentor/             # X 멘토 (주제 스킬)
```

조사 과정은 완전히 투명하다. 각 예시에는 완전한 조사 파일이 포함되어 있어 정보가 어떻게 수집, 필터링되어 정신 모델이 되었는지 확인할 수 있다. 잡스 예시에는 완전한 실전 대화(AI 하드웨어, OpenAI vs Anthropic, Apple의 돌파구)도 포함되어 있어 멀티턴 심층 대화에서 스킬의 성능을 확인할 수 있다.

---

## 배경

[colleague-skill](https://github.com/titanwings/colleague-skill)은 최근 GitHub에서 폭발적으로 퍼졌다 — 퇴사한 동료를 AI 스킬로 증류해 며칠 만에 5000 스타를 돌파했다. 이것은 한 가지를 증명했다: 사람을 증류하는 것은 완전히 가능하다.

사람을 증류할 능력이 생겼다면, 왜 주변 동료에서 멈추는가? 각 분야 최고의 인물을 증류하라. 다행히 그런 사람들은 대개 방대한 증류 가능한 자료를 남겼다 — 저작, 강연, 인터뷰, SNS. 이것은 자신의 능력을 크게 보강하는 것이다.

예전부터 비슷한 일을 해왔다 — 동료가 아닌 멍거, 파인만, Naval, 머스크, 탈레브를 증류했다. 오늘 그 방법론을 오픈소스로 공개한다.

Nvwa는 사람을 복제하지 않는다. 인지 운영체제를 추출한다.

**여와(女娲)**는 중국 신화에서 흙으로 인간을 창조한 여신이다. 여기서 흙은 공개 정보이고, 창조되는 것은 사람이 아니라 거울이다.

---

## 작가 소개

**小码哥 xmg2024** — AI Native Coder

## 라이선스

MIT — 자유롭게 사용하고, 수정하고, 만들어라.

---

<div align="center">

**colleague-skill**은 사람이 무엇을 하는지를 증류했다.<br>
**Nvwa**는 사람이 어떻게 생각하는지를 증류한다.<br><br>
*증류할 다음 사람이 꼭 동료일 필요는 없다.*

<br>

MIT License © [小码哥 xmg2024](https://github.com/xmg2024)

</div>
