# Notes on teaching Bhavik

## How he wants to be taught (his own words, 25 Sep 2026)

- **Do NOT info-dump.** "if u give me out the whole information and all i will be
  much more confused" — large blocks of text actively hurt him.
- **Conversational loop is his explicit request:** "lets like talk till i
  understand the whole thing... then i will attempt to write it on my own in
  rough words."
- So the loop is: small chunk → I ask him a checking question → he answers →
  feedback → next chunk. He produces, I correct.
- He is honest about his level when asked directly. Use that.

## Starting level (25 Sep 2026)

- Topic 1 (What is ML): "basic idea" — has a rough sense, can't structure it
- Topic 2 (Supervised/Unsupervised/Reinforcement): **zero** — "idk anything"
- Topic 3 (Overfitting/Underfitting): one-line understanding, "cannot expand it
  at all" — knows the words, not the substance

## Style preferences observed

- Casual register, calls me "bro" — match his energy, don't be stiff
- Wants to be tested, not lectured
- Values knowing *why* something is being taught in a given order

## Working notes

- Teach Topic 1 first even though it's his strongest: it supplies the vocabulary
  (data, model, training, prediction, labels) that Topics 2 and 3 depend on.
  Doing it first makes the other two much cheaper to teach.
- Everything should be shaped as "points you could write in the exam", because
  that is the literal output format he is assessed on.

## Explicit requests from Bhavik (25 Sep 2026)

- **Always announce topic transitions loudly.** He gets disoriented when we move
  on without a clear marker. Use a visible banner: "MOVING TO TOPIC X".
- **Re-give the material when transitioning.** Don't rely on him scrolling up to
  find what I taught earlier in the session — restate it fresh at the point of
  use, then ask the question.
- He worries we are moving too fast. Counter-move that worked: show him the
  *question-variant table* — map every likely phrasing of an exam question onto
  the material he already has. Seeing "5 of 6 covered" calmed him down and made
  the one genuine gap obvious and worth fixing.
- He finds "difference between" reasoning to be common sense. Fine — so for
  those, teach the **table format**, not the content. The format is the
  deliverable; the content he can generate himself.
- **Ask "ready to move on?" before every transition.** His request. He wants a
  gate where he can raise confusion before it gets buried under new material.
- **He distrusts his own correct answers.** He got a regression/classification
  pair right, then argued against his own answer because the framing felt odd.
  When he pushes back, first check whether he was actually right — often he was.
  Name that explicitly; the confidence gap is as big a problem as any knowledge
  gap.
- **Priority order he needs stated out loud:** concept > real-world example >
  algorithm names. He was anxious about memorising algorithm lists; telling him
  they are the lowest priority visibly reduced the load.
- Abstract definitions are not landing on their own. **Concrete data tables**
  (actual rows and columns with a visible label column) work much better for
  making "labelled data" tangible.

## Session 1 results (25–26 Sep 2026, ~21:50–01:10)

**AI mock test, from memory, no notes:**

| Topic | Score | Notes |
|---|---|---|
| Q1 What is ML | ~5.5/7 | Merged bullets (lost marks); "banking industry" too vague |
| Q2 Supervised | ~6/7 | Algorithm names wrong: "logical regression", "KVM" |
| Q2 Unsupervised | 7/7 | Best answer of the night |
| Q2 Reinforcement | 4/7 | Blanked on the 5 components and pos/neg definitions |
| Q3 Over/underfitting | pass | Re-tested cold after ~90 min — correct |

**ISM:** Module 3 = 11/12 · Module 4 = 10/14

### Recurring patterns worth carrying forward

- **He merges bullets and loses marks.** Content is right; presentation costs
  him. Remind him: one bullet = one mark, split everything.
- **He is vague where he should be specific.** "Banking industry" instead of
  "fraud detection"; Netflix *and* Spotify as two applications. Name the
  **task**, not the sector or the brand.
- **Algorithm names are his weakest recall** — logistic/logical, KNN/KVM. Lowest
  priority for marks, but flag it if there is ever spare time.
- **Letter-based mnemonics do not work on him.** Concrete physical anchors do.
  See [[ism-vocabulary-vs-framework-modules]].
- **He answers fast and accurately when quizzed**, then doubts himself
  afterwards. The confidence gap, not the knowledge gap, is his main risk.

### For next session (post-exam)

- Ask how the two exams actually went; update [[MISSION]] — the current mission
  expires after 26 Sep and will need rewriting around whatever he wants next.
- Reinforcement learning is the thinnest topic; if AI continues as a subject,
  start there.
