# Data Analysis Notebooks (Python)

Jupyter notebooks from my Statistics for Data Science course (MATH 37198) at Sheridan College. Each notebook takes a real dataset or a statistics problem, analyzes it with Python, and explains the results.

| Notebook | Topic | Techniques |
|---|---|---|
| `nba_player_stats.ipynb` | NBA 2024-25 player statistics | Loading CSV data with pandas, descriptive statistics, labelled histograms |
| `ign_game_reviews.ipynb` | IGN video-game reviews | Filtering and grouping with pandas, probability from real data, cleaning inconsistent labels (e.g. platform names) |
| `probability_distributions.ipynb` | Probability distributions | Normal-distribution probabilities with `norm.cdf` / `norm.sf` and shaded plots, Poisson probabilities, sampling histograms |
| `mobile_speed_tests.ipynb` | Android and iPhone speed tests, plus two hypothesis-testing problems | 95% t-interval for mean download speed, 95% z-intervals for country proportions, one-tailed t-tests using both the p-value and critical-value methods |

The notebooks also include debugging notes where I introduce, explain and fix common errors (wrong column names, two-tailed vs. one-tailed p-values, flipped decision rules).

## Data and plots
Plot images were removed from the saved notebooks to keep the repository small. Run the notebooks to regenerate every chart.

The datasets were provided by the course and are **not included** in this repository. Put your copies in a `data/` folder next to the notebooks; each notebook reads its CSV from there.

## Running

```bash
pip install pandas numpy scipy matplotlib jupyter
jupyter notebook
```

## Tech
Python · pandas · NumPy · SciPy · Matplotlib · Jupyter
