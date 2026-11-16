# Data and reproducibility

The notebook is a class research artifact using the public Chicago Traffic Crashes, Vehicles, and People datasets. The full raw CSV exports were not packaged with this repo.

## To reproduce

1. Download the three corresponding Chicago Data Portal datasets, choosing releases/schema compatible with the original notebook.
2. Rename to `Crashes.csv`, `Vehicles.csv`, `People.csv` or adjust the notebook's file-loading cells. Some cells also mention `Crashes_new.csv`.
3. Create a virtual environment and install `requirements.txt`. If using local Jupyter rather than Google Colab, disable/replace any `google.colab`-specific setup.
4. Execute sequentially and compare the reported descriptive totals/model summaries; changes in underlying city data may change results.

**Caveats:** model coefficients describe conditional associations, not causal effects. Re-running this notebook was not possible without the matching raw data exports. The requirements file lists packages inferred from imports; exact version compatibility is not independently validated.
