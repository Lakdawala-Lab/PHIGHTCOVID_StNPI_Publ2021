We are committed to sharing our data for educational use, however, we ask that you attribute our data and keep in mind that this work is licensed under a GNU General Public License v3.0. See our [license](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/LICENSE) file and project [readme.md](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/README.md) in our Github repository: https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021 for how to cite our work.  

Authors: Jiayi (Tracy) Wang and Xinyu (Melody) Ma
Affiliation: Carnegie Mellon University
Project: PHIGHT COVID
Date: April 2021

# state_static_case_time_series

state_static_time_series imports a merged dataset with daily new covid-19 case counts and state level NPI and 
a US population dataset to produce a static time series graph.


## Prerequisites

1. You need to Download R-studio to successfully run the state_static_time_series file.

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
Run code chunk 4.

4. The produced graph will be saved automatically as a png file upon running all code chunks.




