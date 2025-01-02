# Movie Data Analysis for SussexBudgetProductions

## Overview
This project analyzes IMDb movie data to identify the top directors who can maximize profit for SussexBudgetProductions' next movie, with a target budget of **£1.5 million**. By performing exploratory data analysis (EDA) and hypothesis testing, we identified actionable insights to enhance profitability.

---

## Steps and Insights

### 1. **Data Cleaning**
- Removed irrelevant columns and handled null values in critical fields (`director_name`, `gross`, `budget`).
- Converted budget and gross values to million pounds for better readability.
- Created a `profit` column to calculate the profit for each movie.

---

### 2. **Exploratory Data Analysis (EDA)**
- Focused on English-language movies released after 1990 with a budget ≤ **£1.5 million**.
- Grouped movies by directors to calculate their average IMDb score, budget, gross, and profit.
- Selected **97 directors** whose movies generated profits and ranked them by profitability.

---

### 3. **Top Directors Analysis**
- Filtered the top 20 directors based on profitability.
- Visualized the profits of these directors using a bar chart.
- Highlighted the top 5 directors: **Daniel Myrick, Oren Peli, James Wan, William Brent Bell, Jared Hess**.

---

### 4. **Hypothesis Testing**
- **Hypothesis:** Movies directed by the top 5 directors with a budget ≤ **£1.5 million** earn an average profit of **> £30 million**.
- **Null Hypothesis (H₀):** Average profit ≤ **£30 million**.
- Performed a **t-test**:
  - **Result:** p-value < 0.05, indicating statistical significance.
  - **Conclusion:** Reject the null hypothesis. Movies directed by the top 5 directors are likely to generate an average profit of **> £30 million**.

---

## Summary and Recommendations
Based on the analysis:
- Movies directed by **Daniel Myrick, Oren Peli, James Wan, William Brent Bell, or Jared Hess** are highly profitable.
- For the next movie, hiring one of these directors is likely to yield an average profit exceeding **£30 million**, ensuring significant returns within the target budget of **£1.5 million**.

---

## Visualizations
- Bar chart showing the profits of the top 20 directors.
- Statistical summaries and hypothesis testing results validating the recommendations.

This analysis provides a clear, data-driven strategy to maximize profitability for SussexBudgetProductions' next movie.
