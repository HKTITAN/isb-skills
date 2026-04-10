---
title: "Simulation & Monte Carlo"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: carlo, monte, simulation, technology
---

**Monte Carlo Simulation**: Generates many random scenarios based on probability distributions and tracks outcomes. Named after Monte Carlo casino (uses randomness like gambling).

**Methodology**:
1. Define probability distributions for uncertain inputs (normal, triangular, uniform, etc.)
2. Randomly sample from distributions
3. Calculate outcome (project cost, delivery time, etc.) for each sample
4. Repeat thousands/millions of times (typically 10,000-100,000)
5. Analyze distribution of outcomes (histogram, percentiles, probability of bad outcomes)

**Applications**:
- Risk Quantification: Distribution of project duration, cost, inventory; probability of missing targets
- Capacity Planning: What capacity handles demand variability? How many servers needed to hit service level?
- Supply Chain Resilience: Impact of disruptions (supplier failure, transportation delay) on delivery, cost
- Facility Layout: Effects of process variability on throughput and wait times
- Portfolio Risk: Value-at-Risk for financial portfolios or investment decisions
- Product Demand: Probability of stockout at different inventory levels

**Value-at-Risk (VaR)**: Probability that loss exceeds certain amount (e.g., 95th percentile loss); used in financial operations and supply chain risk.

**Expected Shortfall**: Average loss in worst x% of scenarios; more conservative than VaR.

**Scenario Modeling**: Run simulations under different strategic scenarios (demand high/medium/low, competitor entry, recession, etc.) to understand sensitivity.

**Convergence**: Results stabilize after 10,000-50,000 iterations for most applications; can verify by checking if results change with additional iterations.

**Validation**: 
- Compare to analytical solutions when available (e.g., EOQ model)
- Backtesting against historical outcomes
- Stress testing with extreme scenarios
- Sensitivity analysis: which input distributions most affect output?

**Probability Distributions**:
- Normal: Bell curve; used for many natural phenomena (defined by mean and standard deviation); symmetric
- Poisson: Models count data and arrival patterns; discrete integers only; parameter λ
- Exponential: Models time between arrivals or service times (memoryless property); always positive
- Uniform: All values equally likely between min and max
- Triangular: Uses min/likely/max when only three estimates known (expert judgment); simple to explain
- Lognormal: Positively skewed; cannot be negative (stock prices, project costs); right-skewed distribution
- Beta: Flexible distribution bounded between 0 and 1; used for project duration percentiles
