# Project-1-Purple-Team
* Is there a geographic component to readmission?
* Is there a link between socioeconomic conditions and hospital readmission rates? 

## Steps: 
Upload the three CSVs
  * Diabetes (maybe) 
  * Readmission Race and Ethnicity
  * Economics Data
### Readmission Race&Eth CSV 
  * convert to data sheet 
  * use group.by function to groupby states in "state" column 
    * result will be data sheet by state
  * New Data sheet - Reorder/filter "value" column to show top states
    * sorted_df = df.sort_values(by='column_name', ascending=True)
  * New Data sheet - Reorder/filter "value" column to show bottom states
    * sorted_df = df.sort_values(by='column_name', ascending=True)
