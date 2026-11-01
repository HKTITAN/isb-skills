---
title: "Agentic AI"
impact: CRITICAL
impactDescription: "Core MBA framework, foundational to domain"
tags: agentic, frameworks, technology
---

**Agentic systems** operate autonomously, breaking complex tasks into subtasks, using tools, and iterating until goals are met.

Unlike traditional models (input → output), agents can:

- **Plan**: Break goal into steps
- **Use tools**: Call APIs, search databases, run code
- **Reflect**: Evaluate progress, adjust strategy
- **Iterate**: Complete subtasks, combine results

**Agent Loop**:

1. Plan—LLM decides what step to take
2. Act—Execute action (API call, query, calculation)
3. Observe—Get feedback on action
4. Reflect—Update understanding based on feedback
5. Repeat—Continue until goal achieved

**Agent Frameworks**: ReAct pattern (Reasoning + Acting), tool use with decision logic. Agent requires access to tools, planning capability, and error recovery mechanisms. Challenges: hallucination (generating false information), context limits (can't process very long documents), cost (LLM API calls expensive at scale).

**Example**: Financial analysis agent given "Analyze whether company X is a good investment." Agent might: search for financial statements, calculate key metrics, research industry trends, analyze competitor performance, synthesize into recommendation. Customer support agent routes to appropriate team, retrieves documentation, drafts responses. Sales agent researches prospects, schedules meetings, logs interactions. Agentic AI represents frontier of practical AI deployment.