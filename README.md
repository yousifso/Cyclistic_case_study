# Cyclistic Bike-Share Analysis

### Overview
This project is part of the Google Data Analytics Certificate, where I take on the role of a junior data analyst at Cyclistic, a fictional bike-share company in Chicago. The goal is to understand the differences between casual riders and annual members and provide insights to help convert casual riders into annual members.

### Data Analysis Process
The project follows the six-step data analysis process:

### 1. **Ask**
   - **Objective**: Cyclistic wants to increase annual memberships by converting casual riders.
   - **Key Question**: How do casual riders and annual members use Cyclistic differently?

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
Below is a screenshot of the cleaning process results in BigQuery:

### 4. **Analyze**
   - **Task**: Explore the data to uncover trends like ride duration, frequency, and seasonal usage differences between casual riders and members.
   - **Tools**: SQL, R, and Tableau are used to analyze and visualize the data.
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
