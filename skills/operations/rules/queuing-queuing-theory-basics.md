---
title: "Queuing Theory Basics"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: basics, queuing, theory
---

**Queue Notation (Kendall)**: A/B/c
- A: Arrival distribution (M=Markovian/Poisson, D=Deterministic, G=General)
- B: Service distribution (M=Exponential, D=Deterministic, G=General)
- c: Number of servers

**M/M/1 Queue** (Poisson arrivals, exponential service, one server):
- Arrival rate λ, service rate μ
- Stability condition: λ < μ
- Average customers in system: L = λ / (μ - λ)
- Average wait in queue: Lq = λ² / [μ(μ - λ)]
- Average wait in system: W = 1 / (μ - λ)
- Average wait in queue: Wq = λ / [μ(μ - λ)]
- Probability of waiting: Pw = λ / μ

**M/M/c Queue** (Multiple servers):
- Requires numerical calculation (Erlang C formula)
- Adding capacity (c) reduces wait times non-linearly
- First server has high marginal impact; each additional server has less impact

**Little's Law**: L = λ × W (average number in system = arrival rate × average time in system)
- Holds for any queue regardless of distribution
- Powerful relationships: If queue has 5 customers and service takes 30 minutes, arrival rate is 10 per hour

**Applications**:
- Staffing decisions: How many servers (cashiers, servers) needed?
- Capacity planning: What service rate needed to meet wait time targets?
- Service level: How to balance server utilization against wait times?

---
