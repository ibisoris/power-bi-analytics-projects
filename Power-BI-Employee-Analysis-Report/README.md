# Employee Analysis Report

[Back to the Power BI Analytics Projects portfolio](../README.md)

## Overview

This repository contains a Power BI project for analyzing the employee details of TechnoEdge. The dataset includes information such as employee ID, name, position, salary, and attendance. This information is used to gain insights into the company's workforce, their performance, and overall productivity.

**Portfolio Author and Maintainer:** Ibinabo Orifama · [ibisoris2026@gmail.com](mailto:ibisoris2026@gmail.com)

## Business Problem and Objectives

HR teams need a clear view of workforce composition, compensation, and attendance to support staffing decisions.

### Documented objectives

1. **Attendance Patterns:** Analyze employee attendance patterns.
2. **Employee Qualifications and Skills:** Display education qualifications and skills of each employee.
3. **Department and Gender Count:** Use a bar chart to show the count of employees in each department, split by gender.
4. **Experience and Salary:** Understand employee experience and salary.
5. **Age and Nationality:** Investigate employee age and nationality.
6. **Performance by Position:** Use a table to display employee details such as position, name, and sum of salary.
7. **Emergency Contacts:** Identify employee emergency contacts.
8. **Turnover Rate:** Create a line chart to display the count of employees who left each year.

These are the original analysis objectives. An objective is not evidence that a feature or finding was completed. Verified report components and limitations are listed below.

## Dataset and Available Sources

The problem statement describes employee ID, name, position, salary, and attendance. The report also presents employment type, age group, department, year, and country.

The available sources for reviewing this project are the saved [Power BI report](./PowerBI_Employee_Analysis.pbix), [project brief](./Problem_Statement.pdf), [PDF dashboard export](./Employee_Dashboard.pdf), and [dashboard screenshot](./Dashboard.png). No standalone CSV or Excel source dataset is included in this folder. The saved report contains a data-model payload; the original input files, connection settings, source provenance, record count, currency units, and refresh requirements have not been independently verified.

## KPIs and Metrics

Total hired employees, average salary, total departments, salary by employee, employee counts by department/year, and attendance breakdowns.

The screenshot shows metrics in its saved filter context. Metric labels do not, by themselves, verify aggregation rules, population definitions, or calculations.

## Tools and Technologies

- **Power BI Desktop:** The included `.pbix` file contains the report layout and data model.
- **Data visualization:** Cards, Clustered bar charts, Column charts, Detail tables, Donut charts, Line/column combination charts, Pie charts, Slicers.

Tools mentioned only as prerequisites are not treated as verified implementations. This review does not establish Excel, Power Pivot, Power View, or Power BI Service use.

## DAX Measures and Analytical Techniques

No explicit named model-measure references were found in the inspected report layout. Visuals use column references and aggregations; this does not establish that the model contains no DAX measures. No independently verified DAX formulas are available, so no example expressions are presented as implemented code.

**Analytical techniques and verified report components:** Power BI Desktop; country slicer, cards, employee detail table, pie/donut charts, clustered bar chart, column chart, and line/column combination chart confirmed in the report layout.

### Report pages

| Page | Role |
| --- | --- |
| Employee Report | Report page |

## Dashboard Screenshot

![Saved Employee Analysis Report dashboard](./Dashboard.png)

Existing project screenshot, shown without alteration. [View the PDF dashboard export](./Employee_Dashboard.pdf) for another saved view.

## Findings and Business Recommendations

### Observed findings

The saved report shows 46 total hired employees, an average salary of 8.43K, and 11 departments. Its age-group chart shows ages 31–45 as the largest displayed group. Some breakdowns do not reconcile directly with the headcount card, so their aggregation and filter context should be checked before making staffing recommendations.

These observations describe the saved screenshot and are not live, audited, or causal results.

### Recommended follow-up

- Reconcile headcount, employment-type percentages, and departmental/year breakdowns before using the report for workforce planning.
- Compare attendance and compensation within comparable roles and periods; confirm departure counts and a denominator before describing turnover as a rate.

Recommendations are proposed next steps based on the displayed patterns and documented objectives; they are not claims of implemented changes or proven business impact.

## Open and Explore the Report

1. Download [PowerBI_Employee_Analysis.pbix](./PowerBI_Employee_Analysis.pbix) to your Windows computer and open it in Power BI Desktop.
2. Start with the saved report view, then explore the report pages listed above. Tooltip pages support hover detail and may be hidden from normal navigation.
3. Use the available slicers and navigation controls to compare segments or periods. Record the filter context when interpreting values and reset selections before comparing totals.
4. Review [the project brief](./Problem_Statement.pdf) to compare the intended objectives with the available visuals. Hover over charts where tooltips are configured.
5. Inspect visual field aggregations, any model measures, and relationships in Power BI Desktop before relying on reported totals.
6. If refreshing requires unavailable files, credentials, or connections, the original data sources must be obtained and configured first. The screenshot and PDF remain available for reviewing the saved output.

No verified public interactive-report URL is included in this project. Opening the local file does not require publishing it.

## Project Files

| File | Purpose |
| --- | --- |
| [PowerBI_Employee_Analysis.pbix](./PowerBI_Employee_Analysis.pbix) | Power BI report |
| [Problem_Statement.pdf](./Problem_Statement.pdf) | Original problem statement / project overview |
| [Employee_Dashboard.pdf](./Employee_Dashboard.pdf) | Saved dashboard PDF |
| [Dashboard.png](./Dashboard.png) | Existing dashboard screenshot |
| [README.md](./README.md) | Project documentation |

## Limitations and Missing Information

- Original input datasets, data provenance, record counts, refresh configuration, and currency definitions are not verified.
- Full DAX expressions, model relationships, transformation steps, and independent metric validation are not available in this documentation review.
- Headcount and breakdowns require reconciliation. A validated turnover-rate measure, qualifications/skills analysis, and emergency-contact reporting are not confirmed in the saved dashboard.
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
