# Customer Financial Behavior

[Back to the Power BI Analytics Projects portfolio](../README.md)

## Overview

This repository contains a Power BI project for analyzing the financial behavior of TechnoEdge's customers. The dataset includes information such as customer ID, name, gender, age, country, state, job classification, marital status, account type, date joined, balance, and loans taken.

**Portfolio Author and Maintainer:** Ibinabo Orifama · [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

## Business Problem and Objectives

Banking teams need to understand customer segments and how account balances and loan participation vary across demographics and locations.

### Documented objectives

1. **Age Distribution Analysis:** Analyze the age distribution of TechnoEdge banking customers and identify the most common age group.
2. **Gender Balance Comparison:** Compare the average balance in the accounts of male and female customers to determine if there is a gender-based disparity in account balances.
3. **State-wise Customer Analysis:** Identify the top three states with the highest number of TechnoEdge banking customers and determine the percentage of total customers they constitute.
4. **Job Classification and Loans:** Analyze the correlation between job classification and the presence of housing and other loans among TechnoEdge banking customers.
5. **Marital Status and Loans:** Determine the percentage of married customers with housing loans and compare it to the percentage of unmarried customers with housing loans to identify any significant differences.
6. **Account Type Popularity:** Identify the most common account type among TechnoEdge banking customers and determine the percentage of total customers with this account type.
7. **Customer Tenure and Balance:** Analyze the relationship between the length of time a customer has been with TechnoEdge and their account balance to determine if there is a correlation between the two variables.
8. **Country-wise Customer Analysis:** Identify the top three countries with the highest number of TechnoEdge banking customers and determine the percentage of total customers they constitute.

These are the original analysis objectives. An objective is not evidence that a feature or finding was completed. Verified report components and limitations are listed below.

## Dataset and Available Sources

The problem statement lists customer ID, name, gender, age, country, state, job classification, marital status, account type, date joined, balance, and loans taken.

The available sources for reviewing this project are the saved [Power BI report](./PowerBI_Customer_Financial_Analysis.pbix), [project brief](./Problem%20Statement.pdf), [PDF dashboard export](./Customer_Financial_Behavior_Dashboard.pdf), and [dashboard screenshot](./Bank_report.png). No standalone CSV or Excel source dataset is included in this folder. The saved report contains a data-model payload; the original input files, connection settings, source provenance, record count, currency units, and refresh requirements have not been independently verified.

## KPIs and Metrics

Customer count, balance amount, cards labeled Houseloan and Otherloan, and balance breakdowns by account type, month, job classification, and marital status.

The screenshot shows metrics in its saved filter context. Metric labels do not, by themselves, verify aggregation rules, population definitions, or calculations.

## Tools and Technologies

- **Power BI Desktop:** The included `.pbix` file contains the report layout and data model.
- **Data visualization:** Bar charts, Cards, Clustered column charts, Donut charts, Pie charts, Slicers, Stacked area charts.
- **Report tooltips:** A dedicated tooltip page is present in the report layout.

Tools mentioned only as prerequisites are not treated as verified implementations. This review does not establish Excel, Power Pivot, Power View, or Power BI Service use.

## DAX Measures and Analytical Techniques

No explicit named model-measure references were found in the inspected report layout. Visuals use column references and aggregations; this does not establish that the model contains no DAX measures. No independently verified DAX formulas are available, so no example expressions are presented as implemented code.

**Analytical techniques and verified report components:** Power BI Desktop; customer/state slicers, cards, stacked area chart, clustered column chart, bar/pie/donut charts, action buttons, and a tooltip page confirmed in the report layout.

### Report pages

| Page | Role |
| --- | --- |
| Bank_insights | Report page |
| Tootltip | Report tooltip |

## Dashboard Screenshot

![Saved Customer Financial Behavior dashboard](./Bank_report.png)

Existing project screenshot, shown without alteration. [View the PDF dashboard export](./Customer_Financial_Behavior_Dashboard.pdf) for another saved view.

## Findings and Business Recommendations

### Observed findings

The saved age/gender chart shows the largest displayed group at ages 36–45. Account type CA has the largest displayed balance, approximately 7M, and married customers have the largest marital-status balance, approximately 7.7M. These describe balance concentration; they do not establish average wealth or loan eligibility. Loan-card aggregation definitions are not verified.

These observations describe the saved screenshot and are not live, audited, or causal results.

### Recommended follow-up

- Investigate the balance concentration in account type CA and the 36–45 customer group to guide further segment analysis; validate average balances before designing offers.
- Confirm loan-field definitions and use verified loan participation counts before interpreting the Houseloan and Otherloan cards.

Recommendations are proposed next steps based on the displayed patterns and documented objectives; they are not claims of implemented changes or proven business impact.

## Open and Explore the Report

1. Download [PowerBI_Customer_Financial_Analysis.pbix](./PowerBI_Customer_Financial_Analysis.pbix) to your Windows computer and open it in Power BI Desktop.
2. Start with the saved report view, then explore the report pages listed above. Tooltip pages support hover detail and may be hidden from normal navigation.
3. Use the available slicers and navigation controls to compare segments or periods. Record the filter context when interpreting values and reset selections before comparing totals.
4. Review [the project brief](./Problem%20Statement.pdf) to compare the intended objectives with the available visuals. Hover over charts where tooltips are configured.
5. Inspect visual field aggregations, any model measures, and relationships in Power BI Desktop before relying on reported totals.
6. If refreshing requires unavailable files, credentials, or connections, the original data sources must be obtained and configured first. The screenshot and PDF remain available for reviewing the saved output.

No verified public interactive-report URL is included in this project. Opening the local file does not require publishing it.

## Project Files

| File | Purpose |
| --- | --- |
| [PowerBI_Customer_Financial_Analysis.pbix](./PowerBI_Customer_Financial_Analysis.pbix) | Power BI report |
| [Problem Statement.pdf](./Problem%20Statement.pdf) | Original problem statement / project overview |
| [Customer_Financial_Behavior_Dashboard.pdf](./Customer_Financial_Behavior_Dashboard.pdf) | Saved dashboard PDF |
| [Bank_report.png](./Bank_report.png) | Existing dashboard screenshot |
| [README.md](./README.md) | Project documentation |

## Limitations and Missing Information

- Original input datasets, data provenance, record counts, refresh configuration, and currency definitions are not verified.
- Full DAX expressions, model relationships, transformation steps, and independent metric validation are not available in this documentation review.
- Loan-card aggregations, account-type abbreviations, tenure/balance correlations, and gender-based average-balance comparisons are not independently validated.
- Licensing and redistribution terms remain incompletely documented, as explained below.

## Original Technical Documentation

The original prerequisites are retained for reference. They are historical project guidance, not a verified current compatibility list or proof of tool usage.

<details>
<summary>Original technical prerequisites</summary>

### Skill Prerequisites
- Solid understanding of data visualization and analysis concepts.
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
