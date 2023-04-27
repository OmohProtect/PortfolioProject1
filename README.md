# Exploratory Analysis of Covid with SQL
Covid death and vaccination exploratory analysis

1. Downloaded the two .xlsx files
2. created a database 
3. created a table - CovidDeaths
4. created 59 columns with data types numeric character varying and date
5. imported the csv data to populate the table/columns
6. created a table - CovidVaccine
7. created 37 columns with data types numeric character varying (not forgetting to include the char length) and date
8. imported the csv data to populate the table/columns

both tables consisting of 85171 rows each

Started with the insight i'd like to get from the data
1.  Percentage % of people dying  (percentage of deaths) I was interested in knowing the data for my country Nigeria
2. total cases vs population (% of population that has covid)
3. countries with the highest infection compared to the population
4. countries with the highest death count per population
5. highest death count by continent
6. Total population vs vaccination
To do this ;
I Joined covid death and covid vaccine table on location and date
7. Daily new vaccinations
This was gotten by suming new_vaccinations over partition by location
