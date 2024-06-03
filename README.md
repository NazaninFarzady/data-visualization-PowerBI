# Data storytelling using PowerBI
This is a data visualization using PowerBI

# Supermarket Sales Analysis with Power BI

## Project Overview
As a data analyst at the supermarket, I analyzed three months of historical data from three branches to uncover insights that drive business decisions. By answering key business questions, I aim to provide insights and recommendations to help sales managers understand product sales and customer attributes, thereby increasing sales and profits. The next page tells the story of total sales by the time of day, helping us understand sales patterns across different times of the day. The following page, "Median Sales by Product Line," displays a graph showing which product lines are above or below the overall median sales, offering insights for pricing strategies on specific products. Another page in the report presents the differences in purchasing behavior between genders and explains how best to present this data to avoid clutter. Lastly, the "Executive Summary" page provides a summary of the key components, information, and insights derived from the data. This notebook presents the findings and visualizations from the Power BI project.

## Data Description
The dataset includes sales records, product details, customer demographics, and transaction times for three branches.

## Key Business Questions 
- What are the sales patterns across different times of the day?
- Which product lines are above or below the overall median sales?
- What are the differences in purchasing behavior between genders?

## Tasks
- Creating dedicated data tables, tables with no missing values, using CALENDER()
- Creating calculated columns
- Creating a bar chart, to show the categorical data and present variables with distinct categories
- Formatting the bar visual by customizing them with different color codes
- Showing the outliers or extreme values
- Creating the clustered bar chart
- Creating an executive summary page for the report
- Showing the distribution and the trend, highest and lowest points by sparkline
- Creating a cover page and page navigation

## Key Insights
### Monthly Sales Trends
- **January**: Accounted for about 36% of the overall total sales.
- **February**: Total sales dropped by about 20%.
- **March**: Sales improved overall.

## Visual Analysis
### Total sales by months
- Which month had the highest total sales, and which had the lowest total sales immediately?

### Total sales by time
- Which time needs improvement in terms of sales?
- What time of the day had the lower sales?
- Why the lower sales were in the morning marginally lower?
  - The supermarket branches open at 10 AM after most working-class people have gone to work, thereby discouraging people who resume work at 8:30 AM from buying at the supermarket. We can recommend that the store opens earlier than 10 AM, at 8 AM, to increase morning sales.
  - Sales in the morning were lower than afternoon and evening across branch locations. Upon looking at the data, we found that the supermarket branches open at 10 AM after most working-class people must have gone to work. This discourages people who resume at 8:30, for example, in the morning, from buying at the supermarket. This means that we are losing some money from people who would like to purchase some things before heading to work. And we communicated this story clearly and recommended that the supermarket open at 8 AM. This means that-- it may mean employing more attendants or having different employees or attendance shifts to adequately serve our customers and accommodate different buying patterns.

### Median sales by product line
- Which of the product lines are above or below the overall median sales in a bid?
- How to help the sales manager with insights on pricing strategies for the product?

### Total sales by product line and gender
- How best to present this data in such a way as to avoid clutter?
- On which product line or category is there a huge difference in the buying patterns for females and males?



## How to View the Report
1. Download the `.pbix` file from this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Explore the interactive dashboards and visualizations.

## Conclusion
This Power BI analysis provides actionable insights to optimize sales strategies and improve profitability. Adjustments to store opening hours, product line focus, and targeted marketing based on gender differences are recommended.

## License
Practicing data visualization and data storytelling using PowerBI through guided projects in Coursera. The instructor of this guided project is Olayinka Imisioluwa Arimoro.
