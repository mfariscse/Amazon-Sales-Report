# Amazon Sales Dashboard

## 1. Project Title / Headline
❄️ Bolt Analytics: Amazon Product Insights Dashboard  
A dynamic, interactive data visualization tool built with Power BI to explore a dataset of 1351 Amazon products—focusing on performance metrics, discount impacts, profitability, and customer feedback.

## 2. Short Description / Purpose
The Bolt Analytics Dashboard is a visually engaging and analytical Power BI report designed to help users analyze Amazon product data comprehensively. This tool is intended for e-commerce analysts, business strategists, and marketers who need to understand trends in pricing, profitability, and customer sentiment to optimize product strategies and sales.

## 3. Tech Stack
The dashboard was built using the following tools and technologies:
- 📊 **Power BI Desktop** – Main data visualization platform used for report creation.
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing the data.
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic visuals, and conditional logic (e.g., Avg Profit Margin, Overall Sentiment %).
- 📝 **Data Modeling** – Relationships established among product, category, and review data for cross-filtering.
- 📁 **File Format** – `.pbix` for development.

## 4. Data Source
- **Source**: Pre-processed Amazon product dataset embedded in the `.pbix` file.
- **Details**: Includes 1351 products with fields such as `actual_price_clean`, `discounted_price_clean`, `rating_clean`, `review_title`, `review_content`, and custom columns like `Sentiment Score Column`.
- **Notes**: Data is anonymized; update sources in Power Query if using a different dataset, ensuring column names align.

## 5. Features / Highlights
- **Business Problem**  
The e-commerce industry faces challenges in quickly assessing product performance, discount effectiveness, and customer satisfaction across thousands of listings. Key questions like "Which products are most profitable?" or "How do discounts affect reviews?" are hard to answer without integrated analysis.

- **Goal of the Dashboard**  
To deliver an interactive visual tool that:  
- Enables users to explore Amazon product data in detail.  
- Supports decisions such as pricing adjustments, discount strategies, and inventory focus.  
- Uncovers trends in profitability, customer sentiment, and category performance.

- **Walkthrough of Key Visuals**  
  - **Key KPIs (Summary Page)**  
    - Total Products: 1351  
    - Average Price: ₹5,690  
    - Average Discount: 46.69%  
    - Average Profit Margin: 17.74%  
    - Average Rating: 4.1  
  - **Category Filter Panel (All Pages)**  
    An interactive slicer allows users to filter all visuals by category (e.g., Computers&Accessories).  
  - **Products by Category (Bar Chart, Summary)**  
    Bar chart shows product counts per category (e.g., 300+ for Computers&Accessories).  
  - **Rating vs Price (Scatter Plot, Detailed Analysis)**  
    Displays rating vs. price with bubble size for popularity, colored by category.  
  - **Profit Margin Overlay (Line Chart, Detailed Analysis)**  
    Overlays profit margin % with discounted and actual prices by sub-category.  
  - **Sentiment by Category (Stacked Bar Chart, Customer Feedback)**  
    Stacked bars show positive, negative, and neutral sentiment distribution.  
  - **Overall Sentiment % (Gauge, Customer Feedback)**  
    Gauge visualizes overall sentiment as a percentage.  
  - **Review Table (Customer Feedback)**  
    Detailed table with review content, sentiment scores, and product links.

- **Business Impact & Insights**  
  - **Pricing Optimization**: Identify high-profit products to adjust pricing strategies.  
  - **Discount Management**: Analyze discount impact on reviews and revenue loss.  
  - **Customer Focus**: Target improvements based on sentiment trends (e.g., low-rated items).  
  - **Inventory Decisions**: Highlight popular categories for stock prioritization.
