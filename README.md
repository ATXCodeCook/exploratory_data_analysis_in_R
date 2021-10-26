## Yearly and Quarterly Trends in U.S. States' Deaths (2014-2019)
#### Note: Written in R-Markdown. See [Patrick_Cook_R_EDA.md](https://github.com/ATXCodeCook/exploratory_data_analysis_in_R/blob/main/Patrick_Cook_R_EDA.md) for full project output.

### Introduction and Objectives

This report explores the Center for Disease Control's (CDC) Weekly Morbidity and 
Mortality data from 2014 through 2019 (Pre-Covid-19 data). 
The data includes weekly death counts for specific causes in the United States. 
The data also includes weekly death counts for individual states and specific 
areas such as New York City, Puerto Rico and Washington, D.C. The analysis was 
completed as an academic project with a focus on exploratory data analysis using R.

More information on the data set can be found at CDC's website 
using the following links: 

- [2014-2015 MMWR Data Set](https://data.cdc.gov/NCHS/Weekly-Counts-of-Deaths-by-State-and-Select-Causes/3yf8-kanr)
- [2020-2021 MMWR Data Set](https://data.cdc.gov/NCHS/Weekly-Provisional-Counts-of-Deaths-by-State-and-S/muzy-jte6)

#### Objective

The objective of the project is to analyze state level weekly cause of death 
data available from the Centers for Disease Control (CDC) to identify specific 
diseases with the highest **growth** in deaths.

#### Analysis and Recommendations
The analysis shown is based on specific states or special regions of 
interest.  This locations may be changed by changing the parameters of the 
functions used to generate the plots (see examples below):

year_trend_boxplot(**'New York City'**,**c('Natural', 'Heart')**)

state_cause_yearly_compare(**'New York City'**,**c('Natural')**)

qtr_significance_boxplots(**'New York City'**,**c('Natural', 'Heart')**)


See function descriptions in the header of the .rmd file for further details of these functions.

