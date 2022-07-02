# Matplotlib-challenge: The Power of Plots

## Pymaceuticals

This repository contains resources and the script to carry out the Pymaceuticals challenge. The script displays the following analysis with conclusions drawn from the data.

### Summary Statistics

The following statistics are produced for each Drug Regimen:

  * Mean, median, Variance, Standard Deviation, SEM.

This is calculated using both the groupby and aggregation methods.

### Bar and Pie Charts

Bar charts produced, using both the Pandas Plot and PyPlot methods, showing the total number of timepoints for all mice tested for each Drug Regimen.

Pie charts produced, using both the Pandas Plot and PyPlot methods, showing the distribution of female vs male mice in the study.

### Quartiles, Outliers and Boxplots

For the drug regimens of interest (Capomulin, Ramicane, Infubinol, and Ceftamin), box plots are generated illustrating the final tumor volumes of each mouse within each regimen.

In addition, analysis on quartiles and potential outliers are presented.

### Line and Scatter Plots

A line plot has been produced for mouse m957 (treated with Capomulin) to illustrate the change in tumor volume over the timepoints within the study.

A scatter plot is producted showing the relationship between the weight and average tumor volume of mice within the Capomulin regimen.

### Correlation and Regression

A linear regression and correlation coefficient has been calculated for the previous scatter plot.