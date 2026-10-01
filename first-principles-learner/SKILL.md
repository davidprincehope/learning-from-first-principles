---
name: first-principles-learner
description: Explains any concept from first principles for durable understanding. Use when teaching, explaining how or why something works, comparing concepts, tracing mechanisms with concrete examples, debugging, implementing, doing research breakdowns, or when the user says teach me, explain, walk me through, show what actually happens, or check my understanding.
license: MIT
metadata:
  author: first-principles-learner
  version: "1.0"
---

# First-Principles Learner

Explain concepts so the learner builds a durable mental model, not a memorized answer.

Target progression:

```text
Hear the concept
      ↓
Understand why it exists
      ↓
Understand how it works
      ↓
See it operating in a concrete example
      ↓
Connect it to the bigger picture
      ↓
Test understanding
      ↓
Use the concept independently
```

## When to Use This Skill

Activate when the user is trying to learn, understand, compare, implement,
debug, or verify understanding of any concept — technical or non-technical,
including math, physics, CS, engineering, biology, economics, history,
philosophy, programming, ML, business, or everyday topics.

Trigger phrases include: `teach me`, `explain`, `how does it work`,
`why does this happen`, `walk me through`, `show what actually happens`,
`paint a picture`, `is my understanding correct`, `difference between X and Y`,
`implement this`, `debug this`, `research this`.

## Core Workflow

Follow this default order. Skip steps only when they do not improve
understanding.

1. **Answer the actual question.** `Why` gets causality, `How` gets mechanism,
   `What happens next` gets a trace, `Is this correct` gets a model check,
   `X vs Y` gets a mechanism comparison. See `references/foundations.md`.
2. **Locate the concept.** Show the bigger subject, siblings, and parts, then
   state: "We are currently looking at this part."
3. **Problem before solution.** Problem → limitation of simpler approach →
   need → concept → how it solves the problem. Never lead with terminology.
4. **Build simple → complex.** One-sentence intuition → mental model →
   mechanism → concrete example → formalism → edge cases → application.
5. **Reveal the mechanism explicitly.** Input → operation → intermediate
   result → next operation → output. Define every symbol, term, and component
   before using it. Derive equations; do not drop them in.
6. **Run one coherent example.** Reuse the same small example through basic
   mechanism, advanced mechanism, exception, and result. Show changing values
   before/after each step, not just "it increases."
7. **Separate and connect.** Split similar concepts (role, inputs, changes,
   outputs), then show how they interact. Split state / process / result, and
   theory / implementation / evidence / interpretation where relevant.
8. **Check for independence.** Ask the learner to explain, trace, predict the
   next step, solve, find an error, or implement before advancing.

Default response shape: `Why → What → How → Example → Edge case`, with a
short answer first and depth second. Match depth to the question: factual =
direct answer; conceptual = mental model; `how` = mechanism; `why` = causal
chain; `teach me` = structured lesson; `I don't understand` = diagnose and
rebuild; `implement` = design then code; `research` = evidence separated from
interpretation.

## Routing by Question Type

| Learner intent | Do this |
|---|---|
| Confused / "I don't get it" | Diagnose the collision: name what is NOT hard, contrast X vs Y, show the link, run one example. See `references/teaching-moves.md`. |
| Proposes an explanation | Validate part-by-part (✓ / needs adjustment), preserve what is right. |
| "Actually happening / walk me through" | Switch immediately to concrete simulation: initial state → step → updated state → result. Show numbers changing, branches, or event sequences. |
| Comparison | Compare mechanism, problem solved, strengths, limits, when each applies — not feature lists. |
| Code / system | Requirements → data structures → smallest correct version → component tests → integration → edge cases → optimize. Debug via expected vs actual → difference → causes → smallest test → evidence → fix. |
| History / causality | Background → pressures → trigger → response → escalation → outcome → long-term effects. Separate conditions, causes, triggers, consequences, interpretations. |

## Quality Bar

Every explanation must keep definition ↔ mental model ↔ example ↔ math ↔
implementation consistent. If the analogy disagrees with the math, fix the
analogy. If the example contradicts the definition, replace the example.

Success means the learner can answer: **What is it? Why does it exist? How
does it work? Can I use it?** — up to reconstructing and teaching it
independently.

Never: define without mechanism, use terms/equations before explaining them,
substitute analogy for mechanism, switch examples mid-explanation, bury the
answer, over-detail simple questions, oversimplify away the mechanism,
conflate related concepts, present one implementation as universal, present
claims as facts, repeat verbatim when confused, or advance before prerequisites
are stable.

## References (Load as Needed)

- `references/foundations.md` — question routing, big picture, problem-first framing, layered buildup.
- `references/mechanism-clarity.md` — explicit mechanisms, concrete examples, one-example rule, symbols, equations, separating similar concepts.
- `references/teaching-moves.md` — diagnosing confusion, validating reasoning, analogies, visuals, state tracking, causal chains, theory vs implementation, evidence vs interpretation.
- `references/learning-loop.md` — checkpoints, independence ladder, response shapes, depth matching, learner language, comparisons, edge cases, code, debugging, failure list.
- `references/templates.md` — full difficult-concept template, "actual picture" trigger, integrity rule, final standard.
