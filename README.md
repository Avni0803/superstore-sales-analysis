# Superstore Sales & Profitability Analysis

## Project Overview

This project analyses Superstore sales data to understand sales and
profitability across categories, sub-categories, regions and discount
levels.

The main focus of the analysis is to identify strong and weak areas of
the business and understand where sales are not translating into
profit. Particular attention is given to Furniture, where profitability
was significantly lower than the other categories.

## Business Objective

The main objectives of this analysis are to:

- Evaluate overall sales and profitability
- Compare performance across product categories
- Identify loss-making sub-categories
- Analyse the relationship between discounts and profit
- Identify regions with weaker profitability
- Analyse sales and profit trends over time
- Develop data-driven business recommendations

## Dataset

The dataset contains 10,194 transaction records covering:

- 5,111 unique orders
- 804 unique customers
- 1,862 unique products
- 3 product categories
- 3 customer segments
- 4 regions

The dataset contains information about orders, customers, products,
sales, quantities, discounts and profits.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Performance Indicators

| Metric | Value |
|---|---:|
| Total Sales | $2,326,534.35 |
| Total Profit | $292,296.81 |
| Total Quantity | 38,654 |
| Total Orders | 5,111 |
| Total Customers | 804 |
| Profit Margin | 12.56% |
| Average Order Value | $455.20 |

## Analysis Performed

The analysis was carried out in the following areas:

- Data cleaning and validation
- Descriptive statistics
- Overall KPI analysis
- Category and sub-category performance
- Furniture profitability analysis
- Discount and profit analysis
- Correlation analysis
- Regional performance analysis
- Time-series analysis
- Business recommendations

## Key Findings

### Category Performance

Technology was the strongest-performing category, generating
approximately **$146.5K in profit** with a **17.45% profit margin**.

Office Supplies also performed well, with approximately **$126.0K profit** with a **17.22%
profit margin**.

Furniture generated approximately **$754.7K in sales** but only **$19.7K
profit**, resulting in a significantly lower profit margin of **2.61%**.

### Furniture Profitability

The Furniture category's weak profitability was concentrated in
specific sub-categories.

- Tables: -8.53% profit margin
- Bookcases: -3.15% profit margin
- Chairs: 8.11% profit margin
- Furnishings: 14.53% profit margin

Tables and Bookcases were the main loss-making sub-categories, while
Chairs and Furnishings remained profitable.

### Discount Analysis

Discounting was one of the main areas I looked at while investigating
Furniture profitability.

Within Furniture, discount and profit showed a moderate negative
correlation of approximately **-0.48**.

The discount-level analysis also showed that profitability generally
decreased as discounts became higher. Several Furniture groups with
higher discounts recorded negative profit margins.

This suggests that while discounts may help increase sales, excessive
discounting can have a significant impact on the profit generated from
those sales.

### Regional Performance

The West region had the highest overall profit margin at **14.98%**,
while Central had the lowest at **7.92%**.

Furniture in the Central region had a negative profit margin of **-1.70%**
and an average discount of approximately **29.74%**.

This made Central Furniture an important area for further investigation,
as relatively high discounting was accompanied by negative profitability.

### Time-Series Performance

The overall business shows a positive growth trend over the period
analysed.

Sales increased from approximately **$494.0K in 2023** to
**$745.6K in 2026**.

Profit also increased from approximately **$51.7K in 2023** to
**$95.9K in 2026**, while the number of orders increased from
**995 to 1,723**.

Although sales declined slightly in 2024, profit still increased.
From 2025 onwards, both sales and profit increased substantially,
with 2026 recording the highest values for both.

## Business Recommendations

Based on the patterns found in the analysis, I would suggest focusing
on the following areas:

1. **Review high discounts in Furniture**, especially where they are
   resulting in negative profit margins.

2. **Investigate Tables and Bookcases** at the product level to
   identify products that consistently generate losses.

3. **Continue focusing on Technology and Office Supplies**, as both
   categories show stronger profitability.

4. **Investigate Furniture performance in the Central region** to
   understand why relatively high discounts are still accompanied by
   negative profitability.

5. **Look at both sales and profit when evaluating performance**, since
   high sales do not necessarily mean high profitability.

## Overall Conclusion

The analysis shows that the business is growing, with sales, orders and
profit increasing over time.

At the same time, performance varies considerably across categories,
sub-categories and regions. **Furniture, particularly Tables and
Bookcases, stands out as the main area requiring attention.**

The discount analysis also suggests that controlling discounts and
looking more closely at product-level profitability could help improve
profits while maintaining the overall growth of the business.

## Project Structure

```text
Superstore-Sales-Analysis/
│
├── data/
│   └── superstore.xls
│
├── Superstore_Sales_Analysis.ipynb
│
└── README.md
```

## Author

**Avni**

Data Analytics Portfolio Project
