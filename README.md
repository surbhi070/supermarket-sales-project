📊 KPIs Defined
- Total Revenue = SUM(Sales)
- Total Profit = SUM(Profit)
- Profit Margin = Profit / Sales
- Average Order Value = Sales / Number of Orders
- Sales by Payment Method


✅ MYSQL QUERIES
-Total Revenue
SELECT SUM(sales) FROM orders;

-Profit Margin
SELECT SUM(profit)/SUM(sales)*100 FROM orders;

-Sales by Branch
SELECT branch, SUM(sales)
FROM orders
GROUP BY branch;


💡 Key Insights
- Branch A generates highest revenue but lower profit margin
- Cash payments dominate overall transactions
- Certain product categories show consistent high demand.


✅ “Business Recommendations”
- Improve pricing strategy in low-margin branches
- Promote digital payments for better tracking
- Focus inventory on high-demand product lines.
