# DSA 210 Term Project: Analysis of COVID-19 Restrictions and State Repression Events

## Motivation and Overview

The COVID-19 pandemic brought about unprecedented global transformations. People were forced to adapt rapidly to new systems and lifestyle changes as lockdowns, social distancing, and mask mandates became a part of daily life. Education, business operations, and communication shifted dramatically toward digital platforms, reshaping the way individuals and organizations interacted. 

As a student who was a high school freshman when the pandemic began, I experienced this disruption firsthand. The period that is often a formative and social experience was instead defined by isolation. By the time the lockdowns fully ended, those two years had passed, and I was preparing for university entrance exams, leaving my generation with a fundamentally altered high school experience.

This personal experience with the profound, life-altering nature of the restrictions naturally leads to broader questions. The strict governmental policies introduced during this period triggered social tension and public debate. Many questioned whether these measures were implemented fairly and transparently, or if certain decisions reflected misuse of power. The pandemic thus not only represented a public health crisis but also exposed significant social, economic, and political challenges.

This project aims to address the question: *“Did governments use the power granted by COVID-19 restrictions as a political tool to repress their own citizens?”*
To explore this, the project combines data on conflicts such as repressions, political violences and demostrations with government responses during the COVID-19, analyzing their relationship to identify potential correlations between restrictive measures and instances of social or political repression.

## Hypothesis 
**Null Hypothesis (H₀):** There is no statistically significant correlation between a government's *"Stringency Index"* level and the *"Number of State Repression Events"* in the subsequent month.

**Alternative Hypothesis (H₁):** There is a statistically significant correlation between a government's *"Stringency Index"* level and the *"Number of State Repression Events"* in the subsequent month. Higher stringecny index results to higher number of state repression events.

## Data Sources
### Data from the ACLED (Armed Conflict Location & Event Data Project) will be mainly used to gather informations about repressions, political violence and demonstrations 
https://acleddata.com

**Data on Repression (12-month lag):** This is the primary dataset for the project. It contains data on state repression events worldwide from 2020 to 2024.
https://acleddata.com/themed/data-repression-12-month-lag

**Number of political violence events by country-month-year:** This dataset provides monthly data on political violence to support the analysis. 
https://acleddata.com/aggregated/number-political-violence-events-country-month-year

**Number of demonstration events by country-year:** This file provides annual data on demonstration events.
https://acleddata.com/aggregated/number-demonstration-events-country-year

### Additional Data Sources ###
**OxCGRT (Oxford COVID-19 Government Response Tracker):** This dataset provides the goverment responses and policies about the Covid-19 for every country from 2020 to June 2023. 
https://www.bsg.ox.ac.uk/research/covid-19-government-response-tracker
https://github.com/OxCGRT/covid-policy-dataset/tree/main/data


## Data Analysis



## Tools and Technologies 
- **Python**: Main programming environment
- **Pandas:** Data preprocessing, merging, and transformation
- **Matplotlib & Seaborn:** Data visualization


## Possible Limitations
**Correlation vs. Causation:** This analysis, in its initial form, will primarily identify correlations between lockdown stringency and state repression. It cannot definitively prove causation. Other factors such as pre-existing political instability and economic stress could be influencing both.

**Definition of "Repression":** The project is dependent on ACLED's specific definition and data collection methodology for "repression events". This may not capture all forms of repression.

**Data bias:** Authoritarian states might underreport repression or censor news, affecting ACLED data quality.
