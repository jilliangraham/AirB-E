# Squatify

## Creator
Jillian Graham

## Project goal
Building on the BI Airbne project, Squatify is a machine learning program that aims to understand which districts in the US are the most socially vulnerable, as a proxy for determining their 'squatability'.

## Dataset description 

Procured from the Agency for Toxic Substanes and Disease Registry. The dataset contains 3143 rows and 158 columns. The columns are breakdowns of the following categories:

* Socioeconomic Status:
  * Below 150% Poverty
  * Unemployed
  * Housing Cost Burden
  * No High School Diploma
  * No Health Insurance

* Household Characteristics:
  * Aged 65 & Older
  * Aged 17 & Younger
  * Civilian with a Disability
  * Single-Parent Households
  * English Language Proficiency

* Racial & Ethnic Minority Status:
  * Hispanic or Latino (of any race)
  * Black and African American, Not Hispanic or Latino
  * American Indian and Alaska Native, Not Hispanic or Latino
  * Asian, Not Hispanic or Latino
  * Native Hawaiian and Other Pacific Islander, Not Hispanic or Latino
  * Two or More Races, Not Hispanic or Latino
  * Other Races, Not Hispanic or Latino

* Housing Type & Transportation:
  * Multi-Unit Structures
  * Mobile Homes
  * Crowding
  * No Vehicle
  * Group Quarters

## Project plan
### Data Collection and Compilation:
* Gather dataset
* Determine inclusion data 

## Feature Selection and Engineering:
* Identify key indicators of social vulnerability
* Normalize data
 
## Social Vulnerability Index Calculation:
* Develop scoring system to calculate the Social Vulnerability Index for each district
* Aggregate normalized values to compute the SVI
* Rank districts based on their SVI scores to identify areas with the highest squatability.

## Identification of Vulnerable Districts:
* Use clustering techniques to group districts with similar vulnerability profiles and identify spatial patterns of vulnerability.
* Visualize the SVI scores on thematic maps to visualize geographic disparities and identify hotspots of social vulnerability.
Analysis of Vulnerability Drivers:

## (If time allows) Spatial Analysis and Mapping: 
* Analyze the spatial distribution of social vulnerability 
