# Awesome-Feature-Flag-Management

# Top Feature Flag Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Feature Toggles, Progressive Delivery, A/B Testing, Remote Configuration, Experimentation & Safe Software Releases*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Feature Flag Management**. These tools allow teams to decouple deployment from release, control feature exposure with targeting rules, run experiments, and roll out (or roll back) changes safely in production.

**Examples** include LaunchDarkly, Split, Statsig, ConfigCat, Flagsmith, Unleash, GrowthBook, DevCycle, Flipt, CloudBees Feature Management, Harness Feature Flags, Bucket, and Eppo (the category leaders).

**Open-source emphasis**: This section is heavily expanded. Leading platforms such as Unleash, Flagsmith, GrowthBook, and Flipt provide full-featured open-source cores, making self-hosted feature management practical for teams that need data sovereignty, cost control, or deep customization.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[LaunchDarkly](https://launchdarkly.com/)**  
  Enterprise-grade feature management platform with advanced targeting, governance, real-time updates, and extensive SDK support — the long-standing category leader.

- **[Split (Harness)](https://www.split.io/)**  
  Feature flagging and experimentation platform (now part of Harness) focused on controlled rollouts, metric monitoring, and CI/CD integration.

- **[Statsig](https://www.statsig.com/)**  
  Unified feature flags + experimentation + product analytics platform with a strong stats engine and warehouse-native capabilities.

- **[ConfigCat](https://configcat.com/)**  
  Developer-friendly feature flag and remote configuration service with simple SDKs and straightforward targeting.

- **[Flagsmith](https://www.flagsmith.com/)**  
  Feature flagging and remote config platform available as open-source or managed cloud, with strong self-hosting and governance options.

- **[Unleash](https://www.getunleash.io/)**  
  Popular open-source feature management platform (with commercial cloud and enterprise offerings) known for gradual rollouts and broad SDK coverage.

- **[GrowthBook](https://www.growthbook.io/)**  
  Open-source feature flags + experimentation platform that connects to your existing data warehouse for statistical analysis.

- **[DevCycle](https://devcycle.com/)**  
  Feature management platform emphasizing developer experience, real-time updates, and integration with modern delivery workflows.

- **[Flipt](https://www.flipt.io/)**  
  Lightweight, open-source feature flag solution (with cloud option) that supports GitOps-style workflows and high performance.

- **[CloudBees Feature Management](https://www.cloudbees.com/)**  
  Enterprise feature flagging capabilities integrated into the broader CloudBees continuous delivery ecosystem.

- **[Harness Feature Flags](https://www.harness.io/)**  
  Feature flag management within the Harness platform, tightly coupled with CI/CD and progressive delivery practices.

- **[Bucket](https://bucket.co/)**  
  Feature flag and product experimentation tool focused on product teams and modern development workflows.

- **[Eppo](https://www.geteppo.com/)**  
  Experimentation and feature flag platform (now associated with Datadog) strong on warehouse-native analytics and statistical rigor.

## Open-Source GitHub Projects
- **[Unleash](https://github.com/Unleash/unleash)**  
  The most widely adopted open-source feature management platform, supporting gradual rollouts, strategies, and 15+ official SDKs.

- **[Flagsmith](https://github.com/Flagsmith/flagsmith)**  
  Open-source feature flagging and remote configuration service with self-hosting, segmentation, and multi-language SDKs.

- **[GrowthBook](https://github.com/growthbook/growthbook)**  
  Open-source platform combining feature flags, A/B testing, and product analytics with a warehouse-native stats engine.

- **[Flipt](https://github.com/flipt-io/flipt)**  
  Fast, open-source feature flag server written in Go, supporting multiple storage backends and GitOps-friendly workflows.

- **[GO Feature Flag](https://github.com/thomaspoignant/go-feature-flag)**  
  Lightweight, open-source feature flag solution with OpenFeature support and no mandatory database dependency.

- **[flagd](https://github.com/open-feature/flagd)**  
  OpenFeature reference implementation — a simple, standards-based feature flag daemon.

- **[OpenFeature](https://github.com/open-feature)**  
  Vendor-neutral, community-driven standard and SDKs for feature flagging that allow switching providers without code changes.

- **[Flipper](https://github.com/flippercloud/flipper)**  
  Popular open-source feature flag library for Ruby/Rails applications.

- **[FF4J](https://github.com/ff4j/ff4j)**  
  Feature Flipping for Java — an open-source framework with web console and monitoring for JVM applications.

- **[Custom and language-specific toggle libraries](https://github.com/)**  
  Numerous lightweight open-source feature toggle implementations across Python, Node.js, .NET, and other ecosystems.

### Additional Strong Open-Source Options
- PostHog (includes feature flags alongside product analytics).
- Self-hosted experimentation frameworks that integrate with warehouse data.
- GitOps-oriented flag storage patterns using Git + CI.
- Edge evaluation proxies and CDN-friendly flag delivery tools.
- Academic and research feature-flag systems adapted for production use.

**Frameworks for building custom systems**: Adopt **OpenFeature** as the application-facing standard, then back it with **Unleash**, **Flagsmith**, **GrowthBook**, or **Flipt** depending on whether you prioritize maturity, remote config, experimentation, or simplicity. Self-host the chosen platform, evaluate flags at the edge when latency matters, and connect experiment results to your warehouse for analysis. This approach delivers full data ownership and avoids vendor lock-in while retaining modern progressive delivery capabilities.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Feature flags are powerful but can introduce complexity and technical debt if not managed (flag cleanup, targeting rules, evaluation performance). Open-source solutions give excellent control and cost advantages but still require operational ownership of the control plane and SDKs.
- Always design for fail-safe defaults and monitor the impact of flag changes in production.

---
**Made for engineering, product, and platform teams who want safe, flexible software delivery.**
Let's make feature management more open, standards-based, and under your control.
