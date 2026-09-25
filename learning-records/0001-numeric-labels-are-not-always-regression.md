# 0001 — Numeric labels are not always regression

**Date:** 2026-09-25
**Topic:** Supervised learning — classification vs regression

## The misconception

Asked to classify "Which denomination is this currency note?", Bhavik answered
**regression**. The reasoning was implicit but clear: the possible answers are
₹10, ₹20, ₹50 — those are *numbers*, and the rule he had been given was
"numbers → regression."

Notably, he had **already got this right** minutes earlier using his own
folder analogy (sub-folders for ₹10/₹20/₹50 = classification). The knowledge was
there; the rule I gave him overwrote his correct intuition.

## Why my original rule failed

I taught: *"Is the answer a category or a quantity?"* That rule is fine for
`spam/not-spam` and `house price`, but it collapses the moment a **category is
written using digits**. Denominations, star ratings, jersey numbers and postal
codes are all numerals that are not quantities.

The rule was too surface-level — it keyed on the *appearance* of the label
rather than its *structure*.

## The corrected rule

> **Does a value "in between" two possible answers make sense?**

- ₹15 note → does not exist → **Classification**
- ₹62.5 lakh house → perfectly normal → **Regression**

Equivalent formulation that also works: *can you list every possible answer on
paper?* Listable → classification. Infinite → regression.

## Wider lesson about how to teach him

A heuristic that is easy to state but leaky will **overwrite** correct intuition
he already holds. He trusts a stated rule over his own reasoning. So heuristics
given to him must be **robust at the edges**, not merely convenient — otherwise
they actively do damage.

Also worth noting: he had the right answer first, then talked himself out of it.
This matches [[trusting-his-own-correct-answers]] — his confidence gap is a
recurring failure mode independent of his knowledge gaps.

## Exam relevance

High. "Numeric-looking categories" is a standard examiner trap, and a
"differentiate classification and regression" question is very likely on
tomorrow's paper.
