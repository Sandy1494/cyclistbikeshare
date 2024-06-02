# cyclistbikeshare
This repository houses the final capstone project for the "BADM" professional certificate on GUVI. It features a comprehensive dashboard demonstrating the practical application of Power BI for data analysis and visualization respectively in a business context.

Key Highlights:

Dashboard: Explore the interactive visualization created in Power BI, providing clear insights derived from complex data analyses.
Table of Contents

Why this project?

Case study introduction

Scenario

About the company

Step 1: Ask

Step 2: Data Preparation

Step 3: Process (Data Wrangling)

Step 4: Analyze

Step 5: Share (Data Visualization)

Step 6: Act

Why this project?

This document was created as the final deliverable for the BADM Capstone project. I started this certification program through GUVI in Dec 2023 and completed it in May 2024. Throughout each course in the BADM Certificate, I developed the skills such as Analystical thinking, Storytelling, Excel, Tableau, SQL, Digital Marketing and ML Models. Through this project I am demonstrating the skills needed to transition into a career in Business analytics.

Introduction

In this case study, you will perform many real-world tasks of a junior data analyst. You will work for a fictional company, Cyclistic, and meet different characters and team members. To answer the key business questions, you will follow the steps of the data analysis process: ask, prepare, process, analyze, share, and act.

This markdown file structure is modeled on the Data analysis process presented as part of the BADM Certificate which is:

Ask : Business Challenge/Objective/Question
Prepare : Data generation, collection, storage, and data management
Process : Data cleaning/data integrity
Analyze : Data exploration, visualization, and analysis
Share : Communicating and interpreting results
Act : Putting your insights to work to solve the problem
Scenario

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company's future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.

About the company

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system at any time.

Cyclistic's finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, the Director of Marketing Moreno believes that maximizing the number of annual members will be critical to future growth.

Customers who purchase single-ride or full-day passes are called "casual riders". Customers who purchase annual memberships are Cyclistic "members".

Step 1: Ask

Three questions will guide the future marketing program:

How do annual members and casual riders use Cyclistic bikes differently?
Why would casual riders buy Cyclistic annual memberships?
How can Cyclistic use digital media to influence casual riders to become members?
Statement of business task

GOAL : Analyze how annual members and casual riders use Cyclistic bikes differently. The insights from this analysis would be shared with the marketing team which would help them design marketing strategies aimed at converting casual riders into members.

Step2: Data preparation

The data we will be using is Cyclistic historical trip data from Jan 2020 to Dec 2020. The dataset used has been made available by Motivate International Inc.under this license. 

The sheer volume of observations in each file could be a challenge using Excel to wrangle the combined as Excel took a while to perform calculations on all rows. So, we will use python programming to clean and wrangle the data. Also, a sample of the combined dataset was decided to be better due to computational limitations.

Dataset Limitations

A quick review of the datasets for completeness revealed that 'start_station_name' ,' start_station_id',end_station_name', and'end_station_id' are missing for some rides. Further observations suggest that the most missing data about "start station name" belongs to electric bikes

Step 3: Process (Data Wrangling)

Imported data in Python studio.

Made columns consistent and merged them into a single data frame.

Checked for and treated missing values.

Transformed data-format types.

Added new columns

Removed the rows where trip duration is negative.

Cleaned column names and checked for duplicate records in rows.

Step 4: Analyze the Data

Summary of steps performed to identify trends or relationships I found in the data. Exported a summary file for further analysis.

Reviewed the Distribution of the Numerical Variables
Reviewed Categorical Variables
Checked Cardinality of Categorical Variables
Checked Outliers
Review Relationships between independent variables and dependent variables
Performed Descriptive stats analysis
Step 5: Share

Power BI Desktop was used to show some key trends and patterns. Microsoft PowerPoint is used to present the key insights uncovered.

Cyclistic Bike Share Tableau story https://public.tableau.com/shared/T8Y8TWSN6?:display_count=n&:origin=viz_share_link

Step 6: Act

Prepared the deliverables the Director of marketing asked us to create, including the three top recommendations based on my analysis.

Final conclusions

Here are my top 3 recommendations based on the above key findings:

