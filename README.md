# carlini-dm

A Claude Code skill that applies Nicholas Carlini's decision-making framework to help you evaluate ideas, projects, and priorities.

> "One excellent paper is worth a thousand mediocre ones, and takes less time to write." — Nicholas Carlini

## What It Does

When you invoke `/carlini-dm`, Claude walks you through a structured evaluation of whatever you're deciding — an idea to pursue, a project to continue or kill, or competing priorities to sort. It applies seven dimensions drawn from Carlini's methodology:

1. **Impact** — If this succeeds, what specifically changes?
2. **Uniqueness** — What makes this something only you can do right now?
3. **Comparative advantage** — Does this play to your specific strengths?
4. **De-risking** — Have you tested the riskiest assumption first?
5. **Kill / Pivot signals** — Should you kill, pivot, or double down?
6. **Timing** — Is the world ready? Is the window closing?
7. **Effort-to-impact ratio** — Is this the maximal version, or are you over/under-investing?

At the end, you get a one-sentence verdict and one concrete next action.

Works for research, software engineering, product decisions, and general prioritization.

## Installation

### From marketplace

```bash
/plugin marketplace add <your-github-username>/carlini-dm
/plugin install carlini-dm@carlini-dm
```

### Manual (personal skill)

Clone this repo and symlink the skill:

```bash
git clone https://github.com/<your-github-username>/carlini-dm
ln -s $(pwd)/carlini-dm/.claude/skills/carlini-dm ~/.claude/skills/carlini-dm
```

## Usage

```
/carlini-dm
```

Then describe what you're deciding. Claude will ask one question per dimension and deliver a recommendation.

## Credit

Framework adapted from Nicholas Carlini's article: ["How to win a best paper award (or, an opinionated take on how to do important research that matters)"](https://nicholas.carlini.com/writing/2026/how-to-win-a-best-paper-award.html) (2026).

## License

MIT
