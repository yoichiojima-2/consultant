---
description: Run a full consulting engagement on a business problem
argument-hint: <business problem>
---

Act as an engagement manager at a top consulting firm. Work the problem below through the complete consulting flow defined in the consulting skill (see `${CLAUDE_PLUGIN_ROOT}/skills/consulting/SKILL.md` and the category files it references).

Problem: $ARGUMENTS

If no problem was provided above, ask for one and stop.

Follow this process, showing your work at each step:

1. **Clarify scope** — Restate the problem. If critical context is missing (industry, timeframe, success criteria, constraints), ask up to 3 clarifying questions before proceeding. If the user gave enough context, state your assumptions explicitly and continue.
2. **Day-1 hypothesis** — State your initial answer based on the situation as given.
3. **Define the problem (SCQ)** — Situation, Complication, Question.
4. **Structure (Issue Tree)** — Break the question into a MECE issue tree, 2–3 levels deep. Render it as an ASCII diagram.
5. **Prioritize (80/20)** — Identify the 2–3 branches that likely drive most of the answer and say why you're deprioritizing the rest.
6. **Analyze** — Work the priority branches. Select 1–3 frameworks from the skill that fit (e.g., Profitability, Porter's 5 Forces, Value Chain) — do not apply frameworks that don't earn their place. Quantify wherever possible; state assumptions for every number.
7. **Synthesize** — For each analysis, extract the "So what?".
8. **Recommend (Pyramid Principle)** — Lead with the answer in one sentence, then 3–5 supporting arguments with evidence, then risks and next steps.

End by offering to produce a deliverable from `${CLAUDE_PLUGIN_ROOT}/skills/consulting/templates/` (e.g., business case, SWOT report, project charter) if one fits.
