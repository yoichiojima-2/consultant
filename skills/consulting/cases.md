# Case Interview & Analysis Frameworks

Core frameworks for common business case types: profitability, market sizing, M&A, pricing, and market entry.

## Profitability Framework

**Purpose**: Diagnose why profits are declining or how to improve profitability.

### The Basic Equation

```
PROFIT = REVENUE - COSTS

Revenue = Price × Volume
        = Price × (Customers × Transactions × Units per Transaction)

Costs = Fixed Costs + Variable Costs
      = (Rent, Salaries, etc.) + (COGS, Commissions, etc.)
```

### Profitability Tree

```
Profit Decline
├── Revenue Decline
│   ├── Price Decline
│   │   ├── Competitive pressure
│   │   ├── Customer negotiation
│   │   └── Product commoditization
│   └── Volume Decline
│       ├── Fewer customers
│       │   ├── Lower acquisition
│       │   └── Higher churn
│       ├── Lower frequency
│       └── Smaller basket size
└── Cost Increase
    ├── Variable Costs
    │   ├── Raw materials
    │   ├── Direct labor
    │   └── Sales commissions
    └── Fixed Costs
        ├── Rent/facilities
        ├── Salaries (overhead)
        └── Depreciation
```

### Diagnostic Questions

**Revenue Side**:
- Is revenue declining, flat, or growing slower than market?
- Is it a price problem or a volume problem?
- Is it affecting all products/regions or specific ones?
- When did it start? What changed?
- What are competitors doing?

**Cost Side**:
- Are costs increasing absolutely or as a % of revenue?
- Which cost categories are growing fastest?
- How do our costs compare to competitors?
- What's driving the cost increases?

### Profitability Analysis Template

| Metric | Last Year | This Year | Change | Benchmark |
|--------|-----------|-----------|--------|-----------|
| Revenue | | | | |
| - Price | | | | |
| - Volume | | | | |
| Gross Margin | | | | |
| Variable Costs | | | | |
| Fixed Costs | | | | |
| Operating Profit | | | | |
| Profit Margin % | | | | |

---

## Market Sizing

**Purpose**: Estimate the size of a market, opportunity, or quantity.

### Two Approaches

| Approach | Method | Best For |
|----------|--------|----------|
| **Top-Down** | Start with big number, narrow down | When macro data exists |
| **Bottom-Up** | Build up from unit economics | When behavior data exists |

### Top-Down Approach

Start with total population, then apply filters:

```
Total Market = Population × % Applicable × Usage Rate × Price

Example: Coffee shop revenue in NYC
- NYC Population: 8 million
- % Adults (18+): 75% → 6 million
- % Coffee drinkers: 60% → 3.6 million
- % Buy out (vs home): 40% → 1.44 million
- Cups per week: 3 → 4.32 million cups/week
- Price per cup: $4 → $17.3 million/week
- Annual market: ~$900 million
```

### Bottom-Up Approach

Build from individual unit:

```
Market Size = # of Units × Revenue per Unit

Example: Coffee shop revenue in NYC
- # Coffee shops in NYC: ~3,000
- Average customers/day: 200
- Average ticket: $5
- Revenue/shop/day: $1,000
- Days/year: 350
- Revenue/shop/year: $350,000
- Total market: $350,000 × 3,000 = $1.05 billion
```

### Sanity Check

Always cross-check with:
- Alternative calculation method
- Known benchmarks
- Common sense ("does this feel right?")

### Market Sizing Structures

| What to Size | Structure |
|--------------|-----------|
| **Consumer market** | Population × Usage rate × Price |
| **B2B market** | # Companies × Adoption rate × Spend |
| **Physical items** | # Locations × Items per location |
| **Services** | # Users × Frequency × Price |

### Common Assumptions to Know

| Item | Approximate Value |
|------|-------------------|
| US Population | 340 million |
| US Households | 132 million |
| Average household size | 2.5 people |
| US GDP | $29 trillion |
| Life expectancy | 80 years |
| Working years | 40-45 years |
| Days per year | 365 |
| Work days per year | 250 |
| Hours per day | 24 |
| Work hours per day | 8 |

---

## M&A Framework (Mergers & Acquisitions)

**Purpose**: Evaluate whether to acquire a company and at what price.

### M&A Decision Framework

