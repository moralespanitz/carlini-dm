# Carlini Framework — Reference

Detailed criteria, scoring guidance, and cross-domain applications for the ten dimensions.

Source: Nicholas Carlini, ["How to win a best paper award (or, an opinionated take on how to do important research that matters)"](https://nicholas.carlini.com/writing/2026/how-to-win-a-best-paper-award.html), 2026.

---

## Scoring Scale

Each dimension uses a 3-point scale:

| Score | Meaning |
|-------|---------|
| **Strong** | Clear positive signal. This dimension actively supports pursuing the option. |
| **Weak** | Ambiguous or concerning. Not a dealbreaker alone, but accumulates. |
| **Null** | No signal or actively negative. On Impact, Uniqueness, or Focus this is an instant elimination. |

---

## Dimension 1: Impact

**Core idea:** The most important skill is good taste in what problems are worth solving. If you have good taste and keep working, you'll eventually do something of consequence. Bad taste produces a hundred projects no one cares about.

**Carlini test:** Write your best-case conclusion before doing any work. If that conclusion is "our method performs 3% better than baselines", ask whether that's the most important thing you could be doing.

**Scoring signals:**
- Strong: "This changes how the field approaches X", "This unblocks Y for Z people", "In five years this will be the canonical approach"
- Weak: "It fills a gap", "It extends prior work", "It would be useful"
- Null: cannot articulate who benefits or why it matters now

**The craft work exception:** Not every project needs to be a home run. Carlini: "writing good-enough papers is what helps me discover the ideas that lead to important ones." If this is deliberate practice — building skills or positioning for something bigger — score it as Weak-with-intent, not Null. But be honest about which category it falls in.

**Cross-domain:**
- Research: would change how the community thinks about a problem
- Engineering: unblocks a meaningful capability or removes a painful bottleneck
- Product: creates real behavior change in users, not just a feature
- Startup: addresses a problem people will pay to solve, not just acknowledge

---

## Dimension 2: Uniqueness

**Core idea:** "Do something only you can do." Not because no one else could ever do it, but because your particular combination of skills, knowledge, and timing gives you a meaningful head start. Ideas are cheap; execution is hard. Whoever does it first gets disproportionate credit.

**Scoring signals:**
- Strong: specific skill + domain knowledge combination no one else has right now; clear 6-12 month head start
- Weak: "I have capacity", "it hasn't been done yet", "I'm interested in it"
- Null: a dozen people could do this equally well next month

**Early mover advantage:** Writing something high-quality early has outsized impact. People settle on "how things are done" early, and altering a field's direction is much harder than starting it right. Especially when fields are young, being six months earlier can be exceptionally valuable.

**Cross-domain:**
- Research: first to combine fields X and Y; world expert in a niche that just became relevant
- Engineering: team has internal tooling/data/context that makes this uniquely efficient
- Product: proprietary distribution or user relationship that creates a moat
- Startup: unique insight from lived experience that outsiders can't replicate

---

## Dimension 3: Comparative Advantage

**Core idea:** The skill space is high-dimensional. Find the corner where your specific mix of abilities makes you unusually effective — not just adequate.

**Carlini's self-example:** Not a theory-builder or proposer of new directions, but skilled at bringing clarity and order to fuzzy fields. Not the first to find adversarial examples, but laid the groundwork for proper evaluation. Takes ideas from distant fields and connects them (differential cryptanalysis → model stealing).

**Types of comparative advantage (non-exhaustive):**
- **Theory-builder:** develops new frameworks and ways of thinking
- **Problem-solver:** proves/disproves specific claims rigorously
- **Field-bridger:** brings ideas from distant domains together
- **Clarity-bringer:** takes a confused area and makes it legible
- **Executor:** takes known ideas and does them better than anyone
- **Storyteller:** makes complex work approachable and widely read

**Scoring signals:**
- Strong: "This is exactly the type of problem I've solved before in a different context", natural pull toward the approach
- Weak: "I could learn it", doing it because the domain is hot
- Null: someone else is clearly better positioned and more motivated

**Cross-domain:**
- Research: which type of contribution matches your strengths?
- Engineering: is this a systems problem and you're a systems person? Or are you forcing it?
- Startup: does your background give you unfair insight into this market?

---

## Dimension 4: Knowledge & Independence

**Core idea:** You must deeply understand what exists — you can't fix what you don't understand. BUT once you've read everything, form your own view independent of the field's conventions.

**Carlini's three reading modes:**
1. **Scanning:** "Is this useful? What's the one new thing?" — most papers
2. **Extracting:** "What technique/setup/result do I need from this?" — related work
3. **Deep reading:** "Could I reproduce this? What assumptions did they make? What errors?" — a few per month

**The independence paradox:** Every field has bad ideas that became conventions. Someone famous published something wrong, and everyone followed. If you pay too much attention to how the field does things, you subconsciously accept wrong approaches as correct. Carlini's membership inference work succeeded because he formed his own view *before* reading the existing literature's approach, then targeted his argument after understanding what everyone else was doing.

**Scoring signals:**
- Strong: deep understanding of landscape AND clear independent thesis that departs from convention where needed
- Weak: understands the landscape but follows it uncritically, OR has an independent view but hasn't done the reading
- Null: doesn't understand what exists, or is completely captured by the field's bad conventions

**Cross-domain:**
- Research: have you read the key papers AND identified where the field got something wrong?
- Engineering: do you understand existing solutions AND see a fundamentally better approach?
- Startup: do you know the competitive landscape AND have a contrarian thesis about where it's going?

---

## Dimension 5: De-risking

**Core idea:** Start with the sub-problem most likely to fail. Don't build the polished version when a prototype will answer whether the core idea works. Most good ideas die on contact with reality.

**Carlini's principle:** He starts ~5x as many projects as he finishes. The ones he drops aren't necessarily bad — they just didn't survive contact with the key assumption.

**Scoring signals:**
- Strong (de-risked): core bet has been tested; remaining work is execution
- Weak (partially de-risked): some validation, but key unknowns remain
- Null (not de-risked): spent time on comfortable easy parts, core assumption untested

**Questions to surface:**
- What's the one thing that would make this not work?
- Have you tested that yet?
- If you spent the next week only on the hardest thing, what would you learn?

**Cross-domain:**
- Research: does the method/algorithm/attack actually work in principle?
- Engineering: does the technical approach handle the hard edge cases?
- Product: do users actually have the problem you think they have?
- Startup: will people pay for this? Have you asked them?

---

## Dimension 6: Collaboration Leverage

**Core idea:** No one does great work in isolation. Good collaborators catch your mistakes, push back on bad ideas, bring skills you don't have, and give you someone to think with.

**Carlini on cold outreach:** "If you email someone a solution to a problem they appear interested in, you're far more likely to get a reply than if you just send 'I love your work, can we collaborate?' The probability someone will respond increases dramatically with the amount of time you put into sending it."

**Carlini on sharing ideas:** "Ideas are cheap; execution is hard. Most people already have far more ideas than time to pursue them. So share your ideas more freely!"

**Scoring signals:**
- Strong: right team assembled or clearly available; complementary skills covered; active thought partners
- Weak: working solo but could recruit; missing one key skill
- Null: solo effort on a team-sized problem; missing critical skills with no plan to fill them; hoarding ideas out of fear

**Cross-domain:**
- Research: do you have co-authors who cover your blind spots?
- Engineering: does the team have all the skills this requires?
- Startup: do the founders complement each other? Who's missing?

---

## Dimension 7: Timing

**Core idea:** Ideas can be too early (world doesn't accept the premise) or too late (field has moved on). The window matters. Being six months earlier on the right problem has outsized impact.

**The skill-importance product:** Your overall impact = your skill in an area × how important that area is right now. Being very good at a less important problem still beats being mediocre at the hot thing. But you need to be honest about whether the area's importance is rising or falling.

**Carlini's example:** He became one of the few security researchers studying ML just as ML became the most important area in tech. That was luck — but it was also positioning.

**Scoring signals:**
- Strong (right time): field is young enough to define conventions; premise just became accepted; platform shift just opened the window
- Weak (uncertain): could go either way; premise is plausible but unproven
- Null (too early): underlying technology doesn't exist at scale yet; no one accepts the premise
- Null (too late): three competitors just shipped; community settled on a different approach; your contribution is incremental

**Cross-domain:**
- Research: is this the right moment for this problem, or is the field saturated?
- Engineering: is the platform stable enough that this abstraction will last?
- Startup: is this a vitamin (nice to have) or a painkiller (must have) right now?

---

## Dimension 8: Focus

**Core idea:** A project should advance a single idea, expressible in as few words as possible. If you try to communicate many ideas, the audience remembers none.

**Carlini:** "Every experiment should connect to the core idea. Every paragraph and every figure you'll eventually write should be directly attributable to the goal." He writes down the core idea before starting, to avoid losing sight of it.

**The title test:** If you're struggling to describe the project in one sentence, it's trying to do more than one thing. Fix the cause, not the symptom.

**Scoring signals:**
- Strong: one sentence captures the entire contribution; every component serves that sentence
- Weak: core idea exists but scope has bloated; "and also" keeps appearing
- Null: cannot articulate a singular contribution; project is actually 3 projects wearing a trenchcoat

**Cross-domain:**
- Research: can you state the contribution in one sentence?
- Engineering: does this solve one problem well, or three problems poorly?
- Product: does this have one clear value proposition?
- Startup: can you explain it in a tweet?

---

## Dimension 9: Communication Potential

**Core idea:** The most-read work isn't the most technically sophisticated — it's the most approachable. A great idea poorly communicated has lower effective impact. The way you present something determines whether anyone actually engages with it.

**Carlini's membership inference paper:** Cited not because the method is best (it's been surpassed), but because it explained the problem better than anyone before. "The fact that our paper is approachable and readable means it's now one of the canonical papers people point to."

**Storytelling structure:** Meet the audience where they are (what they already believe), guide them into the world where your idea makes sense, then explain your contribution. If the idea is heretical, lay out evidence so the audience arrives at the conclusion themselves — don't state it outright or they'll dismiss it.

**Know your reader:** Carlini writes for "the six-month-younger version of myself — what would I have needed to hear to explain why this idea was good?"

**Scoring signals:**
- Strong: compelling story from problem to solution; audience can be identified; "so what?" has a powerful answer
- Weak: technically sound but hard to explain; no clear narrative; audience unclear
- Null: can't explain it to a smart non-expert; no story; "the work speaks for itself"

**Cross-domain:**
- Research: can you write an abstract with a specific number that makes people want to read more?
- Engineering: can you write a one-page design doc that convinces skeptics?
- Product: can you demo this in 60 seconds and have someone say "I want that"?
- Startup: can you pitch this in 2 minutes to someone who doesn't know your field?

---

## Dimension 10: Kill / Persist

**Core idea:** Kill projects that aren't working, AND kill projects that are working but have low impact. But also: persist when you're right and the world isn't ready yet. The hard part is knowing which is which.

**Three kill types:**
1. **Core doesn't work** — the riskiest assumption failed. Kill fast.
2. **Core works but impact is low** — downscope to a blog post/side project; don't invest further.
3. **Opportunity cost** — something better came along. Pivot immediately. "Even if you're 90% of the way through a 'just ok' project, the marginal return on spending the last 10% to finish it versus spending that same 10% on a project 100x more important makes the latter the clear winner."

**But persistence matters:** Most of Carlini's best-paper-award work was rejected at least once. One was rejected four times. The pattern: paper says something outside what's believed → rejected → authors sharpen the argument → resubmitted when idea is slightly less heretical → wins award.

**Beware shiny objects:** New ideas always sound more exciting than ones you've been working on for months. It's easy to get distracted by something new just because it's new. Distinguish genuine opportunity-cost pivots from shiny-object syndrome.

**Scoring signals:**
- Strong (continue): core works, impact validated, no better alternative competing for time
- Strong (kill): clear signal that core doesn't work, or something dramatically better is available
- Weak: mixed signals; rationalizing in either direction
- Null: deep in sunk-cost spiral, or abandoning good work for shiny objects

---

## Anti-Patterns (from the article)

| Anti-pattern | Description | Which dimensions it violates |
|---|---|---|
| Minimum viable contribution | "What's the least I can do that technically counts?" | Impact, Focus |
| Bad-idea inheritance | Following the field's conventions without questioning them | Knowledge & Independence |
| Sunk cost trap | Finishing a poor project because you've invested in it | Kill/Persist |
| Shiny object distraction | Abandoning good work for new ideas just because they're new | Kill/Persist, Focus |
| Adequate ambition | Goal is acceptance, not impact | Impact |
| Over-reliance on luck | Assuming results will come without managing the distribution | All — luck is a multiplier, not a strategy |
| Lone wolf syndrome | Doing team-sized work alone out of ego or fear | Collaboration |
| Convention capture | Reading so much literature that you can't think independently | Knowledge & Independence |
| Comfort-driven work order | Working on the easy parts first, avoiding the risky core | De-risking |
| "The work speaks for itself" | Assuming quality is enough without clear communication | Communication |

---

## Cross-Domain Quick Reference

### Research
| Dimension | Key question |
|---|---|
| Impact | Would this change how the field thinks, not just the leaderboard? |
| Uniqueness | What's your head start in months? |
| Comparative advantage | Theory-builder, problem-solver, clarity-bringer, or field-bridger? |
| Knowledge & Independence | Have you read everything AND formed your own view? |
| De-risking | Does the method work in principle? |
| Collaboration | Do co-authors cover your blind spots? |
| Timing | Is the community ready to accept the premise? |
| Focus | Can you state the contribution in one sentence? |
| Communication | Can you write an abstract that makes people want to read more? |
| Kill/Persist | Is rejection about your execution or their readiness? |

### Software Engineering
| Dimension | Key question |
|---|---|
| Impact | Does this unblock a meaningful capability or remove real pain? |
| Uniqueness | Does your team's codebase/context knowledge give a head start? |
| Comparative advantage | Is this a systems problem and you're a systems person? |
| Knowledge & Independence | Do you understand existing solutions AND see a better approach? |
| De-risking | Does the technical approach handle the hard edge cases? |
| Collaboration | Does the team have all the skills this requires? |
| Timing | Is the platform stable enough that this abstraction will last? |
| Focus | Does this solve one problem well, or three problems poorly? |
| Communication | Can you write a design doc that convinces skeptics? |
| Kill/Persist | Has the codebase moved on while you were refactoring? |

### Startup / Product
| Dimension | Key question |
|---|---|
| Impact | Will people pay to solve this problem? |
| Uniqueness | What moat do you have that competitors don't? |
| Comparative advantage | Does your background give unfair insight into this market? |
| Knowledge & Independence | Do you know the landscape AND have a contrarian thesis? |
| De-risking | Have you talked to customers? Will they pay? |
| Collaboration | Do the founders complement each other? Who's missing? |
| Timing | Is this a painkiller right now, or a vitamin? |
| Focus | Can you explain it in a tweet? |
| Communication | Can you pitch this in 2 minutes to a non-expert? |
| Kill/Persist | Are you in a sunk-cost spiral, or is the market not ready yet? |
