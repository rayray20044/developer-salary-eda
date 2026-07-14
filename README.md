# Developer Salary EDA

An exploratory data analysis of the **2025 Stack Overflow Developer Survey**
(49,191 responses) — cleaning messy real-world survey data to find out what
actually predicts a developer's salary.

**[View the live site →](https://YOUR_USERNAME.github.io/developer-salary-eda/)**

## What this project covers

- Loading and inspecting a large, messy real-world dataset (172 columns)
- Investigating *why* salary data was missing (not just dropping it blindly)
- Detecting and removing outliers (salaries ranging from $1 to $33.5M/year)
- Visualizing the salary distribution
- Testing whether **years of experience** predicts salary (weak: r ≈ 0.32)
- Testing whether **country** predicts salary (strong: ~5× gap between
  highest- and lowest-paying countries)

## Key finding

Country is a far stronger predictor of developer salary than years of
experience. Median salary ranges from ~$150,000 (United States) down to
~$30,000 (India), while experience alone only weakly correlates with pay.

## Tools used

Python, pandas, matplotlib, Jupyter Notebook

## Files

- `index.html` — the write-up, viewable as a website
- `images/` — charts referenced in the write-up
- `salary_eda.ipynb` — the full analysis notebook
