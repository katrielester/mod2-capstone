# SaaS Sales & Profit Analysis

This project involves an exploratory data analysis (EDA) of a **SaaS sales and profit dataset** to identify high-demand products, understand customer behavior, and optimize pricing and sales strategies. The objective is to uncover valuable insights that can inform business decisions and prioritize investment in high-performing products.

## Project Overview

This project analyzes sales, profit, and customer data from a Software as a Service (SaaS) company to identify key trends and areas for improvement. The analysis focuses on product performance, customer demand, geographic variations, and correlations between sales, profit, discounts, and profit margins. Insights derived from this analysis are aimed at helping the company make informed decisions about product development, marketing, and pricing strategies.

### Key Objectives:
- Identify **top-performing products** based on **sales** and **profit**.
- Analyze **demand** from key customers, segments, and industries.
- Examine **global market trends** and geographic variations in demand.
- Conduct **correlation analysis** to evaluate relationships between **sales**, **profit**, **discounts**, and **profit margins**.

## Project Structure

- **`data/`**: Contains the raw dataset used for analysis.
- **`notebooks/`**: Contains Jupyter Notebooks for performing data analysis and generating visualizations.
- **`outputs/`**: Contains the output of the analysis, such as plots, tables, and reports.
- **`README.md`**: This file, providing an overview of the project.

## Installation

To get started with this project, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/saas-sales-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd saas-sales-analysis
   ```

3. Install required dependencies (use Python 3.7+):
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook for analysis:
   ```bash
   jupyter notebook notebooks/eda.ipynb
   ```

## Analysis Summary

### Key Insights:
1. **Top-Performing Products**:
   - **Alchemy**, **Site Analytics**, and **Data Smasher** are identified as the highest-performing products in both **sales** and **profit**.
   - **Marketing Suite** and **Big Ol Database** have high sales but low profitability, suggesting room for improvement in pricing or operational costs.

2. **Discount Impact**:
   - There is a **strong negative correlation** between **discounts** and **profit margins**, indicating that heavy discounting erodes profitability.

3. **Customer and Industry Trends**:
   - **SMB** customers in the **US**, **Finance**, **Healthcare**, and **Manufacturing** industries show the highest demand for products like **ContactMatcher** and **Support**.
   - **ContactMatcher** is a key driver of customer loyalty and recurring sales.

4. **Geographic Demand**:
   - **US**, **UK**, and **Japan** are the highest-performing regions, with **ContactMatcher** and **Site Analytics** showing strong sales.
   - Countries like **Denmark**, **Qatar**, and **Iceland** exhibit lower performance, suggesting a need for targeted marketing strategies in these areas.

5. **Profitability Insights**:
   - Sales and profit have a moderate positive correlation, meaning that higher sales tend to drive higher profits, but this relationship is not always linear.
   - Profit margins are relatively independent of sales volume, suggesting that the focus should be on increasing margins through cost optimization and high-margin products.

### Key Recommendations:
- **Focus Investment** on high-performing products like **Alchemy** and **Site Analytics** to maximize returns.
- **Reevaluate Discount Strategies** to reduce deep discounts and minimize their impact on profitability.
- **Target Key Customer Segments** (SMB, Finance, Healthcare) and regions (US, UK, Japan) for marketing and sales efforts.
- **Improve Profit Margins** by optimizing pricing strategies and focusing on high-margin products.
