# Revenue Growth Drivers & Inventory Optimization in Fashion Retail (2015–2024)

| Attribute | Details |
|-----------|---------|
| Industry | Fashion Retail |
| Analysis Period | 2015–2024 |
| Records Analysed | **262,747** |
| Technologies | Python, Pandas, NumPy, Matplotlib, Seaborn |
---

## Project Overview

Revenue tells only part of the story.

Between 2015 and 2024, the company increased its revenue by **44.2%**, yet the annual number of orders remained remarkably stable. Traditional growth indicators suggested success, but the underlying drivers were far less obvious.

Was the business selling more products?

Were customers spending more?

Did pricing strategy change?

Or was something happening within the product portfolio itself?

This project explores those questions by combining sales, product and inventory data into a single business analysis. Rather than examining individual metrics in isolation, it connects pricing strategy, product portfolio evolution, customer behaviour and inventory allocation to explain the commercial drivers behind long-term revenue growth.

The result is a data-driven explanation of how the business achieved sustainable growth and where future commercial opportunities may exist.
---

![Revenue Growth vs Order Volume](assets/visualisations/revenue_growth_despite_stable_order_volume.png)

*Figure 1. Revenue increased by 44.2% despite relatively stable annual order volumes, motivating the investigation into the commercial drivers behind long-term growth.*

## Key Business Insights

| Metric | Result |
|---------|-------:|
| Revenue Growth | **+44.2%** |
| Annual Order Volume | Stable |
| Average Order Value | **+41.9%** |
| Returning Customers | **92.6%** |
| Customers Generating 80% of Revenue | **36%** |

![Average Selling Price vs Units Sold](assets/visualisations/price_growth_vs_sales_volume.png)

*Figure 2. Average selling prices increased steadily while sales volume remained relatively stable, indicating that pricing strategy contributed significantly to revenue growth.*

![Sales Mix by Price Segment](assets/visualisations/sales_mix_by_price_segment.png)

*Figure 3. The product portfolio gradually shifted towards higher-priced segments, increasing the contribution of premium products to overall revenue.*

## Business Questions

The analysis was designed to identify the commercial factors behind long-term revenue growth and evaluate how different areas of the business contributed to overall performance.

### Revenue Growth

- How did product prices evolve between 2015 and 2024?
- Was revenue growth driven by higher prices, increased sales volume or changes in the product portfolio?
- How did the sales mix change across different price segments?
- Did newly launched products contribute to long-term revenue growth?

### Commercial Performance

- How did seasonality influence revenue throughout the year?
- To what extent did promotional discounts contribute to commercial performance?

### Market & Product Performance

- Which markets demonstrated the strongest long-term growth?
- Which product categories and subcategories generated the greatest contribution to revenue growth?

### Customer & Inventory Insights

- How did customer behaviour change over time?
- What role did returning customers play in sustaining business performance?
- Was inventory allocation aligned with commercial performance, or were there signs of overstocking and understocking?

### Business Recommendations

- Which data-driven actions could support future revenue growth and improve inventory efficiency?

## Dataset Overview

The analysis is based on three related datasets representing different aspects of the business. Together, the datasets provide a complete view of sales performance, product characteristics and inventory allocation, enabling business performance to be analysed from multiple perspectives.
| Dataset | Description | Rows | Columns |
|----------|-------------|-----:|--------:|
| **Sales Orders** | Transaction-level sales data containing information about orders, customers, products, pricing, discounts and order dates. | **256,506** | **9** |
| **Products** | Product catalogue including categories, subcategories, launch dates and launch prices. | **2,500** | **5** |
| **Inventory** | Inventory records showing stock availability for individual products. | **3,741** | **4** |

The datasets were linked using common identifiers, allowing sales activity to be analysed alongside product characteristics and inventory levels. This integrated approach made it possible to investigate not only **what** changed over time, but also **why** those changes occurred from both commercial and operational perspectives.

## Project Workflow

The analysis followed a structured business analytics workflow, moving from raw data validation to business interpretation. Each stage built on the previous one, ensuring that conclusions were supported by reliable data and a transparent analytical process.

