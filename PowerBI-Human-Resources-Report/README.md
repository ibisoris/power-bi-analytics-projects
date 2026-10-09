# Human Resources Report

[Back to the Power BI Analytics Projects portfolio](../README.md)

## Overview

This repository contains a Power BI project for analyzing the human resources data of TechnoEdge. The dataset includes information such as employee demographics, job positions, salaries, and performance ratings. The project aims to provide insights on employee retention, promotion patterns, and job satisfaction levels through interactive visualizations.

**Portfolio Author and Maintainer:** Ibinabo Orifama · [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

## Business Problem and Objectives

HR leaders need visibility into employee demographics, performance, compensation, and absence patterns to inform workforce planning.

### Documented objectives

1. **Demographic Analysis:** Understand age, gender, marital status, and education level distributions.
2. **Performance Assessment:** Evaluate employee performance using ratings, job involvement, satisfaction, and tenure.
3. **Work-Life Balance Evaluation:** Assess sick days, balance days, and work-life balance ratings.
4. **Tenure and Career Progression:** Analyze years of service, last promotion, and job classification.
5. **Department and Group Analysis:** Evaluate employee distribution across departments and groups.
6. **Compensation Analysis:** Assess salary data for fairness and competitiveness.
7. **Absence Management:** Understand employee absenteeism patterns and its impact.
8. **Employee Engagement Assessment:** Assess job satisfaction, job involvement, and relationship satisfaction for engagement levels.

These are the original analysis objectives. An objective is not evidence that a feature or finding was completed. Verified report components and limitations are listed below.

## Dataset and Available Sources

The project materials describe employee demographics, positions, salaries, performance ratings, satisfaction, job involvement, tenure, promotion information, sick days, and balance days.

The available sources for reviewing this project are the saved [Power BI report](./TechnoEdge_Human_Resources_Report.pbix), [project brief](./Problem_Statement.pdf), [PDF dashboard export](./Human_Resources_Dashboard.pdf), and [dashboard screenshot](./HR_Report.png). No standalone CSV or Excel source dataset is included in this folder. The saved report contains a data-model payload; the original input files, connection settings, source provenance, record count, currency units, and refresh requirements have not been independently verified.

## KPIs and Metrics

Employee count, department count, average salary, average balance days, average sick days, and departmental salary comparisons.

The screenshot shows metrics in its saved filter context. Metric labels do not, by themselves, verify aggregation rules, population definitions, or calculations.

## Tools and Technologies

- **Power BI Desktop:** The included `.pbix` file contains the report layout and data model.
- **Data visualization:** Cards, Donut charts, Funnel charts, Matrices, Pie charts, Ribbon charts, Slicers.
- **Report tooltips:** A dedicated tooltip page is present in the report layout.

Tools mentioned only as prerequisites are not treated as verified implementations. This review does not establish Excel, Power Pivot, Power View, or Power BI Service use.

## DAX Measures and Analytical Techniques

No explicit named model-measure references were found in the inspected report layout. Visuals use column references and aggregations; this does not establish that the model contains no DAX measures. No independently verified DAX formulas are available, so no example expressions are presented as implemented code.

**Analytical techniques and verified report components:** Power BI Desktop; year and business-unit slicers, cards, pie/donut charts, salary funnel, performance ribbon chart, expandable matrix, action buttons, and a tooltip page confirmed in the report layout.

### Report pages

| Page | Role |
| --- | --- |
| HR-Domain | Report page |
| Tooltip | Report tooltip |

## Dashboard Screenshot

![Saved Human Resources Report dashboard](./HR_Report.png)

Existing project screenshot, shown without alteration. [View the PDF dashboard export](./Human_Resources_Dashboard.pdf) for another saved view.

## Findings and Business Recommendations

### Observed findings

The saved cards show 187 employees, 15 departments, average salary of 95.84K, average balance days of 12.48, and average sick days of 6.41. The demographic visuals total 199, which differs from the employee card; population definitions or filters need reconciliation before demographic percentages are used. No retention or promotion outcome is established by the screenshot.

These observations describe the saved screenshot and are not live, audited, or causal results.

### Recommended follow-up

- Resolve the difference between the 187 employee card and demographic totals of 199 before publishing demographic percentages.
- Review sick-day and balance-day patterns by business unit and job type, using verified definitions and periods; the saved report does not establish the causes of absence.

Recommendations are proposed next steps based on the displayed patterns and documented objectives; they are not claims of implemented changes or proven business impact.

## Open and Explore the Report

1. Download [TechnoEdge_Human_Resources_Report.pbix](./TechnoEdge_Human_Resources_Report.pbix) to your Windows computer and open it in Power BI Desktop.
2. Start with the saved report view, then explore the report pages listed above. Tooltip pages support hover detail and may be hidden from normal navigation.
3. Use the available slicers and navigation controls to compare segments or periods. Record the filter context when interpreting values and reset selections before comparing totals.
4. Review [the project brief](./Problem_Statement.pdf) to compare the intended objectives with the available visuals. Hover over charts where tooltips are configured.
5. Inspect visual field aggregations, any model measures, and relationships in Power BI Desktop before relying on reported totals.
6. If refreshing requires unavailable files, credentials, or connections, the original data sources must be obtained and configured first. The screenshot and PDF remain available for reviewing the saved output.

No verified public interactive-report URL is included in this project. Opening the local file does not require publishing it.

## Project Files

| File | Purpose |
| --- | --- |
| [TechnoEdge_Human_Resources_Report.pbix](./TechnoEdge_Human_Resources_Report.pbix) | Power BI report |
| [Problem_Statement.pdf](./Problem_Statement.pdf) | Original problem statement / project overview |
| [Human_Resources_Dashboard.pdf](./Human_Resources_Dashboard.pdf) | Saved dashboard PDF |
| [HR_Report.png](./HR_Report.png) | Existing dashboard screenshot |
| [README.md](./README.md) | Project documentation |

## Limitations and Missing Information

- Original input datasets, data provenance, record counts, refresh configuration, and currency definitions are not verified.
- Full DAX expressions, model relationships, transformation steps, and independent metric validation are not available in this documentation review.
- Employee population totals need reconciliation. Retention, promotion outcomes, salary fairness, and causal engagement/absence findings are not established.
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

**Republication permission:** See the [permission and public-sharing record](../REPUBLISHING_PERMISSION.md). The author has confirmed authorship and that customer/employee data are synthetic or cleared for public sharing. These are author declarations; this portfolio does not claim a repository-wide MIT license.

## Contact and Contributions

**Portfolio Author and Maintainer:** Ibinabo Orifama  
**Email:** [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

The original documentation welcomes improvements and contributions. For documentation corrections or portfolio questions, contact the maintainer.

[Return to the main portfolio](../README.md)
