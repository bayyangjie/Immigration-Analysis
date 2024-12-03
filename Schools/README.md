# Introduction
With the many existing schools across the different levels of education in Singapore, it is all the more essential to provide parents/students with an accurate overview of the school in Singapore for them to select a school that is best suited to their requirements. This analysis serves as a dashboard that can be updated according to changes in the schools structure in Singapore and can be published online for public access. The dashboard breaks down the profiles of all schools in Singapore based on various metrics such as locations, programs offered, single sex/co-ed schools etc.

# About the dataset
This is a dataset containing general information of schools in Singapore taken from March 2021 to March 2022. The information in the dataset includes address, nearest public transportation of primary, secondary and pre-university schools. 

## Analysis
1. The spread of education types per town
2. The number of each school type per town
3. The number of each school type per zone
4. The number of each education types per zone
5. The count of each nature type oer school type

## Data Cleaning
There were some data cleaning steps that were performed prior to the visualizations. 
- The columns 'Second langugage' and 'Third language' had entries as 'na'. These were converted to actual NULL values for consistency as other NULL entries. The NULL values in these 2 columns were also retained as they provided contextual meaning for schools that only had Chinese as the main language, thus the NULL values for the second and third languages.
- NULL values were checked for the other variables and none contained NULL values.
- Check for duplicated rows was also performed and the query returned zero duplicated rows.

## Datset used
- <a href="https://github.com/bayyangjie/Tableau-Projects/blob/main/Schools/Schools_php.xls">Schools Data</a>

## Project Insights
- Amongst all the zones, the North zone has the most number of schools while the other thre zones each have almost the same number schools.
- Primary and Secondary schools make up the bulk of schools in Singapore. Narrowing down the findings, we can also infer the following from the visualization "Education Types per Zone":
  - East has the highest number of primary schools
  - North has the highest number of secondary schools.
  - For Junior Colleges, the number of schools are almost the same across all zones
  - For the mixed levels education, South has the most number of schools with 5.
- Most of the government schools are located in the North followed by the West. On the other hand, government-aided schools are mostly located in the South followed by the East.
- Narrowing down to the nature types of each school type, we can see that government schools (government and government-aided) are mostly co-ed while independent, specialised independent and specialised schools are only either co-ed or girls' school. The number of girls' schools and co-ed schools are the same in all three school types. 

## Dashboard
<img width="953" alt="tableau screenshot" src="https://github.com/user-attachments/assets/2ca69c27-8fbd-4923-ac86-01d45c3463df"> <br>

Please click here to access my interactive dashboard: 
- <a href="https://public.tableau.com/views/Schools_Analysis_17329432822910/Overview?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">Dashboard<a/>
