# Grocery-Product-Category-Analysis
This project analyzes grocery sales performance across product categories using transactional data. It focuses on revenue contribution, quantity sold, and average price per unit, helping identify which product types drive the most value.

| Category     | Revenue ($)   | Units Sold | Avg. Price ($) |
|--------------|----------------|-------------|----------------|
| Confections  | 42.3M         | 816,661     | 51.82          |
| Poultry      | 33.6M         | 678,994     | 49.53          |
| Snails       | 28.3M         | 532,979     | 53.21          |
| Seafood      | 24.9M         | 515,094     | 48.56          |
| ...          | ...           | ...         | ...            |
| **Total**    | $329.9M       | 6.5M        | 50.81          |

## Live Dashboard (Tableau Public)
  [Click here to view the interactive dashboard](https://public.tableau.com/views/GrocerySalesDataAnalysis_17529014455190/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Key Insights

- **Confections** drove the highest revenue, largely due to volume.
- **Grain** had the highest average price but comparatively low sales volume.
- **Shellfish** and **Snails** had niche appeal, showing strong price points with moderate volume.
- High-performing categories showed a balance of **moderate price and high demand**.

## Dataset Source

- Original: [Kaggle Grocery Sales Dataset](https://www.kaggle.com/datasets/andrexibiza/grocery-sales-dataset)
- Aggregated from:
  - `sales.csv` (transactional data)
  - `products.csv` (price, product ID)
  - `categories.csv` (category name)
- Final cleaning done using Excel and Power Query.

## Visuals

- Bar chart: Total revenue per product category

## Tools Used
- Microsoft Excel (Power Query, PivotTables, Charts)
- Visualizations created in Excel
