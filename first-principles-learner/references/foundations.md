# Foundations: Routing, Context, Motivation, Layering

## 1. Start From the Learner's Actual Question

Answer the question actually asked, not the surrounding topic.

- "Why does this happen?" → causality, not just a definition.
- "How does this work?" → mechanism, not just purpose.
- "What exactly happens next?" → trace the process step by step.
- "Is my understanding correct?" → evaluate their mental model directly,
  part by part.
- "What is the difference between X and Y?" → compare mechanisms, roles,
  assumptions, and outcomes directly.

## 2. Start With the Big Picture

Before details, show where the concept fits:

```text
Bigger subject
│
├── Concept A
├── Concept B
│
└── Concept being learned
      ├── Part 1
      ├── Part 2
      └── Part 3
```

Then state: "We are currently looking at this part." Never leave the
learner with isolated facts and no map.

## 3. Explain the Problem Before the Solution

Always motivate before mechanizing:

```text
Problem
   ↓
Limitation of simpler approach
   ↓
Need for a new idea
   ↓
Concept
   ↓
How the concept solves the problem
```

Example — database index:

```text
Problem: Searching a huge table row-by-row is expensive.
Need: Find records without examining every row.
Idea: Create an additional data structure organized for fast lookup.
Result: The database locates relevant records much faster.
```

The learner must feel the need before meeting the terminology.

## 4. Build From Simple to Complex

Use progressive layers; never advance before the current layer is stable.

- **Layer 1 — One-sentence intuition.** Simplest accurate explanation.
- **Layer 2 — Mental model.** What the learner should picture.
- **Layer 3 — Mechanism.** Exactly how it works.
- **Layer 4 — Concrete example.** Run the mechanism on an actual case.
- **Layer 5 — Formalism.** Equations, terminology, diagrams, rules, code.
- **Layer 6 — Edge cases.** Where the simple model breaks down.
- **Layer 7 — Application.** How the concept is actually used.
