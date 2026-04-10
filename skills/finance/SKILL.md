---

## name: finance
description: >-
  Use this skill whenever the user asks about financial analysis, valuation, accounting, capital structure, balance sheets, financial statements, DCF, WACC, equity analysis, debt markets, credit analysis, M&A finance, corporate finance, financial reporting, working capital, cash flow analysis, financial modeling, cost of capital, capital allocation, financial metrics, IPOs, term sheets, risk management, derivatives, fintech, or any question involving company valuation, financial statement interpretation, or investment decisions.
license: MIT
metadata:
  author: ISB-Knowledge-Repository
  version: "1.0.0"

# ISB Finance

Compact router for isb finance domain knowledge. Scan the priority table below, then load specific rule files from `rules/` as needed.

## Priority Table


| Priority | Section                                     | Files | Key Concepts                                                                                                       |
| -------- | ------------------------------------------- | ----- | ------------------------------------------------------------------------------------------------------------------ |
| MEDIUM   | Financial Statements & Fundamentals         | 3     | Key Insight: The Three Statements Connec, The Accounting Equation: Foundation of A, The Three Financial Statements |
| MEDIUM   | Financial Ratio Analysis                    | 5     | Efficiency Ratios, Leverage (Solvency) Ratios, Liquidity Ratios                                                    |
| CRITICAL | DuPont Analysis & Performance Decomposition | 1     | DUPONT ANALYSIS & PERFORMANCE DECOMPOSIT                                                                           |
| CRITICAL | Valuation Methodologies                     | 5     | CAPM (Capital Asset Pricing Model), Comparable Multiples Valuation, DCF (Discounted Cash Flow) Valuation           |
| CRITICAL | Cost of Capital                             | 2     | Industry WACC Ranges (as of 2026), Understanding WACC Components                                                   |
| MEDIUM   | Corporate Finance & Capital Structure       | 4     | Levering/Unlevering Beta, Modigliani-Miller Theorem, Pecking Order Theory                                          |
| HIGH     | Mergers & Acquisitions                      | 6     | Accretion/Dilution Analysis, Common Red Flags in Due Diligence, Hostile Takeovers & Defenses                       |
| MEDIUM   | Private Equity & LBOs                       | 4     | LBO Modeling, PE Exits, PE Fund Economics                                                                          |
| HIGH     | Risk Management & Derivatives               | 4     | Derivatives for Hedging, Hedging Effectiveness, Types of Financial Risk                                            |
| CRITICAL | Specialized Finance Topics                  | 5     | AI in Finance, Bank Valuation, Behavioral Finance & Investor Bias                                                  |
| MEDIUM   | Working Capital Management                  | 1     | WORKING CAPITAL MANAGEMENT                                                                                         |
| CRITICAL | Key Financial Formulas                      | 8     | Capital Structure, DuPont, Efficiency                                                                              |


## Quick Reference by Category

### Financial Statements & Fundamentals (`statements-*`)

- [[rules/statements-key-insight-the-three-statements-connect.md|Key Insight: The Three Statements Connect]]
- [[rules/statements-the-accounting-equation-foundation-of-all-finance.md|The Accounting Equation: Foundation of All Finance]]
- [[rules/statements-the-three-financial-statements.md|The Three Financial Statements]]

### Financial Ratio Analysis (`ratios-*`)

- [[rules/ratios-efficiency-ratios.md|Efficiency Ratios]]
- [[rules/ratios-leverage-solvency-ratios.md|Leverage (Solvency) Ratios]]
- [[rules/ratios-liquidity-ratios.md|Liquidity Ratios]]
- [[rules/ratios-pitfalls-to-avoid.md|Pitfalls to Avoid]]
- [[rules/ratios-profitability-ratios.md|Profitability Ratios]]

### DuPont Analysis & Performance Decomposition (`dupont-*`)

- [[rules/dupont-dupont-analysis-performance-decomposition.md|DUPONT ANALYSIS & PERFORMANCE DECOMPOSITION]]

### Valuation Methodologies (`valuation-*`)

