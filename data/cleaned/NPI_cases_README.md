We are committed to sharing our data for educational use, however, we ask that you attribute our data and keep in mind that this work is licensed under a GNU General Public License v3.0. See our [license](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/LICENSE) file and project [readme.md](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/README.md) in our Github repository: https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021 for how to cite our work. 

NPI data collected by: Annika Avery, Erica Liang, Elizabeth McGrady
JHU case data accessed and preprocessed by: Annika Avery
Affiliation: University of Pittsburgh
Project: PHIGHT COVID
Date: Data last accessed April 2021 

NPI data acquired from March 2020 - March 31, 2021
JHU Case data last accessed April 2021


NPI_cases_04162021.csv was created by merging data/raw/ALL_G1_data_04112021.xlsx with data/raw/COVID_CASES_04132021_pop.csv 

COVID_CASES_04132021_pop.csv:

Data from COVID-19 Dashboard by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University. 

Data acquired on github from COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University https://github.com/CSSEGISandData/COVID-19

The Lakdawala Lab at the University of Pittsburgh restructured the JHU CSSE COVID-19 Data acquired from github and produced the number of new daily cases and deaths as well as the cumulative cases and deaths in a format which fit our project needs. 

|  Column 	|   Information	|
|---	|---	|
|   STATE	|   State name|
|   LATITUDE	|   In degrees	|
|  LONGITUDE 	| In degrees  	|
|   SQMI	| State land area in square miles  	|
|   STUSAB	|  State name abbreviation 	|
|  DATE 	|   Date of Cases recorded and/or NPI effective	|
|  STATEFP 	|  State Federal Information Processing Sysytem (FIPS0 number, used for geographic location identification 	|
|   EVENT_CATG_S	|  A code given to distinguish between the different NPI actions, see belwo for more information about each 	|
|  SCORE 	|  State NPI score given based on scoring rubric 	|
|   GNISID	|   Geographic Names Identification System ID	|
|   RESTRICTIONS	|  restrictions currently being implemented? 1= yes, 0=no 	|
|   PHASED_REOPENING	|  Phased reopening currently being implmented? 1=yes, 0= no 	|
| COUNTYOPEN  	|   Opening at the county level? 1=yes, 0=no	|
|   FACECOVER_RQD	|  Masks/face coverings required? 1=yes, 0=no 	|
