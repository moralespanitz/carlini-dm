# Carlini Framework — Reference

Detailed criteria, scoring guidance, and cross-domain applications for the seven dimensions.

Source: Nicholas Carlini, "How to win a best paper award (or, an opinionated take on how to do important research that matters)", 2026.

---

## Dimension 1: Impact

**Core idea:** The most important skill in research (or any high-stakes work) is good taste in what problems are worth solving. If you have good taste and keep working, you'll eventually do something of consequence. Bad taste produces a hundred papers/projects no one reads.

**Scoring signals:**
- Strong: "This changes how the field approaches X", "This unblocks Y for Z people", "In five years this will be the canonical approach"
- Weak: "It fills a gap", "It extends prior work", "It would be useful"
- Null: Cannot articulate who benefits or why it matters now

**Cross-domain:**
- Research: would change how the community thinks about a problem
- Engineering: unblocks a meaningful capability or removes a painful bottleneck
- Product: creates real behavior change in users, not just a feature

**Carlini test:** Write your best-case conclusion before doing any work. If that conclusion is "our method performs 3% better than baselines", ask whether that's the most important thing you could be doing.

---

## Dimension 2: Uniqueness

**Core idea:** "Do something only you can do." Not because no one else could ever do it, but because your particular combination of skills, knowledge, and timing gives you a meaningful head start. Ideas are cheap; execution is hard. Whoever does it first gets disproportionate credit.

**Scoring signals:**
- Strong: specific technical skill + domain knowledge combination no one else has right now; clear 6-12 month head start
- Weak: "I have capacity", "it hasn't been done yet", "I'm interested in it"
- Null: a dozen people could do this equally well next month

**Cross-domain:**
- Research: first to combine fields X and Y; world expert in a niche that just became relevant
- Engineering: team has internal tooling/data/context that makes this uniquely efficient
- Product: proprietary distribution or user relationship that creates a moat

**Carlini note:** Being on the "critical path" of scientific or technical discovery is partly luck. But you can increase your surface area by reading widely, working with diverse collaborators, and working at the intersection of fields.

---

## Dimension 3: Comparative Advantage

**Core idea:** The skill space is high-dimensional. Find the corner where your specific mix of abilities makes you unusually effective — not just adequate.

**Carlini's self-example:** Not a theory-builder or proposer of new directions, but skilled at bringing clarity and order to fuzzy fields. Not the first to find adversarial examples, but laid the groundwork for proper evaluation.

**Types of comparative advantage (non-exhaustive):**
- Theory-builder: develops new frameworks and ways of thinking
- Problem-solver: proves/disproves specific claims rigorously
- Field-bridger: brings ideas from distant domains together
- Clarity-bringer: takes a confused area and makes it legible
- Executor: takes known ideas and does them better than anyone else

**Scoring signals:**
- Strong: "This is exactly the type of problem I've solved before in a different context", natural pull toward the approach
- Weak: "I could learn it", doing it because the domain is hot
- Null: someone else is clearly better positioned and more motivated

---

## Dimension 4: De-risking

**Core idea:** Start with the sub-problem most likely to fail. Don't build the polished version when a prototype will answer whether the core idea works. Most good ideas die on contact with reality.

**Carlini's principle:** He starts ~5x as many papers as he finishes. The ones he drops aren't necessarily bad — they just didn't survive contact with the key assumption.

**Scoring signals:**
- De-risked: core bet has been tested; remaining work is execution
- Partially de-risked: some validation, but key unknowns remain
- Not de-risked: spent time on comfortable easy parts, core assumption untested

**Questions to surface:**
- What's the one thing that would make this not work?
- Have you tested that yet?
- If you spent the next week only on the hardest thing, what would you learn?

**Cross-domain:**
- Research: does the attack/method/algorithm actually work in principle?
- Engineering: does the technical approach handle the hard edge cases?
- Product: do users actually have the problem you think they have?

---

## Dimension 5: Kill / Pivot Signals

**Core idea:** Kill papers/projects that aren't working. Also kill ones that are technically working but have low impact. Opportunity cost is real and the distribution of returns is exponential.

