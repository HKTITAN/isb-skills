---

## title: "Product Analytics Deep Dive"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: analytics, deep, dive, product, quantitative, technology

**Metrics Funnel**: Users Acquired → Activated → Engaged → Retained → Monetized.

**Key Metrics**:

- **MAU/DAU**: Monthly/daily active users. Baseline reach; high MAU with low DAU indicates weak engagement.
- **Activation**: % completing key actions showing they "get" product. Benchmark: 30-40%.
- **Engagement**: Session frequency, duration, feature adoption, action frequency.
- **Power Users**: Top 10-20% generating 80%+ value. Often best advocates and upsell targets.
- **Retention**: % returning at subsequent periods. Healthy: 40%+ at 4 weeks, curve flattening.
- **Churn**: % discontinuing use. Critical periods: Week 1-2 (not for them), Month 2-3 (post-trial), seasonal.

**Funnel Analysis**: Track through sequential stages. Identify biggest drop-offs. Prioritize by: (Drop Rate × Downstream Value) × Improvement Potential.

**Cohort Analysis**: Group by signup date, behavior, or feature adoption. Reveals product improvement impact and patterns predictive of retention.

**A/B Testing**:

- **Hypothesis**: Specific prediction about impact (strong: "Button red vs gray increases sign-ups 10%")
- **Metrics**: Primary (optimizing), Secondary (unintended consequences), Guardrail (cannot decrease)
- **Sample Size**: Rule of thumb: 10,000 users per variant for 10% improvement
- **Test Duration**: Full week cycles minimum 1-2 weeks for day-of-week variation
- **Significance**: P-value < 0.05 = 95% confident not due to chance
- **Pitfalls**: Multiple comparisons (inflates false positives), novelty effect (users click new just because different), segment interactions (winning variant differs by segment)

**North Star Metric**: Single metric representing customer value aligned with business. Characteristics: leads to long-term success, influenced by product improvements, understandable, measurable.

**PLG Metrics** (Product-Led Growth):

- Free-to-paid conversion: 10-15% benchmark
- Time to paid conversion: How quickly users upgrade
- Upgrade rate: % upgrading to higher tier
- Free trial completion: 50%+ target
- **Viral Coefficient** = (Invites per User) × (Conversion Rate). V<1 requires continuous acquisition; V>1 = exponential growth.

**Northstar and GAME Framework**:

- **Top-down (NSM)**: Start with business vision → Northstar metric → Other metrics ladder into it
- **Bottom-up (GAME)**: Goals (user and business) → Actions (to achieve) → Measures (track actions) → Evaluations (correct measures?)