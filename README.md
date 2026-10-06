# Practical 2: Plotting, visualisation and multiple regression

Practical materials for "Data Science for Geographers".

- `Practical_2_Analysis_with_R.ipynb` and `Practical_2_Analysis_with_Python.ipynb` are the practical notebooks. They do the same things with the same data; choose whichever language you prefer.
- `merged_data.csv` is the dataset created at the end of Practical 1.

Keep the notebook and `merged_data.csv` in the same folder. The practical saves a plot (`simd_smoking_boxplot.png`) and a trimmed dataset (`analysis_data.csv`) to the same folder.

The data are simulated: every datazone and value is fictional.

The R notebook needs `tidyverse`, `knitr`, `skimr`, `viridis`, `table1` and an R Jupyter kernel. It installs `skimr`, `viridis` and `table1` itself with `install.packages()`. The Python notebook needs `pandas` (version 2 or later), `matplotlib`, `seaborn`, `statsmodels` and a Python 3 Jupyter kernel. It installs `seaborn` and `statsmodels` itself with `%pip install`.
