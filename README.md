# carlini-dm

A Claude Code skill that turns Nicholas Carlini's research decision-making methodology into a structured framework you can invoke anytime you're deciding what to work on, whether to kill a project, or how to prioritize competing ideas.

## How it works

You invoke `/carlini-dm`, describe what you're deciding, and Claude walks you through seven dimensions — one question at a time. Not a checklist to justify work you've already decided to do. A framework that forces honest answers.

At the end you get a one-sentence verdict and one concrete next action.

It works for research, engineering, product decisions, and general prioritization — the framework is domain-agnostic.

## The Seven Dimensions

1. **Impact** — If this succeeds, what specifically changes? Who cares, and why now?
2. **Uniqueness** — What makes this something only you can do right now?
3. **Comparative advantage** — Does this play to your specific strengths?
4. **De-risking** — Have you tested the riskiest assumption first — or the easiest parts?
5. **Kill / Pivot signals** — Should you kill, pivot, or double down?
6. **Timing** — Is the world ready? Is the window opening or closing?
7. **Effort-to-impact ratio** — Is this the maximal version, or are you over/under-investing?

> "One excellent paper is worth a thousand mediocre ones, and takes less time to write." — Carlini

## Installation

### Claude Code

```bash
/plugin marketplace add moralespanitz/carlini-dm
/plugin install carlini-dm@carlini-dm
```

### Manual (personal skill)

```bash
git clone https://github.com/moralespanitz/carlini-dm
ln -s $(pwd)/carlini-dm/.claude/skills/carlini-dm ~/.claude/skills/carlini-dm
```

## Usage

```
/carlini-dm
```

Describe what you're deciding. Claude asks one question per dimension, then delivers a direct recommendation.

## The Source

This skill is a direct adaptation of Nicholas Carlini's article:

**[How to win a best paper award (or, an opinionated take on how to do important research that matters)](https://nicholas.carlini.com/writing/2026/how-to-win-a-best-paper-award.html)** — published 2026-03-09.

![Carlini's article](assets/preview.png)

The article covers coming up with good research ideas, executing them well, writing them up clearly, and navigating what happens afterwards. The framework in this skill is drawn from the first two sections — idea selection and project management — and adapted for use beyond academic research.

## Who is Nicholas Carlini?

Nicholas Carlini is a researcher working at the intersection of machine learning and computer security, currently at Anthropic studying what bad things you could do with, or do to, language models. Previously a research scientist at Google Brain (2018–2023) and DeepMind (2023–2025). He holds a Ph.D. from UC Berkeley under David Wagner.

His papers have received best paper awards at IEEE S&P, USENIX Security (twice), and ICML (three times), and have been covered by the New York Times, the BBC, Nature, Science, Wired, and Popular Science.

More at [nicholas.carlini.com](https://nicholas.carlini.com).

## Philosophy

- **Taste over throughput** — one excellent decision is worth a hundred mediocre ones
- **Kill fast** — sunk cost is the enemy of impact
- **De-risk first** — test the riskiest assumption before the easiest parts
- **Focus on the distribution** — the outcome is a sample; control what you can control

## License

MIT
