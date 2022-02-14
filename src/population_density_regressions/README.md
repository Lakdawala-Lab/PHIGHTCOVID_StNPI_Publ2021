We are committed to sharing our data for educational use, however, we ask that you attribute our data and keep in mind that this work is licensed under a GNU General Public License v3.0. See our [license](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/LICENSE) file and project [readme.md](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/README.md) in our Github repository: https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021 for how to cite our work. 

Title: "Population Density and COVID-19 cumulative deaths"
Author: Meredith Shephard
Affiliation: University of Pittsburgh
Project: PHIGHT COVID
Date: October 2021

# pop-density-graphs.Rmd 

pop-density-graphs.Rmd imports and merges two datasets (USA_Counties_Data.csv and 20211013_time_series_covid19_deaths_US.csv) to produce population density and cumulative COVID-19 death analyses at the county level. 


## Prerequisites

1. You need to Download R-studio to successfully run the pop-density-graphs.Rmd file.

2. All the libraries mentioned in code chunk 1 should be installed before the rest of the file.
To install a library, type in the console, install.packages(""), where the library name goes
in between the double quotation marks.


## Running the file

1. Leave code chunks 1-4.0, 5.0, and 6.0 unchanged. .

2. Adjust date range in code chunks 4.1, 5.1, and 6.1 to change the cumulative death time period for desired analysis. 

3. Output .csv files for the regression statistics and .png graphs will automatically be generated. 
