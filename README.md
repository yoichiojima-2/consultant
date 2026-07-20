# Consultant

A Claude Code plugin packaging 50+ consulting frameworks used by top firms (McKinsey, BCG, Bain, Accenture) as a skill plus three slash commands.

## Installation

```bash
# Add marketplace
/plugin marketplace add yoichiojima-2/consultant

# Install plugin
/plugin install consulting@consultant
```

## Frameworks Included

| Category | Frameworks |
|----------|------------|
| **Problem-Solving** | MECE, Pyramid Principle, Issue Tree, McKinsey 7-Step, SCQ, Storyboarding, 80/20 |
| **Strategic Analysis** | McKinsey 7S, Porter's 5 Forces, SWOT, BCG Matrix, PESTEL, Ansoff, GE-McKinsey, Blue Ocean, VRIO |
| **Case Frameworks** | Profitability, Market Sizing, M&A, Pricing, Market Entry |
| **Business Design** | Business Model Canvas, Design Thinking, Customer Journey, STP |
| **Project & Change** | WBS, RACI, Kotter's 8 Steps, ADKAR, OKRs, Balanced Scorecard |
| **Financial Analysis** | ROI, NPV, IRR, Payback, Break-even, Sensitivity Analysis |
| **Operations** | Lean, Six Sigma, 5 Whys, Fishbone, PDCA, Pareto |

## Commands

| Command | What it does |
|---------|--------------|
| `/consult <problem>` | Full consulting engagement: clarify → hypothesis → issue tree → analysis → pyramid-structured recommendation |
| `/analyze <company or market>` | Layered strategic analysis: PESTEL → Porter's 5 Forces → SWOT/3C → "so what" implications |
| `/case-practice [type]` | Mock case interview (McKinsey/BCG/Bain style) with exhibits, math, and a scored debrief |

## Usage

Try asking:

- `/consult our SaaS churn doubled last quarter — what should we do?`
- `/analyze the Japanese convenience store industry`
- `/case-practice profitability`
- "Size the market for EV charging stations in Germany"
- "Help me structure this recommendation for my exec presentation"

The skill also activates automatically when you:
- Analyze business problems
- Develop strategy
- Structure presentations
- Evaluate M&A opportunities
- Size markets
- Improve profitability
- Manage projects
- Drive organizational change

## How it works

Everything is a markdown skill — no runtime code.

- [`skills/consulting/SKILL.md`](skills/consulting/SKILL.md) is the entry point: its frontmatter description tells Claude when to activate, and the body sets behavior (hypothesis-first, pick 1–3 frameworks, end with "so what?") plus a selection guide mapping question types to frameworks.
- The frameworks live in seven category files (`strategy.md`, `cases.md`, `finance.md`, …) that Claude reads on demand, so the full ~3,400 lines of framework content never sit in context at once.
- [`commands/`](commands/) defines the three slash commands as prompt templates over the same skill.
- [`skills/consulting/templates/`](skills/consulting/templates/) holds five fill-in deliverables (SWOT report, business case, project charter, RACI, Business Model Canvas) the skill offers to complete.
- CI ([`validate.yml`](.github/workflows/validate.yml)) validates the plugin manifests, keeps the two version fields in sync, and checks every relative markdown link.

## License

MIT
