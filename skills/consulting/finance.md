# Financial Analysis Frameworks

Frameworks for evaluating investments, building business cases, and making financial decisions.

## Return on Investment (ROI)

**Purpose**: Measure the gain or loss generated relative to the investment cost.

### Formula

```
ROI = (Net Benefit / Cost) × 100%

Where:
- Net Benefit = Total Benefits - Total Costs
- Cost = Initial Investment
```

### Example

| Item | Value |
|------|-------|
| Initial Investment | $100,000 |
| Annual Benefits | $40,000 |
| Annual Costs | $10,000 |
| Time Period | 3 years |

**Calculation**:
- Total Benefits: $40,000 × 3 = $120,000
- Total Costs: $100,000 + ($10,000 × 3) = $130,000
- Net Benefit: $120,000 - $130,000 = -$10,000
- ROI: (-$10,000 / $100,000) × 100% = **-10%**

### ROI Limitations

- Doesn't account for time value of money
- Doesn't consider risk
- Can be manipulated by timeframe selection
- Ignores qualitative benefits

---

## Net Present Value (NPV)

**Purpose**: Calculate the present value of future cash flows, accounting for the time value of money.

### Formula

```
NPV = Σ [Cash Flow_t / (1 + r)^t] - Initial Investment

Where:
- t = time period
- r = discount rate
- Cash Flow_t = cash flow in period t
```

### Simplified Table Approach

| Year | Cash Flow | Discount Factor (10%) | Present Value |
|------|-----------|----------------------|---------------|
| 0 | -$100,000 | 1.000 | -$100,000 |
| 1 | $30,000 | 0.909 | $27,270 |
| 2 | $35,000 | 0.826 | $28,910 |
| 3 | $40,000 | 0.751 | $30,040 |
| 4 | $45,000 | 0.683 | $30,735 |
| **NPV** | | | **$16,955** |

### Discount Factors

| Rate | Year 1 | Year 2 | Year 3 | Year 4 | Year 5 |
|------|--------|--------|--------|--------|--------|
| 5% | 0.952 | 0.907 | 0.864 | 0.823 | 0.784 |
| 8% | 0.926 | 0.857 | 0.794 | 0.735 | 0.681 |
| 10% | 0.909 | 0.826 | 0.751 | 0.683 | 0.621 |
| 12% | 0.893 | 0.797 | 0.712 | 0.636 | 0.567 |
| 15% | 0.870 | 0.756 | 0.658 | 0.572 | 0.497 |

### NPV Decision Rule

- **NPV > 0**: Project creates value → Accept
- **NPV < 0**: Project destroys value → Reject
- **NPV = 0**: Project breaks even → Indifferent

---

## Internal Rate of Return (IRR)

**Purpose**: Find the discount rate at which NPV equals zero.

### Interpretation

- IRR is the project's "break-even" discount rate
- Compare IRR to your required rate of return (hurdle rate)

### Decision Rule

- **IRR > Hurdle Rate**: Accept
- **IRR < Hurdle Rate**: Reject

### Example

If a project has an IRR of 15% and your company's cost of capital is 10%:
- The project returns more than it costs to fund → Accept

### IRR Limitations

- Assumes reinvestment at IRR rate
- Can give multiple values with non-conventional cash flows
- Doesn't account for project size
- Use NPV for mutually exclusive projects

---

## Payback Period

**Purpose**: Determine how long it takes to recover the initial investment.

### Simple Payback

```
Payback Period = Initial Investment / Annual Cash Flow

Example:
- Investment: $100,000
- Annual Cash Flow: $25,000
- Payback: $100,000 / $25,000 = 4 years
```

### Uneven Cash Flows

| Year | Cash Flow | Cumulative Cash Flow |
|------|-----------|---------------------|
| 0 | -$100,000 | -$100,000 |
| 1 | $20,000 | -$80,000 |
| 2 | $30,000 | -$50,000 |
| 3 | $40,000 | -$10,000 |
| 4 | $50,000 | +$40,000 |

**Payback**: 3 years + ($10,000 / $50,000) = **3.2 years**

### Discounted Payback

Same approach but using present values of cash flows.

### Payback Limitations

- Ignores cash flows after payback
- Ignores time value of money (unless discounted)
- Doesn't measure profitability
- Arbitrary acceptance threshold

---

## Break-Even Analysis

**Purpose**: Determine the point where revenue equals costs.

### Formula

```
Break-Even Units = Fixed Costs / (Price per Unit - Variable Cost per Unit)

Break-Even Revenue = Fixed Costs / Contribution Margin Ratio

Where:
- Contribution Margin = Price - Variable Cost
- Contribution Margin Ratio = Contribution Margin / Price
```

### Example

| Item | Value |
|------|-------|
| Fixed Costs | $50,000/month |
| Price per Unit | $100 |
| Variable Cost per Unit | $60 |
| Contribution Margin | $40 |

**Break-Even Units**: $50,000 / $40 = **1,250 units/month**
**Break-Even Revenue**: 1,250 × $100 = **$125,000/month**

### Break-Even Chart

```
Revenue/Cost ($)
     │
     │                    ╱ Revenue
     │                  ╱
     │                ╱
     │              ╱ ──── Break-Even Point
     │            ╱╱
     │          ╱╱   Total Costs
     │        ╱╱
     │──────╱╱─────── Fixed Costs
     │    ╱
     └──────────────────────────── Units
```

---

## Sensitivity Analysis

**Purpose**: Understand how changes in assumptions affect outcomes.

### One-Way Sensitivity

Test one variable at a time:

| Variable | Base Case | -20% | -10% | +10% | +20% |
|----------|-----------|------|------|------|------|
| Revenue | $1M NPV | $0.6M | $0.8M | $1.2M | $1.4M |
| Costs | $1M NPV | $1.3M | $1.15M | $0.85M | $0.7M |
| Discount Rate | $1M NPV | $1.2M | $1.1M | $0.9M | $0.8M |

