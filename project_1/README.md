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


