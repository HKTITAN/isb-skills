---
title: "Auction Theory and Design"
impact: CRITICAL
impactDescription: "Core MBA framework, foundational to domain"
tags: auction, design, technology, theory, valuation
---

**Auction Fundamentals**
- Purpose: Allocate goods, determine prices when value is uncertain or heterogeneous
- Strategy: Optimal bid depends on auction format, own valuation, expectations about competitors' valuations
- Revenue: Revenue depends on auction design; first-price English typically highest revenue
- Efficiency: Vickrey auction (second-price sealed-bid) efficient; highest valuation always wins at second-highest price

**Auction Formats**
- English auction: Ascending bid; bidders observe other bids; highest bidder wins at own price
  - Strategic insight: Bid up to true valuation (dominant strategy)
  - Outcome: Highest valuation wins at second-highest price (approximately)
  - Common use: Art, real estate, online auctions

- Dutch auction: Descending bid; price starts high, falls; first bidder at announced price wins
  - Strategic insight: Optimal bid depends on expected distribution of competitors' values
  - Outcome: Bidders shade bids below true value
  - Common use: Flowers, agricultural goods

- First-price sealed-bid: Bidders submit hidden bids; highest wins at own bid
  - Strategic insight: Bid shading optimal; shade below true valuation
  - Outcome: Highest valuation wins, but at lower price than English
  - Common use: Government contracts, procurement

- Vickrey auction (second-price sealed-bid): Highest bidder wins but pays second-highest bid
  - Strategic insight: Bidding true value weakly dominant (optimal regardless of others' bids)
  - Outcome: Truthful bidding incentivized; highest valuation always wins
  - Property: Allocative efficiency; incentive compatibility
  - Common use: Spectrum auctions, online advertising

**Revenue Equivalence Theorem**
- Theorem: Under certain conditions (risk-neutral bidders, independent values), different auction formats generate equal expected revenue
- Intuition: Trade-off between price paid (bidders bid higher in sealed-bid) vs. information revelation (affects bid shading)
- Exceptions: Risk-averse bidders, affiliated values, collusion possibilities alter revenue rankings
- Practical implication: Design choice affects efficiency and properties beyond revenue
