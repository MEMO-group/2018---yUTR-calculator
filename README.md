# 2018 --- yUTR-calculator

# Code from the article: 'Toward predictable 5'UTRs in Saccharomyces cerevisiae: Development of a yUTR calculator'

In this repository, you can find the code from our article about the yUTR calculator for the development of predictable 5'UTRs in yeast.
To this end, we hope that this will be useful for others to repeat or build further on our results.

To get started, all python files and calculated data files should be stored in the same folder. The 'function' python files can be left in the 'functions' subfolder in your main folder.

## Requirements



## Python files

PLS-regression.R: R code used to develop the PLS regression model

[UTR_feature_calculation](Code/UTR_feature_calculation.py): Python code used to determine the 13 features in the Dvir UTR data set

[yUTR-calculator](Code/yUTR-calculator.py): Python code to develop novel 5'UTRs with a predictive outcome of protein abundances

[yUTR-calculator_reverse_engineering](yUTR-calculator_reverse_engineering.py): Python code to calculate the protein abundance from a given 5'UTR sequence

## Calculated data files

[coefficients](Calculated_data/coefficients.csv): Regression coefficients determined via PLS regression

[output_analysis](Calculated_data/output_analysis.csv): Output of the 13 features determined from the UTRs in the Dvir data set

[scales](Calculated_data/scales.csv): Scales determined via PLS regression
