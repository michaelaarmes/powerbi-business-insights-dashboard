# Power BI Business Insights Dashboard

Executive-level Power BI dashboard designed to surface revenue performance, growth dynamics, and concentration risk in a retail banking context using synthetic sample data.

## What’s Included
- **Executive Summary (PDF):** `docs/Michael_Armes_PowerBI_Business_Insights_Sample.pdf`
- **Power BI File (PBIX):** `pbix/TD PBIX.pbix`
- **Source Data (Excel):** `data/td_synthetic_banking_data.xlsx`


## Key Features
- Executive KPI layer (Revenue, Balance, New Accounts, Attrition, Net Account Growth)
- Monthly trend view for performance monitoring
- Revenue drivers by Product and Customer Segment
- Revenue Mix (%) view for concentration risk
- **Drill-through page** for product-level investigation (trend + segment mix + region mix)
- Star schema modeling approach (dimension tables filtering fact tables)

## How to View
1. Open the PDF in the `docs/` folder for a business-first walkthrough
2. Download the PBIX from the `pbix/` folder and open in Power BI Desktop

## Data Notes
The dataset is fully synthetic and designed to mirror the structure and behavior of a Canadian retail banking environment. It includes monthly transaction-level metrics across products, customer segments, regions, and branches and was created solely for demonstration purposes.

## Reproducibility
The Power BI model can be fully rebuilt by loading the Excel dataset in the `data/` folder and recreating the star schema relationships documented in the executive summary.

