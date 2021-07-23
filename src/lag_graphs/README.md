We are committed to sharing our data for educational use, however, we ask that you attribute our data and keep in mind that this work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License. See our Github repository readme.md at  https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021 for how to cite our work. 

Authors: Jiayi (Tracy) Wang and Xinyu (Melody) Ma
Affiliation: Carnegie Mellon University
Project: PHIGHT COVID
Date: April 2021

# state_lag_easing_restrictions

state_lag_easing_restrictions imports a merged dataset with daily new COVID-19 case counts and state level NPI and 
a US population dataset to produce a lag graph.


## Prerequisites

1. You need to Download R-studio to successfully run the overlapping_time_series file.

2. All the libraries mentioned in code chunk 1 should be installed before the rest of the file.
To install a library, type in the console, install.packages(""), where the library name goes
in between the double quotation marks.


## Running the file

1. Be sure that both datasets are in the same location as the code file.

2. Leave all the code chunks except for the last one unmodified

3. Run the last code chunk. 
If other state lag graphs with different lag days want to be made, please modify 
	- state parameter: type state name inside of the double quotation marks
	- lag_day parameter: type an integer number desired. This will change the difference in days between two records.

4. The produced graph will show up right after the last code chunk.