```
Should We Acquire?
├── Strategic Rationale
│   ├── Why buy vs. build vs. partner?
│   ├── What's the strategic goal?
│   └── Does target align with our strategy?
├── Target Attractiveness
│   ├── Market position
│   ├── Financial performance
│   ├── Competitive advantages
│   └── Management quality
├── Synergies
│   ├── Revenue synergies
│   ├── Cost synergies
│   └── How achievable are they?
├── Risks
│   ├── Integration risk
│   ├── Cultural fit
│   ├── Key person dependency
│   └── Hidden liabilities
└── Valuation
    ├── Standalone value
    ├── Synergy value
    ├── Premium justified?
    └── Returns meet hurdle rate?
```

### Types of Synergies

| Type | Examples | Typical Realization |
|------|----------|---------------------|
| **Revenue Synergies** | Cross-selling, new markets, pricing power | Harder to achieve, 2-3 years |
| **Cost Synergies** | Eliminate duplicates, purchasing power | Easier to achieve, 1-2 years |

### Synergy Analysis

**Revenue Synergies**:
- Cross-sell products to each other's customers
- Enter new markets with combined capabilities
- Increase pricing power
- Accelerate growth through combined R&D

**Cost Synergies**:
- Eliminate duplicate functions (HR, Finance, IT)
- Consolidate facilities
- Purchasing economies of scale
- Shared services

### Due Diligence Checklist

| Area | Key Questions |
|------|---------------|
| **Financial** | Revenue trends? Margin stability? Working capital? Debt? |
| **Commercial** | Customer concentration? Contract terms? Market share? |
| **Operational** | Capacity? Technology? Processes? |
| **Legal** | Pending litigation? IP ownership? Regulatory issues? |
| **HR** | Key employees? Compensation? Union agreements? |
| **Tax** | Tax liabilities? Structure optimization? |

### Valuation Methods

| Method | Approach | When to Use |
|--------|----------|-------------|
| **Comparable Companies** | Multiple × Metric (e.g., 10× EBITDA) | Publicly traded comparables exist |
| **Precedent Transactions** | What others paid for similar deals | Recent relevant transactions |
| **DCF** | PV of future cash flows | Detailed projections available |
| **LBO** | Returns to financial buyer | PE/financial buyer perspective |

### M&A Return Calculation

```
Value Created = Synergies - Premium Paid - Integration Costs

Example:
- Target standalone value: $100M
- Synergies (NPV): $30M
- Acquisition price: $120M
- Premium paid: $20M
- Integration costs: $5M
- Value created: $30M - $20M - $5M = $5M
```

---

## Pricing Framework

**Purpose**: Set or adjust prices for products/services.

### Pricing Approaches

```
                    ┌─────────────────┐
                    │     PRICING     │
                    └────────┬────────┘
                             │
         ┌───────────────────┼───────────────────┐
         │                   │                   │
    ┌────┴────┐        ┌─────┴─────┐       ┌────┴────┐
    │  COST   │        │   VALUE   │       │ COMPET. │
    │  PLUS   │        │   BASED   │       │  BASED  │
    └─────────┘        └───────────┘       └─────────┘

    Cost + Margin      What customer      Match or beat
                       willing to pay     competitor
```

### Pricing Methods

| Method | Formula | Best For |
|--------|---------|----------|
| **Cost-Plus** | Cost × (1 + Margin%) | Commodities, contracts |
| **Value-Based** | Customer value × Capture rate | Differentiated products |
| **Competitive** | Competitor price ± adjustment | Undifferentiated markets |

### Value-Based Pricing

```
Customer Value = Reference Value + Differentiation Value
                = Best alternative + Added value of our product

Maximum Price = Customer Value
Actual Price = Customer Value × Value Capture %
```

### Price Sensitivity Analysis

Factors that reduce price sensitivity:
- Unique product features
- High switching costs
- Low price relative to total cost
- Shared cost (someone else pays)
- Quality/prestige importance
- Can't easily compare prices

### Pricing Decision Tree

```
Pricing Decision
├── Understand Customer Value
│   ├── What problem does it solve?
│   ├── What alternatives exist?
│   └── What would customer pay?
├── Analyze Costs
│   ├── Variable cost per unit
│   ├── Contribution margin required
│   └── Break-even volume
├── Assess Competition
│   ├── Competitor prices
│   ├── Competitor reactions
│   └── Market positioning
└── Set Price
    ├── List price
    ├── Discount structure
    └── Terms and conditions
```

