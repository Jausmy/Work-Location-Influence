# Data Portfolio: Work Location Effects Analysis
![HR-Project-Main-Image](Assets/Images/Work%20Location%20Main%20Image.jpg)

## Overview
This report presents a comprehensive analysis of HR data, focusing on the impact of work location (remote, onsite, hybrid) on employee well-being, stress levels, mental health, and productivity. By examining key metrics and trends across different work locations, we aim to provide actionable insights to optimize work arrangements, promote employee well-being, and enhance productivity.

## Executive Summary
By examining key metrics such as stress levels, mental health conditions, work-life balance ratings, and productivity changes, we identified key trends and potential areas for intervention. A key insight from the analysis is that remote employees reported the highest levels of stress and social isolation, while hybrid employees reported the highest work-life balance ratings [(see Analysis of Employee Well-being by Work Location)](#Analysis-of-Employee-Well-being-by-Work-Location). Based on the analysis, we recommend implementing targeted well-being programs for remote employees to mitigate the negative impacts of social isolation and promote work-life balance. This could involve virtual team-building activities, online mental health resources, and flexible work arrangements. By implementing these recommendations, the company can potentially improve employee well-being, reduce stress levels, and enhance productivity across all work locations [(see Potential Impact of Recommendations)](#Potential-Impact-of-Recommendations).   

## Task/Objective
The objective of this analysis is to understand the impact of different work locations (remote, onsite, hybrid) on employee well-being, stress levels, mental health, and productivity. This involves:
-	Data Exploration: Exploring the HR data to understand its structure, identify key variables, and assess data quality.
-	Comparative Analysis: Comparing key metrics and trends across different work locations to identify any significant differences or patterns.
-	Segmentation Analysis: Segmenting the data by job role and work location to understand the specific needs and challenges of different employee groups.
-	Data Visualization: Creating interactive dashboards and visualizations to effectively communicate the key findings and insights from the analysis.

## Methodology
### Data Sources
The primary data source for this analysis is an HR dataset comprising 5,000 rows and 20 columns, including:
-	Employee Demographics (Employee_ID, Age, Gender)
-	Job-Related Information (Job_Role, Industry, Years_of_Experience)
-	Work Arrangement (Work_Location, Hours_Worked_Per_Week, Number_of_Virtual_Meetings)
-	Well-being and Mental Health (Work_Life_Balance_Rating, Stress_Level, Mental_Health_Condition, Access_to_Mental_Health_Resources)
-	Productivity and Engagement (Productivity_Change, Social_Isolation_Rating, Satisfaction_with_Remote_Work, Company_Support_for_Remote_Work)
-	Lifestyle Factors (Physical_Activity, Sleep_Quality)
-	Location (Onsite, Remote, Hybrid)

![Data-Source](Assets/Images/HR%20-%20Data%20Source.png)

### Tools Used
The following tools were used for data analysis and visualization:
-	Microsoft Excel – Data familiarization
-	Microsoft SQL Server – Data exploration and aggregation
-	Microsoft PowerBI – Data visualization

### Data Exploration
Initial data exploration was conducted using SQL Server to calculate key metrics and aggregate data by work location. This involved:
-	Counting total employees by work location.
-	Counting stress level responses per work location.

![SQL-Code-1](Assets/Images/HR%20-%20Data%20Exploration.png)

-	Counting mental health condition responses per work location.
-	Counting sleep quality responses per work location.

![SQL-Code-2](Assets/Images/HR%20-%20Data%20Exploration%202.png)

-	Calculating the percentage of total employees that fell into each stress level category per work location.

![SQL-Code-3](Assets/Images/HR%20-%20Data%20Exploration%203.png)

-	Calculating average hours worked, average work-life balance rating, and average social isolation rating.

![SQL-Code-4](Assets/Images/HR%20-%20Data%20Exploration%204.png)

-    Calculating average work life balance rating for each job role at each location.

![SQL-Code-5](Assets/Images/HR%20-%20Data%20Exploration%205.png)

### Data Analysis Techniques
The following data analysis techniques were employed:
-	Comparative Analysis: We compared key metrics and trends across different work locations to identify any significant differences or patterns. This involved grouping data by work location and analyzing metrics such as stress levels, mental health conditions, work-life balance ratings, and productivity changes.
-	Segmentation Analysis: We segmented the data by job role and work location to understand the specific needs and challenges of different employee groups. This involved grouping data by job role within each work location and analyzing work life balance to identify any significant differences or trends.
-	Diagnostic Analysis: This analysis was used to identify the root cause of the higher stress levels reported by remote employees. By examining various factors such as social isolation, lack of access to support resources, or challenges with work-life balance, we aimed to understand the underlying reasons for this trend.   

## Future Considerations for Data Analysis
In the future, we can leverage additional data analysis techniques to further refine our understanding of employee well-being and productivity. These techniques include:
-	Feedback Analysis: This technique can be used to analyze employee feedback and survey responses to identify key themes and sentiments related to work arrangements, well-being, and productivity. By extracting insights from unstructured data such as employee comments and suggestions, we can gain a deeper understanding of employee needs and identify areas for improvement.
-	Sentiment Analysis: This method relies on natural language processing to determine whether the unstructured data represents positive or negative emotions. By analyzing employee sentiment towards different work arrangements, policies, or initiatives, we can identify areas where employee satisfaction is high or low and make data-driven decisions to improve the overall employee experience.   
-	Network Analysis: This technique can be used to analyze communication patterns and social connections among employees, particularly in remote or hybrid work environments. By understanding how employees interact and collaborate, we can identify potential communication barriers, promote team cohesion, and optimize virtual collaboration strategies.

## Analysis of Employee Well-being and Productivity

### Overall Trends
The overall distribution of employees across different work locations is as follows:
-	Hybrid: 1,649 employees (33%)
-	Onsite: 1,637 employees (32.7%)
-	Remote: 1,714 employees (34.3%)

![Employee-Count]Assets/Images/HR%20-%20Employee%20Numbers.png)

