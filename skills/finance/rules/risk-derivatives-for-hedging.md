---
title: "Derivatives for Hedging"
impact: HIGH
impactDescription: "Important concept frequently tested in cases"
tags: derivatives, hedging, leadership, technology
---

**Forwards:** Lock in future price. Customized, no upfront cost, binding.

```
Exporter expects €1M in 90 days
Forward: Lock in 1 EUR = $1.10
Result: Guaranteed $1.1M proceeds regardless of FX movement
```

**Futures:** Standardized, exchange-traded, daily settlement.

```
Oil refiner worried about crude price spike
Buy crude oil futures at $80/barrel
If actual price $95: Futures gain offsets higher spot price
```

**Options:** Right (not obligation) to buy/sell at strike price.

```
Call option: Buy at strike, profit if price > strike + premium
Put option: Sell at strike, profit if price < strike - premium
Cost: Premium paid upfront
Benefit: Limited downside (premium lost), unlimited upside
```

Protective put example:
```
Own $100M equity portfolio
Buy put options (strike 5% below current) for $2M
Downside protected; upside unlimited
Cost: $2M = 2% insurance premium
```

**Swaps:** Exchange cash flows. Interest rate swap, currency swap.

```
Company A: Floating-rate debt, wants fixed
Company B: Fixed-rate debt, wants floating

Swap: A pays B fixed 4.5%, B pays A floating SOFR+2%
A's net: Fixed at 4.5%
B's net: Floating at SOFR+0.5%
```