### Tornado Diagram

```
                    NPV Impact
         -$500K   -$250K    $0    +$250K   +$500K
              │       │      │       │       │
   Revenue    ████████████████████████████████
   Costs      ██████████████████████████
   Volume     █████████████████████
   Price      ███████████████
   Timing     █████████
```

### Scenario Analysis

| Scenario | Description | Probability | NPV |
|----------|-------------|-------------|-----|
| Best Case | High demand, low costs | 20% | $2.5M |
| Base Case | Expected outcomes | 60% | $1.0M |
| Worst Case | Low demand, high costs | 20% | -$0.5M |

**Expected NPV** = (0.2 × $2.5M) + (0.6 × $1.0M) + (0.2 × -$0.5M) = **$1.0M**

---

## Business Case Template

### Executive Summary
- Investment required
- Expected benefits
- Recommendation

### Current State
- Problem or opportunity
- Impact of doing nothing

### Options Considered
| Option | Description | Pros | Cons |
|--------|-------------|------|------|
| Option 1 | | | |
| Option 2 | | | |
| Option 3 (Recommended) | | | |

### Financial Analysis

| Metric | Option 1 | Option 2 | Option 3 |
|--------|----------|----------|----------|
| Initial Investment | | | |
| Annual Benefits | | | |
| Annual Costs | | | |
| NPV | | | |
| IRR | | | |
| Payback Period | | | |

### Qualitative Benefits
- Strategic alignment
- Risk reduction
- Customer satisfaction
- Employee productivity

### Risks and Mitigation

| Risk | Impact | Probability | Mitigation |
|------|--------|-------------|------------|
| | | | |

### Implementation Plan
- Key milestones
- Resource requirements
- Timeline

### Recommendation
[Clear recommendation with rationale]

---

## Unit Economics (LTV / CAC)

**Purpose**: Determine whether a business model is viable at the level of a single customer — do you earn more from a customer over their lifetime than it costs to acquire and serve them?

### Core Metrics

```
CAC (Customer Acquisition Cost)
    = Total Sales & Marketing Spend / New Customers Acquired

LTV (Customer Lifetime Value)
    = Average Contribution Margin per Customer per Period × Average Customer Lifetime
    = (ARPU × Gross Margin %) / Churn Rate        ← common subscription shortcut

Customer Lifetime = 1 / Churn Rate
    (e.g., 5% monthly churn → average lifetime of 20 months)

CAC Payback Period = CAC / (ARPU × Gross Margin %)
    (months of margin needed to recover the acquisition cost)
```

### Decision Rules of Thumb

| Metric | Healthy | Warning |
|--------|---------|---------|
| LTV : CAC ratio | ≥ 3× | < 1× means every new customer destroys value |
| CAC payback | < 12 months | > 24 months strains cash even if LTV/CAC looks fine |
| Churn (SaaS, monthly) | < 2% | > 5% caps growth regardless of acquisition |

An LTV:CAC far above 3× isn't automatically good either — it can mean under-investment in growth.

### How to Use

1. **Compute contribution margin per customer**, not revenue — LTV built on revenue overstates value; use gross margin after cost-to-serve.
2. **Compute CAC on a fully loaded basis** — include salaries and tooling of sales/marketing, not just ad spend.
3. **Compare LTV to CAC and check payback** — the ratio tests viability, payback tests cash burn.
4. **Segment before averaging** — blended unit economics often hide one great channel/segment subsidizing a terrible one. Compute per channel, segment, or cohort.
5. **Test the levers** — price, churn, cost-to-serve, and CAC each move the model differently; use Sensitivity Analysis to find which lever matters most.

### Example

A subscription service:

| Input | Value |
|-------|-------|
| Monthly subscription (ARPU) | $50 |
| Gross margin | 70% |
| Monthly churn | 4% |
| Sales & marketing spend / month | $200,000 |
| New customers / month | 1,000 |

**Calculation**:
- CAC: $200,000 / 1,000 = **$200**
- Customer lifetime: 1 / 4% = 25 months
- LTV: $50 × 70% × 25 = **$875**
- LTV : CAC = $875 / $200 = **4.4×** → healthy
- CAC payback: $200 / ($50 × 70%) = **5.7 months** → healthy

**So what?** The model is viable; the biggest lever is churn — cutting it from 4% to 3% raises LTV to ~$1,167 (+33%) without spending another marketing dollar.

### Limitations

- LTV is a projection built on churn holding steady — early-stage churn data is noisy and cohorts often decay differently
- Ignores time value of money (discount long lifetimes for rigor)
- Blended averages conceal segment differences — always check the split
- CAC rises as you saturate the best channels; today's ratio won't hold at scale

**Combines well with**: Break-Even (volume needed to cover fixed costs), Sensitivity Analysis (which lever matters), Profitability Framework in [cases.md](cases.md) (diagnosing where margin leaks).

---

## Quick Decision Guide

| When to Use | Framework |
|-------------|-----------|
| Simple comparison of alternatives | ROI |
| Long-term investments with many cash flows | NPV |
| Finding the break-even return rate | IRR |
| Risk-averse, need quick recovery | Payback |
| Pricing and volume decisions | Break-Even |
| Business model / customer profitability | Unit Economics (LTV/CAC) |
| Understanding key drivers | Sensitivity |
| Complete investment decision | Business Case |

### Decision Hierarchy

1. **NPV** is the gold standard - maximizes shareholder value
2. **IRR** is useful for comparing projects of similar risk
3. **Payback** adds a liquidity/risk constraint
4. **ROI** is simple but should be supplementary