This indicates a relatively balanced distribution of employees across different work arrangements.

### Analysis of Employee Well-being by Work Location
-	Stress Levels: Remote employees reported the highest percentage of high stress levels (34.42%), followed by hybrid (34.02%) and onsite (32.68%) employees. This suggests that remote work may be associated with increased stress levels, potentially due to factors such as social isolation, lack of clear boundaries between work and personal life, or challenges with communication and collaboration.

![Remote-Stress-Level](Assets/Images/HR%20-%20Remote%20Pie.png)

-	Mental Health Conditions: Remote employees also reported a higher prevalence of mental health conditions such as anxiety, burnout, and depression compared to onsite and hybrid employees. This further emphasizes the need to address the potential mental health challenges associated with remote work.

![Mental-Health-Conditions](Assets/Images/HR%20-%20SQL%20Query%20Mental%20.png)

-	Sleep Quality: Remote employees had a slightly higher percentage of employees reporting poor sleep quality compared to onsite and hybrid employees. This suggests that remote work may be impacting sleep patterns, potentially due to increased work hours, blurred boundaries between work and personal life, or heightened stress levels.

![Sleep-Quality](Assets/Images/HR%20-%20SQL%20Query%20Sleep.png)

-	Work-Life Balance: Hybrid employees reported the highest average work-life balance rating (3.02), followed by onsite (2.95) and remote (2.98) employees. This suggests that hybrid work arrangements may offer a better balance between work and personal life compared to fully remote or onsite work.
-	Social Isolation: Remote employees reported the highest average social isolation rating (2.96), followed by hybrid (3.01) and onsite (3.01) employees. This highlights the potential for social isolation among remote employees and the need for interventions to promote social connections and a sense of belonging.

![Average-Ratings](Assets/Images/HR%20-%20SQL%20Query%20Avg%20Ratings.png)

