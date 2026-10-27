# Awesome-Data-Analytics-Platform

# Awesome-Data-Analytics-Platform
**Top Data Analytics Platform (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Business Intelligence, Self-Service Analytics, Embedded Dashboards & Warehouse-Native Query Engines*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Analytics Platforms**. These tools enable organizations to connect to data warehouses, build dashboards, run ad-hoc queries, embed analytics into products, and enable self-service exploration—from fully managed enterprise BI suites with AI-powered insights to self-hosted platforms that give teams complete control over their data and infrastructure.

**Examples** include Tableau, Microsoft Power BI, Looker, Snowflake, Databricks, Qlik Sense, ThoughtSpot, Sisense, Domo, and Workday Prism Analytics (the category leaders in commercial space).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, BI, and open analytics infrastructure—ideal for developers, data teams, and organizations seeking transparent, vendor-independent analytics.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Tableau](https://www.tableau.com/)**
  **Enterprise BI and analytics platform** known for visual analytics and dashboard design. **Pricing**: Per-user licensing (Creator, Explorer, Viewer roles); quote-based for enterprise. **Free tier**: Tableau Public (public data only); no private free tier. **Best for**: organizations prioritizing visual exploration and a mature ecosystem of connectors and community content.

- **[Microsoft Power BI](https://powerbi.microsoft.com/)**
  **Business analytics service** tightly integrated with Microsoft ecosystem. **Pricing**: **Free** desktop version; **Pro** at $14/user/month; **Premium Per User** at $24/user/month; **Premium capacity** quote-based . **Free tier**: Power BI Desktop free; limited free service tier. **Best for**: Microsoft-centric organizations wanting affordable per-user BI with strong Excel and Azure integration.

- **[Looker](https://looker.com/)** (Google Cloud)
  **Enterprise BI and data platform** with LookML semantic modeling. **Pricing**: Quote-only; platform-based pricing with user tiers. **Free tier**: None. **Best for**: organizations wanting a governed semantic layer with consistent metric definitions across the business.

- **[Snowflake](https://www.snowflake.com/)**
  **Cloud data warehouse** with growing analytics and BI capabilities. **Pricing**: Consumption-based (credits for compute, storage separate); quote-based. **Free tier**: Trial credits available. **Best for**: organizations wanting a scalable warehouse foundation with an ecosystem of compatible BI tools.

- **[Databricks](https://www.databricks.com/)**
  **Data lakehouse platform** with SQL analytics and BI capabilities. **Pricing**: Consumption-based (DBUs); quote-based. **Free tier**: Community Edition (limited). **Best for**: data engineering and ML teams wanting unified analytics on a lakehouse architecture.

- **[Qlik Sense](https://www.qlik.com/)**
  **BI and analytics platform** with associative engine for exploration. **Pricing**: Quote-only; per-user and capacity models. **Free tier**: Qlik Sense Desktop free for personal use. **Best for**: organizations wanting associative, exploratory analytics without rigid query paths.

- **[ThoughtSpot](https://www.thoughtspot.com/)**
  **AI-powered analytics platform** with natural language search ("SearchIQ"). **Pricing**: Quote-only; tiered by use case. **Free tier**: Trial available. **Best for**: business users wanting Google-like search over enterprise data without SQL knowledge.

- **[Sisense](https://www.sisense.com/)**
  **Embedded analytics and BI platform** for product teams. **Pricing**: Quote-only; typically per-server or capacity-based for embedding. **Free tier**: None. **Best for**: SaaS companies wanting white-labeled embedded analytics within their products.

- **[Domo](https://www.domo.com/)**
  **Cloud BI and data integration platform** with strong ETL and dashboard capabilities. **Pricing**: Quote-only; consumption and seat-based models. **Free tier**: Trial available. **Best for**: organizations wanting BI bundled with data pipeline and app-building capabilities.

- **[Workday Prism Analytics](https://www.workday.com/)**
  **Data hub within Workday** for blending Workday data with external sources. **Pricing**: Quote-only; bundled with Workday suite. **Free tier**: None. **Best for**: Workday customers wanting to combine HR/finance data with external datasets for reporting within Workday.

## Open-Source GitHub Projects

- **[Apache Superset](https://github.com/apache/superset)**
  **Modern, enterprise-ready business intelligence web application** (Apache 2.0) — **the most widely adopted open-source BI platform** with the broadest warehouse coverage. **Features**: No-code visualization builder, SQL Lab IDE, rich semantic layer with virtual datasets, 40+ database connectors via SQLAlchemy (Snowflake, BigQuery, Databricks, Redshift, ClickHouse, Druid, Pinot, and more) with native SQL dialect support and query pushdown . Role-based access control (Admin, Alpha, Gamma, Public), LDAP/OIDB/database authentication, and embedded dashboard support via iframe . **Tech stack**: Python (Flask), React, SQLAlchemy. **Deploy**: Docker Compose, Kubernetes, or managed via Preset. **Best for**: organizations wanting the most mature, warehouse-native open-source BI platform with enterprise-grade connectors and access controls.

- **[Metabase](https://github.com/metabase/metabase)**
  **Easy-to-use open-source BI and embedded analytics tool** (AGPL-3.0 for open-source edition) — **the most accessible open-source BI tool** with ~41,600 GitHub stars . **Features**: No-code query builder for non-technical users, native SQL editor, dashboards with subscriptions (email/Slack), **unlimited users and questions on the free open-source edition**, connections to 20+ data sources including PostgreSQL, MySQL, BigQuery, Snowflake, Redshift, and ClickHouse . AI questions (Metabot) using your own Anthropic/OpenAI API key; MCP server for AI client integration. **Tech stack**: Clojure, React. **Deploy**: Docker (one command), JAR, or Metabase Cloud. **Trade-off**: SSO (SAML/JWT/OIDC), row-level security, and white-labeling are **Pro/Enterprise features**—the open-source edition includes community support only . **Best for**: teams wanting a free, unlimited-user BI tool that non-technical users can adopt quickly without SQL.

- **[Lightdash](https://github.com/lightdash/lightdash)**
  **Open-source Looker alternative fully integrated with dbt** (license per repo) — **the best choice for dbt-native analytics**. **Features**: Declare dimensions and metrics in YAML alongside dbt models; automatically syncs dbt descriptions and lineage; self-service interface for exploring pre-defined metrics; table calculations; charts and dashboards; share via URL or export . Kubernetes Helm charts for production deployment; 1-click Heroku deploy for evaluation . **Tech stack**: TypeScript, React, Node.js. **Deploy**: Self-hosted (Docker, Kubernetes) or Lightdash Cloud. **Adoption**: ~4,300 GitHub stars . **Best for**: data teams already using dbt wanting a governed BI layer where all business logic lives in the dbt project.

- **[Redash](https://github.com/getredash/redash)**
  **Connect to any data source, visualize, and share** (BSD-2-Clause) — **a proven, query-first BI tool** with ~25,900 GitHub stars . **Features**: Query editor for SQL and NoSQL sources, visualizations, dashboards, alerting, and scheduled refreshes. Supports a broad range of data sources including PostgreSQL, MySQL, BigQuery, Snowflake, Redshift, Cassandra, MongoDB, and more . **Tech stack**: Python, React. **Deploy**: Self-hosted (Docker). **Note**: Development activity has slowed compared to Superset and Metabase; evaluate maintenance cadence before greenfield adoption. **Best for**: teams wanting a straightforward, query-centric BI tool with broad database support and minimal setup complexity.

- **[Grafana](https://github.com/grafana/grafana)**
  **Open-source analytics and monitoring platform** (AGPL-3.0) — **the standard for time-series and operational dashboards**, increasingly used for business analytics. **Features**: Rich visualization library, alerting, mixed-data-source queries, and extensive plugin ecosystem. Strong support for Prometheus, Loki, PostgreSQL, MySQL, ClickHouse, and cloud monitoring services. **Tech stack**: Go, TypeScript. **Deploy**: Self-hosted (Docker, Kubernetes) or Grafana Cloud (free tier available). **Trade-off**: Optimized for time-series and operational metrics, **not a traditional BI tool** for business users—no semantic layer or self-service exploration for non-technical users. **Best for**: engineering and operations teams wanting dashboards over metrics and logs, not business intelligence.

- **[Apache Doris](https://github.com/apache/doris)**
  **Real-time analytics and hybrid search database for AI agents** (Apache 2.0) — **a high-performance query engine, not a BI application**. **Features**: Sub-second analytics on large datasets, MySQL protocol compatibility, and hybrid search capabilities . **Deploy**: Self-hosted. **Trade-off**: A **database/query engine**, not a BI tool—requires a separate visualization layer (Superset, Grafana, etc.). **Best for**: teams needing a fast, open-source OLAP engine behind their BI stack.

- **[StarRocks](https://github.com/StarRocks/starrocks)**
  **Fast open query engine for sub-second analytics on and off the data lakehouse** (Apache 2.0) — **a Linux Foundation project** with ~7,800 GitHub stars . **Features**: Best-in-class performance for multi-dimensional analytics, real-time analytics, and ad-hoc queries; supports data lakehouse architectures . **Deploy**: Self-hosted. **Trade-off**: A **query engine**, not a BI platform—pairs with Superset, Metabase, or Grafana for visualization. **Best for**: teams wanting a high-performance analytical database to power their BI tools.

- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**
  **Column-oriented database for real-time analytics** (Apache 2.0) — **the most widely adopted open-source OLAP database**. **Features**: Exceptional query performance on large datasets, SQL support, and a growing ecosystem of integrations. **Deploy**: Self-hosted or ClickHouse Cloud. **Trade-off**: A **database**, not a BI tool—requires a visualization layer. **Best for**: teams needing a fast, scalable analytical database as the foundation for their analytics stack.

### Additional Strong Open-Source Options

- **RAWGraphs** — Open-source visualization tool for complex data (Apache 2.0). **Note**: A specialized charting tool, not a full BI platform with dashboards or user management . **Best for**: designers and analysts creating custom vector visualizations from spreadsheets.
- **Knowage** — Open-source BI suite (GPL-3.0) with reporting, OLAP, and dashboards. **Note**: Smaller community than Superset or Metabase; evaluate maintenance activity. **Best for**: organizations wanting a traditional BI suite with enterprise features.
- **Preset** — Managed Apache Superset cloud service (not open-source itself, but built on Superset). **Best for**: teams wanting Superset without operational overhead.

**Frameworks for building custom systems**: Combine **Apache Superset** as the primary BI layer with **ClickHouse**, **StarRocks**, or **Apache Doris** as the query engine, **Lightdash** for dbt-native governed metrics, and **Metabase** for non-technical self-service—creating a comprehensive analytics stack matched to each organization's data infrastructure and user personas.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data analytics platforms handling business data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and audit logging.
- **The "BI platform vs. query engine vs. visualization tool" distinction matters.** **Apache Superset, Metabase, Lightdash, and Redash** are **BI platforms**—they provide dashboards, user management, and self-service exploration. **ClickHouse, StarRocks, and Apache Doris** are **query engines**—they store and query data but have no BI interface. **Grafana** is a **monitoring dashboard tool**—excellent for metrics, not business users. **RAWGraphs** is a **visualization utility**, not a platform. **Choose based on whether you need a complete analytics application or infrastructure components.**
- **Metabase's open-source edition is genuinely free and unlimited**—no user caps, no credit card, and includes the query builder, SQL editor, dashboards, and guest embeds . **The trade-off**: SSO, row-level security, and white-labeling are gated behind Pro/Enterprise plans. For organizations needing enterprise governance features, the free edition may not suffice.
- **Apache Superset is the most enterprise-ready open-source BI platform.** It offers the broadest warehouse coverage (40+ connectors), native SQL dialect support with query pushdown, and the most granular access controls (Admin/Alpha/Gamma/Public roles plus LDAP/OIDB/database auth) . **The trade-off**: steeper learning curve than Metabase, and operational complexity for self-hosting at scale.
- **Lightdash is the best choice only if you're already using dbt.** Its entire value proposition—metrics declared in dbt YAML, synced descriptions, lineage—depends on an existing dbt project . **If you're not on dbt, Lightdash's advantages disappear.**
- **Redash's development activity has slowed.** With ~25,900 stars, it remains a capable query-first BI tool, but commit frequency has diminished compared to Superset and Metabase . **Evaluate long-term maintenance before adopting for new deployments.**
- **Pricing transparency varies widely.** Power BI publishes per-user pricing; Snowflake and Databricks use consumption models; Tableau, Looker, Qlik, ThoughtSpot, Sisense, and Domo require sales contact. **Validate with direct vendor conversations against your actual query volumes and user counts.**
- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Analytics platforms query production data**—ensure your hosting meets your organization's security and performance requirements before deploying.

---

**Made for developers, data teams, and organizations building transparent analytics solutions.**
Let's make Data Analytics Platforms more open, data-driven, and user-friendly.
