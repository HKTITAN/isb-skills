---
title: "Scheduling"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: scheduling
---

**Network Diagrams**: Visual representation of task sequence and dependencies.
- Activity-on-Node (AON): Boxes are activities, arrows are dependencies
- Activity-on-Arrow (AOA): Arrows are activities, nodes are events

**Critical Path Method (CPM)**:
- Forward pass: Earliest start and finish times (ES, EF). ES_j = max(EF_i) for all predecessors
- Backward pass: Latest start and finish times (LS, LF). LF_j = min(LS_k) for all successors
- Slack (Float): LS - ES or LF - EF; time activity can slip without delaying project
- Critical path: Sequence of activities with zero slack determining minimum project duration (any slip delays project)
- Critical activities need close management; non-critical have flexibility
- Project duration: Maximum path through network (total duration of critical path)
- Crashing: Reducing activity duration (costs more, requires resources); critical path activities matter
- Time-cost tradeoff: Chart cost vs. time; often exponential (crashing later activities very expensive)

**PERT (Program Evaluation and Review Technique)**:
- Three time estimates: optimistic (O), most likely (M), pessimistic (P)
- Expected time: (O + 4M + P) / 6 (weighted toward most likely)
- Variance: ((P - O) / 6)² (range squared divided by 36)
- Standard deviation: √variance
- Accounts for uncertainty; more realistic than single point estimates
- Useful when activities are novel, uncertain, or research-oriented
- Project duration uncertainty: Variance of critical path = sum of task variances on critical path
- Difference from CPM: CPM uses single time estimate; PERT uses three and probability

**Gantt Charts**: Horizontal bars representing activities and duration; visual timeline.

**Dependency Types**:
- Finish-to-Start: Activity B cannot start until A finishes (most common)
- Start-to-Start: B cannot start until A starts
- Finish-to-Finish: B cannot finish until A finishes
- Start-to-Finish: B cannot finish until A starts (rarely used)

**Critical Chain Project Management**: 
- Traditional projects: Each task padded (contingency); padding consumed by early inefficiencies; project still late
- Critical chain approach: Allocate buffers strategically to critical chain only (not individual activities); protects overall schedule
- Benefits: Eliminates task padding; forces focus on critical chain; reduces overall schedule variance
- Buffer management: Track buffer consumption; investigate when buffers deplete too fast

**Schedule Variance and Schedule Performance Index (SPI)**:
- Schedule Variance (SV): Earned Value (EV) - Planned Value (PV); positive means ahead of schedule
- Schedule Performance Index (SPI): EV / PV; > 1 means ahead, < 1 means behind
- Useful for tracking schedule status; paired with cost metrics
