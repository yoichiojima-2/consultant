# Problem-Solving Frameworks

Core thinking frameworks developed and used by top consulting firms for structured problem-solving.

## MECE (Mutually Exclusive, Collectively Exhaustive)

**Origin**: Developed at McKinsey by Barbara Minto in the 1960s

**Purpose**: Break down complex problems into distinct, non-overlapping categories that cover all possibilities.

### Principles

1. **Mutually Exclusive (ME)**: Each category is distinct - no overlap
2. **Collectively Exhaustive (CE)**: All categories together cover 100% of the problem

### How to Apply MECE

1. **Define the problem clearly** - What exactly are you trying to break down?
2. **Choose a breakdown dimension** - By what criteria will you divide?
3. **Create categories** - List all categories
4. **Check for overlap** - Does anything belong to multiple categories? If yes, redefine
5. **Check for gaps** - Is anything missing? If yes, add categories

### Common MECE Structures

| Structure | Categories | Best For |
|-----------|-----------|----------|
| **Binary** | Yes/No, Internal/External, Current/Future | Simple distinctions |
| **Process** | Input → Process → Output | Workflow analysis |
| **Timeline** | Past, Present, Future | Trend analysis |
| **Stakeholder** | Customers, Employees, Shareholders, Partners | Impact analysis |
| **Geography** | By region, country, city | Market analysis |
| **Lifecycle** | Acquire, Retain, Grow, Win-back | Customer analysis |

### Example: "Why are sales declining?"

**MECE Breakdown by Revenue Formula**:
```
Revenue Decline
├── Volume Decline
│   ├── Fewer customers
│   └── Lower purchase frequency
└── Price/Mix Decline
    ├── Lower prices
    └── Shift to lower-margin products
```

### Common Mistakes

- **Not exhaustive**: Missing a category (e.g., forgetting "Other")
- **Overlapping**: Categories that share elements
- **Wrong level**: Mixing different levels of detail
- **Too granular**: Breaking down beyond what's useful

---

## Pyramid Principle

**Origin**: Barbara Minto at McKinsey, 1970s

**Purpose**: Structure communication (presentations, documents, emails) for maximum clarity and impact.

### Core Concept: Answer First

Start with the conclusion/recommendation, then provide supporting arguments.

```
        ┌─────────────────┐
        │   Main Point    │  ← Start here (answer/recommendation)
        │  (1 sentence)   │
        └────────┬────────┘
                 │
    ┌────────────┼────────────┐
    ▼            ▼            ▼
┌───────┐   ┌───────┐   ┌───────┐
│ Key   │   │ Key   │   │ Key   │  ← Supporting arguments (3-5)
│Point 1│   │Point 2│   │Point 3│
└───┬───┘   └───┬───┘   └───┬───┘
    │           │           │
    ▼           ▼           ▼
 Evidence    Evidence    Evidence   ← Data, examples, analysis
```

### The SCQ Framework (Situation-Complication-Question)

Before presenting your pyramid, set up the context:

1. **Situation**: The current state (facts everyone agrees on)
2. **Complication**: What changed or what's the problem
3. **Question**: The key question this raises (implicitly answered by your main point)

### Example

**Situation**: "We launched Product X in Q1 targeting enterprise customers."

**Complication**: "Sales are 40% below target after 6 months."

**Question**: "What should we do to meet our annual sales target?"

**Main Point**: "We should pivot to mid-market customers and reduce the price by 20%."

**Supporting Arguments**:
1. Enterprise sales cycle is too long (9 months vs. 3 months mid-market)
2. Mid-market has 5x more potential customers
3. Competitors are not focused on mid-market

### MECE in the Pyramid

Each level of the pyramid must be MECE:
- Supporting arguments should not overlap
- Together they should fully support the main point

### Grouping Logic

Arguments can be grouped by:
- **Deductive**: If A and B, then C (logical chain)
- **Inductive**: A, B, C all point to the same conclusion (similar ideas grouped)

---

## Issue Tree

**Origin**: Standard consulting methodology

**Purpose**: Break down a problem into component issues to identify root causes and prioritize investigation.

### Structure

