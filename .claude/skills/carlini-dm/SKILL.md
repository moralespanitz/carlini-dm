---
name: carlini-dm
description: Structured decision framework for evaluating and ranking ideas, projects, and priorities. Based on Nicholas Carlini's research methodology. Use when explicitly invoked to decide what to work on, rank competing options, whether to continue or kill a project, or how to prioritize.
disable-model-invocation: true
---

# Carlini Decision Framework

A structured decision framework for evaluating and ranking ideas, projects, and priorities — adapted from Nicholas Carlini's methodology for high-impact work.

> "One excellent paper is worth a thousand mediocre ones, and takes less time to write." — Carlini

## How to Use This Skill

When invoked, ask the user to describe what they're deciding. This could be:

- **A single idea** — should I pursue this?
- **Multiple options** — I have 5 startup ideas, which should I pick?
- **An active project** — should I kill, pivot, or double down?
- **A priority call** — I have limited time, what matters most?

For detailed criteria and scoring rubrics, see [references/framework.md](references/framework.md).

---

## Process

### For multiple options (2+)

1. **List all options.** Ask the user to briefly describe each one.
2. **Quick elimination round.** Score each option across all 10 dimensions using a rapid 3-point scale (Strong / Weak / Null). Present as a comparison table. This should be fast — the goal is to eliminate obvious losers, not deliberate on each.
3. **Cut the bottom half.** Any option that scores Null on Impact, Uniqueness, or Focus is eliminated immediately. These are non-negotiable.
4. **Deep-dive the top 2-3.** Walk through each surviving option in detail, one dimension at a time, asking targeted questions.
5. **Rank and recommend.** Deliver a final ranking with reasoning. One concrete next action per top option.

### For a single idea or active project

1. Walk through the 10 dimensions, asking one question per dimension.
2. Deliver the verdict: Continue / Kill / Pivot / De-risk first / Practice (craft work).
3. One concrete next action.

---

## The Ten Dimensions

### 1. Impact
**Question:** "If this succeeds wildly, what specifically changes? Who cares, and why now?"

Write your best-case conclusion before doing any work. If the only thing you can say is "the number went up by 2%", it probably doesn't matter. The answer should be articulable in one sentence that would make a peer say "I wish I'd done that."

Not every project needs to be a home run. Carlini: "writing good-enough papers is what helps me discover the ideas that lead to important ones." If this is craft work — practice that sharpens your skills for bigger things — that's a valid score, but name it honestly.

Red flags: "it would be useful", "fills a gap", no concrete beneficiary.

---

### 2. Uniqueness
**Question:** "What makes this something only you — or only your team — could do right now? How many months ahead are you?"

Ideas are cheap; execution is hard. The magnitude of your contribution is measured by counting the months between when you ship and when the next person would have. If the answer is "anyone could do this next week", the contribution is thin.

Writing something high-quality early has outsized impact — people settle on "how things are done" early, and altering a field's direction is harder than starting it right.

Red flags: "it's not done yet", "I have time", no articulated edge, a dozen people could do this equally well.

---

### 3. Comparative Advantage
**Question:** "Does this play to your specific strengths — the corner of the skill space where you might be world-class?"

The skill space is high-dimensional. You are probably the best in the world at some specific corner of it. Find that corner. Types of advantage:

- **Theory-builder:** develops new frameworks
- **Problem-solver:** proves/disproves specific claims rigorously
- **Field-bridger:** brings ideas from distant domains together
- **Clarity-bringer:** takes a confused area and makes it legible
- **Executor:** takes known ideas and does them better than anyone

Red flags: "I could learn it", "it's a hot area so I should do it", doing it because someone else is.

---

### 4. Knowledge & Independence
**Question:** "How well do you understand the existing landscape? And — critically — are you thinking independently from it?"

You must deeply understand what exists. You can't fix what you don't understand. But once you've read everything, forget it. Everything already done has already been done. If you only think about what's been done, you'll never do something new.

Every field has bad ideas that became conventions — someone famous got something wrong and everyone followed. If you pay too much attention to how the field does things, you'll subconsciously accept wrong approaches as correct.

Red flags: can't explain what exists and why, OR slavishly following the field's conventions without questioning them.

---

### 5. De-risking
**Question:** "What's the riskiest assumption? Have you tested it yet — or are you working on the easy parts first?"

Start with the sub-problem most likely to fail. Don't build the polished version when a prototype will tell you whether the core idea works. Carlini starts ~5x as many projects as he finishes.

Fail fast: if the prototype shows promise, clean it up later. If it doesn't, you've saved yourself months.

Red flags: months of work with no test of the core bet, "I'll get to the hard part later", comfort-driven work order.

---

