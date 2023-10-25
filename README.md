# ANALYSIS REPORT ON EDGELINE CALL CENTRE

# INTRODUCTION

The dataset is for the analysis on the customer behavior, to measure agent’s performance, and pattern overtime. A Call Centre is a managed capability that can be centralized or remote that is used for receiving or transmitting a large volume of enquiries by telephone.

# ABOUT THE DATA/DATA COLLECTION

It is a structured data, and it is a secondary data collected. The data contains a table in csv files. It contains 5000 rows and 13 columns. The dataset was given by Ganiyat Olajumoke Ajala
The analysis to be carried out is to answer the following questions;
1.	What is the proportion of the resolved complaint to the unresolved?
2.	What is the total speed of answer in seconds by each of the agents?
3.	What is the total satisfaction rating per calls?
4.	What are the average talk minutes for each topic?
5.	What are the total calls made from January to March?
6.	What is the total call made and the average talk minutes by agents?

# TOOLS

The tool used is Microsoft Power bi for analysis and using power query editor for data cleaning.

# DATA CLEANING AND TRANSFORMATION

The following are the different cleaning procedures;

•	The data contained blanks and duplicates which was removed

•	Added column to insert time for average talk duration and also inserted minutes

•	Added column to insert time for Time

•	Renamed the added columns average talk duration and Time. 1

•	Inserted Day of week to get the day name and also extracted the first three characters

•	Sorted the Day name

•	Replaced the value Y to Yes and N to No for both columns answered and resolved.


# EXPLORATORY DATA ANALYSIS(EDA) AND INSIGHT

For the analysis to be understood and the questions to be answered pivot tables were created for it to properly analyzed for insights. The following consist of questions, its analysis and insight for each;

1.	What is the proportion of the resolved complaint to the unresolved?

Average talk minutes for YES (11841) was higher than NO (1315), In other words, the percentage of the Resolved complaint was higher than the unresolved complaint with 90% and 10% respectively.

                       
A Donut chart was used to show the difference as a visualization

2.	What is the total speed of answer in seconds by each of the agents?

At 35717, Martha had the highest Speed of answer in seconds and was 13.14% higher than Stewart, which had the lowest Speed of answer in seconds at 31570. Across all 8 Agent, Speed of answer in seconds ranged from 31570 to 35717.

 
A stacked bar chart was created to show the Speed of answer in seconds by each of the agent from the highest six to the lowest six.


3.	What is the total satisfaction rating per calls?
The total satisfaction rating ranges from highest with value 1218 to the lowest with value 396. The satisfaction rating ranges from 1 to 5 as the X- axis and the count of call id. The lowest satisfaction rate was 1 and 2 with value 417 and 396 respectively in other words the customer was satisfied above average.

                   

A stacked column chart was created to show to show the relationship of the total satisfaction per calls.

4.	What are the average talk minutes for each topic?

In terms of topic the average talk minutes it shows that the average talk minutes are relatively close amongst the topic. These topics includes; streaming, admin support, technical support, contract related and payment related with 21%, 19.9%,19.86%,19.7% and 19.22% respectively can be seen are closely related in percentage with payment related issue being the highest with 21%.

 
         A Donut chart was used to show the difference as a visualization


5.	What are the total calls made from January to March?
The total calls for January was 1772, February was 1616 and for March was 161. There was drop in calls from January to February but a bit of stagnant amount of calls in from the month February to March.
                                     
The Line chart was created to show the trend in the number of calls from January to March.

6.	What is the total call made and the average talk minutes by agents?

To summarize the average call minutes and the total calls received by each of the agents, a table was created as a visualization tool.

 

# RECOMMENDATION

There is a drop in complaints from January to February. Maintaining consistency in the communication method that contributed to this drop is a good idea, as it may have been more effective in resolving issues or reducing complaints. Here are some steps you can consider taking:

•	Identify the effective communication method: Review the communication channels, processes, or strategies that were used in February when the drop in complaints occurred. Determine which specific actions contributed to this decrease.

•	Analyze the reasons behind the drop: Try to understand why complaints decreased in February. Were there specific changes, improvements, or initiatives that played a role in this reduction?

•	Consistency in communication: Continue using the effective communication method and ensure consistency in its implementation. Ensure that all team members are on the same page and understand the importance of maintaining this consistency.

•	Monitor results: Keep a close eye on complaint levels in the following months. If the drop in complaints is maintained or further reduced, it's a positive sign that your strategy is working.

•	Investigate unresolved complaints: Address unresolved complaints from previous months. These complaints may indicate areas where improvement is needed. Investigate the root causes of these unresolved issues and work to resolve them.

•	Solicit feedback: Encourage customers or clients to provide feedback on the communication process. This can help you identify areas for improvement and ensure that their concerns are being addressed effectively.

•	Continuous improvement: Make an ongoing commitment to improving the customer experience and addressing complaints promptly. Regularly review and update your communication methods and strategies to adapt to changing circumstances and customer needs.

•	Remember that consistency in communication is just one part of the equation. Addressing unresolved complaints and continuously improving your processes are also essential to maintaining a high level of customer satisfaction