```
Main Problem
├── Issue 1
│   ├── Sub-issue 1.1
│   │   ├── Hypothesis 1.1.1
│   │   └── Hypothesis 1.1.2
│   └── Sub-issue 1.2
├── Issue 2
│   ├── Sub-issue 2.1
│   └── Sub-issue 2.2
└── Issue 3
    └── Sub-issue 3.1
```

### How to Build an Issue Tree

1. **Start with the key question** (at the top)
2. **Break into major issues** (first level - use MECE)
3. **Decompose each issue** (second level)
4. **Continue until actionable** (usually 3-4 levels)
5. **Form hypotheses** at leaf nodes

### Example: "How can we increase profitability?"

```
Increase Profitability
├── Increase Revenue
│   ├── Increase Volume
│   │   ├── Acquire new customers
│   │   ├── Increase purchase frequency
│   │   └── Reduce churn
│   └── Increase Price/Mix
│       ├── Raise prices
│       └── Shift to premium products
└── Reduce Costs
    ├── Reduce Variable Costs
    │   ├── Reduce COGS
    │   └── Reduce sales costs
    └── Reduce Fixed Costs
        ├── Reduce headcount
        └── Reduce facilities cost
```

### Prioritization

After building the tree, prioritize branches by:
- **Impact**: How much could this improve the outcome?
- **Feasibility**: How easy is it to address?
- **Speed**: How quickly can we act?

---

## Hypothesis-Driven Problem Solving

**Origin**: Scientific method applied to business consulting

**Purpose**: Efficiently solve problems by testing hypotheses rather than boiling the ocean with data.

### The Approach

1. **Form initial hypothesis** - What do you believe the answer is?
2. **Structure the hypothesis** - Break into testable components
3. **Prioritize tests** - Which tests are most critical?
4. **Gather data** - Only collect data that tests the hypothesis
5. **Analyze and iterate** - Confirm, refute, or refine hypothesis

### Day 1 Answer

Consultants often create a "Day 1 Answer" - their best hypothesis before any analysis:

> "Based on initial information, we believe [hypothesis]. This would require [key assumptions to be true]. We will test this by [analysis plan]."

### Hypothesis Tree

```
Main Hypothesis: "Revenue decline is due to customer churn"
├── Sub-hypothesis 1: "Churn rate has increased significantly"
│   └── Test: Compare churn rates YoY
├── Sub-hypothesis 2: "Churned customers cite product issues"
│   └── Test: Analyze exit surveys
└── Sub-hypothesis 3: "Competitors are winning our customers"
    └── Test: Win/loss analysis
```

### Hypothesis vs. Issue Tree

| Aspect | Issue Tree | Hypothesis Tree |
|--------|-----------|-----------------|
| Starting point | Question | Proposed answer |
| Purpose | Explore all possibilities | Test specific theory |
| Efficiency | Comprehensive | Faster if correct |
| Risk | May be slow | May miss alternatives |

### When to Use Each

- **Issue Tree**: New problem, no prior knowledge
- **Hypothesis Tree**: Experience suggests likely cause, need to validate

---

## McKinsey 7-Step Problem Solving Process

**Origin**: McKinsey & Company's core methodology

**Purpose**: Structured, hypothesis-driven approach to solve any business problem.

### The 7 Steps

```
┌─────────────────────────────────────────────────────────────────┐
│               McKINSEY 7-STEP PROBLEM SOLVING                   │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  1. DEFINE THE PROBLEM                                          │
│     └── What exactly are we trying to solve?                    │
│                     ↓                                           │
│  2. DISAGGREGATE / STRUCTURE                                    │
│     └── Build issue tree (MECE)                                 │
│                     ↓                                           │
│  3. PRIORITIZE ISSUES                                           │
│     └── Focus on high-impact, testable branches                 │
│                     ↓                                           │
│  4. BUILD WORKPLAN & ASSIGN                                     │
│     └── Who does what analysis by when?                         │
│                     ↓                                           │
│  5. CONDUCT ANALYSES                                            │
│     └── Gather data, test hypotheses                            │
│                     ↓                                           │
│  6. SYNTHESIZE FINDINGS                                         │
│     └── So what? Develop recommendations                        │
│                     ↓                                           │
│  7. COMMUNICATE / BUILD BUY-IN                                  │
│     └── Present using Pyramid Principle                         │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### Step Details

#### Step 1: Define the Problem

A good problem statement includes:
- **Context**: Background situation
- **Success criteria**: What does "solved" look like?
- **Scope**: What's in and out of bounds
- **Constraints**: Time, budget, resources
- **Stakeholders**: Who cares about this?

**Problem Statement Template**:
> "[Client] is facing [problem] which is causing [impact]. We need to determine [key question] by [deadline], considering [constraints]."

#### Step 2: Disaggregate / Structure

Build an issue tree that is:
- **MECE** - Mutually exclusive, collectively exhaustive
- **Hypothesis-driven** - Each branch has a testable hypothesis
- **3-4 levels deep** - Enough to be actionable

#### Step 3: Prioritize Issues

Use a 2x2 matrix:

```
                    IMPACT
               Low         High
         ┌───────────┬───────────┐
    Easy │   QUICK   │   DO      │
         │   WINS    │   FIRST   │
