# PROJECT 3: The State of Food Security and Nutrition in the World

## Objectives
Using the Database published by the FAO, state the world's current situation in terms of food security and malnutrition, highlight some specific countries, and suggest some explanations about what causes hunger. This includes the various steps of Data Wrangling such as:
- Discovering and Gathering the appropriate data among the large database. If necessary, find additional resources to deepens the analysis.
- Structuring the data into a valuable schema.
- Cleaning to improve the data quality: error values, outliers, missing values, formats,...
- Enriching the data by creating new key metrics.
- Validating the data quality using check across the data or with external sources.

Followed by:
- Statistical analysis.
- Creation of Insights.

## Data sources
FAOSTAT provides free access to food and agriculture data for over 245 countries and territories and covers all FAO regional groupings from 1961 to the most recent year available. 

➡️ http://www.fao.org/faostat/en/#home

For this project, we will use the following data based on the last year available:
- Food Balance:
    - Vegetal products, Animal products.
    - Import, Export, Domestic Supply...
- Annual population:
    - Total number of inhabitants
    - Total number of people undernourished 
    N.B: The Chinese provinces need to be removed from the global selection.

Additionally, we will use the ISO corresponding table to enrich the analysis: 

➡️ https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes
