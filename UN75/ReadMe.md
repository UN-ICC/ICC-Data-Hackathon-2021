# UN75 DATASET

##### Context:

This dataset was constructed through the UN75 One-minute survey. The UN75 survey (www.un75.online) was open to everyone. It was developed in partnership with the SDG Action Campaign, building on the lessons learned from the MYWorld survey, carried out ahead of adoption of the Sustainable Development Goals in 2015. The UN75 Office additionally sought advice from polling experts, such as Pew Research Centre and Misions Publiques. The survey has been translated into 64 languages and adapted for an offline survey app, SMS, UNICEF’s U-Report and other tools.

##### Survey Structure:

Initially, the survey comprised five questions: two multiple choice questions, with answers appearing in randomized order and the option of adding your own (“If you picture the world in 25 years, what THREE things would you most want to see?” & “Which of these global trends do you think will most affect our future?” ); two sliding scale (“How important –or not –is it for countries to work together to manage the above trends?” & “Overall, do you think that people in 2045 will be better off, worse off, the same as you are today?”); and one optional free text question (“What would you advise the UN Secretary-General to do to address these global trends?”). On 22 April, two COVID-19 related questions were added. The first (“What should the international community prioritize to recover better from the pandemic?”) was a multiple-choice question, with answers appearing in randomized order and the option of adding your own answer. The second (“Has Covid-19 changed your views on cooperation between countries?”) was a sliding scale question.

##### Variables:

| *Variable*                                            | *Description*                                                |
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`vote_id`**                                         | An automatically generated number used to identify each unique entry in the dataset. |
| **`submitted_date`**                                  | Date of the submission                                       |
| **`Month`**                                           | Month of the submission                                      |
| **`Day`**                                             | Day of the submission                                        |
| **`source`**                                          | Type of platform the submission was made from                |
| **`partner_id`**                                      | Platform the submission was made from                        |
| **`url`**                                             | URL that lead the user to the questionnaire                  |
| **`referrer`**                                        | Referrer that lead the user to the questionnaire             |
| **`language`**                                        | Acronym for the language the questionnaire was completed in. |
| **`location`**                                        | Location of the user                                         |
| **`country_long`**                                    | Country of the user                                          |
| **`country_short`**                                   | Acronym of the country                                       |
| **`region_23groups`**                                 | Region of the user. The location is mapped into one of 23 regions or other. |
| **`region_21groups`**                                 | Region of the user. The location is mapped into one of 21 regions or other. |
| **`region_8groups`**                                  | Region of the user. The location is mapped into one of 8 regions or other. |
| **`gender`**                                          | Gender of the user                                           |
| **`education_level`**                                 | Education level of the user. Not specified if left blank.    |
| **`education_level_reduced`**                         | Reduced expression of the education level. Not specified if left blank. |
| **`disability`**                                      | Whether the user suffers from a disability or not. Not specified if left blank |
| **`disability_type`**                                 | Type of disability the user suffers from. Not specified if left blank |
| **`age_group`**                                       | Age group the user belongs to. Not specified if left blank   |
| **`covid_international_cooperation`**                 | Answer to the question: “Has Covid-19 changed your views on cooperation between countries?”. NaN if left blank. |
| **`covid_international_cooperation_numeric`**         | Previous variable, covid_international_cooperation , translated into a numeric scale. |
| **`covid_international_cooperation_numeric`**         | Answer to the question: “How important – or not – is it for countries to work together to manage the above trends?”. |
| **`importance_of_international_cooperation_numeric`** | Previous variable, importance_of_international_cooperation, expressed through a numeric scale. |
| **`outlook_for_2045`**                                | Answer to the question: “Overall, do you think that people in 2045 will be better off, worse off, the same as you are today?” |
| **`outlook_for_2045_numeric`**                        | Previous variable, outlook_for_2045_numeric, expressed through a numeric scale. |
| **`long_term_priority_01`**                           | First priority given as an answer to the question: “If you picture the world in 25 years, what THREE things would you most want to see?”. NaN if left blank. |
| **`long_term_priority_02`**                           | Second priority given. NaN if left blank.                    |
| **`long_term_priority_03`**                           | Third priority given. NaN if left blank.                     |
| **`long_term_priority_other`**                        | Additional priority given by the user.                       |
| **`threat_01`**                                       | First threat given as an answer to the question: “Which of these global trends do you think will most affect our future?”. NaN if left blank. |
| **`threat_02`**                                       | Second threat given. NaN if left blank.                      |
| **`threat_03`**                                       | Third threat given. NaN if left blank.                       |
| **`threat_other`**                                    | Additional threat given by the user.                         |
| **`pandemic_recovery_01`**                            | First Covid-19 priority given as an answer to the question: “What should the international community prioritise to recover better from the pandemic?”. NaN if left blank. |
| **`pandemic_recovery_02`**                            | Second Covid-19 priority. NaN if blank.                      |
| **`pandemic_recovery_03`**                            | Third Covid-19 priority. NaN if blank.                       |
| **`pandemic_recovery_option_other`**                  | Additional Covid-19 priority given by the user.              |
| **`message_to_the_SG`**                               | Advise given by the user to the UN Secretary-General.        |
| **`HDI_2018`**                                        | Human Development Index associated to the user’s country.    |



##### Source:

[UN75 UNDP](https://data.undp.org/UN75/)
