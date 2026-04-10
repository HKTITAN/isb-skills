---
name: mba-tutor
description: >-
  Use this skill whenever the user asks about MBA concepts, business fundamentals, case studies, case analysis, business school topics, management education, cross-functional business problems, integrated business thinking, competitive analysis, industry analysis, company analysis, business frameworks, management principles, or learning business concepts.
license: MIT
metadata:
  author: ISB-Knowledge-Repository
  version: "1.0.0"
---

# ISB MBA Tutor

Compact router for isb mba tutor domain knowledge. Scan the priority table below, then load specific rule files from `rules/` as needed.

## Priority Table

| Priority | Section | Files | Key Concepts |
|----------|---------|-------|-------------|
| MEDIUM | Cross-Domain Connections | 8 | CROSS-DOMAIN CONNECTIONS, Economics ↔ Strategy, Entrepreneurship ↔ Finance |
| MEDIUM | Case Analysis Framework | 7 | CASE ANALYSIS FRAMEWORK, INTEGRATION EXERCISE: THE COMPLETE ANALY, Step 1: Situation Analysis (Context and  |
| CRITICAL | Integrated Thinking by Domain | 23 | AI and Machine Learning, Brand and Positioning, Capital Structure and Strategy |
| CRITICAL | Cross-Case Analysis Patterns | 4 | Industry Disruption Pattern, Market Entry Strategy Pattern, Performance Decline Pattern |
| CRITICAL | Core Frameworks to Teach | 6 | Ansoff Matrix (Growth Strategy), Boston Consulting Group Matrix, McKinsey 7-S Framework |
| CRITICAL | Teaching Approaches | 5 | Teaching Leadership, Teaching Product-Market Fit, Teaching Strategy |
| MEDIUM | Assessment & Feedback | 3 | Common Signs of Surface-Level Understand, Feedback Approach, How to Know Understanding is Real |
| CRITICAL | Advanced Topics for Integrated Thinking | 4 | Digital Disruption and Strategic Respons, Organizational Capability and Strategic , Platform Strategy and Winner-Take-Most D |

## Quick Reference by Category

### Cross-Domain Connections (`connections-*`)
- [[rules/connections-cross-domain-connections.md|CROSS-DOMAIN CONNECTIONS]]
- [[rules/connections-economics-strategy.md|Economics ↔ Strategy]]
- [[rules/connections-entrepreneurship-finance.md|Entrepreneurship ↔ Finance]]
- [[rules/connections-finance-strategy.md|Finance ↔ Strategy]]
- [[rules/connections-leadership-operations.md|Leadership ↔ Operations]]
- [[rules/connections-marketing-economics.md|Marketing ↔ Economics]]
- [[rules/connections-operations-strategy.md|Operations ↔ Strategy]]
- [[rules/connections-technology-all-domains.md|Technology ↔ All Domains]]

### Case Analysis Framework (`case-*`)
- [[rules/case-case-analysis-framework.md|CASE ANALYSIS FRAMEWORK]]
- [[rules/case-integration-exercise-the-complete-analysis.md|INTEGRATION EXERCISE: THE COMPLETE ANALYSIS]]
- [[rules/case-step-1-situation-analysis-context-and-diagnosis.md|Step 1: Situation Analysis (Context and Diagnosis)]]
- [[rules/case-step-2-problem-identification.md|Step 2: Problem Identification]]
- [[rules/case-step-3-alternative-generation.md|Step 3: Alternative Generation]]
- [[rules/case-step-4-recommendation.md|Step 4: Recommendation]]
- [[rules/case-step-5-implementation-plan.md|Step 5: Implementation Plan]]

### Integrated Thinking by Domain (`integrated-*`)
- [[rules/integrated-ai-and-machine-learning.md|AI and Machine Learning]]
- [[rules/integrated-brand-and-positioning.md|Brand and Positioning]]
- [[rules/integrated-capital-structure-and-strategy.md|Capital Structure and Strategy]]
- [[rules/integrated-change-management-and-implementation.md|Change Management and Implementation]]
- [[rules/integrated-competitive-advantage.md|Competitive Advantage]]
- [[rules/integrated-competitive-response-and-game-theory.md|Competitive Response and Game Theory]]
- [[rules/integrated-culture-and-strategy.md|Culture and Strategy]]
- [[rules/integrated-customer-acquisition-and-lifetime-value.md|Customer Acquisition and Lifetime Value]]
- [[rules/integrated-digital-transformation.md|Digital Transformation]]
- [[rules/integrated-efficiency-vs-flexibility-tradeoff.md|Efficiency vs Flexibility Tradeoff]]
- [[rules/integrated-elasticity-and-pricing.md|Elasticity and Pricing]]
- [[rules/integrated-financial-statements-and-what-they-reveal.md|Financial Statements and What They Reveal]]
- [[rules/integrated-leadership-styles-and-context.md|Leadership Styles and Context]]
- [[rules/integrated-market-positioning.md|Market Positioning]]
- [[rules/integrated-market-structures-and-competition.md|Market Structures and Competition]]
- [[rules/integrated-network-effects-and-platform-dynamics.md|Network Effects and Platform Dynamics]]
- [[rules/integrated-organizational-design.md|Organizational Design]]
- [[rules/integrated-quality-and-cost.md|Quality and Cost]]
- [[rules/integrated-segmentation-and-targeting.md|Segmentation and Targeting]]
- [[rules/integrated-supply-chain-as-competitive-advantage.md|Supply Chain as Competitive Advantage]]
- [[rules/integrated-technology-as-enabler-vs-differentiator.md|Technology as Enabler vs Differentiator]]
- [[rules/integrated-unit-economics-and-scalability.md|Unit Economics and Scalability]]
- [[rules/integrated-valuation-and-strategic-decisions.md|Valuation and Strategic Decisions]]

### Cross-Case Analysis Patterns (`patterns-*`)
- [[rules/patterns-industry-disruption-pattern.md|Industry Disruption Pattern]]
- [[rules/patterns-market-entry-strategy-pattern.md|Market Entry Strategy Pattern]]
- [[rules/patterns-performance-decline-pattern.md|Performance Decline Pattern]]
- [[rules/patterns-scaling-challenges-pattern.md|Scaling Challenges Pattern]]

### Core Frameworks to Teach (`frameworks-*`)
- [[rules/frameworks-ansoff-matrix-growth-strategy.md|Ansoff Matrix (Growth Strategy)]]
- [[rules/frameworks-boston-consulting-group-matrix.md|Boston Consulting Group Matrix]]
- [[rules/frameworks-mckinsey-7-s-framework.md|McKinsey 7-S Framework]]
- [[rules/frameworks-porters-five-forces-competitive-analysis.md|Porter's Five Forces (Competitive Analysis)]]
- [[rules/frameworks-strategic-group-analysis.md|Strategic Group Analysis]]
- [[rules/frameworks-vrio-framework-resource-analysis.md|VRIO Framework (Resource Analysis)]]

### Teaching Approaches (`teaching-*`)
- [[rules/teaching-teaching-leadership.md|Teaching Leadership]]
- [[rules/teaching-teaching-product-market-fit.md|Teaching Product-Market Fit]]
- [[rules/teaching-teaching-strategy.md|Teaching Strategy]]
- [[rules/teaching-teaching-unit-economics.md|Teaching Unit Economics]]
- [[rules/teaching-teaching-valuation.md|Teaching Valuation]]

### Assessment & Feedback (`assessment-*`)
- [[rules/assessment-common-signs-of-surface-level-understanding.md|Common Signs of Surface-Level Understanding]]
- [[rules/assessment-feedback-approach.md|Feedback Approach]]
- [[rules/assessment-how-to-know-understanding-is-real.md|How to Know Understanding is Real]]

### Advanced Topics for Integrated Thinking (`advanced-*`)
- [[rules/advanced-digital-disruption-and-strategic-response.md|Digital Disruption and Strategic Response]]
- [[rules/advanced-organizational-capability-and-strategic-execution.md|Organizational Capability and Strategic Execution]]
- [[rules/advanced-platform-strategy-and-winner-take-most-dynamics.md|Platform Strategy and Winner-Take-Most Dynamics]]
- [[rules/advanced-sustainability-and-social-enterprise.md|Sustainability and Social Enterprise]]

## Usage

1. **Scan this SKILL.md** to identify relevant sections
2. **Read `rules/_sections.md`** for the full index with impact levels
3. **Load specific rule files** from `rules/` directory as needed
4. Each rule file is self-contained with one concept, examples, and formulas
