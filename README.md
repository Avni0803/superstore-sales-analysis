</> **Markdown**

# Superstore Sales & Profitability Analysis

## Project Overview

This project analyses Superstore sales data to identify key drivers of
sales and profitability across product categories, sub-categories,
regions and discount levels.

The analysis focuses on identifying areas of strong performance and
potential profit leakage, with particular attention to the relationship
between discounting and profitability.

## Business Objective

The main objectives of this analysis are to:

- Evaluate overall sales and profitability
- Compare performance across product categories
- Identify loss-making sub-categories
- Analyse the relationship between discounts and profit
- Identify regions with weaker profitability
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

## Key Findings

### Category Performance

Technology was the strongest-performing category, generating
approximately $146.5K in profit with a 17.45% profit margin.

Office Supplies generated approximately $126.0K profit with a 17.22%
profit margin.

Furniture generated approximately $754.7K in sales but only $19.7K
profit, resulting in a significantly lower profit margin of 2.61%.

### Furniture Profitability

The Furniture category's weak profitability was concentrated in
specific sub-categories.

- Tables: -8.53% profit margin
- Bookcases: -3.15% profit margin
- Chairs: 8.11% profit margin
- Furnishings: 14.53% profit margin

### Discount Analysis

Within Furniture, discount and profit showed a moderate negative
correlation of approximately -0.48.

Higher discount levels were associated with substantially lower
profitability.

### Regional Performance

The West region had the highest overall profit margin at 14.98%,
while Central had the lowest at 7.92%.

Furniture in the Central region had a negative profit margin of -1.70%
and an average discount of approximately 29.74%.
