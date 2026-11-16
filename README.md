# Chicago Traffic Crash Severity Analysis

Graduate statistical analysis of Chicago traffic crashes, joining crash-, vehicle-, and person-level public datasets to explore associations with injury severity.

## Approach

The original Jupyter notebook includes exploratory analysis, data preparation, person-level logistic regression, odds ratios and confidence intervals, plus robustness/sensitivity checks. Reported effects describe **associations, not causal impacts**.

## Data and reproducibility

The analysis references three Chicago Data Portal exports (typically named `Crashes.csv`, `Vehicles.csv`, and `People.csv`). The complete raw CSV exports are **not included** because of their size. Download the matching public datasets, adjust file paths in the notebook and inspect source schema changes before running.

Main artifact: `chicago_crash_analysis.ipynb`. No independently verified SQL pipeline, deployed model, or dashboard is claimed.

## Limitations

Records may have missing fields, multiple related entities per incident, and nonrandom measurement/reporting. Logistic-model estimates must be interpreted in context of the coded reference categories and dataset coverage.
