# Tiago Ortiz

Senior Software Engineer & founder · Porto Alegre, Brazil (UTC-3)

I design and own systems where software meets revenue: payments, checkout, real-time infrastructure and AI products. Most of my career has been as the engineer closest to the business, so I'm used to deciding what to build, not just how.

### Systems I've designed

- **Real-time platform for 50+ radio stations** · Designed the event-driven layer (MQTT/EMQX) behind live playout data, including automatic failover to a backup source when a station's player goes down. Turned a request/response product into one that reacts to what's on air.
- **Vendor integration layer** · One internal command model translated into 5 external playout and ad systems with different protocols (REST, XML). New vendors plug in without touching the core.
- **Multi-tenant commerce platform (Evonnis)** · White-label e-commerce and back office serving multiple agencies from one codebase, built around revenue recovery: abandoned carts, unsold seats, inactive customers.
- **Payments** · In-house card processing (Cielo) replacing a third-party plugin, Pix lifecycle automation, and Apple Pay / Google Pay / PayPal integrations for PayPal partner merchants.

### Products I've taken from idea to revenue

- **Studio IA** · Generative AI voice-over (LLM + TTS) embedded in radio programming, with usage-based credits and self-serve checkout. Scoped, built and launched end to end; now a separate revenue line.
- **Evonnis** · Founded and run it: discovery with customers, pricing, roadmap and engineering. Led a team of 3.

### How I approach engineering

- **Performance and reliability are product features.** I profile before optimizing and fix root causes in the data-access layer instead of adding caches on top.
- **Security as an owner, not a checklist.** Led incident response and hardening of a live platform: 2FA, credential migration, audit trails.
- **AI-native, human-accountable.** I use coding agents every day and treat their output like any PR: reviewed, tested, and owned by me.
- **Raise the floor for the team.** CI/CD, test environments, PR standards and dev guidelines, so quality doesn't depend on who's coding.

### Stack

PHP · Laravel · Node.js · TypeScript · MySQL · Redis · AWS · Docker · GitHub Actions · MQTT · LLM APIs

[LinkedIn](https://www.linkedin.com/in/tiagoortiz/) · [Evonnis](https://www.evonnis.com)
