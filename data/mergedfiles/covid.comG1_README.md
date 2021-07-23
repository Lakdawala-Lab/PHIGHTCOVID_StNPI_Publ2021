We are committed to sharing our data for educational use, however, we ask that you attribute our data and keep in mind that this work is licensed under a GNU General Public License v3.0. See our [license](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/LICENSE) file and project [readme.md](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/README.md) in our Github repository: https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021 for how to cite our work. 

NPI data collected by: Annika Avery, Erica Liang, Elizabeth McGrady
JHU case data accessed and preprocessed by: Annika Avery
Affiliation: University of Pittsburgh
Project: PHIGHT COVID
Date: Data last accessed April 2021 

NPI data acquired from March 2020 - March 31, 2021
JHU Case data last accessed April 2021


covid.comG1.csv was created by merging data/raw/ALL_G1_data_04112021.xlsx with data/raw/COVID_CASES_04132021_pop.csv in merge_G1.Rmd

COVID_CASES_04132021_pop.csv:

Data from COVID-19 Dashboard by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University. 

Data acquired on github from COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University https://github.com/CSSEGISandData/COVID-19

The Lakdawala Lab at the University of Pittsburgh restructured the JHU CSSE COVID-19 Data acquired from github and produced the number of new daily cases and deaths as well as the cumulative cases and deaths in a format which fit our project needs. 

Field Information: 

|  Field 	|   Information	|
|---	|---	|
|   STATE	|   State name|
|   STUSAB	|  State name abbreviation 	|
|  DATE 	|   Date of Cases recorded and/or NPI implementation date	|
|   LATITUDE	|   In degrees	|
|  LONGITUDE 	| In degrees  	|
|   POPULATION	|  US state population 2017 estimates 	|
|  NEWCONFIRMED 	|   New daily confirmed SARS-CoV-2 cases in the state	|
|  CUMCONFIRMED 	|   All time cumulative confirmed SARS-CoV-2 cases in the state	|
|   NEWDEATHS	|   New daily deaths attributed to COVID-19 cases	|
|  CUMDEATHS 	|   All time cumulative deaths attributed to COVID-19 cases	|
|   SQMI	| State land area in square miles  	|
|  STATEFP 	|  State Federal Information Processing System (FIPS) number, used for geographic location identification 	|
|   GNISID	|   Geographic Names Identification System ID	|
|   UID	|   Unique identifier	|
|  CODE3 	|  Code 3 (From JHU) 	|
|   EVENT_CATG_S	|  A code given to distinguish between the different NPI actions, see below for more information about each 	|
|  SCORE 	|  State NPI score given based on scoring rubric 	|
|  SHORT_DESCRIPT 	|   A short description of the NPI	|
|   RESTRICTIONS	|  restrictions currently being implemented? 1= yes, 0=no 	|
|   PHASED_REOPENING	|  Phased reopening currently being implemented? 1=yes, 0= no 	|
| COUNTYOPEN  	|   Opening at the county level? 1=yes, 0=no	|
|   FACECOVER_RQD	|  Masks/face coverings required? 1=yes, 0=no 	|
|  NEWCD_NORM_500 	|   New daily confirmed SARS-CoV-2 cases normalized to state population and represented per 500,000 people 	|
|  NEWDEATHS_NORM500	|  New daily deaths attributed to COVID-19 cases normalized to state population and represented per 500,000 people	|
|   Region	|  U.S. geographic region 	|

NPI Category Codes:

|  EVENT_CATG_S Codes 	| Information  	|
|---	|---	|
|   1SM	|   Mandatory stay at home order for whole state|
|   1SR	|   Recommended stay at home order for whole state	|
|   1L	|   Stay at home order lifted	|
|  2SM 	|  Mandatory non-essential business closures for whole state 	|
|   2SR	|  Recommended non-essential business closures for whole state 	|
|   2E	|   Eased restrictions and some partial reopenings on non-essential business closures	|
|   2R	|   Re-issued non-essential business closures	|
|   2L	|   Non-essential businesses closures lifted	|
|   3SM	|  Mandatory indoor gathering ban issued 	|
|   3SR	|   Indoor gathering ban recommendation issued	|
|   3E	|   Eased size limitations on indoor gathering bans	|
|   3R	|  Indoor gathering ban limitations re-issued 	|
|  3L 	|   Indoor gathering ban limitations lifted	|
| 4SM  	|   Restaurant and Bar Limitations/Restrictions issued	|
|   4E	|   Eased restaurant and bar limitations/restrictions	|
|   4R	|   Restaurant and Bar Limitations/Restrictions Re-issued	|
|   4L	|   Restaurant and Bar Limitations/Restrictions lifted	|
|   15R	|   State guidance recommending face coverings/masks	|
|   15M	|   State issued order making face coverings/masks mandatory for all citizens out in public areas (exceptions differ by state)	|
|   15M1	|   State issued order making face coverings/masks mandatory for employees in certain businesses	|
|   15M2	|   State issued order making face coverings/masks mandatory for employees and patrons in certain businesses	|
|   15M3	|   State issued order making face coverings/masks mandatory for employees and patrons in state government facilities only	|
|  15COM 	|   Individual counties have mandated masks in public spaces	|
|   15CYM	|  Individual cities have mandated masks in public spaces 	|