**Three kill types:**
1. **Core doesn't work** — the riskiest assumption failed. Kill fast.
2. **Core works but impact is low** — turn it into a workshop paper/blog post; don't invest further.
3. **Opportunity cost killed it** — something better came along. Pivot immediately. Don't fall for sunk cost.

**Carlini's heuristic:** "Even if you're 90% of the way through a 'just ok' project, the marginal return on spending the last 10% to finish it versus spending that same 10% on a paper 100x more important makes the latter the clear winner."

**Kill signals:**
- Rationalizing diminishing returns
- "It's almost there" as the answer for months
- Excitement about a new idea but staying on the old one out of guilt
- Reviewer/stakeholder feedback that reveals the core premise isn't accepted

**Pivot signals:**
- Core idea works, but application/framing is wrong
- Better audience or domain exists for the same contribution
- Related problem is more important and you're 70% of the way there

---

## Dimension 6: Timing

**Core idea:** Ideas can be too early (world doesn't accept the premise) or too late (field has moved on). The window matters. Being six months earlier than the field on an important problem has outsized impact because communities form habits early.

**Too early signals:**
- Reviewers/stakeholders keep rejecting the premise, not the execution
- You're right but can't get traction
- The underlying technology/behavior doesn't exist yet at scale

**Too late signals:**
- Three papers/products doing this just shipped
- Community has "settled" on a different approach
- Your contribution is incremental on top of an established canon

**Right time signals:**
- Field is young enough that you can define how it's done
- The premise has just become accepted by a critical mass
- A platform shift (new model capability, new regulation, new user behavior) just opened the window

**Carlini's example:** Adversarial ML was on the critical path when he entered. Now it's mature; new directions need exploring.

---

## Dimension 7: Effort-to-Impact Ratio

**Core idea:** Great work doesn't have poorly executed experiments or half-finished arguments. But over-engineering a marginal idea is also a trap. The project should be at a local optimum — satisfying when finished.

**Under-investment signals:**
- Obvious improvements left undone that a reader will notice
- Questions a skeptical reader would ask, unanswered
- "Good enough to ship" applied to things that actually matter

**Over-investment signals:**
- Running every conceivable experiment instead of the ones that prove the core claim
- Scope creep that dilutes the singular idea
- Polish on things that don't affect the conclusion

**Carlini's principle:** "Run the experiment that answers the skeptical reader's question before they ask it." But also: "every experiment should connect to the core idea."

**The local optimum test:** After finishing, can a reader who disagrees with you find something essential that's missing? If yes, you're under-invested. If they find themselves wanting a third appetizer (nice to have but not essential), you're at the optimum.

---

## Anti-Patterns (from the article)

| Anti-pattern | Description |
|---|---|
| Minimum viable contribution | "What's the least I can write that technically counts as a paper?" Doomed to mediocrity. |
| Bad-idea inheritance | Reading too much literature before forming your own view; subconsciously accepting wrong approaches as correct |
| Sunk cost trap | Finishing a poor project because you've already invested in it |
| Shiny object distraction | Abandoning good work for new ideas that sound exciting just because they're new |
| Adequate ambition | Writing papers with the goal of being accepted rather than the goal of mattering |
| Over-reliance on luck | Assuming that if you're skilled, results will come — without managing the distribution actively |

---

## Cross-Domain Application Examples

### Software Engineering
- Impact: does this unblock a meaningful capability or remove real pain?
- Uniqueness: does your team's context/codebase knowledge give you a head start?
- Kill signal: refactor that's 50% done but the codebase has moved on
- Timing: is the platform stable enough that this abstraction will last?

### Product Management
- Impact: does this change user behavior, or is it a feature that gets used once?
- Comparative advantage: does your team have distribution/data no one else has?
- De-risking: have you tested the assumption that users have this problem?
- Timing: is this a "vitamin" (nice to have) or a "painkiller" (must have)?

### Research
- Impact: would this change how the field thinks, not just the leaderboard number?
- Uniqueness: what's your head start in months over the next person?
- Kill signal: the community doesn't accept the premise (may be timing, may be wrong)
- Effort ratio: is this the maximal version, or are obvious extensions left undone?
