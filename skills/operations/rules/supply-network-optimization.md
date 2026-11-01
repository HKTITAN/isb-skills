---
title: "Network Optimization"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: network, optimization, technology
---

**Transportation Problem**: Minimize cost of shipping from multiple sources to multiple destinations.

- Linear programming: minimize ΣΣ c_ij × x_ij subject to supply and demand constraints
- Solution methods: Vogel's approximation, stepping stone, simplex algorithm

**Assignment Problem**: Optimally assign n tasks to n workers to minimize cost or maximize productivity.

- Solution: Hungarian algorithm (polynomial time, much faster than brute-force enumeration)
- Applications: salespeople to territories, machines to jobs, project teams to tasks

**Shortest Path Algorithm (Dijkstra)**: Finds minimum-cost route through network.

- Greedy algorithm, O(n²) complexity
- Applications: vehicle routing, logistics network design

**Network Design and Facility Location**:

**Facility Location Optimization**: Determines number, location, and size of facilities (plants, distribution centers).

- Trade-off: more facilities increase fixed costs but reduce transportation distance and inventory
- Objectives: minimize total cost (production + transportation + facility + working capital) while meeting service constraints (delivery time, fill rate)
- Optimization: minimize Σ f_i×y_i + ΣΣ c_ij×x_ij (fixed costs + transportation costs)
- Models: Mixed-integer programming (facility location is binary 0/1 decision)

**Transportation Problem**: Optimize shipments from m sources to n destinations.

- Given: supply at each source, demand at each destination, cost per unit shipped
- Decision: how many units from source i to destination j
- Solution: Vogel's approximation method, stepping stone method, or simplex algorithm

**Assignment Problem**: Optimally assign n tasks to n workers (or machines, projects, etc.).

- Each worker handles exactly one task; each task handled by exactly one worker
- Minimize total cost or maximize total productivity
- Solution: Hungarian algorithm (polynomial time, much faster than brute force)

**Shortest Path Algorithm (Dijkstra)**: Find minimum-cost route through network.

- Used for vehicle routing, logistics network design, supply chain routing
- Greedy algorithm; O(n²) complexity; can be extended to handle constraints

**Hub-and-Spoke Design**: Consolidation centers (hubs) serve remote locations (spokes).

- Benefits: economies of scale, reduced number of shipping lanes, lower total distance
- Trade-off: transshipment time and cost
- Applications: parcel delivery (regional hubs), airlines (hub cities), LTL freight networks

**Centralized vs. Distributed Networks**:

- Centralized: Economies of scale, simplified management, inventory pooling, but long supply lines and slow response
- Distributed: Proximity to customers, supply resilience, faster delivery, but diseconomies of scale, higher total inventory, and complexity
- Hybrid: Often optimal (e.g., regional distribution centers + local fulfillment centers)