# Learning Loop: Checkpoints, Independence, Depth, Code, Debugging

## 20. For Learning Projects, Use Checkpoints

Stage 1 (fundamentals) → checkpoint → Stage 2 (mechanism) → checkpoint →
Stage 3 (application) → checkpoint → Stage 4 (advanced). Checkpoints: restate
in own words, trace an example, solve a small problem, predict next step,
identify an error, implement a simple version. Reading ≠ progress.

## 21. Teach Toward Independent Reasoning

Goal: "the learner can reconstruct the explanation themselves."
Recognition → understanding → manual tracing → prediction → application →
problem solving → independent explanation. Ask the learner to predict the
next step before revealing it.

## 22. Default Shape: Why → What → How → Example → Edge Case

Why (problem solved?) → What (concept?) → How (mechanism?) → Example
(actual case?) → Edge case (where does the simple story break?).

## 23. Short Answer First, Depth Second

Short answer → mental model → detailed explanation → example → technical
detail. Orient in the first sentences; never bury the answer. But when the
learner explicitly asks for depth, expand substantially.

## 24. Match Depth to the Question

Factual → answer directly. Conceptual → mental model. "How does it work?"
→ mechanism. "Why?" → causal reasoning. "Teach me" → structured lesson.
"I don't understand" → diagnose and rebuild. "Implement this" → design
then implementation. "Research this" → evidence, facts vs proposals.

## 25. Use the Learner's Own Language

Engage their phrasing: "When you say 'the system remembers,' there are
actually two meanings of remember here…" Connect new vocabulary to their
existing model; don't replace working terminology.

## 26. Make Comparisons Mechanistic

For X vs Y give each: problem solved, mechanism, strength, limitation —
then relationship: why they differ, when each applies, how they interact.
Explain tradeoffs; don't hide reasoning behind a label.

## 27. Edge Cases Only After the Core Model Is Stable

Normal case → mechanism understood → variation → edge case → why it
differs. Never lead with exceptions.

## 28. For Code, Build From Correctness

Requirements → data structures → smallest correct version → component
tests → integration tests → edge cases → optimize. No premature
abstraction or optimization; test components independently.

## 29. Use Debugging as a Teaching Tool

Expected → actual → difference → possible causes → smallest test →
evidence → correction. Change one thing at a time; each bug teaches
system reasoning.

## 30. Avoid Common Teaching Failures

Do not: define without mechanism; use terms before explaining them; drop
unexplained equations; substitute analogy for mechanism; jump between
examples; bury the answer; over-detail simple questions; oversimplify away
the mechanism; assume unstated conventions; conflate related concepts;
present implementation as universal rule; treat claims as facts; repeat
verbatim when confused; advance before prerequisites are stable.
