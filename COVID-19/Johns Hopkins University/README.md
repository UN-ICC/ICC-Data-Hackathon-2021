# Johns Hopkins University DATASET

##### Context:

2 datasets:

- [Global daily reports for Covid-19](global%20daily%20reports)
- [US-Limited daily reports for Covid-19](us%20daily%20reports)

This datasets were extracted from the data repository for the 2019 Novel Coronavirus Visual Dashboard operated by the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE). Also, Supported by ESRI Living Atlas Team and the Johns Hopkins University Applied Physics Lab (JHU APL).

##### Datasets:
#### [Global daily reports for Covid-19](global%20daily%20reports)

All cases, deaths, and recoveries reported are based on the date of initial report. Exceptions to this are noted in the "Data Modification" and "Retrospective reporting of (probable) cases and deaths" subsections below.


| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`FIPS`**                                         |US only. Federal Information Processing Standards code that uniquely identifies counties within the USA. |
| **`Admin2`**                                  | County name. US only.                                       |
| **`Province_State`**                                           | Province, state or dependency name.                                     |
| **`Country_Region`**                                             | Country, region or sovereignty name. The names of locations included on the Website correspond with the official designations used by the U.S. Department of State.                                      |
| **`Last Update`**                                             | MM/DD/YYYY HH:mm:ss (24 hour format, in UTC).                                      |
| **`Lat and Long`**                                             | Dot locations on the dashboard. All points (except for Australia) shown on the map are based on geographic centroids, and are not representative of a specific address, building or any location at a spatial scale finer than a province/state. Australian dots are located at the centroid of the largest city in each state.                                      |
| **`Confirmed`**                                             | Counts include confirmed and probable (where reported).                                     |
| **`Deaths`**                                             | Counts include confirmed and probable (where reported).                                     |
| **`Recovered`**                                             | Recovered cases are estimates based on local media reports, and state and local reporting when available, and therefore may be substantially lower than the true number. US state-level recovered cases are from COVID Tracking Project.                                    |
| **`Active`**                                             | Active cases = total cases - total recovered - total deaths.                                     |
| **`Incident_Rate`**                                             | Case-Fatality Ratio (%) = Number recorded deaths / Number cases.                                   |
| **`Case_Fatality_Ratio (%)`**                                             |Case-Fatality Ratio (%) = Number recorded deaths / Number cases.                                  |

#### [US daily reports for Covid-19](us%20daily%20reports)


| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`Province_State`**                                         |The name of the State within the USA.|
| **`Country_Region`**                                  | The name of the Country (US).                                       |
| **`Last_Update`**                                           | The most recent date the file was pushed.                                     |
| **`Lat`**                                             | Latitude.|
| **`Long_`**                                             | Longitude.                                     |
| **`Confirmed`**                                             |Aggregated case count for the state.                                    |
| **`Deaths`**                                             | Aggregated death toll for the state.                                 |
| **`Recovered`**                                             | Aggregated Recovered case count for the state.                                     |
| **`Active`**                                             | Aggregated confirmed cases that have not been resolved (Active cases = total cases - total recovered - total deaths).                                   |
| **`FIPS`**                                             | Federal Information Processing Standards code that uniquely identifies counties within the USA.                       |
| **`Incident_Rate`**                                             | cases per 100,000 persons.                                   |
| **`Total_Test_Results`**                                             |Total number of people who have been tested.                                 |
| **`People_Hospitalized`**                                             |Total number of people hospitalized.                            |
| **`Case_Fatality_Ratio`**                                             |Number recorded deaths * 100/ Number confirmed cases.                       |
| **`UID`**                                             |Unique Identifier for each row entry.                                 |
| **`ISO3`**                                             |Officialy assigned country code identifiers.                                 |
| **`Testing_Rate`**                                             |Total test results per 100,000 persons. The "total test results" are equal to "Total test results (Positive + Negative)" from COVID Tracking Project.                                |
| **`Hospitalization_Rate`**                                             |US Hospitalization Rate (%): = Total number hospitalized / Number cases. The "Total number hospitalized" is the "Hospitalized – Cumulative" count from COVID Tracking Project. The "hospitalization rate" and "Total number hospitalized" is only presented for those states which provide cumulative hospital data.              |


##### Source:

[COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)

