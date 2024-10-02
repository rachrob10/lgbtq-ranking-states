# Ranking U.S. States by LGBTQ+ Friendliness - Technical Report

## Introduction

It is no secret that the United States is in the midst of a polarizing, tumultuous and unprecedented time, both socially and politically. 
One of the many underrepresented groups that has come under attack in recent years is the LGBTQ+ community. According to the ACLU, the number of anti-LGBTQ+ bills that have been introduced across the U.S. has risen 79% since 2020. And the Southern Poverty Law Center reports the highest number of anti-LGBTQ+ groups it has ever listed. 
In this environment, as states continue to turn their backs on the LGBTQ+ community, I began to wonder, which states are on the other side of the spectrum and are the most welcoming? 

## Approach

To answer this question, I decided to create a scoring system to rank each state in terms of its LGBTQ+ friendliness. 

The attributes I’ve taken into account in the scores are:
- State Equality
- Legislation
- Municipal Equality
- Safety
- LGBTQ+ Population Density
- Same Sex Marriage

Note that this is not an exhaustive list of attributes. It is possible for the resulting scores to change if other attributes were to be included. These six were chosen due to their comprehensiveness, availability and impact on the queer experience.

## Data Sources

### State Equality
State Equality score pulls from the Movement Advancement Project’s (MAP) LGBTQ Equality by State tally. It is the most comprehensive of all the attributes and includes scores per state in the following categories: Relationship and Parental Recognition, Non-Discrimination Laws, Religious Exemption Laws, LGBT Youth, Healthcare, Criminal Justice and Identity Documents.

Years represented: 2022, 2020, 2010

#### 2022

Source: Movement Advancement Project. "Equality Maps Snapshot: LGBTQ Equality By State." https://www.mapresearch.org/equality-maps/. Accessed 07/16/2024.

Highest possible score: 44.5
Lowest possible score: -18.5  
Min score: -14
Max score: 43
Mean score: 16


#### 2020

Source: Movement Advancement Project. Mapping LGBTQ Equality: 2010 to 2020, United States. Inter-university Consortium for Political and Social Research [distributor], 2021-07-14. https://doi.org/10.3886/ICPSR37877.v2. Accessed 07/16/2024.
 
Highest possible score: 38.5
Lowest possible score: -18.5 
Min score: -6.5
Max score: 34.75
Mean score: 14


#### 2010

Source: Movement Advancement Project. Mapping LGBTQ Equality: 2010 to 2020, United States. Inter-university Consortium for Political and Social Research [distributor], 2021-07-14. https://doi.org/10.3886/ICPSR37877.v2. Accessed 07/16/2024.
 
Highest possible score: 38.5
Lowest possible score: -18.5
Min: -6
Max: 25.25
Mean: 3


### Legislation
Legislation score pulls from the number of Anti-LGBTQ+ bills introduced per state from the ACLU’s Anti-LGBTQ bill tracker. Not all bills become law.

Years represented: 2024 YTD (last downloaded July 16), 2023, 2022, 2021, 2020

#### 2024

Source: American Civil Liberties Union. "Mapping Attacks on LGBTQ Rights in U.S. State Legislatures in 2024." https://www.aclu.org/legislative-attacks-on-lgbtq-rights-2024. Accessed 7/16/2024.

Min: 0
Max: 55
Mean: 10


#### 2023

Source: American Civil Liberties Union. "Mapping Attacks on LGBTQ Rights in U.S. State Legislatures in 2023." https://www.aclu.org/legislative-attacks-on-lgbtq-rights-2023. Accessed 7/16/2024. 

Min: 0
Max: 55
Mean: 10


#### 2022

Source: American Civil Liberties Union. "Past Legislation Affecting LGBTQ Rights Across the Country 2022." https://www.aclu.org/documents/legislation-affecting-lgbtq-rights-across-country-2022. Accessed 7/16/2024.

Min: 0
Max: 18
Mean: 5


#### 2021

Source: American Civil Liberties Union. "Past Legislation Affecting LGBTQ Rights Across the Country 2021." https://www.aclu.org/documents/legislation-affecting-lgbtq-rights-across-country-2021. Accessed 7/16/2024.

