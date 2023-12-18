# Drivers of Wine Quality

This project aims to analyze the drivers of wine quality. The dataset used is the [Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality) from the UCI Machine Learning Repository (specifically only the red wines). The dataset contains 12 variables, 11 of which are physicochemical properties and 1 is the quality rating of the wine. The dataset contains 1599 observations. The dataset is available in the `data` folder.

### Prerequisites

The analysis is done in the `analysis.ipynb` notebook. The analysis is done in Python 3.12. The analysis uses the following libraries:

- `pandas`
- `matplotlib`
- `seaborn`

To run the analysis notebook yourself, you need to have these libraries installed. You can install them using `pip`:

```pip install -r requirements.txt```

### Main findings

For red wines, the variables that are the most highest contributors to the quality of great wines (quality rating of 7 or higher) are:

- Citric acid (+)
- Sulphates (+)
- Alcohol (+)
- Volatile acidity (-)
- Total sulfur dioxide (-)

(+) indicates the high quality wines have higher values of these variables than the low quality wines.

(-) indicates the high quality wines have lower values of these variables than the low quality wines.

### Main Takeaway

In this study, we have identified the main drivers of wine quality. The main drivers of wine quality are citric acid, sulphates, alcohol, volatile acidity, and total sulfur dioxide. The main drivers of wine quality are important for wine makers to know so that they can make better wines that are perceived as higher quality.