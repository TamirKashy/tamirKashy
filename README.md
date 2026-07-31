# Tamir Shevchenko Kashy

**Computer Science undergraduate (HIT, expected 2027). I build and run production web services.**

Most of my work is live software with real users, billing, and uptime concerns rather than practice projects. The product source is private, but the systems themselves are public — you can sign up and use both of them right now.

---

## What I'm running

<a href="ttps://zapifyapi.com"><img src="zapifyapi.png" alt="Zapify API dashboard" width="400"></a>

### [zapifyapi.com](https://zapifyapi.com) — Image Conversion API

A token-metered HTTP API that converts PNG/JPEG to WEBP in a single authenticated request.

- Bearer API-key authentication, per-key rate limiting, and signed URLs
- Token metering with per-request deduction, pay-as-you-go packs, and tiered subscriptions gating premium endpoints
- Self-serve dashboard for signup, API-key management, and live usage tracking
- Direct ingest from S3/GCS; conversion parameters for quality, resize, background fill, and metadata stripping
- Responses expose rate-limit, token-balance, and request-ID headers so clients can back off and trace failures

**Stack:** PHP · JavaScript · MySQL · REST

---
<a href="ttps://playfree.uk"><img src="Playfree.png" alt="playfree.uk server dashboard" width="400"></a>

### [playfree.uk](https://playfree.uk) — On-Demand Game Server Hosting

Free Minecraft Java server hosting that provisions an isolated server per user in 30–60 seconds.

- Orchestrates the Pterodactyl API to provision, boot, and tear down containerised game servers on demand
- Session-based lifecycle with world state persisted across restarts
- Priority queue and tiered resource quotas (RAM, disk, player cap, concurrent servers) to keep a free tier sustainable on fixed capacity
- Automated per-user subdomain allocation via DNS SRV records — players connect on a stable address with no IP or port
- Live dashboard reporting servers online, queue depth, and active players

**Stack:** Next.js · PHP · Docker · Pterodactyl · Coolify

---

## Background

Three years of enterprise IT and networking field work before and alongside my degree — Centrex IP telephony deployments, voice VLAN and QoS design, and nationwide hardware rollouts for enterprise clients including Strauss Group and Microsoft. At Strauss I built an automated network-based imaging pipeline that scaled concurrent device provisioning from 2 to 10+.

That background is why I tend to think about the deployment and operating cost of a system, not just the code.

---

## Currently

- **B.Sc. Computer Science, Holon Institute of Technology** — Machine Learning, Computability & Complexity, Automata & Formal Languages
- Building an AI image-description endpoint for Zapify, running a self-hosted vision model behind the existing metering and rate-limiting layer

**Working with:** C# / .NET · PHP · JavaScript / Next.js · Python · C / C++ · SQL · MongoDB · Docker · Linux

---

## A note on private repositories

Most repos here are private — they're either client work or the source behind the products above. I'm happy to walk through architecture, design decisions, or code directly in an interview.

---

📫 **tamirkashy13@gmail.com** · [LinkedIn](https://www.linkedin.com/in/tamir-shevchenko-kashy)
