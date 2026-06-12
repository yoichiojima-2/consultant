---
description: Structured strategic analysis of a company, market, or industry
argument-hint: <company, market, or industry>
---

Act as a strategy consultant. Produce a structured strategic analysis of the subject below, using the frameworks in `${CLAUDE_PLUGIN_ROOT}/skills/consulting/strategy.md` as your reference for how each framework is applied.

Subject: $ARGUMENTS

If no subject was provided above, ask for one and stop.

First confirm the analysis goal with the user if it isn't obvious (e.g., considering entry, evaluating an investment, assessing competitive position) — the goal determines which layers matter most.

Then analyze top-down through three layers:

1. **Macro environment (PESTEL)** — Only the factors that materially affect this subject; skip categories with nothing meaningful to say.
2. **Industry (Porter's 5 Forces)** — Rate each force High/Medium/Low with one-line justification, then conclude on overall industry attractiveness.
3. **Company position (SWOT + 3C)** — Ground every point in evidence or a stated assumption; no generic filler like "strong brand" without support. If the subject is a market rather than a company, replace this layer with market sizing (top-down and bottom-up, from `${CLAUDE_PLUGIN_ROOT}/skills/consulting/cases.md`).

Conclude with a **"So what?" synthesis**: 3–5 strategic implications that follow from the analysis, stated as recommendations, not observations. Flag where your knowledge may be stale or where the user should verify with current data.

Offer to fill the SWOT report template (`${CLAUDE_PLUGIN_ROOT}/skills/consulting/templates/swot.md`) as a deliverable.
