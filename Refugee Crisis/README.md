# REFUGEE CRISIS

#### Datasets
We have prepared several datasets for this challenge.

#### [fatalities.csv](fatalities.csv)
Dataset containing fatalities per year and country

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`year`**                                         | Year of the event |
| **`iso_o`**                                  | ISO3 code of the country                                       |
| **`Country`**                                           | Name of the country                                      |
| **`Fatalities_acled`**                                             | Fatalities                                      |

[Source ACLED](https://acleddata.com/#/dashboard)

#### [forciby_displaced.csv](forciby_displaced.csv)
Dataset including stock figures of forcibly displaced persons, disaggregated by displaced abroad (REF), displaced internally (IDP), and asylum seekers awaiting decision (ASY). 

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`Year`**                                         | Year of the event |
| **`CountryOriginCode`**                                  | ISO3 code of the country of origin                                  |
| **`CountryAsylumCode`**                                           | ISO3 code of the country of asylum                                   |
| **`CountryOriginName`**                                             | Name of the country of origin                                     |
| **`CountryAsylumName`**                                             | Name of the country of asylum                                     |
| **`REF`**                                             | Displaced abroad that obtained refugee status                                  |
| **`IDP`**                                             | Internally displaced within the country                                  |
| **`ASY`**                                             | Requested asylum and are still waiting for a decision                                  |

[Source UNHCR](https://www.unhcr.org/refugee-statistics/)

#### [terrain_info.csv](terrain_info.csv)
Country-level data on terrain ruggedness and other characteristics of countries.

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`isocode`**                                         | Country 3-letter ISO code. Alpha-3 code definitions from the ISO 3166 Maintenance Agency as of 2000. |
| **`isonum`**                                  | Country numeric ISO code. Numeric-3 code definitions from the ISO 3166 Maintenance Agency as of 2000.              |
| **`country`**                                           | Country name. English full name definitions from the ISO 3166 Maintenance Agency as of 2000.  |
| **`rugged`**                                           |  Ruggedness (Terrain Ruggedness Index, 100 m)                                   |
| **`rugged_popw`**                                           | Alternative ruggedness (pop. weighted TRI, 100 m).|
| **`rugged_slope`**                                           | Alternative ruggedness (average slope, %)                                   |
| **`rugged_lsd`**                                           | Alternative ruggedness (local std. deviation in elevation, 100 m)                                   |
| **`rugged_pc`**                                           | Alternative ruggedness (% moderately to highly rugged)                                   |
| **`land_area`**                                           | Land area (1000 Ha)                                  |
| **`lat`**                                           | Latitude                                   |
| **`lon`**                                           | Longitude                                   |
| **`soil`**                                           | % Fertile soil                                   |
| **`desert`**                                           | % Desert                                   |
| **`tropical`**                                           | % Tropical climate|
| **`dist_coast`**                                           | Average distance to nearest ice-free coast (1000 km)                                 |
| **`near_coast`**                                           |% Within 100 km of ice-free coast                                |
| **`gemstones`**                                           | Gem diamond extraction 1958-2000 (1000 carats)                                |
| **`rgdppc_2000`**                                           |  Real GDP per person 2000 -- World Bank                                 |
| **`rgdppc_1950_m`**                                           | Real GDP per person 1950 -- Maddison                                 |
| **`rgdppc_1975_m`**                                           | Real GDP per person 1975 -- Maddison                                 |
| **`rgdppc_2000_m`**                                           | Real GDP per person 2000 -- Maddison                               |
| **`rgdppc_1950_2000_m`**                                           |  Real GDP per person 1950-2000 Average -- Maddison.                                 |
| **`q_rule_law`**                                           | Rule of law 1996-2000                                 |
| **`cont_africa`**                                           | Continent indicator: Africa                                 |
| **`cont_asia`**                                           | Continent indicator: Asia                               |
| **`cont_europe`**                                           | Continent indicator: Europe                                 |
| **`cont_oceania`**                                           | Continent indicator: Oceania                                |
| **`cont_north_america`**                                           | Continent indicator: North America                                 |
| **`cont_south_america`**                                           | Continent indicator: South America                                 |
| **`legor_gbr`**                                           |Legal origin indicator: Common law.                                |
| **`legor_fra`**                                           |Legal origin indicator: French civil law.                              |
| **`legor_soc`**                                           | Legal origin indicator: Socialist law.                                |
| **`legor_deu`**                                           |Legal origin indicator: German civil law.                               |
| **`legor_sca`**                                           | Legal origin indicator: Scandinavian law.                              |
| **`colony_esp`**                                           | Colonial origin indicator: Spanish.                                |
| **`colony_gbr`**                                           |Colonial origin indicator: British.                                |
| **`colony_fra`**                                           |Colonial origin indicator: French.                              |
| **`colony_prt`**                                           | Colonial origin indicator: Portuguese.                             |
| **`colony_oeu`**                                           |Colonial origin indicator: Other European.                                |
| **`africa_region_n`**                                           | African region indicator: North                             |
| **`africa_region_s`**                                           | African region indicator: South.                               |
| **`africa_region_w`**                                           |African region indicator: West.                               |
| **`africa_region_e`**                                           | African region indicator: East.                              |
| **`africa_region_c`**                                           | African region indicator: Central.                            |
| **`slave_exports`**                                           | Slave exports 1400-1900.                            |
| **`dist_slavemkt_atlantic`**                                           |  Distance to slave markets, Atlantic trade (1000 km).                             |
| **`dist_slavemkt_indian`**                                           | Distance to slave markets, Indian trade (1000 km).                         |
| **`dist_slavemkt_saharan`**                                           |Distance to slave markets, Saharan trade (1000 km).                          |
| **`dist_slavemkt_redsea`**                                           | Distance to slave markets, Red Sea trade (1000 km) .                           |
| **`pop_1400`**                                           | Population 1400.                           |
| **`european_descent`**                                           | % European descent.                          |

[Source Diego Puga](https://diegopuga.org/data/rugged/)  

#### [dist_cepii.dta](dist_cepii.dta)
Dataset including bilateral distance and other bilateral country characteristics

This dataset is dyadic, in the sense that it includes variables valid for pairs of countries. Distance is the most common example of such a variable, and the file includes different measures of bilateral distances (in kilometers) available for most country pairs across the world.

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`iso_o`**                                         | ISO3 alphabetic code of origin |
| **`iso_d`**                                  | ISO3 alphabetic code of destination       |
| **`contig`**                                           | Dummy equal to 1 if countries are contiguous  |
| **`comlang_off`**                                           |  1 if countries share common official or primary language                                   |
| **`comlang_ethno`**                                           | 1 if countries share a common language spoken by at least 9% of the population|
| **`colony`**                                           | 1 if they have ever had a colonial link                                  |
| **`comcol`**                                           | 1 if they have had a common colonizer after 1945                                |
| **`curcol`**                                           | 1 if they are currently in a colonial relationship                                  |
| **`col45`**                                           | 1 if they have had colonial relationship after 1945                                     |
| **`smctry`**                                           | 1 if they were/are the same country                                |
| **`dist`**                                           | Billateral distance between most populated city of each country (km)                                |
| **`distcap`**                                           | Billateral distance between capitals (km)                                 |
| **`distw`**                                           | Billateral Population-weighted distance between most populated cities (km)                                 |
| **`distwces`**                                           | Billateral Population-weighted distance between most populated cities (km) using CES formulation with θ = −1
|

[Source CEPII](http://www.cepii.fr/)

#### [geo_cepii.dta](geo_cepii.dta) 
Dataset including geographic country characteristics

It incorporates country-specific geographical variables for 225 countries in the world, including the geographical coordinates of their capital cities, the languages spoken in the country under different definitions, a variable indicating whether the country is landlocked, and their colonial links

[Source CEPII](http://www.cepii.fr/)


### Other Datasets

Look into the [Additional Datasources](../Additional%20Datasources) folder. All of the datasets contained in the folder can be useful towards the completion of this challenge.

#### Recommended external datasources:

 - [Armed Conflict Dataset. Uppsala Conflict Data Program (UCDP) Uppsala University / Peace](https://www.prio.org/Data/Armed-Conflict/UCDP-PRIO/)
 - [Research Institute Oslo (PRIO)](https://www.prio.org/Data/Armed-Conflict/UCDP-PRIO/)
 - [Freedom in the World Dataset. Freedom House](https://freedomhouse.org)
 
 #### _Special mention to UNHCR for helping us build and shape this challenge_
