# Customer Lifetime Value & Sales Metrics Analysis

This project demonstrates practical SQL skills by calculating **customer lifetime value (LTV)** and key sales metrics from sample order and product data. It showcases how to aggregate, analyze, and categorize customer behavior in a real-world business analytics workflow.

## Key Features

- **Revenue Calculations:** Compute total revenue per order, product, and customer using `quantity × unit_price`.  
- **Customer Metrics:** Calculate purchase frequency and average order size.  
- **Lifetime Value (LTV):** Derived as `purchase_frequency × avg_order_size` to quantify customer value over time.  
- **Tier Assignment:** Assign customers to Platinum, Gold, Silver, or Bronze tiers using `CASE/WHEN`.  
- **Multi-Table Joins:** Combine order, product, and customer tables for comprehensive insights.  
- **CTEs for Readability:** Use Common Table Expressions to structure complex queries cleanly.

## Skills Demonstrated

- SQL SELECT statements, JOINs, and aggregations (`SUM`, `AVG`, `COUNT`)  
- Conditional logic with `CASE/WHEN`  
- Data aggregation and grouping with `GROUP BY`  
- Using CTEs for organized, readable queries  
- Translating business requirements into actionable insights

## Purpose & Use Case

This project models a typical business analytics workflow, providing insights into **customer behavior**, **sales trends**, and **revenue distribution**. It is adaptable for **Oracle SQL, MySQL, PostgreSQL**, or other relational databases.

### Potential Extensions

- Tier-level revenue summaries and dashboards  
- Temporal analyses (monthly, quarterly trends)  
- Visualization and reporting for stakeholders  

## Example Output

| customer_id | total_revenue | tier     |  
|-------------|---------------|----------|  
| 101         | 12,500        | Platinum |  
| 102         | 6,800         | Gold     |  
| 103         | 2,400         | Silver   |  
| 104         | 500           | Bronze   |  

This example shows how customers are categorized based on LTV and demonstrates revenue calculations from order and product data.

---

