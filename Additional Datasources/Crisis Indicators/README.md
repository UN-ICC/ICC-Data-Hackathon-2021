# Crisis Indicators

This dataset contains information on crisis-related events, with specific information on the incident, coordinates, etc. 
There are 3 files:

#### [GDACS.csv](GDACS.csv)

GDACS is a cooperation framework between the United Nations, the European Commission and disaster managers worldwide to improve alerts, information exchange and coordination in the first phase after major sudden-onset disasters. This dataset contains information regarding natural disasters (earthquakes, etc) and where they took place.

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

#### [ACLED.zip](ACLED.zip)

ACLED collects real-time data on the locations, dates, actors, fatalities, and types of all reported political violence and protest events across Africa, the Middle East, Latin America & the Caribbean, East Asia, South Asia, Southeast Asia, Central Asia & the Caucasus, Europe, and the United States of America.

| *Variable*                                            | *Description*                                                |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`Event_Date`**                                         | Event date in YYYYMMDD format|
| **`Country_ISO`**                                  | Country ISO3166 code                                    |
| **`ACLED_Region`**                                           | Geographical Region                                   |
| **`ACLED_Year`**                                             | Year                                        |
| **`ACLED_Event_Type`**                                          | Event Type               |
| **`ACLED_Event_TypeDesc`**                                      | Event Type Description                    |
| **`ACLED_Event_SubType`**                                             | Event Subtype             |
| **`ACLED_Event_SubTypeDesc`**                                        | Event Subtype Description           |
| **`ACLED_Actor1`**                                        | A named actor involved in the event |
| **`ACLED_Ally_Actor1`**                                        | The named actor associated with or identifying with ACTOR1 in one specific event                              |
| **`ACLED_Inter1`**                                    |A numeric code indicating the type of ACTOR1                                 |
| **`ACLED_Actor2`**                                   | The named actor involved in the event. If a dyadic event, there will also be an “Actor 1”.                              |
| **`ACLED_Ally_Actor2`**                                 | The named actor associated with or identifying with ACTOR2 in one specific event.|
| **`ACLED_Inter2`**                                 | A numeric code indicating the type of ACTOR2|
| **`ACLED_Interaction`**                                 | A numeric code indicating the interaction between types of ACTOR1 and ACTOR2. Coded as an interaction between actor types, and recorded as lowest joint number.|
| **`ACLED_Admin1`**                                 | The largest sub-national administrative region in which the event took place|
| **`ACLED_Admin2`**                                 | The second largest sub-national administrative region in which the event took place.|
| **`ACLED_Admin3`**                                 | The third largest sub-national administrative region in which the event took place.|
| **`ACLED_Location`**                                 | The location in which the event took place|
| **`ACLED_Latitude`**                                 | The latitude of the location|
| **`ACLED_Longitude`**                                 | The longitude of the location|
| **`ACLED_Geo_Precision`**                                 | A numeric code indicating the level of certainty of the location coded for the event|
| **`ACLED_Source`**                                 |The source(s) used to code the event|
| **`ACLED_SourceScale`**                                 |The geographic scale of the sources used to code the event|
| **`ACLED_Notes`**                                 |A short description of the event.|
| **`ACLED_Fatalities`**                                 |Number or estimate of fatalities due to event. These are frequently different across reports.|

#### Source
[Source ACLED](https://acleddata.com/#/dashboard)
