---
title: "Linear Programming"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: linear, programming, technology
---

**Core Concept**: Optimize (maximize/minimize) a linear objective function subject to linear constraints.

**Components**:
- Decision Variables: What we're solving for (e.g., units to produce)
- Objective Function: Linear expression to optimize (e.g., maximize 50X + 40Y)
- Constraints: Linear inequalities/equalities representing limitations (e.g., X + Y ≤ 100)
- Feasible Region: Set of all solutions satisfying constraints; optimal solution at corner point
- Non-negativity Constraints: Variables typically ≥ 0 (no negative production)

**Standard Form**: minimize c^T × x subject to Ax ≤ b, x ≥ 0

**Solution Methods**:
- Graphical Method: For two variables; visual representation; optimal at corner point
- Simplex Algorithm: Computational method moving corner to corner; efficient for large problems; can handle thousands of variables/constraints
- Interior Point Methods: Alternative approach; efficient for very large problems
- Software: Excel Solver, CPLEX, Gurobi, PuLP (Python)

**Duality**: Every LP has a primal and dual; dual provides bounds on optimal value and economic interpretation

**Sensitivity Analysis**:
- Shadow Price (Dual Value): Value of one additional unit of constraint resource; allows quick "what-if" analysis
- Reduced Cost: Amount by which objective coefficient must improve before variable enters solution; indicates unprofitable products
- Allowable Ranges: Ranges where coefficients can vary without changing optimal solution mix
- Binding Constraints: Constraints active at optimal solution; limiting performance

**Applications**:
- Product Mix: Determine production quantities to maximize profit given constraints
- Resource Allocation: Distribute limited resources across activities
- Blending: Combine ingredients to meet specifications at minimum cost
- Transportation/Network Flow: Route shipments to minimize cost while meeting supply/demand
- Workforce Scheduling: Assign workers to shifts to minimize cost while meeting coverage
