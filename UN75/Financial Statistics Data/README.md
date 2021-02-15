# FINANCIAL STATISTICS DATA

The United Nations System Chief Executives Board for Coordination (CEB) Financial Statistics database is the only comprehensive source of financial statistics for the organizations of the United Nations system.

Data is collected from 43 United Nations entities (in some instances with further disaggregation) and figures are validated with the organizations’ audited financial statements wherever possible. This data is currently collected annually by the CEB Secretariat, as originally mandated by the Administrative Committee on Coordination (General Assembly decisions 47/449, 53/459, 57/557 and 57/558) and is the basis for the preparation of the statistical report of CEB on the budgetary and financial situation of the organizations of the United Nations system to the General Assembly and the DESA Report on the Operational Activities for Development.

#### Datasets


#### [expenses.csv](expenses.csv)
Dataset containing the expenses of the UN agencies

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`calendar_year`**                                         | Year|
| **`amount`**                                  | Quantity                                 |
| **`currency`**                                           | Currency of the quantity                                 |
| **`agency`**                                             | UN Agency                                      |
| **`transaction_type`**                                             | Type of transaction                                      |

#### [expenses_sdgs_2019.csv](expenses_sdgs_2019.csv)
Dataset containing the expenses of the UN agencies, linked by SDG goal

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`calendar_year`**                                         | Year|
| **`entity code`**                                  | Code of the UN Agency                               |
| **`type of financial information`**                                           | Currency of the quantity                                 |
| **`amount`**                                             | Quantity of the expense                                  |
| **`SDG goal`**                                             | SDG goal number                                      |
| **`SDG target`**                                             | SDG target number                                      |
| **`SDG indicator`**                                             | SDG indicator number                                     |

#### [revenue.csv](revenue.csv)
Revenue amount and type

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`agency`**                                         | Agency|
| **`sub_agency`**                                  | Sub agency                            |
| **`calendar_year`**                                           | Year                                 |
| **`amount`**                                             | Quantity of the revenue                                  |
| **`sub_type_name`**                                             | Revenue subtype                               |
| **`rev_type`**                                             | Revenue type                                    |
| **`rev_code`**                                             | Revenue code                                   |
| **`sub_type`**                                             | Revenue subtype code                           |

#### [revenue_government_donor_2019.csv](revenue_government_donor_2019.csv)
Revenue amount and type where government was the donor

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`entity`**                                         | Entity|
| **`calendar_year`**                                  | Year                          |
| **`amount`**                                           | Quantity of the revenue                                   |
| **`_currency_amoun`**                                             | Currency of the quantity                                 |
| **`government_donor`**                                             | Government Donor                               |
| **`rev_type`**                                             | Revenue type                                    |
| **`contrib_type`**                                             | Contribution type                                 |

#### [total_revenue.csv](total_revenue.csv)
Total revenue 

| *Variable*                                            | *Description*                                                | 
| ----------------------------------------------------- | ------------------------------------------------------------ |
| **`agency`**                                         | Agency|
| **`sub_agency`**                                  | Sub agency                            |
| **`calendar_year`**                                           | Year                                 |
| **`amount`**                                             | Quantity of the revenue                                  |
| **`sub_type_name`**                                             | Revenue subtype                               |
| **`rev_type`**                                             | Revenue type                                    |
| **`rev_code`**                                             | Revenue code                                   |
| **`sub_type`**                                             | Revenue subtype code                           |


#### Source

[UNSCEB Financial Statistics](https://unsceb.org/financial-statistics)
