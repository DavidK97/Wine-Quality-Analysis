# Wine-Quality-Analysis
This is a project that analyse the chemical factors of a wine.
In the project we go through the following:

## Data Cleaning & Preprocessing
* Outlier Removal: We cleaned the data to ensure that extreme values didn't skew our statistical analysis.
* Scaling: We used MinMaxScaler to bring all chemical attributes into a range between 0 and 1.

## Statistical Analysis & Hypotheses
* Hypothesis Testing: We performed a t-test to see if the alcohol % differs between high and low-quality wines.

## Correlations we found
* 'Alcohol', has the highest positive correlation with quality
* 'Density', has the strongest negative correlation with quality
* 'Total Sulfur Dioxide', has the lowest correlation with quality

For the non dependent attributes, there are the following correlations:
* Free Sulfur Dioxide vs. Total Sulfur Dioxide (most positive)
* Density vs. Alcohol (strongest negative)