- [[rules/valuation-capm-capital-asset-pricing-model.md|CAPM (Capital Asset Pricing Model)]]
- [[rules/valuation-comparable-multiples-valuation.md|Comparable Multiples Valuation]]
- [[rules/valuation-dcf-discounted-cash-flow-valuation.md|DCF (Discounted Cash Flow) Valuation]]
- [[rules/valuation-valuation-triangulation.md|Valuation Triangulation]]
- [[rules/valuation-wacc-weighted-average-cost-of-capital.md|WACC (Weighted Average Cost of Capital)]]

### Cost of Capital (`costcap-*`)

- [[rules/costcap-industry-wacc-ranges-as-of-2026.md|Industry WACC Ranges (as of 2026)]]
- [[rules/costcap-understanding-wacc-components.md|Understanding WACC Components]]

### Corporate Finance & Capital Structure (`corpfin-*`)

- [[rules/corpfin-leveringunlevering-beta.md|Levering/Unlevering Beta]]
- [[rules/corpfin-modigliani-miller-theorem.md|Modigliani-Miller Theorem]]
- [[rules/corpfin-pecking-order-theory.md|Pecking Order Theory]]
- [[rules/corpfin-trade-off-theory.md|Trade-Off Theory]]

### Mergers & Acquisitions (`ma-*`)

- [[rules/ma-accretiondilution-analysis.md|Accretion/Dilution Analysis]]
- [[rules/ma-common-red-flags-in-due-diligence.md|Common Red Flags in Due Diligence]]
- [[rules/ma-hostile-takeovers-defenses.md|Hostile Takeovers & Defenses]]
- [[rules/ma-ma-process.md|M&A Process]]
- [[rules/ma-strategic-rationale-for-ma.md|Strategic Rationale for M&A]]
- [[rules/ma-synergy-realization.md|Synergy Realization]]

### Private Equity & LBOs (`pe-*`)

- [[rules/pe-lbo-modeling.md|LBO Modeling]]
- [[rules/pe-pe-exits.md|PE Exits]]
- [[rules/pe-pe-fund-economics.md|PE Fund Economics]]
- [[rules/pe-value-creation-levers.md|Value Creation Levers]]

### Risk Management & Derivatives (`risk-*`)

- [[rules/risk-derivatives-for-hedging.md|Derivatives for Hedging]]
- [[rules/risk-hedging-effectiveness.md|Hedging Effectiveness]]
- [[rules/risk-types-of-financial-risk.md|Types of Financial Risk]]
- [[rules/risk-value-at-risk-var.md|Value-at-Risk (VaR)]]

### Specialized Finance Topics (`specialized-*`)

- [[rules/specialized-ai-in-finance.md|AI in Finance]]
- [[rules/specialized-bank-valuation.md|Bank Valuation]]
- [[rules/specialized-behavioral-finance-investor-bias.md|Behavioral Finance & Investor Bias]]
- [[rules/specialized-financial-inclusion-emerging-markets-context.md|Financial Inclusion & Emerging Markets Context]]
- [[rules/specialized-real-estate-finance.md|Real Estate Finance]]

### Working Capital Management (`workcap-*`)

- [[rules/workcap-working-capital-management.md|WORKING CAPITAL MANAGEMENT]]

### Key Financial Formulas (`formulas-*`)

- [[rules/formulas-capital-structure.md|Capital Structure]]
- [[rules/formulas-dupont.md|DuPont]]
- [[rules/formulas-efficiency.md|Efficiency]]
- [[rules/formulas-growth-sustainability.md|Growth & Sustainability]]
- [[rules/formulas-leverage.md|Leverage]]
- [[rules/formulas-liquidity.md|Liquidity]]
- [[rules/formulas-profitability.md|Profitability]]
- [[rules/formulas-valuation.md|Valuation]]

## Usage

1. **Scan this SKILL.md** to identify relevant sections
2. **Read `rules/_sections.md`** for the full index with impact levels
3. **Load specific rule files** from `rules/` directory as needed
4. Each rule file is self-contained with one concept, examples, and formulas