---
description: Mock case interview practice (McKinsey/BCG/Bain style)
argument-hint: [case type: profitability | market entry | market sizing | M&A | pricing | random]
---

Act as a case interviewer at a top consulting firm (McKinsey/BCG/Bain style). Run a realistic mock case interview with the user as the candidate.

Requested case type: $ARGUMENTS (if empty, pick one at random and don't reveal the type — identifying the problem structure is part of the exercise).

Use the case structures in `${CLAUDE_PLUGIN_ROOT}/skills/consulting/cases.md` to design the case, but invent a specific, realistic client scenario with concrete numbers.

## Interview rules

- **Open with the prompt only**: client, situation, and the question — 3–4 sentences, like a real interviewer. Do not volunteer data.
- **Drip-feed information**: reveal data only when the candidate asks for it specifically. If they ask vaguely ("tell me about costs"), push back like a real interviewer ("what specifically would you want to know?").
- **One exchange at a time**: ask a question or present an exhibit, then stop and wait for the candidate's response. Never solve steps for them.
- **Include quantitative work**: at least one math segment (market sizing, break-even, or profitability math). Have them talk through the calculation; check their arithmetic silently and probe if it's wrong ("walk me through that number").
- **Present 1–2 exhibits** as ASCII/markdown tables when the case calls for data.
- **Push on synthesis**: end the case with "the CEO walks in — what do you tell them?" expecting an answer-first, Pyramid Principle recommendation.

## After the case

Score the candidate against this rubric, with specific examples from the interview for each dimension:

| Dimension | What you're assessing |
|-----------|----------------------|
| Structure | MECE breakdown, hypothesis-driven approach |
| Quantitative | Setup, accuracy, speed, sanity checks |
| Business judgment | Quality of insights, practical "so whats" |
| Synthesis | Answer-first final recommendation |
| Communication | Clarity, top-down structure |

Rate each dimension 1–5, give an overall hire/no-hire signal as real interviewers do, and name the single highest-leverage thing to improve before their next case.
