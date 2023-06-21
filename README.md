# Google-Data-Analytics-Capstone-Project---Video-Game-Sales

Welcome to my Google Data Analytics Capstone Project! This is my first data analysis done outside of the program and I am super excited to have this be the start of my data journey!

For this project I choose a dataset published by Ulrik Thyge Pedersen Called Video Game Sales
https://www.kaggle.com/datasets/ulrikthygepedersen/video-games-sales

Thank you and I home you enjoy my project!

SCENARIO
I am working as a junior data analyst at a small video game startup company, Gameoas. They are looking to create and release a new game and want to know what type of game would have the best chance of success in the market.


1: ASK

1.0 Background
Gameoas is a small yet up and coming video game company looking to expand their current portfolio of games. They are looking to target a genre that is high in popularity in order to generate more sales. Gameoas’s VP of Sales is looking to compare the sales per genre over the past 20 years to see trends of popular games. 

1.2 Business Task - to Identify which video game genres have been the most popular and sold the most copies between the years 2000 - 2020.

1.3 Business Objectives

What is the most popular genre of video games sold?
Over the past 20 years 
Identify which platform(s) the game should be available on

1.4 Stakeholders

	Gameoa VP of Sales
	Executive Director of Planning
	Game Development Staff
	Gameoa data analytics team (my team)
	

2: PREPARE
2.1 Dataset
This dataset is from Kaggle, published by Ulrik Thyge Pedersen
https://www.kaggle.com/datasets/ulrikthygepedersen/video-games-sales
The dataset includes game name, genre, platform. year, and sales for North America, Japan, Europe, Other, and Global
There are over 1,000 lines of data spanning across 1980 - 2020
2.2 Limitations & Bias
This dataset includes all games sold between 1980 and 2020. It also identifies the most popular platform each game was sold on
Limitations:
Dataset does not factor in games that are sold across various platforms 
Only includes specific Countries/Regions as outliers and groups the rest as “all other sales”
Since there are so many variables there is no way to cross check to ensure all games sold between 1980 and 2020 are captured and accounted for

2.3 Does this Data ROCCC?
Reliable - MEDIUM - no was to cross check all games are included, however since there is so much data in the set the results will still be accurate enough to solve the business task
Original - HIGH - this dataset is an original set created by Ulrik Thyge Pedersen
Comprehensive - HIGH - dataset is clear and organized to help identify and solve the business task
Current - MED - the dataset only goes up to 2020 so it is missing 2021 - 2023 which can include key information. The range of data is still enough information to solve the business task with high enough accuracy
Cited - HIGH - since this is from Kaggle we know the publisher and can reach out with any further questions




3: PROCESS
3.1 Tools & Cleaning
SHEETS: I first loaded my data into Sheets so I can organize and clean the data. I identified any missing or null information and addressed it accurately by finding the appropriate information and removing any outliers. After a thorough check I have identified that the data is clean and ready to analyze.
I used Pivot Tables to highlight key data that relates back to the business tasks
R: I then loaded my data into R to confirm the cleaning process. I installed the following packages:
Tidyverse
Ggplot2
Dplyr
Janitor
Skimr



4: ANALYZE
4.1 Business Task
Genre - Identify most popular genre
Sales - total the NA sales compared to the Global Sales
Platforms - identify the most popular platform
4.2 Conclusions
Based on the Pivot Tables created in Sheets and Charts created in R:
The most popular Genre for video games is 


5: SHARE
Identify most popular genres in video games sold
Insert chart and 



Cross reference North America sales vs Global sales 
Insert chart

Identify which platform(s) the game should be available on
Insert chart 


ACT

