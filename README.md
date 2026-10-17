# Marzelino Malintoi

### Data & Automation Engineer

*The data was messy. I took it personally.*

I build data pipelines, reporting, and automation that help teams make decisions and keep work moving. Previously, I led BI work at **VACO, supporting Google Surveys in Taipei**. My background combines an MBA with Chemical Engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-343B43?style=flat-square)](https://www.linkedin.com/in/marzelino/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Selected_work-343B43?style=flat-square)](https://www.datascienceportfol.io/marzelinomalintoi)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-343B43?style=flat-square)](mailto:marzelino.malintoi@gmail.com)

## Selected work

### Understand what drives revenue and delivery performance

**[Olist Executive Dashboard](https://github.com/marzelino10/olist-executive-dashboard)** connects sales, delivery delays, and customer reviews in four Power BI report pages. Built to move from executive KPIs to the categories and regions that need attention.

<a href="https://marzelino10.github.io/olist-executive-dashboard/"><img src="https://raw.githubusercontent.com/marzelino10/olist-executive-dashboard/main/docs/executive_overview.png" width="100%" alt="Olist executive dashboard showing revenue trends, product categories, regional sales, and delivery performance" /></a>

`Power BI` `Power Query` `DAX` `Dimensional modeling`

[Dashboard preview](https://marzelino10.github.io/olist-executive-dashboard/) · [Repository](https://github.com/marzelino10/olist-executive-dashboard)

### Connect field progress to purchasing and payments

**Kairagi PWA** brings construction QC, material workflows, inventory, and contractor payments into one system. Field teams capture evidence; reviewers approve work; accounting data stays connected through recoverable syncs.

Built on Cloudflare for offline field capture, controlled access, private photos, and notifications that keep reviews moving.

<p>
<img alt="Cloudflare Workers" src="https://img.shields.io/badge/Workers-D26B27?style=flat-square&amp;logo=cloudflareworkers&amp;logoColor=white" />
<img alt="Cloudflare Pages" src="https://img.shields.io/badge/Pages-D26B27?style=flat-square&amp;logo=cloudflarepages&amp;logoColor=white" />
<img alt="Cloudflare D1" src="https://img.shields.io/badge/D1-D26B27?style=flat-square" />
<img alt="Cloudflare R2" src="https://img.shields.io/badge/R2-D26B27?style=flat-square" />
<img alt="Cloudflare Durable Objects" src="https://img.shields.io/badge/Durable_Objects-D26B27?style=flat-square" />
<img alt="Cloudflare Queues" src="https://img.shields.io/badge/Queues-D26B27?style=flat-square" />
<img alt="Cloudflare Access" src="https://img.shields.io/badge/Access-D26B27?style=flat-square" />
</p>

`TypeScript` `Next.js` `Hono` `OAuth2`

### Turn raw sources into dependable analytical models

| Project | Purpose | Stack |
| :--- | :--- | :--- |
| **[Global Ski Resorts](https://github.com/marzelino10/ski-resorts)** | Combine resort and snow data to compare locations and skier suitability. Layered models, spatial joins, and quality checks make the transformations inspectable. | AWS S3, Snowflake, dbt |
| **Disaster Monitor** | Turn USGS earthquake records into country-enriched analytics, with daily ingestion, historical backfills, incremental merges, and visibility into failed runs. | Python, Airflow, Docker, GCS, BigQuery, dbt |

<a href="https://marzelino10.github.io/ski-resorts/"><img src="https://raw.githubusercontent.com/marzelino10/ski-resorts/main/docs/architecture/dbt_dag.png" width="100%" alt="Actual dbt lineage graph from the Ski Resorts project, connecting source, cleaned, and analytical models" /></a>

[Explore the Ski Resorts models and documentation](https://marzelino10.github.io/ski-resorts/)

## Workflow automation

### Repair contact data before it reaches reporting or outreach

A cleaning workflow that preserves original values, records corrections, and puts damaged phone numbers and uncertain duplicate matches into a review queue. The goal is usable contact data with an explanation for every unresolved record.

<img src="assets/contact-repair-demo.png" width="100%" alt="Contact-cleaning application comparing original and proposed field values, with unresolved phone numbers and duplicate candidates kept for review; synthetic demo records" />

<sub>Contact repair application, shown with synthetic demo records.</sub>

### Keep customer follow-ups moving

A wellness retail CRM connects customer records with consent-aware emails and staff reminders. Recurring due dates advance after a reminder is sent successfully, keeping the next action visible across staff handovers.

### Trace a stock issue through production

A food-lot workflow follows ingredients into finished batches and customer shipments. Downstream holds and investigation reports help operators identify the affected stock and make evidence-backed release decisions.

`Google Apps Script` `Google Sheets` `Forms` `Drive` `Gmail` `Slack`

**More public work:** [Attendee Badge Generator](https://github.com/marzelino10/label-generator), [WhoScored data collection](https://github.com/marzelino10/WhoScored_Selenium), [World Cup SQL analysis](https://github.com/marzelino10/projectFIFA), and [Moody Quotes](https://github.com/marzelino10/moody-quotes).

## Toolkit

| Area | Tools |
| :--- | :--- |
| Data engineering | SQL, Python, pandas, dbt, Airflow, Docker |
| Warehousing & storage | BigQuery, Snowflake, Google Cloud Storage, AWS S3, PostgreSQL |
| Reporting & analysis | Power BI, DAX, Power Query, Looker Studio, Tableau, Excel |
| Workflow automation | Apps Script, Google Sheets, JavaScript, REST APIs, Selenium |
| Cloudflare | Workers, Pages, D1, R2, Durable Objects, Queues, Access, Wrangler |

## Experience

**VACO, supporting Google Surveys** / Taipei, Taiwan  
BI Team Lead, 2024-2025 / Data Analyst, 2022-2024

- Centralized historical utilization reporting in SQL, improving reporting efficiency by **80%**.
- Automated brand-safety workflows with Apps Script, reducing manual maintenance by **90%**.
- Led BI work across data engineering and analytics, and mentored analysts in SQL, Looker Studio, and Apps Script.

Based in Manado, Indonesia. Open to data and automation opportunities.
