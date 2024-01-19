# Cohort-analysis
Cohort analysis is a type of analysis that focuses on understanding the behavior of a group of individuals who share a common characteristic over a specific period. The individuals in a cohort typically share a common characteristic or experience during a particular time frame, such as the month they joined a service, made their first purchase, or started using a product.

In this data analysis project, the user engagement of new and returning users over every week was inspected. The dataset was loaded, explored for any inconsistencies, datatype mismatch, missing values etc. before doing exploratory data analysis. Correlation matrix and heatmaps were plotted to visualize the kind of relationship that exist between new users vs returning users, duration day 1 and day 7.

### Dataset
The dataset consists of 30 rows and 5 columns. \
Column 1: Date\
Column 2: Number of new users\
Column 3: Number of returning users\
Column 4: Duration Day 1 (in seconds)\
Column 5: Duration Day 7 (in seconds)

### Insights
1.Average 'New users' and 'Returning users' across each day was found to be significantly different from each other as their mean and standard deviation were not overlapping each other.This shows that the number of New users was found to be significantly greater than the number of returning users every week.\
2.Positive correlation exists between New users and Returning users. This indicates a potential trend of new users converting to returning users.\
3.There seem to be no significant difference between the average user engagement on day 1 and day 7 when investigated across every week. Also there exist poor relationship between the user engagement on Day1 and Day7

