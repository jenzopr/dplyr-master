# dplyr masterclass challenge

In this challenge, we will explore the number of tuberculosis cases reported in the WHO Global Tuberculosis Report.

#### Download the data

File | URL
---- | ---
population.csv | https://raw.githubusercontent.com/jenzopr/dplyr-master/master/data/tidypop.csv
cases.csv | https://raw.githubusercontent.com/jenzopr/dplyr-master/master/data/tidytb.csv

*Hint*: Use `?download.file` to get help on how to download data from the internet.

#### Data set 1: Population data from countries

The first dataset, `population.csv` contains three columns, which are described here:

Column | Description | R class
------ | ----------- | -------
country | The observed country | Factor
year | The year the observation was made | int
population | Observed population size of the country in the year | int

#### Data set 2: Tuberculosis case numbers

The second dataset, `cases.csv` contains the following five columns:

Column | Description | R class
------ | ----------- | -------
country | The observed country | Factor
year | The year the observation was made | int
sex | The sex of the observed individuals | Factor
age | The age group of the observed individuals | Factor
cases | The number of tuberculosis cases | int

#### Tasks:

1. Load the `dplyr` library.
2. Load the two datasets into your current R session.
3. Answer the following questions using dplyr and save your code in a file with your-name.R
 + How many tuberculosis observations where made in total?
 + How many tuberculosis cases where observed for children in Cambodia, either male and female in 2005?
 + How many inhabitants were living in Mongolia in the year 2000?
 + How many tuberculosis cases where observed in the Sudan between 1995 and 2013, counting males only.
 + Find the average number of tuberculosis cases in Ghana.
 + Is there a country with a higher number of average tuberculosis cases?
4. Join the `cases` data.frame with the `population` data.frame and answer the following questions:
 + For each observation in `cases`, calculate the infection rate per 10.000 inhabitants.
 + Which country has the highest infection rate (per 10.000 inhabitants), regardless of age, sex and year.
 
In case of problems, e.g. missing data, report how you solved the issue.
