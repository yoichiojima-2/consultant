---
name: consulting
description: Apply consulting methodologies from McKinsey, BCG, Bain, and Accenture for structured problem-solving and strategic analysis. Use whenever the user asks for business advice or analysis — analyzing a business problem, developing or reviewing a strategy or business plan, structuring a presentation or executive summary, evaluating M&A or an investment, sizing a market, setting prices, improving profitability or operations, prioritizing initiatives, managing a project, driving organizational change, or preparing for a case interview — even if they never mention a framework or the word "consulting."
allowed-tools: Read, Grep, Glob, Write
---

# Consulting Frameworks

Comprehensive methodologies used by top consulting firms (McKinsey, BCG, Bain, Accenture) for problem-solving, strategy, and business transformation.

## How to Consult

When applying this skill, act like an engagement manager, not an encyclopedia:

0. **Match effort to the ask.** A quick question deserves a focused answer built on one well-chosen framework — not the full engagement flow. Reserve the complete flow below for `/consult` or when the user asks for a deep dive. Depth should come from the user's problem, not from the skill.
1. **Clarify before analyzing.** If the problem is vague, ask up to 3 questions about scope, success criteria, and constraints — or state your assumptions explicitly and proceed.
2. **Lead with a Day-1 hypothesis.** State your initial answer early, then use analysis to test it. Don't survey frameworks hoping an answer emerges.
3. **Pick 1–3 frameworks, not many.** Choose the ones that fit the question (use the Quick Framework Selection below) and apply them deeply. Listing frameworks is not analysis.
4. **Show your structure.** Render issue trees and matrices as ASCII diagrams so the user can challenge the breakdown. Keep every breakdown MECE.
5. **Quantify wherever possible.** Rough numbers with stated assumptions beat qualitative hand-waving. Sanity-check estimates top-down and bottom-up.
6. **End every analysis with "So what?"** Conclusions must be recommendations the user can act on, not observations. Structure final answers with the Pyramid Principle: answer first, then 3–5 supporting arguments.
7. **Offer a deliverable.** When a [template](templates/) matches the work (SWOT report, business case, project charter, RACI, BMC), offer to fill it in.

## Framework Categories

| Category | Frameworks | File |
|----------|------------|------|
| **Problem-Solving** | MECE, Pyramid Principle, Issue Tree, Hypothesis-Driven, McKinsey 7-Step, SCQ, Storyboarding, 80/20 | [problem-solving.md](problem-solving.md) |
| **Strategic Analysis** | McKinsey 7S, Porter's 5 Forces, SWOT, BCG Matrix, 3C, 4P, Value Chain, PESTEL, Ansoff, GE-McKinsey, Blue Ocean, VRIO, Porter's Generic Strategies | [strategy.md](strategy.md) |
| **Case Frameworks** | Profitability, Market Sizing, M&A/Due Diligence, Pricing, Market Entry | [cases.md](cases.md) |
| **Business Design** | Business Model Canvas, Design Thinking, Customer Journey, STP | [design.md](design.md) |
| **Project & Change** | WBS, RACI, Kotter's 8 Steps, ADKAR, Risk Matrix, Stakeholder Analysis, Balanced Scorecard, OKRs, McKinsey Horizons | [projects.md](projects.md) |
| **Financial Analysis** | ROI, NPV, IRR, Payback, Break-even, Unit Economics (LTV/CAC), Sensitivity Analysis, Business Case | [finance.md](finance.md) |
| **Operations** | Lean (8 Wastes, 5S), Six Sigma (DMAIC), Process Mapping, Root Cause (5 Whys, Fishbone), Pareto, PDCA | [operations.md](operations.md) |

## Quick Framework Selection

### "I need to solve a complex problem"
→ **McKinsey 7-Step Process** + **MECE** + **Issue Tree**
See: [problem-solving.md](problem-solving.md)

### "I need to structure a presentation"
→ **Pyramid Principle** + **SCQ** + **Storyboarding**
See: [problem-solving.md](problem-solving.md)

### "I need to analyze a company or market"
→ **PESTEL** (macro) + **Porter's 5 Forces** (industry) + **SWOT** (company) + **3C** (positioning)
See: [strategy.md](strategy.md)

