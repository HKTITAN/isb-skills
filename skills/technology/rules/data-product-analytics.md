---
title: "Product Analytics"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: analytics, product, quantitative, technology
---

**Metrics Funnel**:

```
Users Acquired → Users Activated → Users Engaged → Users Retained → Users Monetized
```

**Core Engagement Metrics**:

- **Monthly Active Users (MAU) and Daily Active Users (DAU)**: Number of unique users in product at least once per month/day. Baseline measure of reach; critical for fundraising. High MAU with low DAU indicates weak engagement.
- **Activation**: Users completing key actions indicating they "get" the product (profile setup, first transaction, first message, first report). Activation Rate: % of sign-ups completing activation. Target: 30-40%.
- **Engagement**: Users actively using product. Metrics: Session Frequency (sessions per week), Session Duration (avg time per session), Feature Adoption (% using feature), Action Frequency (key actions per week).
- **Power Users**: Top 10-20% by engagement generating 80%+ of value. Often best advocates and upsell targets.

**Retention Analysis**:

Group users by signup date and track % returning at subsequent periods. Healthy retention: 40%+ retained at 4 weeks, curve flattening (stable engaged users), improvement with newer cohorts. Unhealthy: <20% at 4 weeks (product-market fit issues), steep decline weeks 4-12 (engagement problems).

**Churn**: Inverse of retention; % of users discontinuing use. Critical periods: Week 1-2 (users realizing not for them), Month 2-3 (after initial trial), seasonal patterns.

**Funnel Analysis**: Track users through sequential stages toward conversion. Identify biggest drop-offs; prioritize by impact: (Drop Rate × Downstream Value) × Improvement Potential.

**Cohort Analysis**: Group users by signup date, behavior, or feature adoption. Reveals product improvement impact and behavioral patterns predictive of retention. Example: Users adopting Feature A show better retention, indicating its value.

**A/B Testing**:

- **Hypothesis**: Specific prediction about impact. Strong hypothesis: "Changing button from gray to red increases sign-ups 10%."
- **Metrics**: Primary (optimizing), Secondary (unintended consequences), Guardrail (cannot decrease)
- **Sample Size**: 10,000 users per variant detects 10% improvement
- **Test Duration**: Run full week cycles to capture day-of-week variation; minimum 1-2 weeks
- **Statistical Significance**: P-value < 0.05 means 95% confident results not due to chance
- **Pitfalls**: Multiple comparisons inflates false positives; novelty effect; segment interactions

**North Star Metric**: Single metric representing customer value aligned with business model. Characteristics: leads to long-term success, influenced by product improvements, understandable, measurable. Examples: Slack (Message volume), Airbnb (Nights booked), Netflix (Engagement hours).

**Product-Led Growth Metrics**:

- **Free-to-Paid Conversion**: % of free users converting to paid (10-15% benchmark)
- **Time to Paid Conversion**: How quickly users upgrade (faster = better)
- **Upgrade Rate**: % upgrading to higher tier
- **Free Trial Completion**: % completing trial (50%+ target)
- **Viral Coefficient**: New users each user brings = (Invites per User) × (Conversion Rate). V>1 = exponential growth.

---

