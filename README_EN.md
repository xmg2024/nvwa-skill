<div align="center">

# 女娲.skill (Nvwa)

> *"The next person you want to distill doesn't have to be a colleague."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**Nvwa distills the thinking of anyone — let Jobs, Musk, Munger, and Feynman work for you.**

<br>

[colleague-skill](https://github.com/titanwings/colleague-skill) proved that distilling a person into an AI skill is viable.<br>
So why stop at colleagues? Go distill Jobs, Munger, Feynman, Musk.<br>
Just input a name — Nvwa handles research, extraction, and validation automatically.

[Examples](#examples) · [Install](#install) · [What Nvwa Distills](#what-nvwa-distills) · [How It Works](#how-it-works)

<br>

**Other Languages:**

[中文](README.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · [Español](README_ES.md)

</div>

---

## Examples

```
User      ❯ I want to do content creation, write a book, and build an indie app,
            but I never have enough energy.

Naval     ❯ You've listed three desires. Each desire is a contract you signed
            with unhappiness. This isn't about energy — it's about too many contracts.

            Ask yourself: which one makes you lose track of time?
            That's where your specific knowledge lives.

            Not choose one forever. Just one first, then one, then one.
            Serial compounding, not parallel exhaustion.
```

```
User      ❯ Our SaaS customer acquisition cost is too high.

Musk      ❯ Don't think about how to reduce it yet. Calculate the physical minimum first.
            What's the minimum necessary action to acquire a customer?
            What's the theoretically shortest path from knowing you to paying you?

            How many times longer is your actual path vs. the theoretical one?
            If it's more than 3x, there are steps you can eliminate.
            Don't optimize the funnel — question whether the funnel should exist at all.
```

Here's one everyone knows better. After distilling Jobs, ask him "Who has the right direction, OpenAI or Anthropic?":

```
User      ❯ Who has the right direction, OpenAI or Anthropic?

Jobs      ❯ You're asking the wrong question. This isn't a race about direction.
            This is a race about taste.

            OpenAI is like Microsoft in 1985. Do everything, win everything.
            That strategy can win market share. That's how Bill Gates won.
            The problem is — when you do everything, you can't make every single
            thing insanely great.

            Anthropic is more like early Apple. Focus.
            Focus means saying no to a hundred good ideas.

            But both companies are making one mistake I would never make —
            they don't control the hardware.

            The ultimate winner might be whoever controls chips, models, and
            user interface simultaneously.
            You know who's doing all three right now? Apple.
```

After distilling Zhang Xuefeng:

```
User      ❯ My family's finances are average. My kid wants to study finance but
            can't get into a top school. Should they apply?

Zhang     ❯ Absolutely not. How many times do I have to say this — finance isn't
Xuefeng     something you study your way into, it's something your parents bring
            you into. At top schools, your classmates are bank presidents' sons
            and fund managers' daughters — connections ARE resources. If you're
            from an ordinary family at an ordinary school studying finance, what
            do you do after graduation? Sell insurance, work a bank counter, do
            cold calls. Earn first, dream later. If your family doesn't have a
            gold mine, pick a technical major, learn a hard skill, feed yourself.
            The finance table isn't one everyone can sit at.
```

This is not role-play. Jobs uses his "focus means saying no" and "end-to-end control" mental models. Naval uses "desire as contract." Musk uses "asymptotic limit" reasoning. Zhang Xuefeng uses "ROI education view" and "class mobility realism." **They are not reciting quotes — they are analyzing your problem through these minds' cognitive frameworks.**

---

## Install

Terminal:

```bash
npx skills add xmg2024/nvwa-skill
or
GIT_HTTP_CONNECT_TIMEOUT=120 npx skills add https://github.com/xmg2024/nvwa-skill.git -y
```

Then in Claude Code:

```
> Distill Paul Graham
> Build a Zhang Xiaolong perspective skill
> Create a Duan Yongping skill for me
```

After creation, invoke directly:

```
> Use Munger's perspective to analyze this investment decision
> How would Feynman explain quantum computing?
> Switch to Naval, I'm torn between three things
```

---

## What Nvwa Distills

Distilling the best minds in any field requires extracting something deeper than daily work habits. Nvwa extracts five layers:

| Layer | Description |
|---|---|
| **How they speak** | Expression DNA — tone, rhythm, word preferences |
| **How they think** | Mental models, cognitive frameworks |
| **How they judge** | Decision heuristics |
| **What they won't do** | Anti-patterns, value floor |
| **Honest limits** | What the skill genuinely cannot do |

Work habits can be conveyed through process docs. But what makes Munger and Musk reach different conclusions about the same problem is their cognitive frameworks. Nvwa extracts the cognitive operating system.

### Honest Limits

Every skill explicitly states what it cannot do:

- Cannot distill intuition — frameworks can be extracted, inspiration cannot
- Cannot capture change — only a snapshot up to the research cutoff
- Public statements ≠ true beliefs — only based on public information

**A skill that doesn't tell you its limits is not worth trusting.**

---

## Distilled Characters

Nvwa has distilled 13 characters + 1 topic. Each is an independent, directly installable skill:

### Character Skills

| Character | Domain | Standalone Repo | One-Click Install |
|-----------|--------|----------------|-------------------|
| 🔥 **Paul Graham** | Startups / Writing / Products / Life Philosophy | [paul-graham-skill](https://github.com/xmg2024/paul-graham-skill) | `npx skills add xmg2024/paul-graham-skill` |
| 🔥 **Zhang Yiming** | Products / Organization / Globalization / Talent | [zhang-yiming-skill](https://github.com/xmg2024/zhang-yiming-skill) | `npx skills add xmg2024/zhang-yiming-skill` |
| 🔥 **Karpathy** | AI / Engineering / Education / Open Source | [karpathy-skill](https://github.com/xmg2024/karpathy-skill) | `npx skills add xmg2024/karpathy-skill` |
| 🔥 **Ilya Sutskever** | AI Safety / Scaling / Research Taste | [ilya-sutskever-skill](https://github.com/xmg2024/ilya-sutskever-skill) | `npx skills add xmg2024/ilya-sutskever-skill` |
| 🔥 **MrBeast** | Content Creation / YouTube Methodology | [mrbeast-skill](https://github.com/xmg2024/mrbeast-skill) | `npx skills add xmg2024/mrbeast-skill` |
| 🔥 **Trump** | Negotiation / Power / Communication / Behavior Prediction | [trump-skill](https://github.com/xmg2024/trump-skill) | `npx skills add xmg2024/trump-skill` |
| ⭐ **Steve Jobs** | Products / Design / Strategy | [steve-jobs-skill](https://github.com/xmg2024/steve-jobs-skill) | `npx skills add xmg2024/steve-jobs-skill` |
| **Elon Musk** | Engineering / Cost / First Principles | [elon-musk-skill](https://github.com/xmg2024/elon-musk-skill) | `npx skills add xmg2024/elon-musk-skill` |
| **Munger** | Investment / Multidisciplinary Thinking / Inversion | [munger-skill](https://github.com/xmg2024/munger-skill) | `npx skills add xmg2024/munger-skill` |
| **Feynman** | Learning / Teaching / Scientific Thinking | [feynman-skill](https://github.com/xmg2024/feynman-skill) | `npx skills add xmg2024/feynman-skill` |
| **Naval** | Wealth / Leverage / Life Philosophy | [naval-skill](https://github.com/xmg2024/naval-skill) | `npx skills add xmg2024/naval-skill` |
| **Taleb** | Risk / Antifragility / Uncertainty | [taleb-skill](https://github.com/xmg2024/taleb-skill) | `npx skills add xmg2024/taleb-skill` |
| **Zhang Xuefeng** | Education / Career Planning / Class Mobility | [zhangxuefeng-skill](https://github.com/xmg2024/zhangxuefeng-skill) | `npx skills add xmg2024/zhangxuefeng-skill` |

### Topic Skills

| Topic | Domain | Standalone Repo | One-Click Install |
|-------|--------|----------------|-------------------|
| **X Mentor** | Full-Stack X/Twitter Operations | [x-mentor-skill](https://github.com/xmg2024/x-mentor-skill) | `npx skills add xmg2024/x-mentor-skill` |

Character skills distill a person's way of thinking; topic skills distill a domain's methodology. Each repo includes full research data and example conversations.

Want to distill someone not on the list? Install Nvwa and say "Distill [name]."

---

## How It Works

Input a name, and Nvwa does four things:

**1. Six parallel research streams** — writings, podcasts/interviews, social media, critic perspectives, decision records, life timeline. 6 agents running simultaneously, each archived.

**2. Triple-verification extraction** — a claim must pass three tests before being recorded as a mental model: appears across 2+ domains (not a one-off statement), can predict positions on new questions (has predictive power), not something any smart person would think (has exclusivity). All three required.

**3. Build the skill** — 3–7 mental models + 5–10 decision heuristics + expression DNA + values & anti-patterns + honest limits, written into SKILL.md.

**4. Quality validation** — test with 3 questions the person publicly answered; the direction must match. Then test with 1 question they never addressed; the skill should show appropriate uncertainty rather than false confidence.

Full methodology in `references/extraction-framework.md`.

---

## Repository Structure

```
nvwa-skill/
├── SKILL.md                      # Nvwa core
├── references/
│   ├── extraction-framework.md   # Extraction methodology (read this to go deeper)
│   └── skill-template.md         # Template for generating skills
└── examples/                          # 13 characters + 1 topic, with full research data
    ├── steve-jobs-perspective/        # ⭐ Jobs (includes real conversation records)
    ├── paul-graham-perspective/       # Paul Graham
    ├── zhang-yiming-perspective/      # Zhang Yiming
    ├── andrej-karpathy-perspective/   # Karpathy
    ├── ilya-sutskever-perspective/    # Ilya Sutskever
    ├── trump-perspective/             # Trump
    ├── mrbeast-perspective/           # MrBeast
    ├── elon-musk-perspective/         # Musk
    ├── munger-perspective/            # Charlie Munger
    ├── feynman-perspective/           # Feynman
    ├── naval-perspective/             # Naval Ravikant
    ├── taleb-perspective/             # Taleb
    ├── zhangxuefeng-perspective/      # Zhang Xuefeng
    └── x-mastery-mentor/             # X Mentor (topic skill)
```

The research process is fully transparent. Each example includes complete research files — you can see how information was collected, filtered, and turned into mental models. The Jobs example also includes a complete real conversation (on AI hardware, OpenAI vs Anthropic, Apple's path), showing how the skill performs in multi-turn deep dialogue.

---

## The Story Behind It

[colleague-skill](https://github.com/titanwings/colleague-skill) recently exploded on GitHub — distilling departing colleagues into AI skills, crossing 5,000 stars in days. It proved one thing: distilling a person is completely viable.

Since we have the ability to distill people, why stop at colleagues nearby? Go distill the best minds in every field. And fortunately, these people usually left behind vast amounts of distillable material — books, talks, interviews, social media. This is an enormous enhancement to your own thinking.

I've been doing something like this for a while — not distilling colleagues, but Munger, Feynman, Naval, Musk, Taleb. Today I'm open-sourcing the methodology.

Nvwa doesn't copy people. It extracts cognitive operating systems.

**Nvwa (女娲)**, the goddess in Chinese mythology who created humans from clay. Here the clay is public information, and what's created is not a person — it's a mirror.

---

## About the Author

**小码哥 xmg2024** — AI Native Coder

## License

MIT — use it, modify it, build with it.

---

<div align="center">

**colleague-skill** distills what a person does.<br>
**Nvwa** distills how a person thinks.<br><br>
*The next person you want to distill doesn't have to be a colleague.*

<br>

MIT License © [小码哥 xmg2024](https://github.com/xmg2024)

</div>
