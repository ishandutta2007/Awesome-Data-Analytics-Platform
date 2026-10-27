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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global data analytics and business intelligence (BI) market is estimated at approximately **$350B to $390B in 2026** (with core BI software accounting for ~$35B–$40B and the broader analytics/lakehouse infrastructure market expanding rapidly at a ~13–15% CAGR). The sector exhibits **moderate concentration with a barbell distribution**: mega-cap cloud and enterprise incumbents (Microsoft, Alphabet/Google Cloud, Salesforce, Snowflake, Databricks) dominate the enterprise governance and data warehousing tiers, while mid-market BI, headless metrics/semantic layers, and embedded developer analytics remain highly fragmented with intense competition and fast-growing open-source ecosystems.

## SaaS/Hosted Platforms

| Platform | Company Size (Revenue / Valuation) | Pricing | Free Tier Limits | Primary Focus & Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Power BI](https://powerbi.microsoft.com/)** | ~$3.1T Market Cap (Microsoft parent; FY24 Microsoft Cloud revenue $137B+) | Free Desktop; **Pro** starts at **$14/user/month**; **Premium Per User (PPU)** at **$24/user/month**; Fabric capacity from **$262.80/month** (F2) | **Free forever plan**: Power BI Desktop is 100% free for individual local authoring/modeling; Power BI Service free account includes 10 GB personal workspace storage (sharing/publishing requires Pro). 60-day free trial for Pro. | Ubiquitous enterprise BI suite tightly integrated with Microsoft 365, Excel, Azure, and Fabric ecosystem. |
| **[Looker](https://looker.com/)** (Google Cloud) | ~$2.1T Market Cap (Alphabet parent; Google Cloud revenue $40B+ run-rate) | Starting at **$5,000/month** (Standard platform license) + $30/user/month (Standard Viewer), $60/user/month (Standard Explorer), $125/user/month (Developer) | **No free forever plan**. 30-day free trial available via Google Cloud Sales / GCP Marketplace upon request. | Governed enterprise BI and centralized semantic modeling layer (LookML) with in-database query execution. |
| **[Tableau](https://www.tableau.com/)** (Salesforce) | ~$280B Market Cap (Salesforce parent; Tableau estimated revenue ~$2.5B+) | Starting at **$15/user/month** (Tableau Viewer), **$42/user/month** (Tableau Explorer), **$75/user/month** (Tableau Creator, billed annually) | **Free forever plan**: Tableau Public (10 GB cloud storage, all published workbooks and underlying data are public). 14-day fully featured private free trial of Tableau Desktop/Creator. | Best-in-class interactive visual analytics, rich dashboarding canvas, and extensive community visualization ecosystem. |
| **[Workday Prism Analytics](https://www.workday.com/)** | ~$68B Market Cap (Workday annual revenue ~$8.4B) | Starting add-on pricing typically starts at **~$2,500/month (~$30,000/year)** for base ingestion capacity, scaled by user counts and record tiering | **No free forever plan**. 30-day guided sandbox access available only during enterprise proof-of-concept (POC) evaluations. | Enterprise data hub within Workday for blending finance/HR operational records with external third-party data. |
| **[Snowflake](https://www.snowflake.com/)** | ~$48B Market Cap (FY25 annual product revenue ~$3.5B+) | **Standard tier** starts at **$2.00 per credit**; Enterprise at **$3.00 per credit**; Business Critical at **$4.00 per credit** (storage priced separately at ~$23–$40/TB/month) | **No free forever plan**. 30-day free trial including **$400 in free compute/storage credits**. | Cloud data warehouse, data sharing, and SQL analytics engine serving as the foundation for modern BI architectures. |
| **[Databricks](https://www.databricks.com/)** | ~$43B Private Valuation (ARR ~$2.4B+) | Starting at **$0.07 to $0.22 per DBU** (Data Engineering/All-Purpose Compute) and **$0.22 to $0.70 per DBU** for Databricks SQL / Serverless compute | **Free forever plan**: Community Edition (1 driver node, 15 GB RAM, 2 CPU cores, single-user environment without clustering). 14-day free trial for full enterprise platform. | Unified lakehouse platform combining Apache Spark, Databricks SQL warehouse, Unity Catalog, and machine learning. |
| **[Qlik Sense](https://www.qlik.com/)** | ~$10B Private Valuation (Thoma Bravo acquired; ~$1B+ annual revenue) | **Standard** starts at **$825/month** (includes 25 GB data reload/year and basic users); Enterprise tiers require custom capacity quote | **No free forever plan**. 30-day fully functional free trial for up to 5 users on Qlik Cloud. | Associative analytics engine allowing non-linear data exploration across multiple disparate sources without predefined paths. |
| **[ThoughtSpot](https://www.thoughtspot.com/)** | ~$4.5B Private Valuation (~$150M+ ARR) | **Team tier** starts at **$95/month** (includes 5 users and 5M rows indexed); **Essential** starts at **$1,250/month** | **No free forever plan**. 14-day free trial with full AI search and Liveboard capabilities on sample or connected cloud data. | Search- and AI-driven BI platform enabling natural-language querying ("SearchIQ" / ThoughtSpot Sage) over enterprise databases. |
| **[Sisense](https://www.sisense.com/)** | ~$1B Private Valuation (~$140M+ ARR) | Starting at **~$10,000/year (~$833/month)** for entry-level embedded analytics packages, scaling up with server cores and query capacity | **No free forever plan**. 14-day full-access free trial on Sisense Cloud. | Developer-first embedded analytics and API-first business intelligence for white-labeling dashboards inside SaaS products. |
| **[Domo](https://www.domo.com/)** | ~$350M Market Cap (Annual revenue ~$320M) | Starting tier starts at **$300/month** (Consumption-based packages with included monthly credits) | **Free forever plan**: Free tier offering up to 300 credits/month, up to 1M rows of data, and access to 1,000+ pre-built connectors. 30-day full enterprise trial. | Full-stack cloud BI combining data pipelines/ETL, app building, and real-time dashboarding in a single interface. |

## Open-Source GitHub Projects

The following table lists top open-source analytics platforms, query engines, and BI tools, sorted by GitHub star count in descending order:

| Open-Source Project | GitHub Stars | License | Tech Stack | Primary Focus & Architecture |
| :--- | :--- | :--- | :--- | :--- |
| **[Grafana](https://github.com/grafana/grafana)** | [![GitHub stars](https://img.shields.io/github/stars/grafana/grafana?style=social&color=white)](https://github.com/grafana/grafana/stargazers) | AGPL-3.0 | Go, TypeScript, React | The industry standard for time-series analytics, operational observability, and mixed-source metrics dashboards. |
| **[Apache Superset](https://github.com/apache/superset)** | [![GitHub stars](https://img.shields.io/github/stars/apache/superset?style=social&color=white)](https://github.com/apache/superset/stargazers) | Apache-2.0 | Python (Flask), React, SQLAlchemy | Leading enterprise-ready open-source business intelligence platform with 40+ database connectors and SQL Lab IDE. |
| **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** | [![GitHub stars](https://img.shields.io/github/stars/ClickHouse/ClickHouse?style=social&color=white)](https://github.com/ClickHouse/ClickHouse/stargazers) | Apache-2.0 | C++ | Ultra-fast column-oriented distributed OLAP database management system powering real-time analytical reporting at petabyte scale. |
| **[Metabase](https://github.com/metabase/metabase)** | [![GitHub stars](https://img.shields.io/github/stars/metabase/metabase?style=social&color=white)](https://github.com/metabase/metabase/stargazers) | AGPL-3.0 / Commercial | Clojure, TypeScript, React | User-friendly self-service BI and visual question builder enabling non-technical users to explore data and build dashboards. |
| **[DuckDB](https://github.com/duckdb/duckdb)** | [![GitHub stars](https://img.shields.io/github/stars/duckdb/duckdb?style=social&color=white)](https://github.com/duckdb/duckdb/stargazers) | MIT | C++, C | In-process analytical SQL OLAP database management engine designed for fast local analytical queries and serverless data apps. |
| **[Redash](https://github.com/getredash/redash)** | [![GitHub stars](https://img.shields.io/github/stars/getredash/redash?style=social&color=white)](https://github.com/getredash/redash/stargazers) | BSD-2-Clause | Python, React | Query-first BI and dashboarding application with native SQL editor, scheduled query refreshes, and alerting across dozens of sources. |
| **[Cube](https://github.com/cube-js/cube)** | [![GitHub stars](https://img.shields.io/github/stars/cube-js/cube?style=social&color=white)](https://github.com/cube-js/cube/stargazers) | Apache-2.0 | Rust, TypeScript | Universal semantic layer and headless BI platform providing caching, access controls, and SQL/REST/GraphQL APIs over warehouses. |
| **[Presto](https://github.com/prestodb/presto)** | [![GitHub stars](https://img.shields.io/github/stars/prestodb/presto?style=social&color=white)](https://github.com/prestodb/presto/stargazers) | Apache-2.0 | Java, C++ | Distributed SQL query engine for running interactive analytic queries against diverse data sources ranging from gigabytes to petabytes. |
| **[Apache Doris](https://github.com/apache/doris)** | [![GitHub stars](https://img.shields.io/github/stars/apache/doris?style=social&color=white)](https://github.com/apache/doris/stargazers) | Apache-2.0 | C++, Java | Real-time MPP analytical database providing sub-second SQL queries over large-scale tables, semi-structured data, and log search. |
| **[Trino](https://github.com/trinodb/trino)** | [![GitHub stars](https://img.shields.io/github/stars/trinodb/trino?style=social&color=white)](https://github.com/trinodb/trino/stargazers) | Apache-2.0 | Java | High-performance distributed SQL query engine designed for interactive lakehouse analytics over object stores, databases, and streaming sources. |
| **[StarRocks](https://github.com/StarRocks/starrocks)** | [![GitHub stars](https://img.shields.io/github/stars/StarRocks/starrocks?style=social&color=white)](https://github.com/StarRocks/starrocks/stargazers) | Apache-2.0 | C++, Java | Linux Foundation sub-second MPP query engine supporting multi-dimensional real-time analytics on and off data lakehouses. |
| **[RAWGraphs](https://github.com/rawgraphs/rawgraphs-app)** | [![GitHub stars](https://img.shields.io/github/stars/rawgraphs/rawgraphs-app?style=social&color=white)](https://github.com/rawgraphs/rawgraphs-app/stargazers) | Apache-2.0 | JavaScript, React, D3.js | Open visual data exploration utility for creating custom vector charts and high-level graphic representations from spreadsheet data. |
| **[Evidence](https://github.com/evidence-dev/evidence)** | [![GitHub stars](https://img.shields.io/github/stars/evidence-dev/evidence?style=social&color=white)](https://github.com/evidence-dev/evidence/stargazers) | MIT | Svelte, TypeScript, Markdown | "Business Intelligence as Code" framework allowing engineers to generate fast, interactive, version-controlled markdown data apps. |
| **[Lightdash](https://github.com/lightdash/lightdash)** | [![GitHub stars](https://img.shields.io/github/stars/lightdash/lightdash?style=social&color=white)](https://github.com/lightdash/lightdash/stargazers) | MIT / Apache-2.0 | TypeScript, React, Node.js | Modern open-source Looker alternative built natively on dbt, allowing metric definitions and semantic modeling directly in dbt YAML. |
| **[Rill](https://github.com/rilldata/rill)** | [![GitHub stars](https://img.shields.io/github/stars/rilldata/rill?style=social&color=white)](https://github.com/rilldata/rill/stargazers) | Apache-2.0 | Go, Svelte, DuckDB | Fast, BI-as-code operational dashboarding tool paired with embedded DuckDB/ClickHouse for instant exploratory metrics. |

### Additional Notable Open-Source Solutions & Infrastructure

- **[Apache Drill](https://github.com/apache/drill)** — Schema-free SQL query engine for Hadoop, NoSQL, and cloud storage.
- **[Apache Polaris](https://github.com/apache/polaris)** — Open-source enterprise catalog for Apache Iceberg tables providing unified data lakehouse governance.
- **[Apache ECharts](https://github.com/apache/echarts)** — Comprehensive, interactive open-source charting and data visualization library.
- **[Knowage](https://github.com/knowage-labs/knowage-core)** — Full-featured enterprise open-source BI suite offering traditional operational reporting, multidimensional OLAP, and KPI cockpits.
- **[Preset](https://preset.io/)** — Fully managed cloud platform built on Apache Superset with enterprise security, SSO, and automated scaling.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing tabular and detail formats).
3. Include: name, link, specific pricing details, license (for open-source), and star badges.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data analytics platforms handling business data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and audit logging.
- **The "BI platform vs. query engine vs. semantic layer vs. visualization tool" distinction matters.** **Apache Superset, Metabase, Lightdash, and Redash** are **BI platforms**—they provide dashboards, user management, and self-service exploration. **ClickHouse, DuckDB, Trino, Presto, StarRocks, and Apache Doris** are **query engines**—they store and query data but typically require a BI or visualization layer. **Cube** is a **headless semantic layer** providing centralized metric governance and caching. **Grafana** is an **operational and time-series dashboard tool**. **Evidence and Rill** provide modern **BI-as-code** workflows. **RAWGraphs** is a **visualization utility**. Choose based on whether you need a complete analytics application or underlying infrastructure components.
- **Metabase's open-source edition is genuinely free and unlimited**—no user caps, no credit card, and includes the query builder, SQL editor, dashboards, and guest embeds. **The trade-off**: SSO, row-level security, and white-labeling are gated behind Pro/Enterprise plans.
- **Apache Superset is the most enterprise-ready open-source BI platform.** It offers the broadest warehouse coverage (40+ connectors), native SQL dialect support with query pushdown, and granular access controls (Admin/Alpha/Gamma/Public roles plus LDAP/OIDC auth).
- **Lightdash is the best choice only if you're already using dbt.** Its entire value proposition—metrics declared in dbt YAML, synced descriptions, lineage—depends on an existing dbt project.
- Pricing and company valuation details are compiled based on publicly reported numbers, vendor documentation, and SEC filings as of 2024–2026. Validate with direct vendor conversations against your actual query volumes and user counts.
- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. Ensure your hosting meets your organization's security and performance requirements before deploying.

---

**Made for developers, data teams, and organizations building transparent analytics solutions.**
