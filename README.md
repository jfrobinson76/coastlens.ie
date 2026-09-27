# CoastLens

**Before a storm, a council knows the weather. It does not know which stretch of its own coast needs attention first. CoastLens answers that, 250 metres at a time.**

![CoastLens, coastal storm-impact console for County Wexford](screenshot.jpg)

## Why I built it

My entry into the TechIreland National AI Challenge 2026, with teammates Eddie Heffernan and Eduard Dreyer (Team Sunny SouthEast). Councils get broad storm warnings, then have to decide where a handful of crews go first. The evidence to answer that exists, scattered across agencies and decades. We set out to show AI agents can gather it, and a council can still trust the answer, because the AI never touches the physics.

## What's under the hood

- **250 m coastal stretches.** Each with its own baseline, so an alert points at a place a crew can drive to.
- **Published physics, not AI guesswork.** A deterministic engine names the likely storm impact on each stretch, hour by hour.
- **AI agents keep the evidence current,** and every value is labelled measured or modelled.
- **A person approves what leaves.** Outputs are operational, never engineering advice.

## Where it stands

A working prototype, and it says so. Live at [coastlens.ie](https://coastlens.ie). Source: private.

---

Team Sunny SouthEast: Eddie Heffernan, Eduard Dreyer and John Robinson
