# Recession-Analysis

# Visualising UK Recessions Using Monthly GDP Data

This project explores UK recessions using monthly GDP data.  
We:

- Load monthly GDP data from a CSV file.
- Visualise GDP growth over time with an interactive heatmap.
- Aggregate to quarterly growth.
- Automatically detect recession periods.
- Plot the **duration** and **severity** of each recession.

---

## 1. Dataset

The notebook expects a file called **`UK_monthly_gdp.csv`** in the same directory.

A typical structure could look like:

| Date       | GDP Growth |
|-----------|------------|
| 1997-01-01| 0.3        |
| 1997-02-01| 0.4        |
| ...       | ...        |

> If your column names differ, just tweak the code where indicated.

---

## 2. Requirements

Install dependencies with:

```bash
pip install pandas plotly
