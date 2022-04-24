# An Analysis of Kickstarter Campaigns

## Overview of Project

There are many factors that influence whether or not a campagin/project will be successful, will fail or be cancelled, such as monetary conrtibutions and backers, location, and launch date, to name a few. Louise aims to create a successful play ‘Fever’ and considers reviewing and analyzing data from past campaigns, zoning into the cateogry theather, specifically 'plays', to make an informed decision to increase the chance of success for her campaign. The analysis will provide insights as to potentially the time period that increases the probability of success and how funding goals relates to the project outcome. 

### Purpose
 - Determine potentially the best time, if any, to release a theater campaign to attain success, and to determine if any particular period should be avoided to prevent failure or cancellation
 - Investigate how the funding goal affects the outcome. In other words, is there any relation between the outcomes ‘successful’, failed’ and ‘cancelled’, and funding goals.

## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Date

The following steps were utilized in analyzing the data:
 1. A pivot table was created to investigate how the different outcomes were related to the months of the year. Specifically, the theater category was filtered. The data was also sorted in descending order. The final table is presented in the image below 
 2. A line chart was then created to visualize the data 

![image](https://user-images.githubusercontent.com/92636438/139605355-5301ad16-9c37-491b-be9e-bfc55d00a017.png)




### Analysis of Outcomes Based on Goals

This analysis counts the number of successful, failed and cancelled plays and arranges it according to funding goals. The following steps were utilized in analyzing the data:

 1. A range was created for the funding goal. The number of outcomes for ‘successful’, ‘failed’ and ‘canceled’ falling into each range was then counted. The Countifs() function in excel was utilized to do the analysis. As an example, the code used to count the number of failed plays in the range $20,000 to $24,999 is shown in the image below.
 2. The total number for each range was then calculated and percentage of each outcome within the different ranges were then calculated
 3. A line chart was constructed for the outcome based on goals
 
![image](https://user-images.githubusercontent.com/92636438/139605724-6b1b2dca-c016-408a-ab2a-27ae60f36cad.png)

![image](https://user-images.githubusercontent.com/92636438/139607076-3f62ccd6-3f4f-45d1-bbda-2f32c99f71ef.png)



### Challenges

The main challenge in completing the task was to accurately write the 'CountIFs' code. Since the range was constantly changing and or the outcome variable, then it wasn't a simple case of writting the code in the first cell then dragging the code/function. There was always one variable that needed to be updated. Still trying to figure out the more efficient solution

## Results

#### Theater Outcomes by Launch Date

![image](https://user-images.githubusercontent.com/92636438/164970561-09a8095e-01cf-4cd2-ae76-259d588f34c0.png)


Two conclusions that can be drawn about Theater Outcomes by Launch Date are:

  1. The probability of a successful outcome is highest during the period April to August, peaking in May.
  2. The number of failed outcomes is generally steady throughout the year, averaging around 41, and not necessarily affected by date. On the graph, this can be visualized from the line graph fluctuating only slightly around the count number 40. Additionally, one can observe that there is no distinct peak and or deviation when compared to the successful graph for one to conclusively state a time period to avoid to prevent failure. In addition, cancelled outcomes aren’t affected by date.

#### Outcomes Based on Goals

    (With reference to the Outcomes vs goal graph (see resources folder))
    
It can be concluded that in general, plays will be successful for funding goals less than $19,999. Further, the percent of success generally decreases as the funding goals increases. The opposite is true percent for failed outcomes; that is, the rate of failure generally increases as the funding goals increases. However, there is a funding goal between the approximate 35000 to 44999 range where the general pattern is not observed, and the percent of success is higher than failure. Noteworthy, cancellations are not dependent on funding goals

#### Recommendations

 1. It would be interesting to know the factors that influence cancellation so it may be worthwhile investigating outcomes (either as a count or %) against category (and or subcategory for a deeper analysis) and constructing a bar graph.
 2. Another factor which may have a significant impact on the outcome would be number of backers. So creating a table and or charting outcomes vs backers (possibly in a range) could be constructed.
 3. If Louise wishes to create a successful play, she should also consider the country. Investigating outcomes based on location and on specific categories should be done.
