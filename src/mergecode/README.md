We are committed to sharing our data for educational use, however, we ask that you attribute our data and keep in mind that this work is licensed under a GNU General Public License v3.0. See our [license](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/LICENSE) file and project [readme.md](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/README.md) in our Github repository: https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021 for how to cite our work. 

Title: "Merge file for COVID BSpline"
Author: Alvin Pan 
Affiliation: Carnegie Mellon University
Project: PHIGHT COVID
Date: April 2021

# merge_G1.Rmd 

mergeG1.Rmd imports daily new COVID-19 case counts COVID_CASES_20210413_pop.xlsx and state level NPI  ALL_G1_data_04112021.xlsx to produce a merged dataset (covid.comG1.csv) to be used to create B splines in the BSplineRegressions.Rmd file.


## Prerequisites

1. You need to Download R-studio to successfully run the state_time_series_interactive file.

2. All the libraries mentioned in code chunk 1 should be installed before the rest of the file.
To install a library, type in the console, install.packages(""), where the library name goes
in between the double quotation marks.


## Running the file

1. Be sure that both datasets are in the same location as the code file.

2. Leave all code chunks unmodified, all code should run without any need for modifications. 

