# World Development Indicators:

World Development Indicators (WDI) is the primary World Bank collection of development indicators, compiled from officially recognized international sources. It presents the most current and accurate global development data available, and includes national, regional and global estimates.

We recommend you to look into the [World Bank Databases](https://databank.worldbank.org/databases) and their [API](http://api.worldbank.org/) (documentation can be found [here](https://datahelpdesk.worldbank.org/knowledgebase/topics/125589-developer-information))

#### Structure:

The structure of this dataset is the following:

| *File or folder*                                            | *Description*                                                |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`World Development Indicators`**                                         | Contains an index with all the indicators |
| **`Dataset`**                                  | This folder contains a large dataset of each World Development Indicator. In order to make it more manageable, it has been divided into subsets. The criteria followed to make the split is using the first component of the id of an indicator as the grouping value for that subset, i.e "AG.LND.ARBL.HA" and "AG.SRF.TOTL.K2" can both be found in the "AG.csv" file.
                                       |
#### World Development Indicators.csv variables:

| *Variable*                                            | *Description*                                                |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`id`**                                         | Id of the indicator |
| **`name`**                                  | Name of the indicator                                       |
| **`sourceNote`**                                           | Description of the indicator                                      |
| **`sourceOrganization`**                                             | Source organization for this indicator                                        |
| **`topics`**                                          | Dictionary containing the categories this indicator belongs to                |

#### Indicator variables (any of the subsets that can be found within Dataset):

| *Variable*                                            | *Description*                                                |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`country_id`**                                         | Id of the country |
| **`country`**                                  | Name of the country                                      |
| **`indicator_id`**                                           | Id of the indicator                                   |
| **`countryiso3code`**                                             | ISO3 code for the country                                       |
| **`value`**                                             | Value of the data point                                    |
| **`unit`**                                             | Unit of the data point                                    |
| **`obs_status`**                                          | Indicates the observation status for country, indicator and year combination, i.e "F" means forecast|
| **`decimal`**                                             | Decimal points                                    |

#### Source:

[World Development Indicators](https://databank.worldbank.org/source/world-development-indicators)
