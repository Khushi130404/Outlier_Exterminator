# Outlier_Exterminator

Outlier_Exterminator is a Python-based tool designed to handle and process outliers in datasets. It provides implementations of the Interquartile Range (IQR), Z-Score, and Percentile methods to detect and treat outliers. The tool supports various outlier treatment techniques, including trimming, capping, and Winsorization.

This project is developed and demonstrated in a Jupyter Notebook for ease of use and understanding.

## Features

1. Outlier Detection Methods :-
  - IQR Method: Detects outliers using the Interquartile Range.
  - Z-Score Method: Identifies outliers based on the standard deviation.
  - Percentile Method: Flags outliers based on specified percentile thresholds.
    

2. Outlier Treatment Techniques :-
  - Trimming: Removes detected outliers from the dataset.
  - Capping: Replaces outliers with the nearest valid value within bounds.
  - Winsorization: Replaces extreme values with predefined percentiles.


3. Customizable Parameters :-
  - Configure thresholds for Z-scores.
  - Set percentile ranges for trimming and Winsorization.
  - Define the IQR multiplier for flexible outlier detection.
    

4. Visualization :-
  - Generate boxplots and histograms to visualize the effects of outlier treatment.

## Required Libraries :-
- pandas
- numpy
- matplotlib
- seaborn
