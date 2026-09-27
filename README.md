# Awesome-Engineering-Productivity-Platform

## Top Engineering Productivity Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Developer Experience, DORA Metrics, Engineering Analytics & Team Performance*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Engineering Productivity**. These tools help engineering leaders, platform teams, and developers measure delivery performance, identify bottlenecks, improve developer experience, and make data-driven decisions about their software delivery process.

**Examples** include LinearB, Swarmia, Code Climate Velocity, DX, Haystack, GitPrime (Pluralsight Flow), Velocity by Jellyfish, Faros AI, Typo, and Jellyfish (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom metrics pipelines, and transparent engineering data — ideal for teams that need full control over their delivery metrics without per-developer SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[LinearB](https://linearb.io/)**  
  Engineering intelligence platform with real-time DORA metrics, automated improvement actions, and workflow optimization. Integrates with GitHub, GitLab, Jira, and CI/CD tools to provide visibility into delivery performance and team planning accuracy .

- **[Swarmia](https://www.swarmia.com/)**  
  Engineering effectiveness platform focused on investment distribution (feature work vs. tech debt vs. incidents), PR review health, and working agreements. Trusted by 600+ engineering teams, with strong adoption in European technical organizations .

- **[Code Climate Velocity](https://codeclimate.com/)**  
  Engineering metrics platform providing DORA metrics, code quality insights, and team performance analytics. The deploy action tracks deployments for Velocity integration.

- **[DX](https://getdx.com/)**  
  Developer experience platform combining quantitative DORA metrics with qualitative developer sentiment surveys (based on DX Core 4 and SPACE frameworks). Identifies friction points by team and role .

- **[Haystack](https://haystackapp.com/)**  
  Engineering analytics platform providing visibility into team performance, code review efficiency, and delivery metrics with actionable insights.

- **[GitPrime (Pluralsight Flow)](https://www.pluralsight.com/product/flow)**  
  Engineering metrics platform providing detailed analytics on team performance, code review patterns, and delivery velocity using Git repository data.

- **[Jellyfish](https://jellyfish.co/)**  
  Engineering management intelligence platform focused on mapping engineering investment to business initiatives. Connects engineering work to product themes and business outcomes for VP-level reporting. Enterprise SaaS with contract-based pricing .

- **[Faros AI](https://www.faros.ai/)**  
  Engineering intelligence platform with 200+ data source connectors and a unified data model. Enterprise-only managed SaaS estimated at $30-60/dev/month. The open-source **Faros Community Edition** provides the core data integration layer for self-hosting .

- **[Typo](https://typo.ai/)**  
  Engineering productivity platform focused on code review analytics and delivery metrics.

## Open-Source GitHub Projects

- **[Apache DevLake](https://github.com/apache/incubator-devlake)**  
  Apache incubating open-source dev data platform that ingests, analyzes, and visualizes data from DevOps tools (GitHub, GitLab, Jira, Jenkins, BitBucket, Azure DevOps, SonarQube, PagerDuty). Provides out-of-the-box dashboards including DORA metrics, community growth, and engineering throughput. Extensible framework for custom data sources and metrics via SQL. Docker Compose, Kubernetes, and Helm deployment options. **Apache-2.0** .

- **[CDviz](https://github.com/cdviz/cdviz)**  
  Open-source platform that turns CI/CD pipeline events into insights. Built on CDEvents and Grafana, tracks DORA metrics across GitHub Actions, GitLab CI, ArgoCD, and more. Positions itself as a self-hostable alternative to LinearB, Swarmia, and Jellyfish. Key differentiators: data sovereignty, CDEvents open standard, event-driven workflow triggers, and customizable storage backends (PostgreSQL, ClickHouse). Self-hosted free (Apache-2.0); Cloud €20/mo; Pro €200/mo .

- **[Middleware](https://github.com/middlewarehq/middleware)**  
  Open-source DORA metrics platform for engineering teams. Automates collection and visualization of deployment frequency, lead time for changes, MTTR, and change failure rate. Integrates with CI/CD platforms, Git repositories, and project management tools. Simple Docker deployment with minimal configuration. ~1,287 stars. **Open-Core / Self-Hosted** .

- **[Faros Community Edition](https://github.com/faros-ai/faros-community-edition)**  
  Open-source core of Faros AI's data integration layer. Connect development tools, normalize data into a unified model, and query it. A subset of the 200+ connectors is available. Self-hosted infrastructure costs only, but requires DevOps expertise for maintenance. Faros AI positions CE as an evaluation path for the managed enterprise platform .

- **[DevOpsMetrics](https://github.com/DeveloperMetrics/DevOpsMetrics)**  
  C# project to extract and process high-performing DevOps metrics (DORA) from GitHub and Azure DevOps. Focused on deployment frequency, lead time, MTTR, and change failure rate. ~252 stars .

- **[Pelorus](https://github.com/dora-metrics/pelorus)**  
  Automates the measurement of organizational behavior, specifically DORA metrics. Python-based, part of the dora-metrics GitHub organization .

- **[Dorametrix](https://github.com/mikaelvesavuori/dorametrix)**  
  Serverless web service that calculates DORA metrics by inferring them from events created via webhooks or manually. Supports GitHub Actions and Bitbucket Pipes integration. Lightweight and easy to deploy .

- **[Backstage DORA Plugin](https://github.com/liatrio/backstage-dora-plugin)**  
  Backstage plugin to surface organizational DORA metrics directly in the developer portal .

### Additional Strong Open-Source Options

- **DORA Foundations**: **Apache DevLake** (comprehensive, multi-source), **Middleware** (simple DORA deployment), **CDviz** (CDEvents-based, event-driven).
- **Lightweight Tools**: **Dorametrix** (serverless, webhook-driven), **DevOpsMetrics** (.NET, GitHub/Azure DevOps).
- **Developer Experience**: **Slack DevEx Survey** (serverless Slack survey tool for developer sentiment, TypeScript, MIT) .
- **Portal Integration**: **Backstage DORA Plugin** (surface metrics in developer portal).

**Frameworks for building custom systems**: Combine **Apache DevLake** for comprehensive data ingestion and dashboards, **CDviz** for CI/CD pipeline observability with event-driven automation, **Middleware** for simple DORA deployment, and **Grafana** for visualization. Add **PostgreSQL** for persistence and **Backstage** for portal integration.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Engineering productivity tools collect sensitive developer activity data; ensure compliance with privacy regulations and internal policies.
- **Open-source is not free**: Apache DevLake and Faros CE require dedicated data engineering and DevOps resources for data ingestion, model tuning, and platform maintenance. Organizations without data teams should prioritize managed platforms .