### Price Elasticity

```
Elasticity = % Change in Quantity / % Change in Price

If Elasticity > 1: Demand is elastic (lower price → higher revenue)
If Elasticity < 1: Demand is inelastic (higher price → higher revenue)
```

---

## Market Entry Framework

**Purpose**: Decide whether and how to enter a new market.

### Market Entry Decision Tree

```
Should We Enter This Market?
├── Market Attractiveness
│   ├── Size and growth
│   ├── Profitability
│   ├── Competitive intensity
│   └── Barriers to entry
├── Company Fit
│   ├── Do we have required capabilities?
│   ├── Can we leverage existing assets?
│   ├── Strategic alignment
│   └── Risk tolerance
├── Entry Strategy
│   ├── Organic build
│   ├── Acquisition
│   ├── Partnership/JV
│   └── Licensing
└── Implementation
    ├── Investment required
    ├── Timeline
    ├── Success factors
    └── Exit criteria
```

### Market Attractiveness Analysis

| Factor | Questions | Analysis Tools |
|--------|-----------|----------------|
| Size | How big is the market? | Market sizing |
| Growth | How fast is it growing? | Trend analysis |
| Profitability | What are typical margins? | Industry benchmarks |
| Competition | Who are the players? How intense? | Porter's 5 Forces |
| Barriers | What does it take to enter? | Entry barrier analysis |

### Entry Mode Comparison

| Mode | Investment | Control | Speed | Risk |
|------|------------|---------|-------|------|
| **Organic** | High | Full | Slow | High |
| **Acquisition** | Very High | Full | Fast | Medium |
| **JV/Alliance** | Medium | Shared | Medium | Medium |
| **Licensing** | Low | Low | Fast | Low |
| **Franchising** | Low | Medium | Fast | Low |

### Go/No-Go Criteria

| Criteria | Threshold | Actual | Go? |
|----------|-----------|--------|-----|
| Market size | >$500M | | |
| Growth rate | >5% | | |
| Profit margin | >15% | | |
| Achievable share | >10% | | |
| Payback period | <5 years | | |
| NPV | >$50M | | |

### Barriers to Entry

| Barrier | Description | Implication |
|---------|-------------|-------------|
| Economies of scale | Incumbents have cost advantage | Need volume quickly |
| Capital requirements | High upfront investment | Financial resources needed |
| Switching costs | Customers locked to incumbents | Must offer compelling value |
| Distribution access | Channels controlled by others | Build or acquire access |
| Regulatory | Licenses, approvals needed | Time and compliance cost |
| Brand loyalty | Strong incumbent brands | Marketing investment |

---

## Combining Frameworks

### Typical Case Flow

```
1. CLARIFY THE OBJECTIVE
   └── What exactly are we trying to solve?
              ↓
2. STRUCTURE THE PROBLEM
   └── Which framework(s) apply?
              ↓
3. HYPOTHESIZE
   └── What do we think the answer is?
              ↓
4. ANALYZE
   └── Test each branch systematically
              ↓
5. SYNTHESIZE
   └── What did we learn? So what?
              ↓
6. RECOMMEND
   └── What should the client do?
```

### Framework Selection Guide

| If the question is about... | Use this framework |
|-----------------------------|-------------------|
| Why are profits down? | Profitability |
| How big is the market? | Market Sizing |
| Should we acquire X? | M&A |
| What price should we charge? | Pricing |
| Should we enter market Y? | Market Entry |
| What's our strategy? | 3C, Porter's, SWOT |
| How do we grow? | Ansoff Matrix |
| How do we improve operations? | Value Chain, Lean |

### Multi-Framework Cases

Many cases require combining frameworks:

**"Should we launch a new product?"**
1. Market Sizing → Is the opportunity big enough?
2. Market Entry → Can we compete effectively?
3. Profitability → Will it be profitable?
4. Pricing → What should we charge?

**"How do we turn around this business?"**
1. Profitability → Where are we losing money?
2. 3C Analysis → What's the competitive situation?
3. Value Chain → Where can we improve?
4. Prioritization → What should we do first?