### "I need to evaluate growth options"
→ **Ansoff Matrix** + **GE-McKinsey Matrix** + **BCG Matrix**
See: [strategy.md](strategy.md)

### "I need to create a new strategy"
→ **Blue Ocean** + **VRIO** + **Porter's Generic Strategies**
See: [strategy.md](strategy.md)

### "Why are profits declining?"
→ **Profitability Framework** (Revenue × Volume breakdown)
See: [cases.md](cases.md)

### "How big is this market?"
→ **Market Sizing** (Top-down + Bottom-up)
See: [cases.md](cases.md)

### "Should we acquire this company?"
→ **M&A Framework** + **Due Diligence** + **Synergy Analysis**
See: [cases.md](cases.md)

### "What price should we set?"
→ **Pricing Framework** (Cost-plus, Value-based, Competitive)
See: [cases.md](cases.md)

### "Should we enter this market?"
→ **Market Entry Framework** + **Porter's 5 Forces** + **Profitability**
See: [cases.md](cases.md)

### "I'm designing a new product or business"
→ **Business Model Canvas** + **Design Thinking** + **Customer Journey**
See: [design.md](design.md)

### "I'm managing a project"
→ **WBS** + **RACI** + **Risk Matrix** + **Stakeholder Analysis**
See: [projects.md](projects.md)

### "I'm driving organizational change"
→ **Kotter's 8 Steps** + **ADKAR** + **Stakeholder Analysis**
See: [projects.md](projects.md)

### "I need to set goals and measure performance"
→ **OKRs** + **Balanced Scorecard** + **KPIs**
See: [projects.md](projects.md)

### "I need to make an investment decision"
→ **NPV** + **IRR** + **Payback** + **Sensitivity Analysis**
See: [finance.md](finance.md)

### "Is this business model viable? Are customers profitable?"
→ **Unit Economics (LTV/CAC)** + **Break-even**
See: [finance.md](finance.md)

### "I need to improve operations"
→ **Process Mapping** + **Root Cause Analysis** + **Lean** + **Six Sigma**
See: [operations.md](operations.md)

## The Complete Consulting Flow

```
1. RECEIVE PROBLEM
   └── Clarify scope and success criteria
              ↓
2. CREATE DAY-1 ANSWER
   └── Initial hypothesis based on experience
              ↓
3. DEFINE PROBLEM (SCQ)
   └── Situation, Complication, Question
              ↓
4. STRUCTURE (MECE + Issue Tree)
   └── Break into testable components
              ↓
5. PRIORITIZE (80/20)
   └── Focus on high-impact branches
              ↓
6. BUILD WORKPLAN
   └── Who, what, when, how
              ↓
7. STORYBOARD (Ghostpack)
   └── Design the end deliverable
              ↓
8. CONDUCT ANALYSES
   └── Test hypotheses with data
              ↓
9. SYNTHESIZE ("So What?")
   └── Extract insights and implications
              ↓
10. STRUCTURE COMMUNICATION (Pyramid)
    └── Answer-first, supporting arguments
              ↓
11. PRESENT & DELIVER
    └── Communicate, get approval, implement
```

## Framework Combinations

### Strategic Planning
```
PESTEL → Porter's 5 Forces → 3C → SWOT → Issue Tree → Recommendations
```

### New Market Entry
```
Market Sizing → Porter's 5 Forces → 3C → Market Entry Framework → Financial Analysis
```

### M&A Evaluation
```
Strategic Rationale → Target Analysis → Due Diligence → Synergies → Valuation → Integration Plan
```

### Business Turnaround
```
Profitability Analysis → Root Cause → Value Chain → Cost Reduction → Quick Wins → Transformation Roadmap
```

### Product Launch
```
Market Sizing → STP → Business Model Canvas → Pricing → Go-to-Market → OKRs
```

### Transformation Program
```
Current State → Gap Analysis → Kotter's 8 Steps → WBS → RACI → Balanced Scorecard
```

## Available Templates

See [templates/](templates/) for ready-to-use documents:
- SWOT Analysis Report
- Business Model Canvas
- Business Case Template
- Project Charter
- RACI Matrix

