## Project Background

This project demonstrates end-to-end housing market analysis using a modern data stack powered by Google Cloud Platform (BigQuery) and Power BI. The workflow covers data ingestion, transformation, modeling, and visualization, showcasing advanced DAX functions and analytical storytelling.

## Project Workflow
Step	Description	Tools Used
| Step | Description | Tools Used |
|-----------|-----------|-----------|
| **1. Google Cloud Setup** | Created a free Google Cloud account and configured a BigQuery project for housing data storage. | Google Cloud Console |
| **2. Data Ingestion** | Loaded CSV files containing housing transactions (region, type, price, area, date, etc.) into **Google BigQuery tables**. | BigQuery |
| **3. SQL Data Transformation** | Used **SQL queries in BigQuery** to clean, filter, and structure datasets for reporting. | BigQuery SQL |
| **4. Power BI Connection** | Connected BigQuery to Power BI using the native connector to enable real-time cloud querying. | Power BI |
| **5. Data Cleaning in Power Query** | Removed duplicates, standardized formats, converted date fields, and managed missing values. | Power Query Editor |
| **6. KPI Calculation using DAX** | Developed custom measures for YOY growth, last 12-month sales, offer ratios, and SQM pricing. | DAX |
| **7. Dashboard Design** | Built multiple visuals — regional sales maps, offer-vs-purchase comparison, key influencers, and sales by type. | Power BI Visuals |
| **8. Insights & Interpretation** | Derived executive insights for pricing trends, sales performance, and buyer behavior. | Data Storytelling |

## Core DAX Functions Used

| Function | Purpose |
|-----------|-----------|
| **CALCULATE()** | Used to apply filters dynamically for conditional aggregations. |
| **DATESINPERIOD()** | Extracted rolling 12-month sales windows. |
| **DISTINCTCOUNT()** | Counted unique property sales (units sold). |
| **TOTALYTD()** | Tracked Year-to-Date performance metrics. |
| **MEDIANX()** | Calculated median sales price changes per region. |
| **ALLEXCEPT()** | Evaluated region-specific sales while preserving context. |
| **MAX(), YEAR(), QUARTER()** | Extracted time intelligence features for visuals. |

## Visual Storytelling Highlights
House Market Overview

![Housemarket Overview](https://i.imgur.com/3rBKJ0C.jpeg)

Sales Performance
![Sales Performance Analysis Analysis]([https://i.imgur.com/PI0wzCF.jpeg](https://i.imgur.com/7tFbV1v.jpeg))


House Type Analysis
![HouseType Analysis](https://i.imgur.com/PI0wzCF.jpeg)

## Business Insights & Recommended Actions
The following table summarizes key findings from the Housing Market Analysis dashboard and provides strategic actions for management and operational teams.

| Analysis Area | What Was Understood | Recommended Action |
|----------------|---------------------|--------------------|
| **YOY Sales Growth by Sales Type** | Regular sales grew slightly, but auction and family sales declined. Auction sales show a -0.75 drop indicating weak demand in distressed or forced-sale markets. | Reevaluate auction strategies, focus on marketing campaigns for family-sale listings, and assess factors causing slower auction conversions. |
| **Median Sales Price Change by Region** | Zealand maintained stable growth (~+5%), while other regions (Fyn & Islands, Jutland, Bornholm) remained flat or negative. Indicates regional imbalance. | Allocate more resources and promotions to underperforming regions. Explore pricing incentives to stimulate growth outside Zealand. |
| **Offer Price vs Purchase Price Ratio (1.02)** | Slight overvaluation in listings; buyers are negotiating below offer price, suggesting market is price-sensitive. | Adjust pricing strategies and improve valuation accuracy before listing. Use analytics to refine price recommendations for agents. |
| **Average SQM Price by Region** | Zealand is the most premium region (20.85K per SQM), while Bornholm is the most affordable (10.6K per SQM). Highlights diverse market segments. | Target luxury marketing in Zealand and affordability campaigns in Bornholm. Align regional investment portfolios accordingly. |
| **Sales Performance by Region** | Zealand leads with 95B total sales, followed by Jutland at 81B. Fyn & Islands and Bornholm contribute less. | Focus on maintaining Zealand dominance while developing secondary market growth strategies in Jutland and Fyn. |
| **Key Influencers (Purchase Price Drivers)** | Property age and size strongly impact price. Houses under 16 years old or larger in area achieve up to +314K higher prices. | Promote renovation programs, highlight newer listings, and emphasize modern construction in marketing. |
| **Average Offer/Purchase by House Type** | Villas and farms have higher average transaction values; apartments and townhouses show moderate pricing. | Position villas and farms as premium investments, while offering flexible financing options for apartments to attract mid-range buyers. |
| **Average Yield, Interest, Inflation by House Type** | Yield and interest rates vary significantly; villas and apartments offer better returns. Inflation slightly affects small properties. | Prioritize investment in property types with higher yields. Adjust ROI projections considering inflation impact. |
| **Offer-to-SQM Ratio by Sales Type** | Regular sales have the highest offer per SQM; auctions and family sales are lower. Reflects varying buyer confidence. | Monitor regular sale trends to benchmark pricing. Reassess auction property quality and visibility. |
| **Sales Units (Latest Year & Quarter)** | 77 units sold with 13.29B total sales in the last 12 months shows stable but not high-volume turnover. | Increase listings volume and optimize advertising budgets for regions with fewer transactions. Encourage seasonal promotions. |





