---
title: "Bottleneck Analysis and Theory of Constraints (TOC)"
impact: HIGH
impactDescription: "Important concept frequently tested in cases"
tags: analysis, bottleneck, constraints, frameworks, technology, theory
---

A bottleneck (constraint) is the resource or process limiting overall throughput. TOC principle: improving non-constraint resources doesn't improve overall performance (chain is only as strong as weakest link).

**Five Focusing Steps** (repeat continuously):
1. **Identify the constraint**: Which resource operates at full capacity? Where is inventory queuing? Which operation limits throughput?
2. **Exploit the constraint**: Fully utilize it on most valuable work; prevent downtime or waste of constraint capacity (constraint bottleneck is expensive time)
3. **Subordinate non-constraints**: Schedule secondary resources to support constraint; accept lower utilization of non-constraints (idle time on non-constraints is free)
4. **Elevate the constraint**: Invest in constraint capacity only if needed (overtime, additional machines, process improvement). Don't invest in non-constraints.
5. **Return to step 1**: Process repeats as new constraint emerges (don't let constraint improvement become complacency)

**Drum-Buffer-Rope (DBR) Scheduling System**: 
- Drum: Constraint operation sets production pace; paces entire line to match constraint rate
- Buffer: Protective inventory before constraint prevents constraint from starving; absorbs upstream variation
- Rope: Signal back to upstream (release authorization) controls when jobs enter system; prevents excess WIP

**Throughput Accounting**: TOC financial perspective applied to decision-making.
- Throughput = Sales - Variable Costs (contribution before fixed costs)
- Metrics: Throughput, Investment (assets tied up), Operating Expenses
- Prioritize decisions optimizing total system throughput, not individual product margins
- Example: Low-margin product using non-constraint resources preferred to high-margin using constraint resource

**Identifying Constraints Practically**:
- Queuing: Where do jobs wait longest?
- Utilization: Which resource runs 24/7?
- Bottleneck analysis: Track job flow; find slowest step
- Quality: Poor upstream quality causing rework at constraint
- Staffing: Constraint operation understaffed?

**Performance Metrics** (comprehensive):
- Efficiency: minimizing inputs for given output (cycle time, throughput, utilization, OEE)
- Quality: defect rates, conformance, reliability, responsiveness, empathy
- Responsiveness: wait time, delivery speed, order fulfillment time
- Cost: cost per unit, material cost, labor cost, overhead
- Flexibility: Time to change product, response to demand variation

---
