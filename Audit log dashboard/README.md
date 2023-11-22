# Audit Log Dashboard

This dashboard provides information on the number of tickets raised, their current states, the duration for completing each ticket, year-wise ticket distribution, and details about the individuals who resolved the tickets.

# About Data
We collected the dataset from the Kaggle platform.

# Data Transformation:

After collecting the dataset from the Kaggle website, we utilized MSSQL to store it in a database. Subsequently, in MSSQL, we performed transformations such as changing columns with "?" to "N/A" and calculated the duration using the "opened_at" and "closed_at" date columns. Finally, employing the Import mode method from Power BI to SQL Server, we executed additional transformations on the data.

Post-transformation, DAX (Data Analysis Expressions) was employed to create new columns and measures for the purpose of conducting a comprehensive analytical analysis.

# Dashboard 

![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149667836/0a89f2ae-ccfb-4d09-8e03-278461c88d92)

A card visual was employed to present the following metrics: the total number of incidents was 120K, reassigned incidents totaled 138K, sys_mod_incidents amounted to 624K, and there were 2523 reopened incidents.

Using a Column chart, we illustrated the ticket counts based on their respective ticket types. The chart reveals that the "Active" state had 33.58K tickets, "New" tickets totaled 30.32K, "Resolved" tickets stood at 21.50K, "Closed" tickets amounted to 20.83K, while "Awaiting User Info" accounted for 12.88K, "Awaiting Vendor" tickets were 0.56K, "Awaiting Problem" tickets were 0.40K, and "Awaiting Evidence" tickets were 0.02K.

The average time for completing a ticket was 18 days, and I created a column to represent the average time taken for each ticket state. Specifically, tickets in the "Awaiting Evidence" state took an average of 193 days, "Awaiting Vendor" tickets took 135 days, "Awaiting Problem" tickets took 41 days, "Active" tickets took 19 days, "New" tickets took 16 days, and "Resolved" and "Closed" tickets took an average of 14 days.

I employed a column line chart to visualize reassigned and reopened tickets based on their ticket states. The reassigned tickets were represented using a column chart, while the reopened tickets were depicted with a line chart. It was observed that the "Active" state had the highest number of tickets across all states, while "Awaiting Evidence" had the lowest count.

Line chart to illustrate the number of tickets year and month-wise. It was evident that March of the year 2016 had the highest count, totaling 57.96K tickets, while May of the year 2017 marked the lowest count with 0.03K tickets.









