E-commerce Data Analysis

Exploratory and metric-driven analysis of an e-commerce dataset (2020–2022).

The goal was to understand how revenue changes over time and what drives those changes: order volume, basket size, or pricing.

This repository focuses on a simple analyst workflow:
Clean → aggregate → visualize → interpret.

Dataset

Downloaded the Online-eCommerce dataset from Kaggle.

Each row represents a product within an order.
From item-level data, order-level and monthly metrics were built.

Focus

- Revenue over time
- Order volume
- Average order value (AOV)

The analysis looks at how these interact and which metric explains revenue volatility.

Key observations

- Revenue spikes appear consistently between January and May.
- Order volume closely mirrors revenue changes.
- Items per order remain roughly constant.
- AOV is relatively stable compared to revenue swings.

This suggests revenue changes are primarily driven by order volume rather than basket size.

Structure

ecommerce-data-analytics/
  data/
    raw/
    processed/
  notebooks/
  charts/
  src/

notebooks/ → exploration, cleaning, analysis, insights

data/processed/ → cleaned order-level & monthly metrics

charts/ → final visualizations

src/ → reserved for reusable metric helpers

The project is intentionally simple and notebook-driven.

Tools

- Python
- Pandas
- Matplotlib
- NumPy
- VS Code (Jupyter-style workflow)
- AI assistance for syntax and plotting

Notes

This project sits alongside my full-stack e-commerce app and reflects how I approach data from a product/engineering perspective:
Start from events → build metrics → visualize → interpret.

Author
Name: Dániel Cserpák
Portfolio: https://daniel-cserpak-portfolio.netlify.app/
LinkedIn: https://www.linkedin.com/in/d%C3%A1niel-cserp%C3%A1k-109057283/