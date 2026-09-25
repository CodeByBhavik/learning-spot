# 0003 — Framework modules drill differently from vocabulary modules

**Date:** 2026-09-26 (~01:00)
**Topic:** ISM Modules 3 and 4, MCQ/True-False prep

## The observation

Two modules, same format, same night, very different results on first exposure:

- **Module 3 (Design Thinking): 11/12** — including all three deliberate traps
- **Module 4 (Industry 4.0): 10/14** — every miss a pure vocabulary item

I predicted Module 4 would be harder before either quiz, and the prediction held.

## Why

**Module 3 is a *framework* module.** Fixed ordered lists (5 stages), fixed sets
(4 empathy quadrants, 7 SCAMPER letters, 3 lenses), each with internal logic.
You can *reason* toward a forgotten answer: empathise must precede define,
because you cannot frame a problem you have not yet observed.

**Module 4 is a *vocabulary* module.** Digital twin, IoT, CPS, IaaS/PaaS/SaaS,
AR/VR, additive manufacturing — arbitrary term-to-definition pairings with no
connective logic. Nothing to reason from. You either hold the mapping or you
don't.

## Consequence for how to drill each

- **Framework modules:** teach the structure once, then test the order and the
  traps. Cheap.
- **Vocabulary modules:** need a **concrete anchor per term**, not a definition.
  Abstract definitions did not survive even ten minutes with him.

The anchors that worked:

- **AR/VR** — the letter mnemonic ("A for Adds, V for Vanishes") **failed**; he
  flipped it again minutes later. The **device** anchor worked:
  *phone → AR, headset → VR.* Physical and concrete beats alphabetical.
- **IaaS/PaaS/SaaS** — the pizza ladder (frozen pizza in your oven / delivery to
  your table / a restaurant), plus the identity question *"who are you when you
  use this — sysadmin, developer, or end user?"*
- **Digital twin** — a jet engine spinning in the real world and its live copy
  spinning on a screen.

## Root cause of the SaaS error specifically

He classified Gmail as PaaS because **"platform" carries an everyday meaning**
("Gmail is a platform") that collides with its technical meaning (a *development*
platform). Worth checking for other terms where ordinary usage fights the
technical definition — that collision, not ignorance, caused the error.

## Generalisable

Diagnose module type before drilling. Reasoning-based content can be taught
thin; arbitrary mappings need a concrete image each, and mnemonics built on
letters are the weakest option available. See also
[[numeric-labels-are-not-always-regression]] — again, a neat verbal rule lost to
a concrete counterexample.
