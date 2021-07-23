We are committed to sharing our data for educational use, however, we ask that you attribute our data and keep in mind that this work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License. See our Github repository readme.md at  https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021 for how to cite our work. 

Authors: Jiayi (Tracy) Wang and Xinyu (Melody) Ma
Affiliation: Carnegie Mellon University
Project: PHIGHT COVID
Date: April 2021

# state_case_time_series_interactive

state_time_series_interactive imports a merged dataset with daily new COVID-19 case counts and state level NPI and 
a US population dataset to produce an interactive time series graph.


## Prerequisites

1. You need to Download R-studio to successfully run the state_time_series_interactive file.

2. All the libraries mentioned in code chunk 1 should be installed before the rest of the file.
To install a library, type in the console, install.packages(""), where the library name goes
in between the double quotation marks.


## Running the file

1. Be sure that both datasets are in the same location as the code file.

2. Leave code chunk 1-3 unmodified.

3. If other state graphs want to be made, please modify the state parameter. 
	- all state names need to be in upper case
	- all state names need to go in between a pair of double quotation marks
If other moving average windows want to be picked, please modify the window_num parameter.
If produced graph is missing some information and/or aesthically unpleasing, please follow
the commented instructions to change days_diff, space_dec, label_position_offset, and
no_score_legend_upper. For latest parameters used see attached file "SuggestedHardCodeParameters.xlsx"
Run code chunk 4. 

4. The produced graph will be saved automatically as a html file upon running all code chunks.




