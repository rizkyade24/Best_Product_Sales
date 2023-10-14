# Best_Product_Sales

I have performed a comprehensive Exploratory Data Analysis (EDA) on product sales data. Your first step is to ensure that the data is clean and ready for processing, including addressing missing, duplicate, or invalid data. Then, you prepare the working environment by importing the necessary Python libraries such as Pandas, NumPy, and Matplotlib.

After that, I start the EDA process by examining the structure and content of the data, understanding the summary descriptive statistics, and creating data visualizations such as histograms and scatter plots to see sales distributions and patterns. Next, you perform correlation analysis to understand the relationships between variables.

During the EDA process, I also make feature additions by creating new columns for the month, day, and day of the week of the sale date. In addition, you clean up the data by removing columns that do not provide useful information, such as columns without names.

I analyzed the performance of specific products such as S-P3 and Q-P1, noting that S-P3 generated the most revenue, even though Q-P1 had higher unit sales. Next, you identify 2016 as the year with the highest revenue and note that peak revenue occurred on Fridays and Saturdays.

Lastly, I observed the pattern of sales and revenue during the month of October, where unit sales and revenue peaked. Overall, you've done a great job analyzing the data.

**Insight**

1. Added columns month, day and day of the week and changing the dtype of date from object to datetime64 through feature engineering.
2. Drop columns unnamed as it was not providing any usefull information.
3. S-P3 has gained the most revenue but the unit sale of Q-P1 is more.
4. In 2016 most revenue most revenue generated and on fridays and staurdays most revenue generated.
5. On Weekdays and weekend the S-P3 has the highest revenue whereas on weekend and weekday the Q-P1 has more unit sales.
6. In month of October unit sale and revenue was at peak.
