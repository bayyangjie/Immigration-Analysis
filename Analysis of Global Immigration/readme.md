## Background

Migration has grown steadily in recent decades surpassing 280 million which is equivalent to 3.6% of the world's population being international migrants. Often people move and take their religion with them, contributing to gradual changes in their new country’s religious makeup. Sometimes, though, migrants shed the religion they grew up with and adopt their new host country’s majority religion, some other religion or no religion. This study is an exploratory analysis aimed at understanding the religious composition of global immigrants from 1990 to 2020. 

 ## Objectives
- Studies the proportion of immigrants from each region throughout the years which includes both incoming and outgoing immigrants from the country
- Analyze the proportion of religions that make up the global immigration population in the dataset to understand the spread of immigrant count among the different religions globally
- Understand the growth profile of global immigration from 1990 to 2020


## About the dataset
The dataset was retrieved from the Pew Research Centre online database and it contains 9 columns and 26712 rows.


## Data cleaning 
The first row was deleted and the second row which contains the various column headers was set as the column labels. 

Entries that are '<10000' in the column variable 'Count' are excluded from the analysis since the scale is very small and might pose as noise to the overall dataset analysis

As this analysis considers individual countries when analyzing the religious composition and population spread, the entries under the column variable 'Region' that begin with 'All' are excluded since they represent a combination of all countries under the specific region. 

The same goes for the column variable 'Religion' where entries such as 'All' are excluded as the analysis takes into consideration individual religions instead of using them as a group.

## Findings
Throughout the years, Europe and Asia Pacific remain as the two regions with the largest composition of immigrants. The global population of immigrants also show an upward trend from 1990 to 2020. The amount of immigrants (incoming and outgoing) remain relatively flat for North America while the growth of immigrant population shows an increasing trend for the other regions. Asia Pacific and Europe show the largest increases from 1990 to 2020 as compared to the other regions. 

## Dashboard
<img width="953" alt="Immigrant screenshot" src="https://github.com/user-attachments/assets/c7f3670b-a3cd-4f40-a460-a84264a51f70">__
Please click here to access my interactive dashboard:
<a href="https://public.tableau.com/views/Global_immigrants_analysis/Dashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">Global Immigrants</a>