1. **Data Import**
   - Imported and configured the sales, products and inventory datasets.
   - Prepared the analytical environment.

2. **Data Quality Assessment**
   - Assessed data completeness, consistency and validity.
   - Identified missing values and potential quality issues.

3. **Data Cleaning & Standardisation**
   - Standardised date formats, country names and categorical values.
   - Corrected data types and removed invalid records where necessary.
   - Preserved missing values representing unavailable business information.

4. **Data Preparation**
   - Created analytical features and business metrics.
   - Combined datasets using common identifiers.

5. **Exploratory & Business Analysis**
   - Investigated pricing, product portfolio, customer behaviour, market performance and inventory allocation.

## Key Findings

The analysis revealed that revenue growth was driven primarily by higher transaction values rather than increasing sales volume. Although the number of annual orders remained largely unchanged, revenue increased by **44.2%**, indicating that commercial performance improved through changes in pricing, product portfolio and customer purchasing behaviour.

The most important findings include:

- **Pricing strategy emerged as the primary growth driver.** Higher average selling prices, a gradual shift towards premium products and more expensive product launches consistently increased Average Order Value.

- **Revenue growth was achieved without heavy discounting.** Most transactions were completed with discounts below 20%, suggesting that pricing discipline remained an important part of the commercial strategy.

- **Growth was concentrated rather than evenly distributed.** Some markets and product categories contributed disproportionately to revenue growth, highlighting clear differences in commercial performance.

- **Returning customers became increasingly valuable.** A relatively small group of loyal customers generated a significant share of total revenue, emphasising the importance of customer retention.

- **Inventory allocation created opportunities for optimisation.** Comparing inventory levels with sales performance identified categories where stock distribution could be better aligned with commercial demand.

Overall, the analysis indicates that sustainable revenue growth resulted from pricing strategy, portfolio development and customer loyalty rather than increasing order volumes.

## Business Recommendations

The analysis identified several opportunities to strengthen long-term business performance.

- **Prioritise investment in high-performing categories.** Women's products and Accessories consistently delivered the strongest revenue growth and offer the greatest potential for further expansion.

- **Focus on customer retention.** Returning customers generated most of the revenue, making retention initiatives more valuable than relying solely on new customer acquisition.

- **Align inventory with commercial demand.** Inventory allocation should reflect both sales volume and revenue contribution to improve stock efficiency.

- **Maintain a value-based pricing strategy.** Revenue growth was achieved without relying heavily on discounts, supporting a selective approach to promotions.

- **Review underperforming categories.** The declining performance of the Men's category should be investigated to identify opportunities for improvement.

## Repository Structure

```text
Revenue_Growth_Drivers/
├── assets/
│   └── visualisations/
├── data/
│   ├── inventory.csv
│   ├── products.csv
│   └── sales_orders.csv
├── notebooks/
│   └── Revenue_Growth_Drivers_Inventory_Optimization.ipynb
├── README.md
├── requirements.txt
└── LICENSE
```

## Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualisation | Matplotlib |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Revenue_Growth_Drivers.git
```

2. Install the required dependencies.

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook and run the notebook sequentially.

```bash
jupyter notebook
```

## Future Improvements

Future work could extend the scope of the analysis by:

- incorporating profitability and margin data to complement the revenue analysis,
- investigating the factors behind declining performance in selected product categories,
- introducing customer-level metrics such as Customer Lifetime Value (CLV),
- integrating demand forecasting to support inventory planning and stock optimisation.

## Final Remarks

Building this project allowed me to apply the complete business analytics workflow—from assessing data quality and preparing datasets to identifying business insights and translating them into actionable recommendations.

It reflects how I approach analytical problems: by combining technical analysis with business context to support data-driven decision-making.
---

## Author

**Oliwia Małkus**

Aspiring Data Analyst passionate about business analytics, data visualisation and solving business problems with data.

Feel free to connect with me on LinkedIn or explore my other GitHub projects.