EFFORT   ├───────────┼───────────┤
    Hard │   DON'T   │ PLAN      │
         │   BOTHER  │ CAREFULLY │
         └───────────┴───────────┘
```

Apply 80/20 rule: 80% of insights come from 20% of analyses.

#### Step 4: Build Workplan

For each prioritized issue:

| Issue | Hypothesis | Analysis | Data Source | Owner | Due |
|-------|------------|----------|-------------|-------|-----|
| | | | | | |

#### Step 5: Conduct Analyses

- Test hypotheses with data
- Look for "so what?" - what does this mean?
- Iterate - refine hypotheses based on findings

#### Step 6: Synthesize Findings

Move from "what we found" to "what it means":

| Finding | So What? | Implication |
|---------|----------|-------------|
| Churn increased 15% | Customer satisfaction issue | Invest in retention |

#### Step 7: Communicate

Use the Pyramid Principle:
1. Lead with the answer
2. Support with 3-5 key arguments
3. Back up with data

---

## SCQ Framework (Situation-Complication-Question)

**Purpose**: Set up any communication to create tension and engagement.

### The Structure

```
SITUATION    →    COMPLICATION    →    QUESTION    →    ANSWER
(Stable)          (Unstable)           (Tension)        (Resolution)
```

### Components

| Component | Purpose | Characteristics |
|-----------|---------|-----------------|
| **Situation** | Establish common ground | Facts everyone agrees on; stable state |
| **Complication** | Create tension | What changed; the problem; the threat/opportunity |
| **Question** | Focus attention | The question that naturally arises |
| **Answer** | Your main message | Your recommendation or conclusion |

### SCQ Examples

**Strategy Recommendation**:
- **S**: "Our company has been the market leader for 10 years."
- **C**: "A new competitor entered with 30% lower prices and is growing rapidly."
- **Q**: "How should we respond to maintain our market position?"
- **A**: "We should launch a fighter brand targeting price-sensitive segments."

**Operational Issue**:
- **S**: "Our customer service team handles 10,000 calls per day."
- **C**: "Wait times have increased from 2 to 8 minutes, and complaints are up 50%."
- **Q**: "How can we reduce wait times while controlling costs?"
- **A**: "Implement a chatbot for simple queries, freeing agents for complex issues."

### SCQ Variations

| Variation | When to Use |
|-----------|-------------|
| **S-C-Q** | Standard setup for recommendation |
| **S-C-S-C-Q** | Complex situations with multiple complications |
| **C-S-Q** | When complication is most urgent/attention-grabbing |

---

## Storyboarding (Ghostpack / Ghost Deck)

**Purpose**: Plan the final deliverable before doing the analysis.

### What is a Ghostpack?

A "ghost" version of the final presentation:
- Slide titles and key messages written
- Charts sketched with expected patterns
- Sources/analyses identified but not yet done

### Why Storyboard First?

1. **Efficiency**: Know exactly what analyses to run
2. **Alignment**: Get buy-in on approach before investing time
3. **Quality**: Story flows logically from start
4. **Speed**: Parallel work - team knows what to build

### Storyboard Template

For each slide:

```
┌─────────────────────────────────────────────────────────────┐
│ SLIDE TITLE (Action Title - contains the "so what")         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│    [Sketch of chart/visual]          Key Message:           │
│                                      • Point 1              │
│         📊                           • Point 2              │
│                                      • Point 3              │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│ Data Source:                    Analysis Needed:            │
│ Owner:                          Due:                        │
└─────────────────────────────────────────────────────────────┘
```

### Action Titles

Each slide title should be a complete sentence with the insight:

| Weak Title | Strong Action Title |
|------------|---------------------|
| "Market Overview" | "Market is growing 8% annually, driven by emerging segments" |
| "Competitive Analysis" | "Competitors are investing 2x more in digital channels" |
| "Recommendations" | "Three initiatives can recover $50M in lost revenue" |

### Storyboard Flow

```
1. Executive Summary (answer + 3 key points)
        ↓
