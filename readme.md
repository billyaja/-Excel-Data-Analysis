# Hardware Sales Analysis at Atliq Technologies

## Introduction
This project analyzes hardware sales data from Atliq Technologies to identify key trends and insights. The analysis was performed using SQL and the results were presented here in a way that highlights trends in sales, popular products, and new products that were introduced in 2021.

## Business Questions
This project aims to answer the following business questions:
*   What are the top 10 products based on the percentage increase in their net sales from 2020 to 2021?
*   Which products are ranked in the top 5 and bottom 5 in terms of quantity sold?
*   What are the top 5 countries in terms of net sales in 2021?

## Data Source
The data was provided by Atliq Technologies for practice purposes.

## Methodology
![image](Data%20Modelling.png)

- This analysis was conducted using **Microsoft Excel**, with a focus on extracting actionable business insights from a hardware sales dataset provided by Atliq Technologies. The process began with **ETL using Power Query**, where data from fact and dimensional tables was extracted, transformed, and loaded. The data was then cleaned and modeled to accommodate around 800k rows, incorporating a date dimension to facilitate time-based reporting.

![image](Creating%20Metrics%20using%20DAX.png)

- **DAX calculations** were used to generate essential business metrics, including net sales and year-on-year growth, which are the North Star metrics for this analysis. These calculations were performed to understand the financial performance of hardware sales across different products and regions. Reporting was done primarily through **pivot tables**, which allowed for easy exploration of these metrics. I used a structured approach for my **Exploratory Data Analysis (EDA)**. This involved identifying the question type, breaking the question down into smaller more specific questions, and then using Excel tools to answer these questions. The goal was always to prioritize clarity and ease of understanding.

## Key Metrics
The main metrics used were:
*   Net sales
*   Growth percentage (year-over-year)
*   Quantity sold

## Findings/Insights
### Top 10 Products by Sales Growth 
![image](Top%2010%20Products-Category.jpeg)

- **Dominant Category:** The top products experiencing the highest growth in sales from 2020 to 2021 are mainly from the battery category (AQ Mx NB, AQ Lion x3, AQ Lion x2, and AQ Lion x1), suggesting a significant market demand for batteries.

*  **Top Performers**:

    *   **AQ Mx NB** (Battery Category):  Achieved an outstanding 5623.5% growth in sales. This exceptional growth suggests strong consumer interest in this product line.
    *  **AQ Smash 2** (Gaming Laptop): Showed a 2489.2% growth in sales, indicating a high demand for gaming products.
    *   **Other Battery Products:** AQ Lion x3, AQ Lion x2, and AQ Lion x1 also experienced impressive growth rates of around 1600%, reinforcing the demand for products in the battery category.

### Top and Bottom 5 Category Products by Quantity Sold
![pdf](Top%20bottom%205%20categories.jpeg)

This analysis identifies the top and bottom 5 product categories based on the total quantity of items sold. This information is crucial for understanding product performance and optimizing inventory and resource allocation.



**Key Findings:**

*   **Top Performing Categories:**
    *   The **keyboard and mouse categories** are the top performers in terms of total quantity sold. This indicates a strong, consistent demand for these essential peripherals.
*   **Low Performing Categories:**
    *   The **Batteries, Gaming Laptop, Personal Desktop** are the lowest performing categories. This suggests these products may not be resonating with customers, are overstocked, or could benefit from a marketing refresh.

### Top 5 Countries by Sales in 2021
*   **India:** India had the highest sales revenue in 2021, with a total of 161.3 million USD, highlighting its significance as a key market.
*   **Other Top Countries:** The USA, South Korea, Canada, and the United Kingdom also had substantial sales revenues, indicating the importance of these markets.


## Recommendations
*   **Trend Analysis:** Examine sales trends over time and explore the factors contributing to each market’s performance.
*   **Invest in Batteries:** Given the high growth rates across multiple battery products, Atliq should consider further investment in this category. This includes optimizing inventory, marketing, and potentially expanding the product line.
*   **Optimize Keyboard and Mouse Inventory:** Given the high demand, Atliq should ensure sufficient inventory and potentially explore expanding its product line in these categories.
*   **Investigate Low Performing Categories:** It would be beneficial to analyze the reasons for the low sales in the laptop and desktop categories. This could involve understanding if a change in product strategy is needed.
*  **Resource Allocation:**
    -   Consider reallocating resources to optimize inventory, marketing, and pricing strategies for these high and low-performing categories.
    - Given the significant sales from the top 5 countries, ensure resources are appropriately allocated to support these key markets and potentially explore growth opportunities.
*  **Further Analysis**: 
    - Investigate the reasons for the high demand in the keyboard and mouse categories to leverage this demand.
    - It would be beneficial to further analyze the reasons behind India's high sales. This could involve examining product-specific sales and understanding the effectiveness of sales and marketing strategies.

## Tools Used
*   Excel



