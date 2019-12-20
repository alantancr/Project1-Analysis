# SAT-ACT-Analysis

## Problem Statement

SAT and ACT are two of the most commonly accepted standardised tests used in college applications. In 2015, the lawmakers had voted that Department of Education to take competitive bids for college entrance examinations. Using data for both tests in 2017 and 2018, we want to investigate the correlation amongst the variable of both tests systems. We also want to study any trends and anomalies that might be present in the data, and understand the events that could explain these findings.

## Executive Summary

SAT was created to standardize college admissions procedures and increase access to higher education. Both SAT and ACT have a long history of providing competition solution since 1950s.  In this analysis, we are comparing how SAT fare against ACT in participation rates, look at potential factors that influence major increase in participation, and recommend actions to take and states to focus on to increase the participation for SAT. Data was obtained internally. It was noted that as participation rate increases, the average Total/Compsite score decreases.  Findings showed that there were certain states which legistrated mandatory requirement for either of these tests and have influenced the pariticipation rates of either of them. 

## Limitations

- The data timeframe was given for two years(2017,2018) and likely to be heavily impacted by neaby events e.g. 2015 law makers voted for department of Education to accept competitive bid for college entrance examinations,2017 ruling in Colorado that makes SAT testing mandatory. 
- Other information could be also evaluated like (e.g median household income)

## Conclusion

As certain states have yet to legistrate which test to adopt, it is recommend that the College Board to step up the following activities to enhance participation rates for SAT in states which do not have manadatory requirements to take ACT.

1) Influence state school districts to include PSAT for high school juniors

2) Partner with more education enterprise to create sat awareness in high schools
3) Bursary and Fee waivers to cover test costs: lower entry barrier for lower-income students
4) Introduce PSAT(Preliminary SAT) for junior school students to prepare them for SAT examination
5) Create more workshops and talks on sat to showcase success stories of SAT

## Data Dictionary

|                      Feature                      |   Type   | Dataset | Description                                                  |
| :-----------------------------------------------: | :------: | :-----: | :----------------------------------------------------------- |
|                     **state**                     | *object* | SAT/ACT | The state in the United States of America.                   |
| **sat_participation_2017 sat_participation_2018** | *float*  |   SAT   | SAT participation rate (%) by state for the respective year  |
|           **sat_ewr_2017 sat_ewr_2018**           | *float*  |   SAT   | Average score for Evidence-Based Reading and Writing by state for the respective year. The average English reading and writing score in a maximum score of 800. |
|          **sat_math_2017 sat_math_2018**          | *float*  |   SAT   | Average score for Math by state for the respective year.The average math score in a maximum score of 800. |
|         **sat_total_2017 sat_total_2018**         | *float*  |   SAT   | Total average score by state for the respective year.        |
| **act_participation_2017 act_participation_2018** | *float*  |   ACT   | ACT participation rate (%) by state for the respective year  |
|       **act_english_2017 act_english_2018**       | *float*  |   ACT   | Average score for English by state for the respective year. The average math score in a maximum score of 36. |
|          **act_math_2017 act_math_2018**          | *float*  |   ACT   | Average score for Math by state for the respective year. The average reading score in a maximum score of 36. |
|       **act_reading_2017 act_reading_2018**       | *float*  |   ACT   | Average score for Reading by state for the respective year.The average reading score in a maximum score of 36. |
|     **act_composite_2017 act_composite_2018**     |  float   |   ACT   | The average score calculated by the 3 ACT scores of each state. |



# 