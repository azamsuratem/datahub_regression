# Regression Analysis on the Data from DataHub.io
A Jupyter Notebook using Python 3 environment on regression analysis of selected data extracted from the open data repository DataHub.io

<b>REMINDER:</b> If this notebook cannot be viewed from this GitHub platform, there are two alternatives to view it:
1. Download the .ipynb Notebook file and view it using JupyterLab or Jupyter Notebook in your local machine (PCs/Laptops), or
2. View them online by copying the below link to the Notebook and paste it in this [online Notebook viewer](https://nbviewer.jupyter.org/) :
<br>https://github.com/azamsuratem/datahub_regression/blob/main/Regression%20Analysis%20on%20DataHub.io%20Extracted%20Data.ipynb

## Introduction
This notebook is created to answer these curiosity questions related to the extracted data:
1. Do all the four data extracted are changing positively or negatively as time passes?
2. Is it true that the spike in gold prices affecting the natural gas prices?
3. Is it true that temperature rises is affected by the increasing atmospheric CO<sub>2</sub> level?
4. Do the changes in natural gas prices involve in the increasing atmospheric CO<sub>2</sub> level?

Data are extracted from the open data repository DataHub.io:
<br>
`price_gold`: Gold Prices - Dataset | Link https://datahub.io/core/gold-prices
<br>
`price_ng`: Natural gas prices - Dataset | Link https://datahub.io/core/natural-gas
<br>
`co2_level`: CO2 PPM - Trends in Atmospheric Carbon Dioxide - Dataset | Link https://datahub.io/core/co2-ppm-daily
<br>
`temp_anom`: Global Temperature Time Series - Dataset | Link https://datahub.io/core/global-temp

## Table of Contents
1. Data Extraction and Data Cleaning
2. Correlation and Causation Analysis
3. Summary on the Regression Analysis using OLS method
4. Linear Regression Model

## References
This notebook was made possible thanks to these sources as references:
- <b>Hypothesis test and p-values</b> Notebook entry by `@ostrowski` in Kaggle.com | [Link to the Notebook entry](https://www.kaggle.com/ostrowski/hypothesis-test-and-p-values)
- <b>Multiple Linear Regression Model in 7 Steps</b> blog entry by `@sametgirgin` in Medium | [Link to the blog entry in Medium](https://medium.com/@sametgirgin/multiple-linear-regression-model-in-7-steps-with-python-f02dbb13c51e)
- <b>Basic of Statistical Viz : Plotly & Seaborn</b> Notebook entry by `@subinium` in Kaggle.com | [Link to the Notebook entry](https://www.kaggle.com/subinium/basic-of-statistical-viz-plotly-seaborn)
- Scikit-Learn online documentation on <b>Linear Regression Example</b> | [Link to the online documentation](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html)
