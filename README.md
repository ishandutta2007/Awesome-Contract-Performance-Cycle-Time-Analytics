# Awesome-Contract-Performance-Cycle-Time-Analytics

# Top Contract Performance & Cycle Time Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Contracting Velocity, Bottleneck Identification & Operational KPI Reporting*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Contract Performance & Cycle Time Analytics**. These tools help legal, procurement, and sales operations teams measure how long contracts take to move from request to signature—surfacing bottlenecks, approver workload imbalances, and cycle-time trends that slow down revenue.

**Examples** include Ironclad Insights, SirionLabs, Icertis, Agiloft, Docusign CLM, Conga, Tableau, Looker, Power BI, and Metabase (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted BI, open-source contract analytics, and community-driven reporting infrastructure—ideal for organizations seeking to build cycle-time dashboards without per-seat enterprise analytics licensing. Note that purpose-built open-source contract analytics is extremely thin; the practical path is composing general-purpose BI tools with contract data extraction.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Ironclad Insights](https://ironcladapp.com/)** | Native contract analytics within Ironclad. Prebuilt charts answer operational questions: in-progress workflow statuses, median execution time by workflow configuration, time-to-execution trends, and approver workload distribution. Legal Ops report focuses on cycle time and turn tracking. Drill down from any chart to underlying workflows; export as image, PDF, or CSV [citation:3][citation:12]. | Included with Ironclad CLM subscription (quote-only) | No separate free tier; requires Ironclad CLM |
| **[SirionLabs](https://www.sirion.ai/)** | Ranked **#1 in Advanced Contract Analytics** in the 2025 Gartner Critical Capabilities report (score 4.03/5), and #1 across all CLM use cases for three consecutive years. Agentic CLM with real-time reporting, interactive dashboards, and obligation monitoring. AskSirion enables natural-language queries over the contract corpus [citation:1][citation:4]. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Icertis](https://www.icertis.com/)** | Contract intelligence platform with performance analytics focused on revenue leakage prevention. AI agents match transactional documents against governing contract terms, monitor obligations, and trigger actions (e.g., notifying suppliers of overbilling). Integrates with ERP systems for real-time performance visibility [citation:2]. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Agiloft](https://www.agiloft.com/)** | CLM with reporting on contract value, compliance, obligations, and renewal pipelines. Customizable dashboards by stakeholder, location, or contract type; drill-down into individual contracts. Integrates with Tableau and Power BI for advanced analytics [citation:5][citation:13]. | Quote-only (enterprise; median ~$67,000/year) | No free tier; demo via sales |
| **[Docusign CLM](https://www.docusign.com/)** | Process reporting for workflow analysis. Administrators can view a report for any workflow completed in the last **3 years**, broken down by step duration. Filter by time period; drill into task-level details including duration and completing user. Export to CSV for external analysis [citation:6][citation:14]. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Conga](https://www.conga.com/)** | CLM with custom analytics dashboards and a **Contract Cycle Time Report** showing average time from one stage to another, by record type and stage. Also includes dashboards for legal, sales, and supplier performance. Scheduled reports with configurable frequency and recipients [citation:7][citation:15]. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Tableau](https://www.tableau.com/)** | Visual analytics platform for building custom contract performance dashboards from extracted CLM data. Common choice when CLM native reporting is insufficient and organizations want full control over visualization and data blending. | Quote-only (per-user Creator/Explorer/Viewer licensing); Tableau Public free for public data | **Tableau Public**: free for publicly shared dashboards; **14-day trial** for full platform |
| **[Looker (Google Cloud)](https://looker.com/)** | BI platform with semantic modeling (LookML) for governed contract metrics. Enables consistent cycle-time definitions across the organization with drill-down and scheduled delivery. | Quote-only (enterprise contract; Google Cloud billing) | No free tier; trial via Google Cloud sales |
| **[Microsoft Power BI](https://powerbi.microsoft.com/)** | Microsoft's BI platform with desktop authoring and cloud publishing. Integrates with Agiloft and other CLM systems for contract performance dashboards. Power BI Embedded available for product teams. | Pro: $14/user/month; Premium Per User: $24/user/month | **Free**: Power BI Desktop (authoring only); **60-day trial** for Pro/Premium |
| **[Sisense](https://www.sisense.com/)** | BI platform focused on embedded analytics. Allows embedding contract performance dashboards directly into customer-facing or internal applications with white-labeling. | Quote-only (custom enterprise pricing) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Metabase](https://github.com/metabase/metabase)** | [![Stars](https://img.shields.io/github/stars/metabase/metabase?style=social&color=white)](https://github.com/metabase/metabase/stargazers) | **The most practical open-source path to contract cycle-time analytics.** User-friendly BI tool with a question builder and SQL editor. Can connect directly to a CLM database or a synced warehouse to build cycle-time dashboards. The Metabase team publishes a **renewal forecast dashboard template** that models ARR up for renewal, forecast categories, and at-risk accounts—directly applicable to contract performance tracking if your CLM data is accessible [citation:22][citation:30]. |
| **[Apache Superset](https://github.com/apache/superset)** | [![Stars](https://img.shields.io/github/stars/apache/superset?style=social&color=white)](https://github.com/apache/superset/stargazers) | Open-source data exploration and BI platform. Drag-and-drop dashboard builder with rich visualization library and SQL Lab for ad-hoc queries. Suitable for teams needing more customization than Metabase offers. One academic deployment noted performance degradation with complex contract dashboards, requiring OLAP cubes for acceptable speed [citation:19]. |
| **[Helical Insight](https://github.com/helicalinsight/helicalinsight)** | [![Stars](https://img.shields.io/github/stars/helicalinsight/helicalinsight?style=social&color=white)](https://github.com/helicalinsight/helicalinsight/stargazers) | Open-source BI platform with **AI conversational analytics** (bring-your-own LLM), pixel-perfect paginated reports, interactive dashboards, SSO, embedding, multi-tenancy, and row-level security. Every feature free in Community Edition; Docker-ready [citation:17][citation:25]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[DataPallas Server](https://github.com/flowkraft/datapallas)** | [![Stars](https://img.shields.io/github/stars/flowkraft/datapallas?style=social&color=white)](https://github.com/flowkraft/datapallas/stargazers) | Self-hosted BI and reporting platform with dashboards, semantic layer (cubes), pixel-perfect PDF/Excel/Word report generation, and report bursting. Includes AI agents for data exploration and automation. Docker deployment with no per-seat metering [citation:21]. |
| **[sqldash](https://pypi.org/project/sqldash/)** | — | YAML-based dashboard framework with AI Studio for agent-assisted chart editing. Defines metrics in a semantic layer (`metrics.yaml`) that both dashboards and agents query. Supports DuckDB, Snowflake, Postgres, BigQuery, and more. Lightweight alternative for teams wanting version-controlled dashboard definitions [citation:9]. |
| **[Aakd](https://github.com/aaked-app/aakd)** | [![Stars](https://img.shields.io/github/stars/aaked-app/aakd?style=social&color=white)](https://github.com/aaked-app/aakd/stargazers) | Open-source CLM with **obligation and renewal views, owners, deadlines, and audit history**. Not a dedicated analytics tool, but its structured obligation data can feed into Metabase or Superset for cycle-time reporting. AGPL-3.0, self-hosted via Docker Compose [citation:24][citation:28]. |
| **[draftLegal](https://github.com/AniketTati/draft-legal)** | [![Stars](https://img.shields.io/github/stars/AniketTati/draft-legal?style=social&color=white)](https://github.com/AniketTati/draft-legal/stargazers) | Self-hosted AI-native CLM with **portfolio intelligence** via hybrid retrieval. Can answer questions like "how does this SOW compare with ones we've signed?" but lacks built-in cycle-time dashboards—pair with Metabase for quantitative analytics [citation:16]. |

**Frameworks for building custom systems**: The open-source path to contract cycle-time analytics is **compositional**. Extract contract and workflow data from your CLM (via API or database export) into a warehouse or PostgreSQL, then build dashboards in **Metabase** or **Superset**. If you need embedded analytics in a product, **Helical Insight** or **DataPallas** provide white-labelable dashboards. Expect to define your own cycle-time metrics (median time-to-execution, stage duration, approver turnaround) since no open-source project ships with prebuilt contract-specific KPIs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Contract performance analytics involves sensitive commercial timing and workload data; enforce role-based access and ensure dashboards respect CLM record-level permissions.
- **Purpose-built open-source contract cycle-time analytics does not exist as a mature category.** Ironclad Insights, Sirion, Docusign, and Conga ship native reporting, but their pricing is quote-only enterprise. The realistic open-source path is exporting CLM data and building dashboards in Metabase or Superset—expect engineering effort to define metrics and maintain pipelines. Academic deployments of Superset for contract dashboards have required OLAP cube optimization to achieve acceptable performance [citation:19]. Commercial BI platforms (Tableau, Looker, Power BI, Sisense) are priced per-user and require separate CLM data extraction.

---

**Made for legal ops analysts, contract managers, procurement operations teams, and developers building contracting analytics infrastructure.**  
Let's make contract performance analytics more open, measurable, and actionable.
