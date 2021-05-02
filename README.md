# Kickstarting with Excel
Regina Negrycz
genglist@yahoo.com
Module 1 Challenge
Submitted and Due 2 May 2021
Kickstarter_Challenge.xlsx
Theater_Outcomes_vs_Launch.png
Outcomes_vs_Goals.png
README.md

## Overview of Project

### Purpose
The goal of the project was to understand how theater campaigns succeeded based upon their launch dates and how plays succeeded based upon their goal ranges.

## Analysis and Challenges
Theater Outcomes by Launch Date
In order to analyze theater outcomes by launch date, I needed to create a pivot table whereby the report filters were Parent Category and Years.  I then had to filter Parent Category to theater.  The rows in the pivot table are the months of the year, in ascending order.  The columns are in descending order:  successful, failed, then canceled.  A line chart was created off this pivot table.  See Theater_Outcomes_vs_Launch.png.

Outcomes Based Upon Goals
In order to analyze the outcomes for plays based upon goals, I needed a spreadsheet that aggregated the successful, failed and canceled plays by ranges of goal amounts.  The COUNTIFS() function was used for this effort.  After totaling the number of successful, failed and canceled plays, I calculated percentages for those outcomes.  I created a pivot table off the ranges of goal amounts and percentages of outcomes. See Outcomes_vs_Goals.png.


### Analysis of Outcomes Based on Launch Date
Outcomes Based Upon Launch Date
Approximately 3% of the theater launches were canceled while 61% were successful and 36% failed.

### Analysis of Outcomes Based on Goals
Outcomes Based Upon Goals
In evaluating the outcome of the campaigns against all the total of all goal ranges, 66% were successful and 34% failed.  It was also interesting to learn that none of the campaigns were canceled.  In evaluating the goal ranges individually, the ranges of less than $1,000 and $1,000 to $4,999 were three times more successful than those that failed.


### Challenges and Difficulties Encountered
Challenges Encountered
For outcomes based upon goals, I had initially chosen the wrong line chart so my output had Percentage Failed as a stagnant 100%.  Upon choosing a different line chart, I then saw the correct variations for Percentage Failed.

The range of 5000-9999 was displaying after 45000-45999 and before greater than 50,000.  I added a greater than (>) sign before 5000-9999 and it then appeared immediately after Less than 1000.  I then had to add a greater than (>) sign after 1000-4999 so it then appeared as the 2nd column on the y axis.



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Conclusions of Outcomes Based Upon Launch Date
May and June were the most popular months for successful launches.  December's successes canceled out the failures.  The ratio of successes to failures for February, May and June was 2:1.

- What can you conclude about the Outcomes based on Goals?
Conclustions of Outcomes Based Upon Goals
Projects with goals through $14,999 had the highest success rates.  Once the project goal hit $20,000, the fail rate grew astronomically.


- What are some limitations of this dataset?
Dataset Limitations
The population of kickstarter campaigns for this project was 4,113 across 21 countries.  As there are 195 countries in the world, the campaign only used approximately 10% of the number of countries in the world.  Were the countries chosen representative of the countries in the world?

- What are some other possible tables and/or graphs that we could create?
Other Tables/Graphs to Investigate
The outcome of goals was only analyzed for plays.  Musicals and spaces should also be analyzed utilizing line charts.
Goals and launch dates should be analyzed based upon the countries included in the data captured.

