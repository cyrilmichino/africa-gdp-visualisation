# African Countries GDP Visualisation
This project involves building intricate dashboards on African economies by visualising GDP, GDP per capita, GDP growth, and Population. The dashboard is meant to inform business decisions on which countries to prioritise based purely on the status of the economy. Of course, businesses should consider alternative factors such as the business sector metrics, competition in their sector, and business friendliness (regulation) among others.worl

## Data Sources
This data has been sourced from [the World Bank](https://data.worldbank.org/) on March 6th, 2024. Below are the exact sources of the data:
- **GDP Data:** Original data available in the folder `data >> worldbankGDP`. Sourced exactly from this [link](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)
- **Population Data:** Original data avaiable in the folder `data >> worldbankPopulation`. Sourced exactly from this [link]()
- **Cleaned Data:** After exploring and lightly cleaning the data on Excel, the following csv files were created: `gdp.csv`, `population.csv`, and `metadata.csv`
    - No changes made the actual GDP and actual population data. Only the first three-five lines were redacted so that the final CSV start exactly from the column names. This is what outputs the `gdp.csv` and `population.csv` csv data files
    - On the country metadata, we had to create our own continental categorisation as well as intra-continental regional categorisation. Most of our categorisation was consistent with UN Regional classification apart from the following countries:
        - Malta and Djibouti, categorised as Middle East and North Africa but switched to Western Europe and Eastern African respectively

## Africa region imputation
For clarity on how we imputed regions in Africa, here is the final list of countries and their assigned regions:
| Region | Size | Countries |
|---|---|---|
| West Africa | 15 countries | Benin, Burkina Faso, Cape Verde, Gambia, Ghana, Guinea, Guinea Bissau, Ivory Coast, Liberia, Mali, Niger, Nigeria, Senegal, Sierra Leone, Togo|
| Southern Africa | 12 countries | Botswana, Comoros, Lesotho, Madagascar, Malawi, Mauritius, Mozambique, Namibia, South Africa, Swaziland, Zambia, Zimbabwe|
| Eastern Africa | 11 countries | Burundi, Djibouti, Ethiopia, Eritrea, Kenya, Tanzania, Rwanda, Seychelles, Somalia, South Sudan, Uganda|
| Central Africa | 9 countries | Angola, CAR, Cameroon, Chad, Congo, DRC, Equatorial Guinea, Gabon, Sao Tome |
| North Africa | 7 countries | Algeria, Egypt, Libya, Mauritania, Morocco, Sudan, Tunisia|