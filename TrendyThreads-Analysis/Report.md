# Social Media Campaign Analysis - TrendyThreads

## Introduction
TrendyThreads, a fashion e-commerce company, aimed to enhance the return on investment (ROI) of its social media campaigns. This project focused on analyzing their sales data to identify trends, patterns, and opportunities for optimization. Using SQL, Python, and Power BI, I derived actionable insights to improve their marketing strategy.

## Approach
- **Data Collection**: Created a simulated dataset (1000 rows) representing TrendyThreads' social media campaign data, with columns such as `Campaign_ID`, `Platform`, `Post_Date`, `Sales`, and `Engagement`.
- **Analysis**:
  - Utilized SQL to query platform-wise sales, monthly trends, and top-performing campaigns.
  - Employed Python (pandas, sklearn, matplotlib) for trend visualization and sales prediction for the next month.
  - Built an interactive dashboard in Power BI to visually present the insights.

## Key Findings
- **Platform Performance**: The Website generated the highest sales (~2.62M), followed by X (~2.57M), and Instagram (~2.44M). All platforms are closely competitive, indicating potential across each.
- **Seasonal Trends**: Sales peaked in June and August (729K and 735K, respectively), with a dip in November (548K), suggesting higher demand during the summer season.
- **Top Campaigns**: Top campaigns were dominated by Instagram and Website (sales ~14K-15K per campaign), but engagement was inconsistent—some campaigns had high sales but low engagement.
- **Prediction**: Predicted sales for January 2025 are approximately 572K, indicating a stable trend.

## Recommendations
- **Focus on High-ROI Platforms**: Allocate more budget to Instagram and Website, as they yield higher ROI.
- **Seasonal Strategy**: Stock up inventory for summer months (June-August), particularly for Jeans and Sneakers, to meet increased demand.
- **Boost Engagement on X**: Implement new strategies on X, such as influencer collaborations, to improve engagement, as the platform shows sales potential but lacks engagement.
- **Address Low Seasons**: Plan winter promotions to tackle the November dip and maintain stable sales.

## Dashboard
Below is a screenshot of the Power BI dashboard that visually presents all insights:

[/Powerbi project1.png]

## Tools Used
- **SQL**: For data querying and aggregation.
- **Python**: For data analysis, visualization, and prediction (pandas, sklearn, matplotlib).
- **Power BI**: For creating an interactive dashboard.

## What I Learned
- Writing SQL queries for trend analysis and complex aggregations.
- Performing time-series analysis and building prediction models in Python.
- Creating interactive dashboards in Power BI to present business insights effectively.
