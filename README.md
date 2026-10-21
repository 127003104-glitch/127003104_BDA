# 127003104_BDA# BDA Assignment – Weekly Business Review

**Student Name:** Jayavignesh J  
**Roll Number:** 21  
**Registration Number:** 127003104  
**Subject:** Big Data Analytics (BDA)

## 1. Introduction

This project presents a Weekly Business Review of the Brazilian Olist e-commerce dataset. The objective is to analyze sales performance, customer purchasing behavior, delivery delays, customer reviews, and product category performance using data analytics.

The dataset contains approximately 100,000 marketplace orders placed between late 2016 and mid-2018.

## 2. Tools and Technologies

- PostgreSQL
- SQL
- Data Analysis
- Data Visualization
- Brazilian Olist E-commerce Dataset

## 3. Data Quality Checks

Data quality checks were performed using SQL in PostgreSQL.

The checks included:
- Duplicate order IDs
- Null order IDs
- Delivery timestamps before purchase
- Review scores outside the valid range
- Missing customer records
- Payment amount mismatches

Most checks passed successfully. Payment amount mismatches were retained as warnings for further consideration.

## 4. Key Metrics

- **Total Sales (GMV):** R$ 13.22 million
- **Repeat Purchase Rate:** 3.04%
- **On-Time Delivery Rate:** 92.20%
- **Average Days Late:** +11.8 days
- **Average Review Score:** 4.09 out of 5

## 5. Analysis Performed

### Monthly Sales Trend
Analyzed monthly sales and month-over-month growth from September 2016 to September 2018. Sales peaked at approximately R$ 992.8k in May 2018.

### Delivery Delays and Customer Reviews
Analyzed the relationship between delivery delays and customer review scores. Late deliveries were more common among 1-star reviews.

### Repeat Customer Analysis
Analyzed repeat purchases and found that only 3.04% of eligible customers made another purchase.

### Rolling 7-Day Order Trend
Examined daily order volumes and the 7-day rolling average to understand marketplace growth and order patterns.

### Top Product Categories and States
Identified leading product categories and analyzed sales performance across Brazilian states.

## 6. Key Findings

- Total marketplace sales reached approximately R$ 13.22 million.
- Only 3.04% of eligible customers made a repeat purchase.
- The on-time delivery rate was 92.20%.
- The average customer review score was 4.09 out of 5.
- Health and Beauty, Watches and Gifts, and Bed, Bath and Table were among the highest-earning product categories.
- Delivery delays were associated with a higher proportion of low customer ratings.

## 7. Recommendations

1. Provide more realistic delivery estimates based on shipping distance.
2. Encourage sellers to hand over orders to couriers within 48 hours.
3. Send follow-up discounts to encourage repeat purchases.
4. Monitor delivery performance and customer satisfaction regularly.

## 8. Weekly Monitoring Targets

| Metric | Current Value | Target |
|---|---:|---:|
| Total Monthly Sales | R$ 848k/month | Above R$ 1.0M/month |
| Repeat Purchase Rate | 3.04% | Above 6.00% |
| On-Time Delivery Rate | 92.20% | Above 96.00% |
| Average Days Late | +11.8 days | Below 3.0 days |
| Average Review Rating | 4.09/5.0 | Above 4.30/5.0 |

## 9. Limitations

- The dataset does not separate seller packing time from courier transit time.
- Marketing expenditure and customer acquisition costs are not available.
- Product returns and warranty complaints are not recorded.
- Website traffic and shopping cart abandonment data are unavailable.

## 10. Conclusion

This project demonstrates how SQL-based data analysis can help identify business trends and operational challenges in an e-commerce marketplace. The findings highlight opportunities to improve customer retention, delivery performance, and customer satisfaction through data-driven decisions.

## Project Repository

GitHub: https://github.com/127003104-glitch/127003104_BDA
