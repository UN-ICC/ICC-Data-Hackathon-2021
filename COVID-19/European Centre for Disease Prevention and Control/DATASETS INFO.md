# ECDC DATASETS

##### Context:

- The 14-day notification rate of new COVID-19 cases, along with the 14-day death rate are the main indicators displayed. These rates are calculated based on data collected by the ECDC Epidemic Intelligence from various sources and are affected by the local testing strategy, laboratory capacity and the effectiveness of surveillance systems. Comparing the epidemiological situation regarding COVID-19 between countries should therefore not be based on these rates alone. At individual country level, this indicator may however be useful for monitoring the national situation over time.
- Testing policies and the number of tests performed per 100 000 persons, vary markedly across the EU/EEA and presumably even more so among third countries. More extensive testing will inevitably lead to more cases being detected.
- The 14-day notification rate of new COVID-19 cases should be used in combination with other factors including testing policies, number of tests performed, test positivity, excess mortality and rates of hospital and Intensive Care Unit (ICU) admissions, when analysing the epidemiological situation in a country. Most of these indicators are presented for EU/EEA Member States in the [Country Overview](http://covid19-country-overviews.ecdc.europa.eu/) report.
- Even when using several indicators in combination, comparisons between countries should be done with caution and relevant epidemiological expertise.

##### Structure:

There are 8 different datasets extracted from the ECDC (European Centre for Disease Prevention and Control) platform. You can find a detailed description of each dataset below or refer directly to the (original source)[https://www.ecdc.europa.eu/en/covid-19/data] for further information.



##### 14_day_age_specific_notification_rate.csv : 

14-day notification rate of newly reported COVID-19 cases per 100 000 population by age group, week and country. Each row contains the corresponding data for a certain week and country. 

##### Variables:

| *Variable*                 | *Description*                      |
| -------------------------- | ---------------------------------- |
| **`country`**              | Country name                       |
| **`country_code`**         | ISO 2-letter code                  |
| **`year_week`**            | Year and week of the measurement   |
| **`age_group`**            | Age group of the measurement       |
| **`new_cases`**            | Number of new cases                |
| **`population`**           | Number of people in that age group |
| **`source`**               | Source of the information          |
| **`rate_14_day_per_100k`** | 14 day rate per 100 000 population |

##### country_response_measures.csv : 

Disclaimer: The data on non-pharmaceutical interventions (or response measures) are based on information available from official public sources, and may not capture measures being taken by countries that are not reported on publicly available websites. The situation is evolving rapidly and this represents a snapshot of the measures that countries in the EU/EEA have reported to date. The response measures displayed are national measures, reported on official public websites. Response measures collected include mass gathering cancellations (for specific events or a ban on gatherings of a particular size); closure of public spaces (including restaurants, entertainment venues, non-essential shops, partial or full closure of public transport etc.); closure of educational institutions (including daycare or nursery, primary schools, and secondary schools and higher education); ‘stay-at-home’ recommendations for risk groups or vulnerable populations (such as the elderly, people with underlying health conditions, physically disabled people etc.); ‘stay-at-home’ recommendations for the general population (which are voluntary or not enforced); and ‘stay-at-home’ orders for the general population (these are enforced and also referred to as ‘lockdown’), use of protective masks in public spaces/on public transport (mutually exclusive voluntary recommendations and mandatory obligations shown separately) and also teleworking recommendations/closure of workplaces.

The data on response measures has several limitations. Firstly, there is substantial heterogeneity in physical distancing policies and their implementation between countries. For instance, the level of enforcement of measures may vary between countries and there may be specific rules and exceptions to the measures, making interpretation of the data challenging. The measures displayed in these figures are measures reported at national level and it should be noted that due to the evolution of the outbreak in certain regions, regional or local measures often preceded national ones. The exact dates of introduction were often available from official sources but delays in their implementation may have occurred. Additionally, availability of public data from official government sources varies among countries. For some countries, data are no longer available on official websites concerning measures that are no longer in force, which may result in the data for more recent measures being more complete

##### Variables:

| *Variable*             | *Description*                         |
| ---------------------- | ------------------------------------- |
| **`Country`**          | Country name                          |
| **`Response_measure`** | Response measure                      |
| **`date_start`**       | Starting date of the response measure |
| **`date_end`**         | Ending date of the response measure   |

##### daily_subnational_14_day_notification_rate.csv : 

14-day notification rate of new cases per 100 000 inhabitants for COVID-19 by day and subnational region. Each row contains the corresponding data for a certain day and per subnational region. Please note that daily data on cases per subnational region are not available for all countries.

##### Variables:

| *Variable*                 | *Description*                                                |
| -------------------------- | ------------------------------------------------------------ |
| **`country`**              | Country name                                                 |
| **`region_name`**          | Name of the region                                           |
| **`nuts_code`**            | (Nomenclature of Territorial Units for Statistics). Geocode standard for referencing the subdivisions of countries for statistical purposes. |
| **`date`**                 | Date of the measurement                                      |
| **`rate_14_day_per_100k`** | 14 day rate per 100 000 population                           |

##### hospital_icu_info.csv : 

Hospitalisation and Intensive Care Unit (ICU) admission rates and current occupancy for COVID-19 by date and country. Each row contains the corresponding data for a certain date (day or week) and per country.

##### Variables:

| *Variable*      | *Description*                                                |
| --------------- | ------------------------------------------------------------ |
| **`country`**   | Country name                                                 |
| **`indicator`** | Type of measurement displayed in the row                     |
| **`date`**      | Date of the measurement                                      |
| **`year_week`** | Year and week of the measurement                             |
| **`value`**     | Admission rate or current occupancy value (depending on the indicator) |
| **`source`**    | Source of the data                                           |
| **`url`**       | Link to the data source                                      |

##### national_14_day_notification_rate.csv : 

14-day notification rate of newly reported COVID-19 cases per 100 000 population and the 14-day notification rate of reported deaths per million population by week and country. Each row contains the corresponding data for a certain day and per country.

##### Variables:

| *Variable*             | *Description*                                                |
| ---------------------- | ------------------------------------------------------------ |
| **`country`**          | Country name                                                 |
| **`country_code`**     | ISO 2-letter code                                            |
| **`continent`**        | Continent the country belongs to                             |
| **`population`**       | Population size of the country                               |
| **`indicator`**        | Measured indicator (either cases or deaths)                  |
| **`weekly_count`**     | Amount measured in that week, relative to the indicator type |
| **`year_week`**        | Year and week of the measurement                             |
| **`cumulative_count`** | Total number of the measurement for that specific country, relative to the indicator type |
| **`source`**           | Source of the data                                           |
| **`rate_14_day`**      | 14 day rate                                                  |

##### overall_info.csv : 

Data on which the maps requested in the Council Recommendation on a coordinated approach to the restriction of free movement in response to the COVID-19 pandemic in EU/EEA are based.

Areas are marked in the following colours: 

- Green if the 14-day notification rate is lower than 25 cases per 100 000 and the test positivity rate below 4%
- Orange if the 14-day notification rate is lower than 50 cases per 100 000 but the test positivity rate is 4% or higher or, if the 14-day notification rate is between 25 and 150 cases per 100 000 and the test positivity rate is below 4%; 
- Red if the 14-day notification rate is 50 cases per 100 000 or higher and the test positivity rate is 4% or higher or if the 14-day notification rate is higher than 150 cases per 100 000
- Grey if there is insufficient information or if the testing rate is lower than 300 cases per 100 000. 

If testing data are available at subnational level, the calculation is done at subnational level.

##### Variables:

| *Variable*                     | *Description*                                                |
| ------------------------------ | ------------------------------------------------------------ |
| **`country`**                  | Country name                                                 |
| **`country_code`**             | ISO 2-letter code                                            |
| **`geo_id_final`**             | Region code (NUTS or specific)                               |
| **`region`**                   | Name of region                                               |
| **`subnational_cases_7`**      | Number of cases in region during the reporting week          |
| **`subnational_population`**   | Population of the region                                     |
| **`subnational_rate_14`**      | 14-day notification rate in the region                       |
| **`national_cases_7`**         | Number of cases at national level in the reporting week (used when subnational testing data are not available) |
| **`national_population`**      | National population (used when subnational testing data are not available) |
| **`national_testing_rate`**    | Testing rate at national level (used when subnational testing data are not available) |
| **`national_positivity_rate`** | Positivity rate at national level (used when subnational testing data are not available) |
| **`subnational_testing_data`** | Availability of testing data at subnational level            |
| **`positivity_rate_combined`** | Positivity rate used for the calculation of the combined indicator (at subnational level if available, otherwise at national level) |
| **`testing_rate_combined`**    | Testing rate used for the calculation of the combined indicator (at subnational level if available, otherwise at national level) |
| **`colour`**                   | Combined indicator colour according to the algorithm described above |
| **`week`**                     | Week                                                         |

##### testing.csv : 

 Testing volume for COVID-19 by week and country. Each row contains the corresponding data for a country and a week.

The data displayed from public online sources have been automatically or manually retrieved (‘web-scraped’) on a daily basis. It should be noted that there are limitations to this type of data including that definitions vary and the data collection process requires constant adaptation to avoid to interrupted time series (i.e. due to modification of website pages, types of data).

##### Variables:

| *Variable*                | *Description*                                                |
| ------------------------- | ------------------------------------------------------------ |
| **`country`**             | Country name                                                 |
| **`country_code`**        | ISO 2-letter code                                            |
| **`year_week`**           | Year and week of the data                                    |
| **`level`**               | National or subnational                                      |
| **`region`**              | Code of the region, similar to country_code but might contain a numerical identifier attached (i.e AT11) |
| **`region_name`**         | Name of the region                                           |
| **`new_cases`**           | Number of new cases                                          |
| **`tests_done`**          | Number of tests done                                         |
| **`population`**          | Population of the country                                    |
| **`testing_rate`**        | Testing rate                                                 |
| **`positivity_rate`**     | Positivity rate                                              |
| **`testing_data_source`** | Data source of the row                                       |

##### weekly_subnational_14_day_notification_rate.csv : 

14-day notification rate of newly reported COVID-19 cases per 100 000 population by week and subnational region. Each row contains the corresponding data for a certain week and subnational region.

Please note that daily data on cases per subnational region are also available for selected countries in the "daily_subnational_14_day_notification_rate.csv" dataset. There may be differences between the rates shown in these two datasets since they are based on different sources of data.

##### Variables:

| *Variable*                 | *Description*                                                |
| -------------------------- | ------------------------------------------------------------ |
| **`country`**              | Country name                                                 |
| **`region_name`**          | Name of the region                                           |
| **`nuts_code`**            | (Nomenclature of Territorial Units for Statistics). Geocode standard for referencing the subdivisions of countries for statistical purposes. |
| **`year_week`**            | Year and week of the information                             |
| **`source`**               | Source of the information                                    |
| **`rate_14_day_per_100k`** | 14 day rate per 100 000 population                           |

##### Source:

[European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu/)