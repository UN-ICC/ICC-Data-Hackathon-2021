# Crisis Indicators

This dataset contains information on crisis-related events, with specific information on the incident, coordinates, etc. 
There are 3 files:

#### [GDACS.csv](GDACS.csv)

| *Variable*                                            | *Description*                                                |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`GDACS_EventID`**                                         | GDACS Event ID |
| **`TimeFK_FromDate`**                                  | FROM Date in YYYYMMDD format                                     |
| **`TimeFK_ToDate`**                                           | TO Date in YYYYMMDD format                                   |
| **`Country_ISO`**                                             | Country ISO3166 Code                                        |
| **`GDACS_Longitude`**                                          | Longitude in Decimal Degrees               |
| **`GDACS_Latitude`**                                      | Latitude in Decimal Degrees                    |
| **`GDACS_Subject`**                                             | Event Subject               |
| **`GDACS_EventType`**                                        | Event Type           |
| **`GDACS_EventTypeDescription`**                                        | Event Type Description |
| **`GDACS_AlertLevel`**                                        | Alert Level                                        |
| **`GDACS_Population`**                                    |Affected population                                       |
| **`GDACS_Title`**                                   | Event title                                  |
| **`GDACS_Description`**                                 | Event description|
| **`GDACS_Cap`**                                 | GDACS URL|

[Source GDACS](gdacs.org)
#### [sources.csv](sources.csv)

Contains the sources used to extract the information.

#### Source
[UNDP](https://www.undp.org/)
