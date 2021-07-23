## Source code and data files for *Variations in Non-Pharmaceutical Interventions by State Correlate with COVID-19 Disease Outcomes*

Annika J. Avery<sup>1</sup>, Jiayi Wang<sup>2</sup>, Xinyu Ma<sup>2</sup>, Qingkai Pan<sup>2</sup>, Elizabeth McGrady<sup>1</sup>, Zongyuan Yuan<sup>2</sup>, Yuqing Liang<sup>1</sup>, Rebecca Nugent<sup>2</sup>, Seema S. Lakdawala<sup>1,3</sup>*

1 – Department of Microbiology and Molecular Genetics, University of Pittsburgh, School of Medicine, Pittsburgh, PA 15219

2 – Department of Statistics and Data Science, Carnegie Mellon University, Pittsburgh PA, 15213

3 – Center for Vaccine Research, University of Pittsburgh, School of Medicine, Pittsburgh, PA 15219

*Please reach out to: Lakdawala@pitt.edu with any questions. 
_________

#### Repository information 
This repository was created to share data and source code from "Variations in Non-Pharmaceutical Interventions by State Correlate with COVID-19 Disease Outcomes", a PHIGHT COVID project publication. The code and data shared can be used to recreate the figures displaed in the paper and on our website: https://phightcovid.org/ 

#### License and Citation Information
We are committed to sharing our data for educational use, however, we ask that you attribute our data and keep in mind that this work is licensed under a GNU General Public License v3.0. See our [license](https://github.com/Lakdawala-Lab/PHIGHTCOVID_StNPI_Publ2021/blob/main/LICENSE) file in this Github repository.

Please cite our work as follows: 

#### Source code provided is to produce the following figures we created:

-static time series graphs (cases and deaths)

-interactive time series graphs (cases and deaths)

-overlapping time series graphs

-time lag graphs

-B-spline graphs 

#### Directories

- data: All data files needed to run the code
   - data/cleaned: Cleaned data files ready to be used in for all code
   - data/mergedfiles: covid.comG1.csv data file created from the merge_G1.Rmd file (file will be re-written if merge_G1.Rmd is run)
   - data/raw: Raw data files used in the merge_G1.Rmd file
- output: Data that is created when running the .Rmd files
    - output/clusterings: Contains all 20 cluster simulations created when running BSplineRegressions.Rmd
- src: All .Rmd files needed to created the figures presented in the paper and on the PHIGHT COVID website
    - src/Bsplines
    - src/interactive_cases_time_series
    - src/interactive_death_time_series
    - src/lag_graphs
    - src/mergecode
    - src/overlapping_time-series
    - src/static_cases-time_series
    - src/static-death_time_series
- SupplementalFiles: Additional supplemental files not included in the paper
 
#### Data file usage:

Use covid_K12_data.xlsx, covidUpdated_04162021.csv and USA_States_Data.csv all found in data/cleaned inside the following code:
- src/interactive_cases_time_series/state_case_time_series_interactive.Rmd
- src/interactive_death_time_series/state_death_time_series_interactive.Rmd
- src/lag_graphs/state_lag_easing_restrictions.Rmd
- src/overlapping_time-series/overlapping_time_series.Rmd
- src/static_cases-time_series/state_case_time_series_static.Rmd
- src/static-death_time_series/state_death_time_series_static.Rmd

Use ALL_G1_data_04112021.xlsx and COVID_CASES_20210413.xlsx found in data/raw inside the following code:
- src/mergecode/merge_G1.Rmd

Use covid.comG1.csv (the output of src/mergecode/merge_G1.Rmd) found in data/mergedfiles inside the following code:
- src/Bsplines/BSplineRegressions.Rmd 

