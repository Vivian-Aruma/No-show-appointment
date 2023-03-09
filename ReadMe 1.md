#                   No-Show Medical Appointment


## Overview

The purpose of this project is to examine the appointment records for Brasil public hospitals. The dataset contains features of patients and I try to check how each attribute influence attendance of patients to appointments. The analysis focused on finding patterns/trends that influence patients decision to show or not show up to appointments. The use of descriptive statistics helped answer questions such as: What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment? 

# Details
The data was cleaned before analysis, I had to drop some columns that I guessed were not needed for my analysis. Changed some datatype to appropriate ones, checked for missing and duplicate values in each of the columns. No_show variable is the dependent variable that was compared with several independent variables in the dataset and observations were made. As this was only an exploratory analysis, many potential correlations may remain uncovered. The data should be investigated further with more advanced statistical analysis to potentially reveal new insights and correlations.

# Tools used
•	Python libraries: numpy, pandas, matplotlib, seaborn, warnings

•	Jupyter Lab

# Scope of Analysis
•	Data Wrangling

•	Exploratory Data Analysis (EDA)

•	Descriptive Analysis

•	Data visualizations

# Findings

Exploration of the No_show_appointment dataset reveals that 110527 total number of patients were scheduled for appointments. The patients consists of people of different background (neighbourhood), health statues (such as Diabetetes, Hipertension,Alcoholism, Handcap), as well as of different age groups.

The Analysis shows;
: Out of 110527 patients, 88208 patients showed up for appointment on their scheduled day, whereas 22319 patients did not show up. The start day for scheduling was on 2015-11-10 and ended on 2016-06-08 .

:The patient's booking was for a two years period (2015-2016) that took place for just seven month (January, February, March, April, May ,June, November and December). The distribution graph of scheduled_Day against No_show is skewed to the left with just 62 persons scheduled in 2015 as against 110465 persons scheduled in 2016.

: Patients from age -1 to 115 were scheduled for appointment. From the analysis, the mean age being 37.7 approximately 38 years. Patients aged from 20-49 years (adults) showed up most for their appointments with those aged 70 and above(old people) having least attendance. A right skewed graph was produced.

: Scholarship statues had little influence on keeping to schedule as majority that honored their appointment were not on scholarship. Out of 110527 patients scheduled for appointment, only 10861 were on scholarship and 99666 patients were not on scholarship. A total of 79925 patients that did not have of their scholarship statues showed up against 19741 who did not. Out of 10861 that were on scholarship, 8283 showed up for appointment whereas 2578 did not.

: Alcoholism decreased with age.

: The number of females booked were more than that of men. A total of 71840 females as against 38687 men scheduled appointment and more females showed up.

: Among 7943 diabetic patients scheduled for appointment, 6513 showed up while 1430 did not show up. It is important to note that most patients were not diabetic.

: Majority of patients did not have hipertension. Total number of hipertensives was 21801 were booked for appointment. 18029 hypertensive patients showed up whereas 3772 did not show up.

: There were four degree of handicap patients 1,2,3,4 with the numbers that showed up (1676, 146, 10 2) respectively as against (366,37,3,1) handicap patients that did not show up. More handicapped patients were found among the elderly 80 years and above. The mean age of patients scheduled for appointment is 37 years
                             
                              LIMITATION
: The data consists of numerous numerical variables; hence minimal statistical analysis was carried out.
: One obvious limitation is that there are no data on patients scheduled for appointment for the months of July, August September and October and no explanation was given.




```python

```
