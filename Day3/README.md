# Pandas, Seaborn, and the Stack Overflow Survey

This notebook series uses the Stack Overflow Developer Survey to practice real-world data work. You’ll load the dataset, clean and cast columns, explore with filters and groupby, and build simple visuals.

**Pandas** is the go-to library for tabular data in Python (I/O, selection, missing data, grouping). **Seaborn** sits on Matplotlib and makes common plots—histograms, scatter/line charts, pairplots, jointplots—quick to produce and easy to style.

The data comes from the annual Stack Overflow Developer Survey: [https://survey.stackoverflow.co/](https://survey.stackoverflow.co/)
After downloading and unzipping, you’ll typically use `survey_results_public.csv` (one row per respondent) plus the schema file that maps column codes to their questions.

## Install

Using pip (recommended):

```bash
python -m pip install --upgrade pandas seaborn matplotlib
```

Using conda:

```bash
conda install pandas seaborn matplotlib
```

Quick check:

```python
import pandas as pd, seaborn as sns, matplotlib
print(pd.__version__, sns.__version__, matplotlib.__version__)
```

Then: load the CSV, inspect with `df.info()` / `df.head()`, clean types and missing values, aggregate (e.g., salary by country, language usage by age), and visualize with Seaborn.

