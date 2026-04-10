---
title: "Inventory Management"
impact: HIGH
impactDescription: "Important concept frequently tested in cases"
tags: frameworks, inventory, management, operations, quantitative
---

**ABC Analysis**:
- A items: 20% of SKUs but 80% of value; tight control, frequent review
- B items: Medium value; moderate control
- C items: Low value; loose control, periodic review

**Economic Order Quantity (EOQ)**:
Formula: Q* = √(2DS/H)
- D = annual demand (units)
- S = order/setup cost per order
- H = holding cost per unit per year
- Balances ordering costs (decrease with larger orders) and holding costs (increase with larger orders)
- Total cost = (D/Q)×S + (Q/2)×H

**Key Assumptions/Limitations of EOQ**:
- Assumes constant known demand (reality: lumpy, seasonal, variable)
- Assumes instant replenishment (reality: lead time exists)
- Assumes no quantity discounts (reality: bulk discounts common)
- Real-world adjustments: continuous vs. periodic review systems, VMI, JIT, demand-driven systems

**Safety Stock Calculation**:
Formula: SS = Z × σ × √L
- Z = z-score for desired service level (1.65 for 95%, 2.33 for 99%)
- σ = standard deviation of demand
- L = lead time in periods

**Reorder Point (ROP)**:
Formula: ROP = (d × L) + SS
- d = average daily/weekly demand
- L = lead time
- Triggers order when inventory reaches this level

**Service Level Tradeoff**: 95% service level means out of stock 5% of time (lower inventory); 99% service requires 2.33σ vs. 1.65σ of safety stock (substantially more inventory).

**Lead Time Reduction Benefit**: 
- ROP = d × L + SS; reducing lead time from 2 weeks to 1 week cuts ROP by ~50% (L is reduced)
- Safety stock = Z × σ × √L; reducing L by half cuts safety stock by ~30% (√L reduced)
- Combined: Lead time reduction often allows largest inventory reductions
- Strategic priority: Improve supplier reliability and reduce lead times for high-value items

**Lead Time Variability**: Unpredictable lead times (variance high) require larger safety stock than long but predictable lead times.
- Coefficient of variation: σ / μ (relative variability)
- Highly variable suppliers risky (large safety stock needed) vs. reliable suppliers allow lower safety stock

**Demand Allocation**: When constrained, allocate more inventory to high-margin products, high-value customers, or products with longer lead times.

**Markdown Strategies**: For excess inventory, discount to clear before obsolescence. Aggressive early markdowns free capital; conservative markdowns gamble on continued sales. Optimal strategy depends on forecast error and holding costs.

**Seasonal Products**: Forecast demand by season, build inventory in advance, manage markdowns for excess. Portfolio approach: some trend bets (higher risk/reward), others safe basics.

**Inventory Accounting and Valuation**: 
- FIFO (First-In-First-Out): Lower costs, higher profits in inflation, matches physical flow in many industries
- LIFO (Last-In-First-Out): Higher costs, lower profits and taxes in inflation, matches economic reality but can distort ending inventory value
- Weighted Average: Smooths cost variations
- Obsolescence Reserves: Write down aging inventory; common in fashion, electronics, pharmaceuticals

**Inventory Turns and Days Inventory Outstanding (DIO)**:
- Turns = COGS / Average Inventory (higher is better; faster cash conversion)
- DIO = 365 / Inventory Turns (days inventory sits before sale)
- Industry varies: Perishables (10+ turns/year), durables (2-4 turns/year)
- High turns free capital but risk stockouts

**Demand Allocation Under Constraint**:
- When total demand exceeds supply, allocate inventory to:
  1. High-margin products (maximize profit, not volume)
  2. High-value customers (preserve relationships)
  3. Products with longer lead times (earlier demand materializes)
  4. Stable-demand products (reduce forecast error risk)