Min: 0
Max: 20
Mean: 4


#### 2020

Source: American Civil Liberties Union. "Past Legislation Affecting LGBTQ Rights Across the Country 2020." https://www.aclu.org/documents/legislation-affecting-lgbtq-rights-across-country-2020. Accessed 7/16/2024.

Min: 0
Max: 11
Mean: 2


### Municipal Equality
Municipal Equality score pulls from the Human Rights Campaign’s (HRC) Municipal Equality Index. The index includes scores per city in the following categories: Non-Discrimination Laws, Municipality as Employer, Municipal Services, Law Enforcement and Leadership on LGBTQ+ Equality. The index rates a total of 506 cities of varying sizes from every state.

Years represented: 2023

#### 2023

Source: Human Rights Campaign. "MEI 2023: See Your Cities' Scores." https://www.hrc.org/resources/mei-2023-see-your-cities-scores. Accessed 07/16/2024.

Highest possible score: 100
Lowest possible score: 0
Min: 24
Max: 99
Mean: 68


### Safety
Safety score pulls from the number of hate crimes reported to the FBI on the basis of sexual orientation or gender identity. It is then reported as hate crimes per 100,000 people to normalize for state population size.

Years represented: 2022, 2021, 2020

Population Source, All Years: 

United States Census Bureau. "Annual Estimates of the Resident Population for the United States, Regions, States, District of Columbia and Puerto Rico: April 1, 2020 to July 1, 2023 (NST-EST2023-POP)." https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html. Accessed 07/16/2024.

Crime Source, All Years: 

United States Department of Justice, Federal Bureau of Investigation. "Hate Crime Statistics Annual Reports." https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/downloads. Accessed 07/16/2024.

#### 2022

Min: 1
Max: 490
Mean: 53


#### 2021

Min: 0
Max: 139
Mean: 30


#### 2020

Min: 0 
Max: 269
Mean: 28


### LGBTQ+ Population Density
Density score pulls from reporting done by the UCLA Williams School of Law on LGBT population in the U.S based on the CDC Behavioral Risk Factor Surveillance System (BRFSS) and the Gallup Daily Tracking survey.

Years represented: 2021, 2017

#### 2021

Source: UCLA Williams Institute School of Law. "Adult LGBT Population in the United States." https://williamsinstitute.law.ucla.edu/wp-content/uploads/LGBT-Adult-US-Pop-Dec-2023.pdf.  Accessed 07/19/2024.

Min: 4.10%
Max: 14.30%
Mean: 5.88%


#### 2017

Source: UCLA Williams Institute School of Law. “LGBT Data & Demographics.”  https://williamsinstitute.law.ucla.edu/visualization/lgbt-stats/?topic=LGBT#density. Accessed 07/16/2024.

Min: 2.70%
Max: 9.80%
Mean: 4.21%


### Same Sex Marriage
Marriage score pulls from the year same sex marriage was legalized and calculates how many years same sex marriage has been legal in the state.

Source: Movement Advancement Project. "Equality Maps Snapshot: LGBTQ Equality By State."https://www.lgbtmap.org/equality-maps/marriage_relationship_laws/. Accessed 07/16/2024.

Min: 9
Max: 20
Mean: 11


## Scoring Methodology

### Process
1. Set a min and max value for each attribute
2. Score each state’s actual value for that attribute from 1-10 according to the min and max range
3. Weight the attributes
4. Compose the scores

### Scoring

Assigned a score 0-10 based on where the state’s indicator result fell within the min and max range for each indicator.
​​
### Weighting

The most comprehensive attributes that can be improved upon in the future have higher weights

    0.225 = state equality
    0.225 = legislation

Less comprehensive attributes, ones that are low prevalence or aren’t implemented by the state have medium weights

    0.15 = mei
    0.15 = crime
    0.15 = density

Marriage cannot be changed moving forward, but was included to give a nod to a state’s history and where it has come from

    0.1 = marriage

### Composing

Added all of the attributes after weighting to compose the final score out of 10.

