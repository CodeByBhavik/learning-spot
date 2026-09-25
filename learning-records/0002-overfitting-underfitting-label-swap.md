# 0002 — Overfitting / underfitting: labels swapped, concept intact

**Date:** 2026-09-25
**Topic:** Overfitting & Underfitting

## What happened

Given accuracy pairs, Bhavik answered:

- 98% train / 61% test → said **underfitting** (correct: overfitting)
- 55% train / 53% test → said **overfitting** (correct: underfitting)

Both reversed. **But in the same message he correctly identified Student B —
the textbook-memoriser who aces practice and fails the real exam — as
overfitting.**

## Diagnosis

This was **not** a conceptual failure. The analogy was intact and correctly
applied; only the mapping from *pattern of scores* → *name* was inverted. A
wiring error between two correct representations, not a missing understanding.

Supporting tell: he justified the 55/53 case with "it also learnt the noise."
Learning noise *requires* memorising the training set, which forces training
accuracy **high**. His own reasoning contradicted the number in front of him.

## The fix that worked

Point at his own contradiction rather than re-explaining the concept: *you said
Student B is overfitting; Student B scores high-then-low; that is the 98/61 row.*
Letting him collide with his own correct answer is faster and stickier than
re-teaching.

Then anchor the names to their literal meaning:

- **OVER**fitting = fits the training data **too much** → memorises it →
  **high train, low test**
- **UNDER**fitting = fits the data **too little** → learned nothing →
  **low train, low test**

Compressed hook: **"Over = too good on training. Under = bad at everything."**

## Generalisable lesson

When he holds a correct intuition *and* a wrong label simultaneously, the repair
is to **surface the contradiction**, not to re-explain. Same failure mode as
[[numeric-labels-are-not-always-regression]], where he also had the right answer
and talked himself out of it. Twice now: **his intuition outperforms his recall
of stated rules.** Teach him to check answers against the analogy, not against a
memorised rule.

## Exam relevance

Very high. "Given these accuracies, identify the problem" is a standard question
format, and the swap would cost the whole mark despite genuine understanding.

---

## Follow-up — same session, ~00:30

Re-tested cold, roughly 90 minutes after the original error and with no access to
notes. Answer: *"underfitting where everything is trash, and overfitting means
good on training but fails on real tests."*

**Correct, and in his own compressed language.** The literal-meaning anchor
("over = fits too much, under = fits too little") held. Confirms the diagnosis:
the original failure was a label-wiring problem, not a conceptual gap — once the
names were tied to their plain meaning it corrected in one pass and survived a
delay plus three intervening topics.