## Framework Index (Alphabetical)

| Framework | Primary Use | File |
|-----------|-------------|------|
| 3C Framework | Competitive positioning | [strategy.md](strategy.md) |
| 4P Marketing Mix | Marketing strategy | [strategy.md](strategy.md) |
| 5 Whys | Root cause analysis | [operations.md](operations.md) |
| 5S | Workplace organization | [operations.md](operations.md) |
| 80/20 Rule | Prioritization | [problem-solving.md](problem-solving.md) |
| ADKAR | Individual change management | [projects.md](projects.md) |
| Ansoff Matrix | Growth strategy | [strategy.md](strategy.md) |
| Balanced Scorecard | Strategy measurement | [projects.md](projects.md) |
| BCG Matrix | Portfolio management | [strategy.md](strategy.md) |
| Blue Ocean Strategy | Market creation | [strategy.md](strategy.md) |
| Business Model Canvas | Business model design | [design.md](design.md) |
| Customer Journey | Customer experience | [design.md](design.md) |
| Design Thinking | Innovation process | [design.md](design.md) |
| DMAIC | Process improvement | [operations.md](operations.md) |
| Due Diligence | M&A evaluation | [cases.md](cases.md) |
| Fishbone Diagram | Root cause analysis | [operations.md](operations.md) |
| GE-McKinsey Matrix | Portfolio prioritization | [strategy.md](strategy.md) |
| Hypothesis Tree | Testing theories | [problem-solving.md](problem-solving.md) |
| Issue Tree | Problem decomposition | [problem-solving.md](problem-solving.md) |
| Kotter's 8 Steps | Organizational change | [projects.md](projects.md) |
| Lean / 8 Wastes | Waste elimination | [operations.md](operations.md) |
| M&A Framework | Acquisition evaluation | [cases.md](cases.md) |
| Market Entry | New market decisions | [cases.md](cases.md) |
| Market Sizing | Opportunity sizing | [cases.md](cases.md) |
| McKinsey 7-Step | Problem-solving process | [problem-solving.md](problem-solving.md) |
| McKinsey 7S | Organizational analysis | [strategy.md](strategy.md) |
| McKinsey Horizons | Growth portfolio | [projects.md](projects.md) |
| MECE | Structuring | [problem-solving.md](problem-solving.md) |
| NPV/IRR/ROI | Investment analysis | [finance.md](finance.md) |
| OKRs | Goal setting | [projects.md](projects.md) |
| Pareto Analysis | Prioritization | [operations.md](operations.md) |
| PDCA Cycle | Continuous improvement | [operations.md](operations.md) |
| PESTEL | Macro environment | [strategy.md](strategy.md) |
| Porter's 5 Forces | Industry analysis | [strategy.md](strategy.md) |
| Porter's Generic Strategies | Competitive strategy | [strategy.md](strategy.md) |
| Pricing Framework | Price setting | [cases.md](cases.md) |
| Process Mapping | Workflow visualization | [operations.md](operations.md) |
| Profitability Framework | Profit analysis | [cases.md](cases.md) |
| Pyramid Principle | Communication | [problem-solving.md](problem-solving.md) |
| RACI Matrix | Role clarity | [projects.md](projects.md) |
| Risk Matrix | Risk prioritization | [projects.md](projects.md) |
| SCQ | Storytelling | [problem-solving.md](problem-solving.md) |
| Sensitivity Analysis | Risk assessment | [finance.md](finance.md) |
| Six Sigma | Quality improvement | [operations.md](operations.md) |
| Stakeholder Analysis | Stakeholder management | [projects.md](projects.md) |
| Storyboarding | Presentation planning | [problem-solving.md](problem-solving.md) |
| STP | Market targeting | [design.md](design.md) |
| SWOT Analysis | Situation assessment | [strategy.md](strategy.md) |
| Unit Economics (LTV/CAC) | Customer profitability | [finance.md](finance.md) |
| Value Chain | Activity analysis | [strategy.md](strategy.md) |
| VRIO | Resource advantage | [strategy.md](strategy.md) |
| WBS | Work decomposition | [projects.md](projects.md) |
