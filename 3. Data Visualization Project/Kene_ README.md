# Part I - Ford GoBike System Data
## by Kenechukwu Nwankwo

## Dataset

>This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There are 183412 rows and 16 columns in the dataset. Before performing analysis on the dataset, I wrangled the data and deleted rows with null values, changed the data types for some columns and added new columns to the dataframe.


## Summary of Findings

> As seen in the summary of the dataset, there are null values in the start_station_id, start_station_name, end_station_id, end_station_name columns. All four columns have the same number of missing values.  
> Also, the member_birth_year and member_gender columns have the same number of missing values.
>Getting random samples of the null values in the 'start_station_id' column shows that the null values appear in all four columns in the same places. This is also the case in the member_birth_year and member_gender columns.
>As it is difficult to infer the missing values from the rest of the data, I would be dropping all null values.
> I extracted and created new columns for member age and Day of the week'

### Exploration
> Most rides usually last between 0 - 1500 seconds.
>- Most riders are male, followed by female and then other genders
> There are some riders over 100 years old, even as much as 140 years
> Most riders are between 20 - 80 years

## Key Insights for Presentation

> some key insight found from thd dat set are:

- Male users made up a higehr percentage than female and other genders
- Most users are subscribers 
- Customers ride for a longer time than subscribers
- Most of the Long trips were not shared trips and were mostly done by younger drivers. 
