---
title: "Process Design and Flow Analysis"
impact: HIGH
impactDescription: "Important concept frequently tested in cases"
tags: analysis, design, flow, frameworks, marketing, operations, process, technology
---

**Value vs. Waste**: In lean thinking, value is anything a customer pays for; everything else (waiting, redundant checks, motion, idle inventory) is waste.
- Value-adding time: Direct work advancing product/service toward customer need (typically 5-20% of total time)
- Non-value-adding time: Transportation, waiting, inspection, rework, motion
- Lead time = Value-adding time + Non-value-adding time (typically 80%+ is non-value-adding)
- First-pass yield: % of work requiring no rework (high yield reduces rework waste)

**Process Flow Types**:
- Manufacturing: 
  - Flow lines (continuous): High volume, low variety, highly automated (car assembly)
  - Batch processing: Medium volume, grouped identical items, flexible equipment (printing)
  - Job shops: Low volume, high variety, general-purpose equipment, skilled workers (custom engineering)
- Services: low-contact (processing documents) to high-contact (consulting, healthcare, personal services)
- Hybrid: Many operations are mixed (e.g., restaurants have batch prep, then individual assembly)

**Standardization vs. Customization Trade-off**: 
- Standardized processes are repeatable and predictable (McDonald's: identical process worldwide)
- Pure customization is expensive and slow (bespoke tailoring)
- Sweet spot: Narrow customization with standardized components (Shouldice Hospital does only hernias with identical procedures; achieves efficiency with specialization)
- Modular design: Base components assembled/customized for different customer needs

**Flow Analysis Tools**:
- Value stream mapping: Visual trace of steps from raw material to finished product; identifies waste, bottlenecks, lead times. Typical finding: 80%+ of time is waiting, <20% actual work
- Cycle time: Time one unit takes to complete process; includes all delays
- Takt time: Rate at which output should leave process to meet demand. Takt = Available time / Demand. If takt > cycle time, process has excess capacity
- Process flow diagram: Sequence of steps, which are parallel, where inventory queues
- Batch sizing analysis: Large batches reduce setup costs but increase wait times; small batches improve responsiveness (especially important in make-to-order)
- Parallel vs. sequential activities: Some steps must follow others (dependencies); others can overlap (concurrent engineering, parallel development reduces time)
- Lead time = sum of processing times + sum of queue times
