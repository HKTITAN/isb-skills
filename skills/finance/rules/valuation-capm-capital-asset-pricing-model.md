---
title: "CAPM (Capital Asset Pricing Model)"
impact: CRITICAL
impactDescription: "Core MBA framework, foundational to domain"
tags: asset, capital, capm, finance, frameworks, marketing, model, pricing
---

Estimates required return on equity for DCF discount rate.

**Formula:**
```
Cost of Equity = Rf + β × (Rm - Rf)

Where:
- Rf = Risk-free rate (10-year government bond yield)
- β = Beta (systematic risk relative to market)
- Rm - Rf = Market Risk Premium (historical equity premium)
```

**Risk-Free Rate (Rf)**

Use government bond yield matching investment horizon:
- For DCF (long-term): 10-year government bond
- US: Currently ~4-4.5%
- India: ~6-7% (10-year GSec)

**Beta (β)**

Measures systematic risk relative to market:
- β = 1.0: Moves with market (average risk)
- β > 1.0: More volatile (higher risk, higher return required)
- β < 1.0: Less volatile (lower risk, lower return required)

Example:
```
Company A: β = 0.8 (20% less volatile than market) = Defensive stock
Company B: β = 1.5 (50% more volatile than market) = Aggressive stock
```

Levered Beta (reflects actual leverage):
```
Levered β = Asset β × [1 + (1 - Tax Rate) × (Debt/Equity)]

Example:
Asset β: 0.8, Tax Rate: 25%, D/E: 0.5
Levered β = 0.8 × [1 + 0.75 × 0.5] = 0.8 × 1.375 = 1.1
```

Unlevered Beta (debt-free):
```
Asset β = Levered β / [1 + (1 - Tax Rate) × (D/E)]

Use to adjust for different capital structures
```

**Market Risk Premium (Rm - Rf)**

Expected excess return of equities over risk-free rate:
- Historical global average: 6-8%
- India-specific: 6.5-7.5% (includes country risk premium)

**Example CAPM Calculation:**
```
Risk-free rate: 6.5% (India 10-year GSec)
Beta: 1.2 (company more volatile than market)
Market Risk Premium: 7%

Cost of Equity = 6.5% + 1.2 × 7% = 6.5% + 8.4% = 14.9%
```

Interpretation: Equity investors require 14.9% return to compensate for this company's risk.
