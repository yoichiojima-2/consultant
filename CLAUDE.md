# Consultant

A Claude Code plugin providing 50+ consulting frameworks used by top firms (McKinsey, BCG, Bain, Accenture).

## Project Structure

```
commands/
├── consult.md         # /consult — full engagement flow on a problem
├── analyze.md         # /analyze — PESTEL → 5 Forces → SWOT/3C analysis
└── case-practice.md   # /case-practice — mock case interview with scoring
skills/consulting/
├── SKILL.md           # Entry point
├── problem-solving.md # MECE, Pyramid, Issue Tree, McKinsey 7-Step, SCQ
├── strategy.md        # Porter's 5 Forces, SWOT, BCG, PESTEL, Blue Ocean, VRIO
├── cases.md           # Profitability, Market Sizing, M&A, Pricing, Market Entry
├── design.md          # Business Model Canvas, Design Thinking, Customer Journey
├── projects.md        # WBS, RACI, Kotter's 8 Steps, OKRs, Balanced Scorecard
├── finance.md         # ROI, NPV, IRR, Payback, Break-even
├── operations.md      # Lean, Six Sigma, 5 Whys, Fishbone, PDCA
└── templates/         # Ready-to-use templates
```

When versions change, keep `.claude-plugin/plugin.json` and
`.claude-plugin/marketplace.json` in sync (CI enforces this).

## Adding New Frameworks

1. Identify the appropriate category file in `skills/consulting/`
2. Add framework with: Purpose, Structure/Diagram, How to Use, Example
3. Update the Framework Index table in SKILL.md
4. Add to Quick Framework Selection if commonly used

## Conventions

- Use ASCII diagrams for visual frameworks (no images)
- Include practical examples with each framework
- Keep descriptions actionable, not academic
- Reference other frameworks when they combine well

## Commit Messages

Do not include AI-generated attribution in commit messages.
