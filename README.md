# Superstore SQL Analysis

Business analysis of the Sample Superstore dataset using SQL (SQLite). The data was loaded into a database and queried to answer key business questions, covering aggregation, filtering, sorting, and computed metrics.

## Questions answered
- Sales and profit by region
- Top-selling product sub-categories
- Which sub-categories are losing money (using HAVING)
- Profit margin by product category (computed in-query)

## Key findings
- West is the strongest region on both sales and profit. Central is the weak spot: high sales but the lowest profit of any region.
- Tables is a top-5 product by revenue but the single biggest loss-maker, losing over 17,000. Selling more of it actively loses money.
- The Furniture category has a profit margin of just 2.5%, versus around 17% for Technology and Office Supplies. High revenue, almost no profit, dragged down by loss-making sub-categories like Tables and Bookcases.

## SQL techniques used
- Aggregation with SUM, COUNT, AVG
- GROUP BY and ORDER BY
- Filtering groups with HAVING
- Computed metrics (profit margin %) inside the query
- LIMIT for top-N results

## Takeaway
High sales does not mean high profit. The analysis pinpoints where revenue is quietly losing money, the kind of insight that drives real pricing and product decisions.
