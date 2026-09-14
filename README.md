# superstore-sales-analysis

Power BI dashboard analyzing Superstore sales, profit, and customer profitability trends.


## Dashboard Overview

![Dashboard Overview](Screenshot%202026-09-14%20204333.png)

Built in Power BI using Power Query for data cleaning and DAX for custom measures. Includes KPI cards, a sales trend line, category breakdown, regional map, and a top-customer table — all connected with interactive slicers (Year, Region, Category).

**Key metrics:**
- Total Sales: $2.30M
- Total Profit: $286.4K
- Total Quantity: 38K units
- Return Rate: 5.91%

## Key Insight: The "Sean Miller Problem"

## Key Insight: The "Sean Miller Problem"

![Sean Miller Filtered View](Screenshot%202026-09-14%20204325.png)
Sean Miller is the company's top customer by sales ($25,043), but he's actually **losing the business money** (-$1,980.74 in profit). Two compounding factors explain this:

- His average discount is **24.67%**, well above what the margin on Technology/Accessories products can absorb.
- His personal return rate is **20%**, more than 3x the company average of 5.91%.

This suggests high discounts combined with elevated returns can turn a top-line "best customer" into a bottom-line loss — worth flagging for account review.

**Recommendation:** Cap or tier discount rates by product sub-category profitability, and flag customers with return rates significantly above the 5.91% baseline for account review.

## Tools Used
- Power BI Desktop
- Power Query (data cleaning, custom columns)
- DAX (Total Sales, Total Profit, Profit Margin, Avg Order Value, Return Rate)
