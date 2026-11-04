# Data Analysis Notebooks (Python)

Jupyter notebooks from MATH 37198, Statistics for Data Science, at Sheridan College. Each notebook takes a real dataset or a statistics problem, analyzes it with Python, and explains the results.

| Notebook | Topic | Techniques |
|---|---|---|
| `Assignment1.ipynb` | NBA 2024-25 player statistics | Loading CSV data with pandas, descriptive statistics, labelled histograms |
| `Assignment2.ipynb` | IGN video-game reviews | Filtering and grouping with pandas, probability from real data, cleaning inconsistent labels (e.g. platform names) |
| `Assignment3.ipynb` | Probability distributions | Normal-distribution probabilities with `norm.cdf` / `norm.sf` and shaded plots, Poisson probabilities, sampling histograms |
| `assignment4.ipynb` | Android and iPhone speed tests, plus two hypothesis-testing problems | 95% t-interval for mean download speed, 95% z-intervals for country proportions, one-tailed t-tests using both the p-value and critical-value methods |

Each assignment also includes a short "mistakes" section, required by the course, where I introduce, explain and fix common errors (wrong column names, two-tailed vs. one-tailed p-values, flipped decision rules).

## Data and plots
Plot images were removed from the saved notebooks to keep the repository small. Run the notebooks to regenerate every chart.

The datasets were provided by the course and are **not included** in this repository. Update the `pd.read_csv(...)` paths at the top of each notebook to point to your own copies.

## Running

```bash
pip install pandas numpy scipy matplotlib jupyter
jupyter notebook
```

## Tech
Python · pandas · NumPy · SciPy · Matplotlib · Jupyter