2. Situation & Context
        ↓
3. Analysis & Findings (grouped by theme, not by analysis type)
        ↓
4. Implications
        ↓
5. Recommendations
        ↓
6. Implementation Roadmap
        ↓
7. Appendix (detailed analyses)
```

---

## Workplan Development

**Purpose**: Translate problem structure into actionable tasks with clear ownership.

### Workplan Components

| Component | Description |
|-----------|-------------|
| **Workstream** | Major theme or track of work |
| **Activity** | Specific task or analysis |
| **Deliverable** | Output produced |
| **Owner** | Person responsible |
| **Duration** | Time required |
| **Dependencies** | What must happen first |

### Workplan Template

```
┌────────────────────────────────────────────────────────────────────┐
│                         PROJECT WORKPLAN                           │
├──────────────┬─────────────┬────────┬─────┬───────────────────────┤
│ Workstream   │ Activity    │ Owner  │Days │  Week 1  │  Week 2   │
├──────────────┼─────────────┼────────┼─────┼──────────┼───────────┤
│ Market       │ Size market │ Alice  │  3  │ ████     │           │
│ Analysis     │ Segment     │ Alice  │  2  │     ██  │           │
│              │ Trends      │ Bob    │  3  │ ███      │           │
├──────────────┼─────────────┼────────┼─────┼──────────┼───────────┤
│ Competitive  │ Map players │ Carol  │  2  │ ██       │           │
│ Analysis     │ Benchmark   │ Carol  │  4  │   ████   │           │
├──────────────┼─────────────┼────────┼─────┼──────────┼───────────┤
│ Internal     │ Financials  │ Dave   │  3  │ ███      │           │
│ Assessment   │ Operations  │ Dave   │  3  │    ███   │           │
├──────────────┼─────────────┼────────┼─────┼──────────┼───────────┤
│ Synthesis    │ Integrate   │ Lead   │  3  │          │ ███       │
│              │ Present     │ Lead   │  2  │          │    ██     │
└──────────────┴─────────────┴────────┴─────┴──────────┴───────────┘
```

### One-Page Analysis Template

For each analysis:

| Field | Description |
|-------|-------------|
| **Question** | What are we trying to answer? |
| **Hypothesis** | What do we expect to find? |
| **Analysis** | What work will we do? |
| **Data** | What data do we need? Source? |
| **Output** | What will the deliverable look like? |
| **Owner** | Who is responsible? |
| **Timeline** | When is it due? |

---

## 80/20 Rule (Pareto Principle in Consulting)

**Purpose**: Focus effort on the vital few factors that drive most of the impact.

### Application in Problem Solving

| Area | 80/20 Application |
|------|-------------------|
| **Analysis** | 20% of analyses yield 80% of insights |
| **Issues** | 20% of issues cause 80% of the problem |
| **Customers** | 20% of customers generate 80% of revenue |
| **Products** | 20% of products account for 80% of sales |
| **Time** | 20% of activities create 80% of value |

### How to Apply

1. **Don't boil the ocean** - Focus on most impactful analyses
2. **Hypothesis-driven** - Test likely causes first
3. **Perfect is enemy of good** - 80% right today beats 100% right never
4. **Iterate** - Start rough, refine as needed

---

## Combining Frameworks

These frameworks chain together into a complete engagement: see **The Complete Consulting Flow** in [SKILL.md](SKILL.md), which is the single source of truth for the end-to-end sequence.
