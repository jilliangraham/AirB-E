# Airbne - Squatabilty by US State

## Creator
Jillian Graham

## Project goal
Building on the BI Airbne project, this iteration will aim to make a supervised machine learning model that predicts the 'squatability' of the US states through the use of different independent variables.

## Dataset description 
All datasets were procured by from worldpopulationreview.com.
 * Abortion rates by state; 4 columns; 48 rows
   * The abortion rate is calculated as the number of abortions per 1,000 women ages 15-44 years old. Data includes only legal abortions performed at authorized medical facilities. Data exclude California, Maryland, and New Hampshire, which either did not report or did not meet reporting standards. Abortion rates are per 100,000 women aged 15-44 in the calendar year 2020, the most recent year available as of mid-2023. Data for New Jersey are considered incomplete, as they include totals from hospitals and licensed ambulatory care facilities, but not from private physicians and womens' centers
 * Corporate tax rates by state; 6 columns; 52 rows
   * The federal corporate tax is based on a percentage of the income that a company or corporation generates within the United States. The corporate tax rate in the U.S. ranges based on income bracket from 15 percent to 35 percent.
 * Cost of living by state; 7 columns; 53 columns
   * Cost of living refers to the amount needed to cover basic expenses, such as food, shelter, transportation, and healthcare. Cost of living indexes are calculated by first determining a baseline for comparison. When comparing costs across states, the average cost of living in the United States is used as the baseline set at 100. States are then measured against this baseline. For example, a state with a cost of living index of 200 is twice as expensive as the national average. Likewise, living in a state with an index of 50 will cost about half the national average.
 * Crime rate by state; 8 columns; 52 rows
   * A criminal act is either a violent crime or a property crime. The four criminal behaviors that fall into the category of violent crime include aggravated assault, robbery, homicide, whether intentional or accidental, and rape. Property crime is another category of crime in America, and the specific crimes that fall into this category are arson, burglaries, larceny, and motor vehicular theft and damage. Rates per 100k People.
* Foreclosure rate by state; 5 columns; 52 rows
   * HU is an acronym for "housing unit," a term which refers to a single dwelling place such as a house or an apartment. Foreclosure rate represents the proportion or percentage of housing units that are going through the foreclosure process or have been foreclosed upon. The phrase "1/every X HU" suggests that, on average, one out of every X housing units in a given area or region is being foreclosed upon. For example, if the foreclosure rate is 1/every 100 HU, it means that, on average, one out of every 100 housing units is experiencing foreclosure.
* GDP by state; 5 columns; 52 rows
   * The numbers from this dataset are the GDP for each state in Q4 of 2022 from the Bureau of Economic Analysis.
* Happiness by state; 5 columns; 51 rows 
   * Data is sourced from WalletHub, who looked at both internal and external factors in the form of different metrics in three categories: Emotional & Physical Well-Being, Work Environment, and Community & Environment. The categories are broken down into 31 metrics. These metrics include the number of work hours, job security, adult depression, income growth, and the weather, among others. Each metric is weighted differently and graded on a scale from zero to 100, with 100 corresponding with maximum happiness. Each state’s weighted average across all metrics was determined to calculate its overall score. 
* Homelessness by state; 8 columns; 52 rows
   * Total homeless populations are made up of two general groups: adults or youths who live by themselves, and those who live in family units that include at least one adult and one youth. Additional sub-groups tracked include veterans, unaccompanied homeless youths, and chronically homeless individuals. These subgroups' numbers do not add to the totals because they are already included in one of the two main groups.
* Median household income by state; 2 columns; 53 rows
   * Median incomes displayed are per household rather than per individual.
* Corruption by state; 11 columns; 51 rows
   * Data was sourced from Best Lide, who looked at the following information to create their list: number of public corruption convictions per 10,000 residents, number of reported violations by medical providers between 1990-2020 (both adverse action reports and medical malpractice payment reports), states With Anti-Corruption Measures for Public Officials (S.W.A.M.P. Index), and State Integrity Score. Each metric was given a weighted value and was given a Corruption Index Score, where 100 is the most corrupt score a state can receive, and 0 is the least.
* Police officers by state; 4 columns; 51 rows
   * Nothing notable to report in terms of data interpretation.
* Political parties by state; 5 columns; 52 rows
   * The data include: legislative majority paired with governor control; party affiliation of each state's governor, senate, and house; and percentage of adults who identify as a Democrat, Republican, or neither.
* Population by state; 13 columns; 51 rows
   * Nothing notable to report in terms of data interpretation.
*  Poverty rate by state; 3 columns; 52 rows
   *  Poverty is defined as not having enough income to meet basic needs, i.e. to maintain rent, put food on the table, or purchase basic items like clothing, shoes, and hygiene items.
* Quality of life by state; 7 columns; 51 rows
   *  Data sourced by U.S News & World Report. In order to determine rankings, U.S. News & World Report considers a wide range of factors: healthcare includes access, quality, and affordability of healthcare, as well as health measurements, such as obesity rates and rates of smoking; education measures how well public schools perform in terms of testing and graduation rates, as well as tuition costs associated with higher education and college debt load; economy looks at GDP growth, migration to the state, and new business; infrastructure includes transportation availability, road quality, communications, and internet access; opportunity includes poverty rates, cost of living, housing costs and gender and racial equality; fiscal stability considers the health of the government's finances, including how well the state balances its budget; crime and corrections ranks a state’s public safety and measures prison systems and their populations. natural environment looks at the quality of air and water and exposure to pollution.
* Registered voters by state; 3 columns; 53 rows
   * Nothing notable to report in terms of data interpretation.
* Squatter's rights by state; 4 columns; 51 columns
   * RTOO refers to Required Time of Ownership.
* Welfare recipients by state; 5 columns; 52 rows
   * Welfare is a type of government support for the citizens of that society to meet their basic human needs such as food and shelter. Welfare programs typically provide either a free or subsidized supply of certain goods and services such as healthcare and education. SNAP refers to the official program name, Supplemental Nutrition Assistance Program. Data for 2019 is preliminary and can be subject to change.

## Project plan
### Day 1 (data collection)
* Collect data
* Create README

### Day 2 (data cleaning)
* Handle missing data
* Standardize information
* Merge datasets
* Define target variable

### Day 3 (feature engineering)
* Create new features
* Transform data

### Day 4 (model selection)
* Select models
* Select regularization methods
* select evaluation methods

### Day 5 (preprocessing)
* Split data into training and testing sets

### Day 6 (train model)

### Day 7 (train model)

### Day 8 (interpret result)

### Day 9 (communication)
* Present case and findings
