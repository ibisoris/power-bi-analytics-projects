# Sales Analysis Report

[Back to the Power BI Analytics Projects portfolio](../README.md)

## Overview

This repository contains a Power BI project for analyzing sales data of TechnoEdge, a company dealing with diverse products. The project aims to provide insights into sales performance, customer behavior, and product performance across different regions and categories.

**Portfolio Author and Maintainer:** Ibinabo Orifama · [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

## Business Problem and Objectives

Sales and marketing teams need a consolidated view of revenue, profit, customer activity, and product performance to identify improvement opportunities.

### Documented objectives

1. **Analyze Sales Data:** Evaluate sales data across different regions, countries, and product categories.
2. **Identify Trends:** Discover patterns and trends in sales data to enhance business performance.
3. **Understand Customer Behavior:** Analyze customer buying patterns to gain insights into their behavior and preferences.
4. **Evaluate Product Performance:** Identify high-performing and underperforming products and categories.
5. **Monitor Key Metrics:** Track key sales metrics such as sales, profit, and profit margin to identify improvement areas.
6. **Create Informative Reports:** Develop reports and visualizations to aid stakeholders in making informed sales and marketing decisions.

These are the original analysis objectives. An objective is not evidence that a feature or finding was completed. Verified report components and limitations are listed below.

## Dataset and Available Sources

The project overview describes order and product identifiers, categories, sub-categories, sales, quantity, discount, and profit. The report also provides state, ship-mode, segment, and year filters.

The available sources for reviewing this project are the saved [Power BI report](./Technoedg%20Sales%20-%20%28PBI%29dashboard.pbix), [project brief](./Project%20Overview.pdf), [PDF dashboard export](./Technoedg%20Sales%20-%20%28PBI%29dashboard.pdf), and [dashboard screenshot](./Dashboard_summary.png). No standalone CSV or Excel source dataset is included in this folder. The saved report contains a data-model payload; the original input files, connection settings, source provenance, record count, currency units, and refresh requirements have not been independently verified.

## KPIs and Metrics

Total sales, net profit, total customers, and total quantity appear on the summary dashboard. Profit margin is a documented analysis objective.

The screenshot shows metrics in its saved filter context. Metric labels do not, by themselves, verify aggregation rules, population definitions, or calculations.

## Tools and Technologies

- **Power BI Desktop:** The included `.pbix` file contains the report layout and data model.
- **DAX:** The original README documents DAX use; the inspected layout does not expose explicit named measure references.
- **Power Query and data modeling:** The original README documents transformation, filtering, data preparation, and creation of a supporting model. Query steps and relationships are not independently validated here.
- **Data visualization:** Bar charts, Cards, Clustered bar charts, Column charts, Detail tables, Donut charts, Line charts, Line/stacked-column combination charts, Page navigation, Pie charts, Scatter charts, Scrolling-text custom visual, Slicers.
- **Report tooltips:** A dedicated tooltip page is present in the report layout.

Tools mentioned only as prerequisites are not treated as verified implementations. This review does not establish Excel, Power Pivot, Power View, or Power BI Service use.

## DAX Measures and Analytical Techniques

No explicit named model-measure references were found in the inspected report layout. Visuals use column references and aggregations; this does not establish that the model contains no DAX measures. No independently verified DAX formulas are available, so no example expressions are presented as implemented code.

**Analytical techniques and verified report components:** Power BI Desktop; Power Query transformation, filtering, and preparation and DAX calculations documented in the project README; summary, customer, and product pages; slicers, page navigation, cards, bar/pie/line charts, scatter plots, and report tooltips confirmed in the report layout.

### Report pages

| Page | Role |
| --- | --- |
| Home Page | Report page |
| Summary | Report page |
| Customer | Report page |
| Product | Report page |
| Tooltip | Report tooltip |

## Dashboard Screenshot

![Saved Sales Analysis Report dashboard](./Dashboard_summary.png)

Existing project screenshot, shown without alteration. [View the PDF dashboard export](./Technoedg%20Sales%20-%20%28PBI%29dashboard.pdf) for another saved view.

## Findings and Business Recommendations

### Observed findings

The saved summary shows BoomBox leading the displayed top-five products at approximately 8.2K. Annual net profit is highest in 2022 among the displayed years. These views support product prioritization and investigation of year-to-year profitability; they do not establish the causes of performance.

These observations describe the saved screenshot and are not live, audited, or causal results.

### Recommended follow-up

- Review BoomBox's contribution alongside margins and discount levels before prioritizing promotions or inventory.
- Investigate the drivers of the 2022 profit peak using product, customer, and regional breakdowns; compare like-for-like filters before changing sales plans.

Recommendations are proposed next steps based on the displayed patterns and documented objectives; they are not claims of implemented changes or proven business impact.

## Open and Explore the Report

1. Download [Technoedg Sales - (PBI)dashboard.pbix](./Technoedg%20Sales%20-%20%28PBI%29dashboard.pbix) to your Windows computer and open it in Power BI Desktop.
2. Start with the saved report view, then explore the report pages listed above. Tooltip pages support hover detail and may be hidden from normal navigation.
3. Use the available slicers and navigation controls to compare segments or periods. Record the filter context when interpreting values and reset selections before comparing totals.
4. Review [the project brief](./Project%20Overview.pdf) to compare the intended objectives with the available visuals. Hover over charts where tooltips are configured.
5. Inspect visual field aggregations, any model measures, and relationships in Power BI Desktop before relying on reported totals.
6. If refreshing requires unavailable files, credentials, or connections, the original data sources must be obtained and configured first. The screenshot and PDF remain available for reviewing the saved output.

No verified public interactive-report URL is included in this project. Opening the local file does not require publishing it.

## Project Files

| File | Purpose |
| --- | --- |
| [Technoedg Sales - (PBI)dashboard.pbix](./Technoedg%20Sales%20-%20%28PBI%29dashboard.pbix) | Power BI report |
| [Project Overview.pdf](./Project%20Overview.pdf) | Original problem statement / project overview |
| [Technoedg Sales - (PBI)dashboard.pdf](./Technoedg%20Sales%20-%20%28PBI%29dashboard.pdf) | Saved dashboard PDF |
| [Dashboard_summary.png](./Dashboard_summary.png) | Existing dashboard screenshot |
| [README.md](./README.md) | Project documentation |

## Limitations and Missing Information

- Original input datasets, data provenance, record counts, refresh configuration, and currency definitions are not verified.
- Full DAX expressions, model relationships, transformation steps, and independent metric validation are not available in this documentation review.
- Profit-margin, customer-lifetime-value, and retention calculations are described as goals but are not verified here. The original README says reports were shared; no working published-report URL is provided.
- Licensing and redistribution terms remain incompletely documented, as explained below.

## Original Technical Documentation

The original prerequisites are retained for reference. They are historical project guidance, not a verified current compatibility list or proof of tool usage.

<details>
<summary>Original technical prerequisites</summary>

### Skill Prerequisites
- Proficiency in data visualization and analysis concepts.
- Experience with data modeling and ETL processes.
- Proficiency in Power BI tools such as Power Query, Power Pivot, and Power View.
- Ability to collaborate effectively with stakeholders.

### System Requirements
- **Operating System:** Windows 10, Windows 8.1, Windows 8, or Windows 7 Service Pack 1 (32-bit and 64-bit).
- **Processor:** 1 GHz or faster x86 or x64-bit processor.
- **RAM:** 1 GB (32-bit) or 2 GB (64-bit) RAM.
- **Hard Disk Space:** 1 GB available disk space.
- **Display:** 1024 x 768 resolution.

</details>

<details>
<summary>Original implementation notes</summary>

- **Data Cleaning:** Utilized Power Query for data transformation, filtering, and preparation.
- **Data Modeling:** Created a robust data model to support the analysis.
- **Visual Insights:** Employed DAX functions to derive insights and create compelling visualizations.
- **Published Report:** Generated and shared interactive Power BI reports.

The original publishing statement is retained as documentation; no live report link or current deployment is verified.

</details>

## Attribution and Licensing

Original project materials are credited to **Dagogo Orifama**, from [Complete Power BI Projects](https://github.com/DagogoOrifama/Complete-Power-BI-Projects). **Ibinabo Orifama** maintains this portfolio and its documentation; this does not claim original development of the report.

**Existing license notice (preserved):**

> This project is licensed under the MIT License.

**Unresolved terms:** Neither this local collection nor the verified upstream root includes a standalone license file. GitHub repository metadata reports no detected license, despite the project README's MIT statement. This documentation preserves the statement without adding a new license or resolving the missing license text. Confirm the intended license, applicable copyright/permission notices, and dataset or third-party asset rights with the original author before reuse or redistribution. Do not assume unrestricted redistribution from the README statement alone. See the [portfolio licensing review](../README.md#attribution-and-licensing).

**Republication permission:** See the [permission and public-sharing record](../REPUBLISHING_PERMISSION.md). Permission scope and clearance are pending confirmation; this portfolio does not claim a repository-wide MIT license.

## Contact and Contributions

**Portfolio Author and Maintainer:** Ibinabo Orifama  
**Email:** [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

The original documentation welcomes improvements and contributions. For documentation corrections or portfolio questions, contact the maintainer.

[Return to the main portfolio](../README.md)
