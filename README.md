# Defence Budget Analysis Project

## Overview
This project performs comprehensive data analysis on India's Defence and R&D budget trends using data from [data.gov.in](https://data.gov.in/). The analysis visualizes budget allocations over time and explores correlations between total defence spending and R&D investments.

## Dataset Source
**Dataset:** Department of Defence R&D Budget Over the Years  
**Source:** [data.gov.in](https://data.gov.in/)  
**File:** `Departofdefence_RandD_budgetover_1.csv`

The dataset contains historical data from 1961-62 to 2013-14 (BE), including:
- Annual Defence Budget (in Crores ₹)
- Defence R&D Budget (in Crores ₹)
- Percentage of DRDO Budget to Defence Outlay

## Project Structure
defence-budget-analysis/
│
├── Defence_budget.ipynb                    # Main Jupyter notebook with analysis
├── Departofdefence_RandD_budgetover_1.csv  # Dataset file
├── README.md                               # Project documentation
│
└── Visualization/                                  
├── 1_line_plot.png                    # Line plot showing budget trends
├── 2_bar_plot.png                     # Bar plot comparing budgets year-wise
├── 3_scatter_plot.png                 # Scatter plot showing correlation
└── 4_percentage_trend.png             # R&D percentage trend over time

## Visualizations Created

### 1. Line Plot - Defence Budget Trends Over Time
- **File:** `1_line_plot.png`
- **Description:** Dual-line plot showing the growth trajectory of both Annual Defence Budget and Defence R&D Budget from 1961 to 2013
- **Key Insight:** Both budgets show exponential growth, with the total defence budget increasing from ₹313 Cr (1961-62) to ₹203,672.1 Cr (2013-14)

### 2. Bar Plot - Year-wise Budget Comparison
- **File:** `2_bar_plot.png`
- **Description:** Side-by-side bar chart comparing Annual Defence Budget and R&D Budget for each year
- **Key Insight:** Visual comparison reveals the consistent gap between total defence spending and R&D allocation across all years

### 3. Scatter Plot - Correlation Analysis
- **File:** `3_scatter_plot.png`
- **Description:** Scatter plot with trend line showing the relationship between Total Defence Budget and R&D Budget
- **Key Insight:** Strong positive correlation (≈0.99) indicates that R&D budget grows proportionally with total defence budget

### 4. Line Plot - R&D Percentage Trend
- **File:** `4_percentage_trend.png`
- **Description:** Shows DRDO budget as a percentage of total defence outlay over time, with average line and above/below average shading
- **Key Insight:** R&D allocation as percentage peaked during 2007-09 period (~6.7%) and has slightly declined since then

## Technologies Used
- **Python 3.12**
- **Libraries:**
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computations
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical data visualization

## Key Findings

1. **Average Defence Budget Change:** ₹12,033 Crores/year
2. **Average R&D Budget Change:** ₹627 Crores/year
3. **Average Defence Growth Rate:** 22.85% per year
4. **Average R&D Growth Rate:** 25.12% per year
5. **R&D as % of Defence Budget (Average):** 4.48%
6. **Correlation (Defence vs R&D):** 0.9954 (Strong Positive)

## Observations

Exponential Growth: Both defence and R&D budgets show consistent exponential growth over the 52-year period
R&D Investment: R&D budget as a percentage of total defence spending has fluctuated between 1% to 6.7%
Recent Trends: R&D percentage has stabilized around 5-6% in recent years after peaking in 2006-2010
Strong Correlation: The near-perfect correlation (0.9954) suggests R&D budget planning is closely tied to overall defence budget
