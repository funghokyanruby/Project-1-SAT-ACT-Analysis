# Project 1: SAT & ACT Analysis

### Problem Statement 

Our team has been tracking the statewide participation of SAT between 2017 and 2018. In this report, I will present my findings and recommendations on how to improve the participation rate of SAT. 

Though College board is a not-for-profit organisation, it is necessary to identify target states where we can focus resources on given the circumstances that SAT is facing tough competition from the ACT.  

The below analysis is carried out to identify target states. 


## Executive Summary

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)


### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|State| 
|sat_participation_17|float|SAT|SAT Participation Rate 2017| 
|sat_reading_writing_17|int|SAT|SAT Evidence-Based Reading and Writing Mean Score 2017 | 
|sat_math_17|int|SAT|SAT Math Mean Score 2017| 
|sat_total_17|int|SAT|SAT Total Mean Score 2017| 
|act_participation_17|float|ACT|ACT Participation Rate 2017| 
|act_english_17|float|ACT|ACT English Mean Score 2017| 
|act_math_17|float|ACT|ACT Math Mean Score 2017| 
|act_reading_17|float|ACT|ACT Reading Mean Score 2017| 
|act_science_17|float|ACT|CT Science Mean Score 2017|
|act_composite_17|float|ACT|ACT Composite Mean Score 2017|
|sat_participation_18|float|SAT|SAT Participation Rate 2018| 
|sat_reading_writing_18|int|SAT|SAT Evidence-Based Reading and Writing Mean Score 2018 | 
|sat_math_18|int|SAT|SAT Math Mean Score 2018| 
|sat_total_18|int|SAT|SAT Total Mean Score 2018| 
|act_participation_18|float|ACT|ACT Participation Rate 2018| 
|act_english_18|float|ACT|ACT English Mean Score 2018| 
|act_math_18|float|ACT|ACT Math Mean Score 2018| 
|act_reading_18|float|ACT|ACT Reading Mean Score 2018| 
|act_science_18|float|ACT|CT Science Mean Score 2018|
|act_composite_18|float|ACT|ACT Composite Mean Score 2018|



## Outside Research
The participation rate of Colorado increased from 11.0 in 2017 to 100.0 in 2018.

The participation rate of Illinois increased from 9.0 in 2017 to 99.0 in 2018.

These two states have a drastic increment in SAT participation rate, due to the mandatory requirment of the state to take SAT.

## Mandatory requirement affects SAT participation rate

The relationship between SAT and ACT participation rate is totally competent. Most states with participation rates in one test have low participation rate in the other. Bascially, in one state with high SAT participation rate, the ACT partipation rate is very low. 

Since there is mandatory requirement in certain states to take either SAT and ACT, this can explain the distribution of SAT and ACT participaton rate in U.S.

Below are 3 articles that show which few states have listed ACT or SAT as mandatory, and some states that have made both tests optioal for college admission. 

### Standardized Testing Preference State by State 
Which states like the SAT? What about the ACT? Click here for College Raptor's infographic to see standardized testing preferences state by state.
https://www.collegeraptor.com/getting-in/articles/act-sat/preference-act-sat-state-infographic/

### Which States Require Students to Take the SAT or ACT?
A growing number of states are requiring high school students to take the SAT or ACT, according to Education Week's annual testing survey.
https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html


### Colorado Changed to the SAT in 2017: What You Need to Know - Testive
On April 11th, 2017 all Colorado high school juniors will take the SAT. Why does this matter? In 2016, only 5500 Colorado students took the test. Effective this spring, Colorado and the College Board partnered to administer the SAT as the state’s accountability exam and every ...
https://www.testive.com/colorado-sat-change-2017/


## Negative correlation between participation rate and totoal score

The total SAT score of Illinois dropped from 1115 to 1019

The total SAT score of Colorado	droppef from 1201 to 1025

The total SAT score of Miinesota maintained high above 1200, with a low participation rate of 3.0 and 4.0 in 2017 and 2018.

It seems there is a negative correlation between participation rate and totoal score: the higher the participation rate, the lower the total score.



## Conclusions and Recommendations

When identifying the target states, there are 3 conditons to consider:
    1. participation rate 
    2. market size (college enrolment population)
    3. mandatory state requirement on which test to take 
    
States like Colorado, Connecticut, New Hampshire are required to take SAT, and some other like Montana, Montana, Hawaii are required to take ACT, this restriction must be taken into consideration when choosing which state to expand the growth of SAT growth.

After filtering out those states that are unable to take SAT, then we can look into the market size of the states - college enrollment population. A sizable market is more ideal to expand the growth, those below 500,000 would not be considered.

Among the 50 states, some states are taken by ACT, and those in the middle are the potential markets that College Board can consider to grow. If I have to choose one state with a lower participation rate, I would choose Ohio, due to below reasons: 

Ohio has relatively lower participation rate as 12% only. 

Ohio has made ACT and SAT scores optional for admission of college.   

Ohio has about 1.6 million of students - fufill the criteria of being a sizable market. 

Since Ohio fits all the criteria of being an ideal market to expand SAT participation rate growth, it's my top pick. 

Source: 
https://nces.ed.gov/programs/digest/d19/tables/dt19_203.20.asp
Table: Enrollment in public elementary and secondary schools, by region, state, and jurisdiction: Selected years, fall 1990 through fall 2029




