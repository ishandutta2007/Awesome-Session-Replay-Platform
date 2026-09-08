# Awesome-Session-Replay-Platform

## Top Session Replay Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Session Recording, User Behavior Replay, Heatmaps, Frontend Debugging & Digital Experience Analytics*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Session Replay**. These tools capture and replay user interactions on websites and applications so teams can understand behavior, debug issues, improve UX, and optimize conversion funnels.

**Examples** include FullStory, LogRocket, Hotjar, Microsoft Clarity, Mouseflow, Lucky Orange, Inspectlet, Smartlook, OpenReplay, Glassbox, UXCam, Quantum Metric, and Contentsquare (the category leaders).

**Open-source emphasis**: Session replay has excellent open-source options. **OpenReplay** is the leading self-hosted dedicated platform. **rrweb** is the foundational MIT-licensed recording/replay library used by many products. **PostHog** also provides robust open-source session replay alongside product analytics. This section is heavily expanded with every major active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Starting Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[FullStory](https://www.fullstory.com/)** | Enterprise digital experience platform offering high-fidelity session replay, autocapture, search, and behavioral analytics. | $0/mo (Free plan) / Paid starts at ~$250/mo (~$10,000/yr) | Free plan includes 30,000 sessions/month (10 seats); 14-day free trial (up to 5,000 sessions) |
| **[LogRocket](https://logrocket.com/)** | Session replay and frontend monitoring tool capturing console logs, network requests, errors, and state alongside replays. | Starts at $69/mo (billed annually) / $99/mo | Free plan includes 1,000 sessions/month (3 seats); 14-day free trial for paid plans |
| **[Hotjar](https://www.hotjar.com/)** | Behavior analytics platform combining session recordings, heatmaps, surveys, and feedback tools. | Starts at $39/mo (Growth plan) | Free plan includes up to 200,000 monthly sessions; 15-day free trial |
| **[Microsoft Clarity](https://clarity.microsoft.com/)** | Free session replay and heatmap product with rage-click detection and simple setup. | $0/mo (100% free) | Unlimited sessions and recordings (30-day data retention) |
| **[Mouseflow](https://mouseflow.com/)** | Session replay and heatmap platform offering form analytics, funnels, and qualitative user insights. | Starts at $25/mo (Essential plan) | Free plan includes 500 sessions/month (1 website); 14-day free trial |
| **[Lucky Orange](https://www.luckyorange.com/)** | Conversion optimization tool featuring session recordings, heatmaps, dynamic funnels, and live chat. | Starts at $19/mo (Build plan) | Free plan includes 100 sessions/month; 7-day free trial |
| **[Inspectlet](https://www.inspectlet.com/)** | User testing and session recording platform with eye-tracking heatmaps and A/B testing support. | Starts at $39/mo (Micro plan) | Free plan includes 2,500 recorded sessions/month (up to 3 websites) |
| **[Smartlook](https://www.smartlook.com/)** | Qual-quant analytics tool providing session recording, automatic event tracking, and funnel analysis. | Starts at $55/mo (Pro plan) | Free plan includes 3,000 sessions/month; 30-day free trial |
| **[Glassbox](https://www.glassbox.com/)** | Enterprise digital experience analytics platform with session replay, journey analysis, and CX intelligence. | Paid contracts start at ~$833/mo (~$10,000/yr) | 14-day free trial / Demo POC available upon request |
| **[Quantum Metric](https://www.quantummetric.com/)** | Real-time digital experience platform focusing on session replay, customer journey analytics, and business impact. | Paid contracts start at ~$2,083/mo (~$25,000/yr) | Guided demo & proof-of-concept (POC) trial upon request |
| **[Contentsquare](https://contentsquare.com/)** | Digital experience analytics platform providing session replay, customer journey mapping, and merchandising analysis. | Starts at $39/mo (Growth plan) | Free plan includes 200,000 monthly sessions (10,000 replays); 15-day free trial |
| **[UXCam](https://uxcam.com/)** | Mobile-focused session replay and analytics platform for iOS and Android native apps. | Starts at $99/mo (Starter plan) | Free plan includes 3,000 sessions/month; 14-day free trial (up to 100,000 sessions) |

## Open-Source GitHub Projects

- **[OpenReplay](https://github.com/openreplay/openreplay)**  
  Leading open-source session replay and product analytics platform you can self-host. Captures user interactions, network activity, console logs, errors, performance metrics, and supports co-browsing. Designed for privacy, security, and full data control.

- **[rrweb](https://github.com/rrweb-io/rrweb)**  
  Foundational MIT-licensed library for recording and replaying web sessions. Provides snapshot, mutation recording, and high-fidelity playback. Used as the capture engine by many commercial and open-source products.

- **[PostHog](https://github.com/PostHog/posthog)**  
  Open-source product analytics platform that includes powerful session replay, heatmaps, funnels, feature flags, and more. Fully self-hostable with strong privacy controls.

- **[Highlight](https://github.com/highlight/highlight)**  
  Open-source session replay and error monitoring platform that combines replays with stack traces and debugging context.

- **[rrHog and rrweb-based analytics](https://github.com/rrHog/rrHog)**  
  Open-source self-hosted web analytics and session replay stacks built on rrweb, often paired with modern storage and UI layers (e.g., ClickHouse).

- **[Sentry Session Replay](https://github.com/getsentry/sentry)**  
  Error monitoring platform that includes open-source session replay capabilities tightly integrated with issue tracking and performance data.

- **[Other rrweb ecosystem tools](https://github.com/search?q=rrweb+session+replay)**  
  Community players, storage engines, and wrappers that extend rrweb for custom recording, playback, or analytics use cases.

### Additional Strong Open-Source Options

- **Capture & player libraries**: Tools built on or compatible with rrweb for embedding replay inside products or support tools.
- **Privacy & masking utilities**: Open-source components for sanitizing PII, blocking sensitive fields, and complying with data-protection requirements.
- **Analytics companions**: Open-source product analytics or heatmap projects that complement pure session replay.
- **Frontend debugging stacks**: Combinations of replay + console/network capture for developer workflows.
- **Self-hosted observability**: Broader stacks that incorporate session data alongside logs and traces.
- Research and experimental recorders for specialized environments (mobile web, canvas, etc.).

**Frameworks for building custom systems**:  
For a complete self-hosted session replay product, start with **OpenReplay**.  
For maximum flexibility or embedding replay into your own product, use the **rrweb** library and build (or adopt) ingest, storage, and player layers.  
**PostHog** is ideal when you want session replay tightly integrated with product analytics and feature flags in one open-source platform.  
Commercial tools (FullStory, LogRocket, Hotjar, Clarity, Glassbox, etc.) remain popular for polished UX, advanced search, enterprise compliance, and managed infrastructure. Many teams successfully run open-source replay for privacy-sensitive or cost-sensitive workloads while using commercial tools for specific advanced needs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Session replay tools capture detailed user interactions and can include sensitive data. Proper consent, masking, data-retention policies, and compliance with privacy regulations (GDPR, CCPA, etc.) are essential.
- Self-hosted open-source solutions give full data control but require secure deployment, storage management, and ongoing maintenance.

---

**Made for product managers, UX researchers, frontend engineers, and digital experience teams.**  
Let's advance transparent, privacy-respecting, and developer-friendly session replay through strong open-source tools.
