#Amazon Dashboard Project

1. Short Description/purpose
This repository hosts a Power BI dashboard designed to analyze a dataset of 1351 Amazon products. The dashboard provides actionable insights into product performance, discount impacts, profitability, and customer feedback, serving as a tool for e-commerce decision-making with interactive visuals and a custom theme.
2. Tech Stack

Power BI Desktop: For building and visualizing the dashboard.
DAX: For creating custom measures (e.g., Avg Profit Margin, Overall Sentiment %).
Power Query: For data transformation and calculated columns (e.g., Sentiment Score Column).

3. Dataset

Source: Pre-processed Amazon product dataset embedded in the .pbix file.
Details: Includes 1351 products with fields like actual_price_clean, discounted_price_clean, rating_clean, review_title, review_content, and more.
Notes: Update data sources in Power Query if using a different dataset; ensure column names match.

4. Features/Highlights

Pages:

Main Page: Navigation hub with buttons for Summary, Detailed Analysis, and Customer Feedback.
Summary: KPIs (e.g., Average Price, Profit Margin) and category insights.
Detailed Analysis: Price comparisons, rating vs. price scatter plots, profit trends, and product table.
Customer Feedback: Word Cloud, Stacked Bar for sentiment, Gauge for overall sentiment, and review table.
