---
title: "APIs and Integration"
impact: MEDIUM
impactDescription: "Supporting concept that enhances domain understanding"
tags: apis, integration, quantitative, technology
---

**API (Application Programming Interface)**: Set of rules allowing programs to communicate and share data. Don't need to build everything yourself; integrate third-party services.

**REST APIs**: Most common web integration pattern. Client sends HTTP request specifying action (GET, POST, PUT, DELETE), resource, parameters. Server responds with data (JSON).

**Webhooks**: Reverse of API; instead of your app asking provider, provider sends data to your app when event happens. Example: Customer makes purchase via Stripe; Stripe sends webhook with details; your app processes (send receipt, update inventory). Benefits: Real-time, no constant polling.

**Authentication and Rate Limiting**: 
- **API authentication**: API key (simple, less secure) or OAuth (redirect to provider's login, secure)
- **Rate limiting**: Provider limits requests per minute/hour preventing abuse
