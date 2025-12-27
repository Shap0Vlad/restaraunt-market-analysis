# restaurant-market-analysis

Exploratory data analysis of U.S. restaurant chains (Top 250, Independence 100, Future50)

## Project Overview
This project analyzes growth patterns of restaurant chains across different segments
to understand what drives revenue expansion, scalability, and long-term performance.

The analysis focuses on three strategic perspectives:
- Top-performing large chains
- Independent operators
- Fast-growing emerging brands

## Business Questions
The project aims to answer the following high-level business questions:
- What factors have the strongest relationship with revenue growth?
- Does network expansion translate into sales growth?
- How do franchised and non-franchised models differ in performance?
- Are high-performing units more likely to sustain growth?

## Data
The analysis is based on three datasets:
- `Top250.csv` — large, established restaurant chains
- `Independence100.csv` — independent operators
- `Future50.csv` — fast-growing emerging brands

The datasets originate from a publicly available Kaggle.

Source:
-
https://www.kaggle.com/datasets/michau96/restaurant-business-rankings-2020

All datasets are stored in the `data/` directory and are used for educational and analytical purposes.

## Methodology
The analysis includes:
- Exploratory data analysis (EDA)
- Correlation analysis
- Segment comparison
- Visualization of key relationships

## Key Outcome
The goal of this project is not prediction, but **business interpretation**:
identifying strategic levers that influence growth and understanding their limitations.

## Tools
- Python
- Pandas
- Numpy
- Matplotlib/Seaborn

## Key Business Insights

1. Revenue growth is positively associated with network expansion,
   but the relationship weakens as brands scale.

2. Segments focused on operational efficiency often outperform
   aggressive expansion strategies in terms of sales per unit.

3. Larger networks tend to experience diminishing returns per unit,
   indicating rising complexity and coordination costs.

4. Franchised models demonstrate more consistent average growth
   compared to non-franchised operators.

5. High-performing units do not necessarily scale faster,
   suggesting that local success is not always replicable.
