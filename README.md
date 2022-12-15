# DL_Assignment
Alloted dataset: 12.txt

Following are the steps:

    Import pandas and matplotlib.pyplot, seaborn, warnings.
    Load data using pd.read_csv
    Calculate mean, median and mode for all columns.
    Use percentile to find outliers.
    Visualize outliers
    Delete verified outliers.
    Scale the data to fit in a particular range using Maximum Absolute Scaling and MinMax Scaling

Formulas used
Mean = sum(X) / len(X)
Median = mid(sorted(X))
Min Max Scaler x' = (x - min(X)) / (max(X) - min(X))
Max Absolute Scaler is x' = x / max(abs(X))
