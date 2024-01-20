# Case Study 1: How Does a Bike-Share Navigate Speedy Success?
This case study is the Capstone project for the Google Data Analytics Professional Certification. The analysis was conducted using R and visualization was done with Tableau.

### About the Company
Cyclistic, the bike-share program launched in 2016, has grown to 5,824 bikes across 692 Chicago stations. The marketing strategy focused on broad consumer segments with flexible pricing plans.  Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders, prompting a shift in strategy. The goal is to convert casual riders into annual members, rather than creating a marketing campaign that targets all-new customers. To achieve this, historical bike trip data will be analyzed to understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics.

![image](https://github.com/Mide203/Google-Capstone-Project-Cyclistic-bike-share-analysis/assets/130792306/0f52d244-7a21-44d5-b346-62c2b161e94a)

#### ASK

Three questions will guide the future marketing program:

1. How do annual members and casual riders use Cyclistic bikes differently?

2. Why would casual riders buy Cyclistic annual memberships?

3. How can Cyclistic use digital media to influence casual riders to become members?

#### THE BUSINESS TASK

To analyze historical bike trip data and understand the differences between annual members and casual riders. Identified insights and trends from the analysis will inform the design of a new marketing strategy for converting casual riders into annual members. The new strategy seeks to enhance the number of annual members and drive future growth for Cyclistic.

**Key Stakeholders**

Lily Moreno

Cyclistic marketing analytics team

Cyclistic executive team

#### PREPARE

##### Data Source Used

[Cyclistic’s historical trip data](https://divvy-tripdata.s3.amazonaws.com/index.html) :  The datasets have a different name because Cyclistic is a fictional company, the 2023 dataset was used.

The data has been made available by Motivate International Inc. under this [license](https://divvybikes.com/data-license-agreement)

This is public data, but note that due to data-privacy issues riders PII (personally identifiable information) are prohibited from being used.

#### ANALYZE

1. The dataset was imported into R and merged into a single data frame.
2. The column headers were renamed.
3. Null, NA values and duplicates were dropped.
4. The start_time and end_time columns were changed from character data type to date and time format.
5. The length of each trip was calculated in minutes
6. Values <= 0 were dropped from the trip_length column.
7. New columns for day_of_the_week and month were created.

**Descriptive statistics**

The summary statistics for trip_length indicate that the variable has a right-skewed distribution, with a relatively high mean compared to the median. 


**The clean csv file was exported and uploaded on Tableau**

#### SHARE

The data visualization was done using Tableau. Please see the interactive dashboard by clicking [this](https://public.tableau.com/app/profile/ayomide.onayemi/viz/Bikeshare_17055266326250/Dashboard2) and download as a Tableau Workbook

![Dashboard 2](https://github.com/Mide203/Google-Capstone-Project-Cyclistic-bike-share-analysis/assets/130792306/f217836a-96d1-4d03-b941-902cb3adb6b1)


The below images display the top start and end stations for both casual and member riders, providing additional insights into the most frequently used locations by each rider category.

![Top 10 end station](https://github.com/Mide203/Google-Capstone-Project-Cyclistic-bike-share-analysis/assets/130792306/f023a433-10ef-4a7b-966a-0a98344f0a73)

![Top 10 start station](https://github.com/Mide203/Google-Capstone-Project-Cyclistic-bike-share-analysis/assets/130792306/036bc178-3c27-4841-9614-f7a3dd07cdfa)


#### ACT

**Recommendations**


1. Seasonal promotions and Campaigns : Discounts or promotions specifically tailored for weekend rides may be introduced. Special promotions can also be launched during summer or towards the end of spring. Flexible subscription plans can also be introduced, for instance, short-term plans during peak summer months for casual riders.

2. Target digital media campaigns : Since peak activity for casual riders occurs at 17:00, targeted digital media campaigns may be run during peak activity hours to maximize their effectiveness.

3. Provide more docked bikes : To attract more casual riders, since they are exclusively used by them. 

4. Promote the benefits of annual membership : To effectively communicate the advantages of annual membership to casual riders, targeted advertising strategies(eg. informative flyers) should be implemented at the top stations frequented by casual riders.
