---
title: "DCF (Discounted Cash Flow) Valuation"
impact: CRITICAL
impactDescription: "Core MBA framework, foundational to domain"
tags: cash, dcf, discounted, flow, quantitative, valuation
---

**Core Principle:** Business value = Present value of all future cash flows

**Why discount?** Because money today is worth more than money tomorrow.

**Formula:**
```
Enterprise Value = Σ [FCF_t / (1 + WACC)^t] + Terminal Value / (1 + WACC)^n

Where:
- FCF = Free cash flow to the firm
- WACC = Weighted average cost of capital (discount rate)
- Terminal Value = Value of cash flows beyond explicit period
- t = Year
- n = Final explicit forecast year
```

**Step 1: Project Free Cash Flows (5-10 Years)**

```
Starting point: Revenue projections
EBIT (Operating Profit)
- Taxes
= NOPAT (Net Operating Profit After Tax)
+ Depreciation/Amortization (non-cash)
- CapEx (capital expenditures)
- Change in Net Working Capital
= FCFF (Free Cash Flow to Firm)
```

Example projection:
```
Year 1:
Revenue: $500M
EBIT Margin: 20% → EBIT: $100M
Tax Rate: 25%
NOPAT: $100M × 0.75 = $75M
+ D&A: $20M
- CapEx: $30M
- Change in NWC: $5M
= FCFF: $60M
```

**Step 2: Calculate Terminal Value**

The business doesn't end in year 5; it continues indefinitely.

*Method A: Gordon Growth Model*
```
Terminal Value = Year 5 FCFF × (1 + g) / (WACC - g)

Example:
Year 5 FCFF: $100M
Long-term growth (g): 2.5% (near GDP growth)
WACC: 9%

TV = $100M × 1.025 / (0.09 - 0.025) = $100M × 1.025 / 0.065 = $1,577M
```

Sensitivity: Even 0.5% change in growth rate significantly affects value.

*Method B: Exit Multiple*
```
Terminal Value = Year 5 EBITDA × Exit Multiple

Example:
Year 5 EBITDA: $150M
Assumed exit multiple: 10x
TV = $1,500M

Rationale: Use market multiples for sanity check
```

**Step 3: Discount to Present Value**

```
PV of Year 1 FCF = $60M / 1.09^1 = $55.0M
PV of Year 2 FCF = $70M / 1.09^2 = $58.9M
PV of Year 3 FCF = $80M / 1.09^3 = $61.8M
PV of Year 4 FCF = $90M / 1.09^4 = $63.8M
PV of Year 5 FCF = $100M / 1.09^5 = $64.9M
PV of Terminal Value = $1,577M / 1.09^5 = $1,025M

Total Present Value: $55.0 + $58.9 + $61.8 + $63.8 + $64.9 + $1,025M = $1,329.4M
```

**Step 4: Calculate Equity Value**

```
Enterprise Value: $1,329M
- Net Debt:
  (Total Debt: $200M - Cash: $50M): $150M
= Equity Value: $1,179M

÷ Diluted Shares Outstanding: 100M
= Value Per Share: $11.79
```

**Key Sensitivities:**

DCF is sensitive to assumptions. Build sensitivity table:

| WACC / Terminal Growth | 2% | 2.5% | 3% |
|---|---|---|---|
| 8% | $1,650M | $1,900M | $2,250M |
| 9% | $1,250M | $1,330M | $1,500M |
| 10% | $950M | $1,050M | $1,175M |

If stock trades at $10, DCF shows undervalued (most scenarios >$11.79). If stock trades at $25, DCF shows overvalued.
