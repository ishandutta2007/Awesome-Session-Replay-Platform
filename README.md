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

- **[FullStory](https://www.fullstory.com/)**  
  Enterprise digital experience platform offering high-fidelity session replay, autocapture, search, and powerful behavioral analytics.

- **[LogRocket](https://logrocket.com/)**  
  Session replay and frontend monitoring tool popular with engineering teams. Captures console logs, network requests, errors, and application state alongside video-like replays.

- **[Hotjar](https://www.hotjar.com/)**  
  Widely used behavior analytics platform combining session recordings, heatmaps, surveys, and feedback tools for UX and conversion teams.

- **[Microsoft Clarity](https://clarity.microsoft.com/)**  
  Free session replay and heatmap product from Microsoft with unlimited recordings, rage-click detection, and simple setup.

- **[Mouseflow, Lucky Orange, Inspectlet, Smartlook](https://mouseflow.com/)**  
  Mid-market session replay and heatmap platforms offering form analytics, funnels, and qualitative insights.

- **[Glassbox, Quantum Metric, Contentsquare](https://www.glassbox.com/)**  
  Enterprise digital experience analytics platforms with advanced session replay, journey analysis, and customer experience intelligence.

- **[UXCam](https://uxcam.com/)**  
  Mobile-focused session replay and analytics platform for iOS and Android apps.

- **[Other experience platforms](https://www.fullstory.com/)**  
  Additional tools that combine session replay with product analytics, error monitoring, or customer journey mapping.

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