### Segmentation Analysis by Job Role
A segmentation analysis of work-life balance ratings by job role within each work location revealed the following:
-	Remote: Software engineers reported the highest work-life balance rating (3.23), while marketing employees reported the lowest (2.72).
-	Onsite: Sales employees reported the highest work-life balance rating (3.07), while software engineers reported the lowest (2.91).
-	Hybrid: Sales and project managers reported the highest work-life balance ratings (3.08 and 3.07 respectively), while HR employees reported the lowest (2.93).

![Work-Life_Balance](Assets/Images/HR%20-%20Job%20Role%20Work%20Life%20Balance.png)

This suggests that the impact of work location on work-life balance may vary depending on the specific job role and its associated responsibilities and demands.

## Recommendations
Based on the analysis of HR data, the following recommendations are proposed:
-	Implement Targeted Well-being Programs for Remote Employees: Develop and implement targeted well-being programs for remote employees to mitigate the negative impacts of social isolation and promote work-life balance. This could involve:
    -	Virtual Team-building Activities: Organize regular virtual team-building activities, social events, and online communication channels to foster social connections and a sense of community among remote employees.
    -	Online Mental Health Resources: Provide access to online mental health resources, such as counseling services, stress management tools, and mindfulness programs, to support remote employees' mental well-being.
    -	Flexible Work Arrangements: Offer flexible work arrangements for remote employees, such as flexible work hours or the option to work from co-working spaces, to promote work-life balance and reduce stress levels.
-	Promote Work-Life Balance for All Employees: Encourage all employees to prioritize work-life balance by promoting healthy work habits, offering flexible work arrangements where possible, and providing resources and support for managing stress and mental health.
-	Address Mental Health Concerns: Provide access to mental health resources and support for all employees, regardless of work location. This could involve offering employee assistance programs, mental health workshops, or partnerships with mental health providers.
-	Monitor Employee Well-being: Regularly monitor employee well-being through surveys, feedback sessions, and performance reviews to identify any emerging trends or areas for improvement.
-	Tailor Support by Job Role: Consider the specific needs and challenges of different job roles when developing well-being programs and support initiatives.

## Potential Impact of Recommendations
By implementing these recommendations, the company can anticipate the following positive outcomes:
-	Improved Employee Well-being: Targeted well-being programs and support initiatives can lead to improved employee well-being, reduced stress levels, and enhanced mental health across all work locations.
-	Increased Productivity: By promoting work-life balance and addressing mental health concerns, the company can potentially increase employee engagement, motivation, and productivity.
-	Reduced Turnover: Improved employee well-being and job satisfaction can lead to reduced employee turnover and associated costs.
-	Enhanced Company Culture: By prioritizing employee well-being and creating a supportive work environment, the company can enhance its company culture and attract and retain top talent.

## Limitations and Future Considerations
While this analysis provides valuable insights and recommendations, it's important to acknowledge certain limitations:
-	Data Availability: The analysis is limited by the available HR data. Access to more granular data, such as employee feedback, performance reviews, and health records, would allow for a more comprehensive analysis and more personalized recommendations.
-	External Factors: External factors such as economic conditions, industry trends, employee salaries, cost of living data, and personal circumstances can influence employee well-being and productivity and should be considered in future analyses.

## Key Takeaways
This analysis provides valuable insights into the impact of work location on employee well-being and productivity. Here are the key takeaways:
-	Remote work may be associated with increased stress: Remote employees reported the highest levels of stress and social isolation.
-	Hybrid work may offer a better work-life balance: Hybrid employees reported the highest work-life balance ratings.
-	Mental health support is crucial for all employees: Mental health conditions were prevalent across all work locations, highlighting the need for comprehensive mental health support.
-	Job roles influence work-life balance: The impact of work location on work-life balance varies depending on the specific job role.

By implementing the recommendations outlined in this report and continuously monitoring employee well-being and productivity, the company can optimize work arrangements, create a supportive work environment, and achieve its business objectives while prioritizing employee health and well-being.
