---
title: "Levering/Unlevering Beta"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: beta, finance, levering, unlevering
---

When valuing companies with different leverage, adjust beta to reflect financial risk.

**Unlever Beta** (remove leverage effects):
```
Asset β = Levered β / [1 + (1 - Tax Rate) × (D/E)]

Example:
Levered β: 1.5, D/E: 0.5, Tax Rate: 25%
Asset β = 1.5 / [1 + 0.75 × 0.5] = 1.5 / 1.375 = 1.09
```

**Relever Beta** (apply new leverage):
```
New Levered β = Asset β × [1 + (1 - Tax Rate) × (New D/E)]

If new target D/E: 1.0
New Levered β = 1.09 × [1 + 0.75 × 1.0] = 1.09 × 1.75 = 1.91

Higher leverage → Higher cost of equity
```

---
