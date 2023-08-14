# PwC-Call-Centre-dashboard
PwC Power BI Virtual Case Experience Task 1- Call Centre Analysis and Dashboard

## Problem Statement:
In this project, I have created a dashboard in Power BI for the call centre manager that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset.

Possible KPIs include (but are not limited to):
1. Overall customer satisfaction
2. Overall calls answered/abandoned
3. Calls by time
4. Average speed of answer
5. Agent’s performance quadrant -> average handle time (talk duration) vs calls answered

## Dataset:
The dataset used for this task was presented by https://www.theforage.com

## Data Cleaning/ Preparation:
1. The data consists of over 5000 rows and 16 columns.
2. Cleaned the data in Excel and Power BI.
3. Changed the datatypes of certain columns.
4. From the time column, created the time of day column which reflects the number of calls at a specified time of the day such as afternoon, morning or evening.
5. From the average talk duration, the duration was calculated in secs and minutes separately.
6. The speed of the answer was calculated in minutes as well for consistent data.
7. The month name and weekday are extracted for further analysis.
8. Replaced Y/N with Yes/No for better readability.
9. Sorted the month and week in charts using the daynum and monthnum columns.
10. Various Dax Measures were created beforehand like Average satisfaction rating, average speed of answers in minutes/seconds, Total calls etc.

## Questions to be answered:
1. Important Overall metrics like :
   i. Total Calls
   ii. Average Speed of Answer in mins
   iii. Average talk duration in mins
   iv. Average Satisfaction rating and target rating
2. Agent statistics like totals calls, total resolved calls, answered calls, satisfaction ratings etc
3. What time of day received the maximum number of calls?
4. What was each month's stat ie calls answered- Yes and no?
5. What was the total number of calls answered and resolved?
6. What day of the week receives the most calls? 

![screencapture-file-C-Users-ADMIN-Documents-Call-Center-Trends-pdf-2023-08-07-15_52_51](https://github.com/rasikasalvi4801/PwC-Call-Centre-dashboard/assets/72073065/ad8a2e85-89b5-43f4-bbed-e99744a5b463)

## Insights :
1. The dashboard is filtered by various columns like agents, months and calls by topic.
2. The total calls made in the 3 months are 5000 and the average satisfaction rating is around 3.40 whereas it should be around 4.5 for most customer satisfaction.
3. The average satisfaction rating has decreased over the three months.
4. The average speed of answer of all agents is around 1.1 minutes and the average talk duration is around 3.75 minutes.
5. As we can see, the afternoon is the time of the day which receives the most calls followed by morning time and the least evening. The evening is the least because the workday ends at 6 and after that no calls are received and the evening time is considered from 5-6 pm only.
6. Out of all three months, January received the most calls(1772) and around 82.1% were answered and 17.8% were not answered. That was most probably because January month had the highest number of issues which were resolved (~74%) and which can be seen because February and March had fewer calls.
7. Out of the total calls only 73% are resolved over the three months and 27% remain unsolved.
8. Streaming and technical support were the topics for which the most calls were received(~21%) followed by payment-related issues(20%).
9. Monday and Saturday were the days where most calls were recorded followed by Thursday.
10. Becky has the quickest average speed of answer (1.09 mins) whereas Joe is the agent who answers late(1.18 mins) because of which the average satisfaction rating of Joe is the lowest (3.33) and Martha has the highest satisfaction rating(3.47).
11.  Jim received the highest number of calls where he answered ~81% of calls and resolved ~73% of calls.

## Recommendations: 
1. The decreasing customer satisfaction rating should be analysed because compared to the January performance both months received almost the same performance but then why the satisfaction rating decreased? Were the issues not resolved properly?
2.  The average speed of the answer should be decreased because 1.1 minutes to answer is on the higher side.
3.  The streaming and technical aspects of the business should be analysed properly because they received the highest number of calls.
4.  Certain benefits/incentives can be provided to employees who get the highest satisfaction rating or depending on other factors like most reloved or most answered every month.
5.  The resolve rate should be increased which will lead to a higher satisfaction rate eventually.
