# Cyclistic Bike-Share Analysis

### Overview
This project is part of the Google Data Analytics Certificate, where I take on the role of a junior data analyst at Cyclistic, a fictional bike-share company in Chicago. The goal is to understand the differences between casual riders and annual members and provide insights to help convert casual riders into annual members.

### Data Analysis Process
The project follows the six-step data analysis process:

Here’s a version of the "Ask" section formatted for your README:

---

### Step 1: Ask

In the Ask phase, the goal is to clearly identify the problem, define the business objectives, and understand the stakeholders involved. This step helps to set the direction for the entire analysis.

**Problem Definition**  
Cyclistic’s Director of Marketing seeks to develop marketing strategies that will convert casual riders into annual members. To guide this effort, the analysis will focus on three main questions:

1. **How do annual members and casual riders use Cyclistic bikes differently?**
2. **What would motivate casual riders to purchase annual memberships?**
3. **How can digital media be used to encourage casual riders to become members?**

**Objective**  
Analyzing the different behaviors and patterns of annual members and casual riders will provide valuable insights into each group. These insights will help the marketing team design targeted strategies that appeal specifically to casual riders, encouraging them to become members. The findings will also support the Cyclistic executive team in their efforts to grow the company by increasing the number of annual memberships.
### 2. **Prepare**
   - **Data**: Historical trip data of the past 12 months from Cyclistic’s bike-sharing program.
   - **Task**: Download and organize the data for analysis, ensuring it's clean and ready for processing.
     - ### explore the data
       The screenshot below will show column names and their types
       ![Data Cleaning Screenshot](https://github.com/yousifso/Cyclistic_case_study/blob/main/colum_names.png)


### 3. **Process**
   - **Task**: Clean the data by handling missing values, standardizing formats, and creating new columns like ride length and day of the week.
   - **Documentation**: Steps taken to clean and prepare the data for analysis.
   - ### Step 1: Initial Data Check
The initial check of the data revealed several missing values in key columns, which needed to be addressed before further analysis.
--Previewing the first 10 rows of the data

SELECT *
FROM `my-second-project-429115.case_study.cyclistics_case_study`
LIMIT 10;

![Data Cleaning Screenshot](https://github.com/yousifso/Cyclistic_case_study/blob/main/first_10_rows.png)

### Data Cleaning Results
Below is a screenshot of the cleaning process results in BigQuery whihch shows that i removed all emapty and null fields.

![Data Cleaning Screenshot](https://github.com/yousifso/Cyclistic_case_study/blob/main/after_cleaning1.png)
![Data Cleaning Screenshot](https://github.com/yousifso/Cyclistic_case_study/blob/main/after_cleaning2.png)

i also checked for duplication but the dataset has now duplication:

![Data Cleaning Screenshot](https://github.com/yousifso/Cyclistic_case_study/blob/main/check_for_duplication.png)

### 4. **Analyze**
   - **Task**:
     Explore the data to uncover trends like ride duration, frequency, and seasonal usage differences between casual riders and members.
   - **Tools**: SQL and Tableau are used to analyze and visualize the data.
     ### Average Ride Length by Rider Type:
        This query calculates the average ride duration in minutes, comparing casual riders and members.
     ### Insight:
      The results highlight differences in riding behavior,
        showing whether casual riders or members tend to have longer or shorter rides on average.

     ![Data Analyzing](https://github.com/yousifso/Cyclistic_case_study/blob/main/avg_ride_dur.png)

     ### Top 10 Most Popular Start Stations by Rider Type:
        This query identifies the top 10 start stations with the highest ride counts,
           grouped by whether the rider is a member or casual.
     ### Insight:
        The results help pinpoint the stations with the most activity,
           offering valuable information for operational improvements and targeted marketing strategies for different rider types.
     ![Data exploration](https://github.com/yousifso/Cyclistic_case_study/blob/main/popular_station.png)

     ### Bike Type Popularity:
        This query counts the number of trips taken using each type of bike (classic, docked, and electric),
           ordered by the most used bike type.
     ### Insight:
        The results reveal which bike types are most frequently used, providing insights into rider preferences that can inform fleet              management and marketing efforts
     ![Data exploration](https://github.com/yousifso/Cyclistic_case_study/blob/main/Bike_Type_Popularity.png)
     
   - **Visualizations**: Graphs showing key differences in rider behavior.

### 5. **Share**
   - **Task**: Create a clear report and data visualizations to present findings to the Cyclistic executive team.
   - **Deliverables**: Report with insights on how casual riders and members differ, backed by data visualizations.

### 6. **Act**
   - **Recommendations**: Propose marketing strategies to convert casual riders into annual members, such as offering trial memberships, promoting benefits for commuters, and using targeted digital marketing campaigns.
   - **Next Steps**: Test these strategies and refine based on results.

### Tools Used
- SQL: For data extraction and cleaning.
- R: For analysis and calculations.
- Tableau: For data visualization.

### Conclusion
By following this structured approach, the analysis provides actionable insights to help Cyclistic improve membership conversion through targeted marketing strategies.
