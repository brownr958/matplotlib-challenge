# matplotlib-challenge
# Ryan Brown
# Janurary 11, 2020

This repository contains the analysis of "Pymaceuticals" data. The major goals of this repository is to analyze
two sets of data that describe mice under going different drug treatments. The data measures tumor volume on the mice
at different time points. Using a jupyter notbook that is described below, the data is analyzed and graphics are
produced in order to assess the different drug treatments. The code used is all in python and graphics are produced
using matplotlib and pandas.

The following is a description of the files within this repository and their location:

1. Pymacuiticals folder: This folder is located within the "matplotlib-challenge" folder and contains all of
the files necessary for this analysis.

2. Mouse_metadata: This file is located within Pymacuiticals -> data. This CSV file contains information on 
mice druge regimine, sex, age, and weight. It contains 250 rows of data.This file will be merged with the mouse_metadata in order to create the full data set used in the analysis notebook
below.

3. Study_results: This file is located within Pymacuiticals -> data. This CSV file contains the information 
on the results of tumor volumes for each mice and is a time series data set. It contains over 1800 rows of data.
This file will be merged with the mouse_metadata in order to create the full data set used in the analysis notebook
below.

4. pymaceuticals_notebook: This notebook is the main file that is used for the analysis. This pulls in both of the
CSV files that are described above and merges them together in order to analyze both data sets. This notebook will 
produce summary statistics of the csv files above, produce graphical outputs based on the study_results, quantify the
quartiles and describe any outliers, and calculate the correlation and regression of the data. Finally, this notebook also includes
a written analysis of three different trends at the very begining. These trends are based on the analysis conducted within
the notebook.