### 6. Collaboration Leverage
**Question:** "Do you have — or can you get — the right people for this? What skills are you missing?"

No one does great work in isolation. Good collaborators catch your mistakes, push back on bad ideas, bring skills you don't have, and give you someone to think with.

Collaboration is more accessible than people think. A cold email with a partial solution to a problem someone cares about is surprisingly effective. Share ideas freely — most people won't steal them because they already have more ideas than time.

Red flags: solo effort on a team-sized problem, missing critical skills with no plan to fill them, hoarding ideas out of fear.

---

### 7. Timing
**Question:** "Is the world ready for this? Is the window opening, open, or closing?"

Ideas that are too early get rejected because stakeholders don't believe the premise yet. Ideas that are too late mean you're following. Being six months earlier than the field on the right problem has outsized impact.

Your overall impact = your skill multiplied by how important the area is right now. Being very good at a less important problem still beats being mediocre at the hot thing.

Red flags: "everyone is doing this now" (late), "no one gets why this matters" (possibly too early — or wrong), the underlying technology doesn't exist at scale yet.

---

### 8. Focus
**Question:** "Can you state this in one sentence? Does every part of the work connect to that one idea?"

A project should advance a single idea, expressible in as few words as possible. If you try to communicate many ideas, the audience remembers none.

Every experiment, feature, or deliverable should connect to the core idea. If you're struggling to describe it in one sentence, the project is trying to do too much. Fix the cause, not the symptom.

Red flags: "it does X and Y and also Z", scope that can't be summarized, no clear singular contribution.

---

### 9. Communication Potential
**Question:** "Can this be explained compellingly? Will people understand why it matters — not just what it does?"

The most-read work in any field isn't the most technically sophisticated — it's the most approachable. A great idea poorly communicated has lower effective impact. Carlini's membership inference paper is cited not because the method is best, but because it explained the problem better than anyone before.

Meet the audience where they are. Tell a story: start with what they believe, guide them to where your idea makes sense, then explain your contribution. If your idea is heretical, lay evidence so the audience arrives at the conclusion themselves.

Red flags: can't explain it to a smart non-expert, "the work speaks for itself", no story connecting problem to solution.

---

### 10. Kill / Persist
**Question:** "If you're honest — should you stop, continue, or double down? And is something better competing for your time?"

Three kill types:
1. **Core doesn't work** — the riskiest assumption failed. Kill fast.
2. **Core works but impact is low** — downscope to a blog post; don't invest further.
3. **Opportunity cost** — something better came along. The exponential distribution of impact means even 90%-done mediocre work should sometimes be abandoned for 10%-started great work.

But persistence matters too. Most of Carlini's best-paper-award work was rejected at least once. One paper was rejected four times before winning. If you're right and the world isn't ready, be persistent — but make the argument sharper each time.

Red flags: "I've put too much in to stop" (sunk cost), "it's almost there" for months, OR giving up on something right just because it's hard to sell.

---

## Delivering the Recommendation

### For multiple options
Present a comparison table:

| Option | Impact | Unique | Advantage | Knowledge | De-risk | Team | Timing | Focus | Comms | Kill/Persist |
|--------|--------|--------|-----------|-----------|---------|------|--------|-------|-------|-------------|
| A      | Strong | Strong | Weak      | Strong    | None    | ...  | ...    | ...   | ...   | ...         |
| B      | Weak   | Null   | ...       | ...       | ...     | ...  | ...    | ...   | ...   | ...         |

Then:
1. **Eliminate** options with Null on Impact, Uniqueness, or Focus
2. **Rank** survivors by strongest overall signal
3. **Recommend** top 1-2 with reasoning
4. **One concrete next action** per recommended option

### For a single idea
1. **Top 2-3 strongest signals** (positive or negative)
2. **One-sentence verdict**: Continue / Kill / Pivot / De-risk first / Practice (craft work)
3. **One concrete next action**

---

## Verdicts

- **Continue** — signals are strong; execute with urgency
- **Kill** — core doesn't work, impact is low, or something better is available
- **Pivot** — core works but framing/application/audience is wrong
- **De-risk first** — promising but untested; spend one week on the hardest assumption
- **Practice** — won't be a home run but builds craft, skills, or positioning for something bigger

Don't hedge. Be direct, honest, focused on what matters. If signals are mixed, say so — but still give a recommendation.

---

## What This Framework Is Not

- Not a checklist to justify work you've already decided to do
- Not a way to make every idea sound good
- Not a substitute for taste — it helps articulate taste, not replace it
- Not deterministic — luck matters, but you control the distribution

> "Focus on the distribution. The award, if it comes, is just someone noticing where your distribution ended up." — Carlini
