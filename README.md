This repo shows my data analysis practice based on the case study of Cyclistic, a fictional bike rental company, from Google Data Analysis Certificate course.
# Business Task Statement
Cyclistic marketing teams is aiming at attracting its current casual riders to join the membership. To ahiceve the goal, this analysis compares the riding preferences between casual riders and members in terms of ride lengths, dates, and frequent days of week. The result is expected to assist the marketing team to further identify the characteristics of casual riders.
# Data Sources
This research uses the public data of bike rides from 2023-AUG to 2024-AUG from [Index of bucket "divvy-tripdata"](https://divvy-tripdata.s3.amazonaws.com/index.html) under [Data License Agreement | Divvy Bikes](https://divvybikes.com/data-license-agreement) to mock the data for Cyclistic. Given the large amount of data in each files, this analysis takes samplings from each month based on 5% margin of error and 95% confidence level.
# Data Manipulation
In addition to the original data, this analysis added the columns of ride length and day of week for further investigation. The ride length is obtained via reducing the end time by start time, and the day of week is simply attained based on the Excel function WEEKDAY. Data with ride lengthes equal or below zero is excluded from the research.
# Analysis and Findings
## Ride Lengths by Months
