# Revenue Intelligence Dashboard | Amazon QuickSight

## Project Overview

The Revenue Intelligence Dashboard was developed for NovaTech Solutions, a B2B SaaS company whose sales, marketing, and customer-support data was held in separate systems.

The objective was to bring these business domains into one interactive reporting experience, giving the VP of Revenue Operations, Sarah Chen, a more unified view of marketing performance, sales pipeline progression, and customer health. By connecting these areas, the dashboard supports analysis across the **customer journey**, from marketing engagement and deal progression to customer-support activity.

Using Amazon QuickSight, I verified the available data, prepared and integrated datasets, developed an interactive dashboard, configured QuickSight Q for natural-language analysis, and prepared an executive report.

## 1. Data Quality Verification

I began by querying the four pre-indexed knowledge bases available in the project workspace: CRM Deals, Marketing Campaigns, Support Tickets, and Company Background.

I used the available information and supplied data dictionary to verify business data and documented the checks and findings in the verification log.

## 2. Source Data and SPICE

I uploaded the three supplied CSV datasets to Amazon QuickSight:

- `crm_deals.csv`
- `marketing_campaigns.csv`
- `support_tickets.csv`

I saved the source datasets to SPICE, QuickSight’s in-memory data engine, making them available for subsequent preparation and analysis.

## 3. Data Transformation and Integration

I began data preparation with the CRM Deals dataset, reviewing its fields and applying the required field-name and data-type changes. I created calculated fields using the project’s business logic and prepared the data for analysis and integration.

I then joined CRM Deals, Marketing Campaigns, and Support Tickets into a unified dataset. I documented the join configuration, anchor table, and join logic. After creating the unified dataset, I saved it to SPICE for use in the dashboard.

## 4. Interactive Dashboard Development

I built a three-sheet dashboard, with each sheet addressing a distinct business need:

- **Marketing Funnel:** Examines campaign performance and lead-to-deal conversion.
- **Sales Pipeline:** Presents the sales pipeline by deal stage and segment, including deal values and win-rate measures.
- **Customer Health:** Uses the unified dataset to examine customer accounts across the available data domains and help identify accounts that may need attention.

The dashboard includes KPI cards, relevant visualizations, interactive filters, one-click filtering between visuals, and cross-sheet navigation. I published the dashboard and exported a PDF covering all three sheets.

## 5. QuickSight Q and Natural-Language Analysis

I configured a QuickSight Q Topic to support natural-language questions about the business data. I tested baseline questions before and after Topic configuration and documented the results.

I also recorded questions across marketing, sales, and customer support in the Q Exploration Log, including questions requiring cross-dataset analysis. I verified more than five AI-generated answers against dashboard results, documenting agreements and discrepancies to assess answer accuracy.

## 6. Business Insights and Executive Reporting

I added dashboard annotations connecting quantified findings to their business implications and recommended actions.

I also prepared an executive report for Sarah Chen, VP of Revenue Operations, presenting the project’s findings and recommendations. The report included comparisons between AI-generated answers and dashboard results, supporting more informed interpretation of the analysis.

## Project Outcome

The project brought sales, marketing, and customer-support analysis into one reporting experience. It combined prepared and integrated data, interactive business intelligence, natural-language exploration, and verification of AI-generated answers to support revenue decisions and provide a more connected view of the customer journey.

**Skills Demonstrated**
- Data quality verification
- Data transformation and field renaming
- Data type correction and calculated fields
- Multi-source data integration and joins
- KPI development
- Interactive dashboard design
- Customer journey analysis
- Natural-language analysis using QuickSight Q
- AI response verification against dashboard results
- Business insights and executive reporting

**Tools:** Amazon QuickSight, QuickSight Q, SPICE, and CSV datasets.
