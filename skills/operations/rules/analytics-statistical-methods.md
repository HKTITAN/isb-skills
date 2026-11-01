---
title: "Statistical Methods"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: methods, statistical, technology
---

**Descriptive Statistics**: Mean, median, standard deviation, correlation summarize data.

- Variance: Measure of spread; σ² (squared units, less intuitive)
- Standard deviation: σ (square root of variance, same units as data)
- Coefficient of variation (CV): σ / mean (normalized measure, allows comparison across scales)
- Skewness: Asymmetry of distribution (positive = right-tail, negative = left-tail)
- Kurtosis: Heaviness of tails (normal = 3, high = outliers)

**Probability Distributions**:

- Normal: Bell curve; mean ± σ contains 68%, ±2σ contains 95%, ±3σ contains 99.7%
- Poisson: Models count data (arrivals, defects); parameter λ
- Exponential: Memoryless; time between arrivals or service times
- Uniform: All outcomes equally likely
- Binomial: Fixed n trials, probability p of success
- Triangular: Uses min/likely/max estimates (useful with limited data)

**Hypothesis Testing**: Determine if observed difference is real or due to chance.

- Null hypothesis (H0): No effect
- Alternative hypothesis (H1): Effect exists
- P-value: Probability of result if null is true; reject if p < 0.05
- Common tests: t-test (means), chi-square (categorical), ANOVA (multiple groups)
- Type I error (α): False positive (rejecting true H0)
- Type II error (β): False negative (failing to reject false H0)
- Power (1-β): Probability of detecting true effect

**Confidence Intervals**: Range around point estimate where true parameter likely lies (e.g., 95% confident true mean is between X and Y).

- Standard error: SE = σ / √n (smaller for larger samples)
- CI = point estimate ± z × SE

**Regression Analysis**:

- Simple: y = a + bx (one dependent, one independent)
- Multiple: Multiple independent variables; y = a + b₁x₁ + b₂x₂ + ... + bₙxₙ
- R-squared: Proportion of variation explained; higher is better (0 to 1)
- Adjusted R²: Penalizes adding variables; better for comparing models with different numbers of predictors
- Standard error of regression: Residual standard deviation
- Assumptions: Linearity, independence, normality of residuals, homoscedasticity (constant variance)
- Multicollinearity: High correlation between independent variables; causes unstable coefficients
- Model selection: Add variables if they improve adjusted R² or reduce AIC/BIC

**Categorical Analysis**: 

- Chi-square test: Tests independence between two categorical variables
- Contingency tables: Cross-tabulation of categorical variables
- Standardized residuals: Identify cells deviating most from independence

**ANOVA (Analysis of Variance)**: Tests whether means differ significantly across multiple groups.

- F-statistic: Ratio of between-group variance to within-group variance
- F > critical value suggests at least one group mean differs significantly