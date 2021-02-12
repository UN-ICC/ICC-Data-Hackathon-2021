# World Development Indicators:

World Development Indicators (WDI) is the primary World Bank collection of development indicators, compiled from officially recognized international sources. It presents the most current and accurate global development data available, and includes national, regional and global estimates.

#### Structure:

The structure of this dataset is the following:

| *File or folder*                                            | *Description*                                                |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`World Development Indicators`**                                         | Contains an index with all the indicators |
| **`Dataset`**                                  | This folder contains a large dataset of each World Development Indicator. In order to make it more manageable, it has been divided into subsets. The criteria followed to make the split is using the first component of the id of an indicator as the grouping value for that subset, i.e "AG.LND.ARBL.HA" and "AG.SRF.TOTL.K2" can both be found in the "AG.csv" file.
                                       |

#### Source:

[World Development Indicators](https://databank.worldbank.org/source/world-development-indicators)
