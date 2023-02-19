# MICROBUISNESS PREDICTION (KAGGLE COMPETITION)

https://www.kaggle.com/competitions/godaddy-microbusiness-density-forecasting/data

## External Data

### Education (2017-) 
https://data.census.gov/table?t=Education&g=0400000US53$0500000,54$0500000,55$0500000,56$0500000&y=2017&tid=ACSST1Y2017.S1501&moe=false


## Data Pre-Processing 
- Given data
  1. Seperate month and date from " first_day_of_month " 
  2. Merge 2 years previous data with census starter data.
- External data
  1. Education (18 years to up, from 2017)
  2. Poverty (18 years to up, from 2017)
  3. Industry accupation of employment (16 years to up, don't know
  4. Covid Data by County 
    data source: https://github.com/nytimes/covid-19-data/blob/master/us-counties-recent.csv

# TODO
with internal data: 2018/1/1 microb data need previous year (2017) college percentage so that we can maybe merge them together 

  1. put previous year pct_college on trainig data
  2. merge pct_foreign_born
  3. pct_it_workders
  4. median_hh_inc 
  
Explore external data 
  - yearly data per county may not have good relationship
  - covid may affect to the density (may need monthly/ yearly covid data)

Covid data 
 - clean data to monthly average by county (2020- 2023)
 - merge with train data 
