# Analysis of the world population in 2015 

![header](https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/3ef4c925850873.5634bb924adc1.jpg)

In this project, we'll work with data from the [CIA World Factbook](https://www.cia.gov/library/publications/the-world-factbook/), a compendium of statistics about all of the countries on Earth. The Factbook contains demographic information like:

population - The population as of 2015. population_growth - The annual population growth rate, as a percentage. area - The total land and water area.

In this project, we'll use SQL in Jupyter Notebook to explore and analyze data from this database.

### Database: 

The dataset is quite simple and will not allow us to answer complicated question. It is composed of 11 colums and 262 row.

- id - id number attribuated to a country.
- code - country code, made from the two first letters of the country.
- area - total area of the country (area_water + area_land).
- population - population of the country
- population_growth - ratio of the population growth in 2015
- birth_rate
- death_rate
- migration_rate - ratio of people that left the country to another.

It is important to note that the last row (id 262) is not a country but "World" (code: xx). In the end the data is only composed of 261 countries.

## Notes: 

The database being very simple, we could answer complicated questions. This project was intented to practise my SQL skills and show knowledge of simple and more complicated queries (subqueries). 
