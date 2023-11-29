# Analyzing the Impact of the COVID-19 Pandemic on Public Transit in Urban Areas across the United States


# Objective
The goal of this analysis is to provide a historical analysis of the impact of the COVID-19 pandemic on public transit (also known as [public transportation](https://en.wikipedia.org/wiki/Public_transport)) and commuting behaviors within urbanized areas across the United States with a population of at least 500,000. 


# Context
The COVID-19 pandemic saw a major change across the United States and the world of lockdown and social distancing. According to the [US Department of Health and Human Services](https://www.hhs.gov/about/news/2023/05/09/fact-sheet-end-of-the-covid-19-public-health-emergency.html), the US COVID-19 Public Health Emergency ended on May 11th, 2023. 

Because public transit has increased density of commuters compared to car travel, it was expected that ridership decreased during the pandemic. Here are some questions related to how the pandemic effected public transit across the US.

- How much did ridership decrease by? <br>
- Has ridership returned to normal? If not, how far are pre-pandemic ridership numbers is post-pandemic numbers? <br>
- How do urban areas compare across the United States in terms of returning to commuting patterns from pre-pandemic? <br>
- How has the advent of work from home changed commuting patterns?


# Data Source

The first dataset is an adjusted monthly ridership information updated to August of 2023 with data through 2002. The source of the dataset is the Federal Transit Administration’s (FTA) National Transit Database (NTD). The dataset can be found [here](https://www.transit.dot.gov/ntd/data-product/monthly-module-adjusted-data-release).

The second dataset include estimated data based on the US census on commuter means of transportation to work updated to 2022. The dataset covers commuter information from 2018 to 2022. The dataset can be found [here](https://data.census.gov/table/ACSST1Y2022.S0801?t=Commuting&g=010XX00US$4000000). 

The third dataset includes generic urban area statistics like population, land area, and housing units for 2020 urban areas. The source of the dataset is the US Census Bureau. The dataset can be found [here](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html).

These datasets will allow for thorough exploration of public transit and commuting characteristics of the period before and during the pandemic. Information on ridership will showcase the affect of COVID-19 on transit while commuter mode share may showcase what modes increased in use when public transit decreased.

In addition, an urban area shapefile from the [US Census Bureau](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=Urban+Areas) was used to support the maps created for the visualizations within Python and Tableau.


# Data Limitations

The main consideration is that 2022 was still a year with many COVID-19 cases. In late 2021 to early 2022, the Omicron variant of COVID-19 spread throughout the world. According to the [CDC](https://www.cdc.gov/museum/timeline/covid19.html#Early-2022), on January 14, 2022, the daily average of new COVID-19 infections reported in the US spikes from 119,215 to 805,062 over the course of one month.  
Therefore, the 2022 commuter and ridership datasets may be skewed by the increased virality of the Omicron variant of COVID-19. 

Another consideration is that at the time of analysis, the latest datasets are for the 2022 year for the commuter dataset and august of 2023 for the transit datasets. Therefore, ridership and vehicle miles can be extrapolated for the 2023 year, but no commuter data can be found for 2023. With full 2023 and 2024 data, a more thorough analysis of pre, during, and post pandemic public transit can be conducted.


# Dashboard

The following Tableau Public dashboard that showcases the results of the above analysis. No link yet [Link]().


# Terminology
- Urban area - short for 'urbanized area'; an urbanized area is defined by the [US Census Bureau](https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html) as "a densely settled core of census blocks that meet minimum housing unit density and/or population density requirements ... the territory identified according to criteria must encompass at least 2,000 housing units or have a population of at least 5,000."
- Commute mode share - commute mode share is defined by the [US Department of Transportation](https://www.transportation.gov/mission/health/commute-mode-share) as "the percentage of workers aged 16 years and over who commute either by bicycle, by private vehicle, including car, truck, van, taxicab, and motorcycle, by public transportation, including bus, rail, and ferry, or by foot." In addition, commuter percentages working from home is also included in within commute mode share data as "commute by worked from home."
- Transit trips - shortened from 'unlinked passenger trips'; unlinked passenger trips are defined by the [National Transit Database](https://www.transit.dot.gov/ntd/national-transit-database-ntd-glossary#U) as "the number of passengers who board public transportation vehicles. Passengers are counted each time they board vehicles no matter how many vehicles they use to travel from their origin to their destination"
- Transit vehicle miles - shortened from 'vehicle revenue miles'; vehicle revenue miles are defined by the [National Transit Database](https://www.transit.dot.gov/ntd/national-transit-database-ntd-glossary#V) as "the miles that vehicles are scheduled to or actually travel while in revenue service."

