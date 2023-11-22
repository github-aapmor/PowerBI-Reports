# Audit Log Dashboard

This dashboard provides information on the number of tickets raised, their current states, the duration for completing each ticket, year-wise ticket distribution, and details about the individuals who resolved the tickets.

# About Data
We collected the dataset from the Kaggle platform.

https://www.kaggle.com/datasets/vipulshinde/incident-response-log?select=incident_event_log.csv

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

![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149667836/797c635a-33e8-4e03-bab1-57b95445a4af)

I created a donut chart to visualize how tickets were reported. Phone type reports dominated, occupying 99.9%, while email type reports constituted a minor percentage at 0.1%.

Additionally, another donut chart was generated to represent notify generated for the tickets. In this chart, phone type notifications occupied 99.9%, with email type notifications accounting for the remaining 0.1%.

I created bar charts to visualize the distribution of the top symptoms among the total number of tickets. The representation is as follows:

Symptom 541, occupying 57.89%.

Symptom 161, accounting for 15.78%.

Symptom 567, constituting 15.79%.

Symptom 590, making up 5.26%.

Symptom 599, representing 4.89%.

used bar chart to depict the distribution of the top countries within the overall ticket count. The representation is as follows:

• Country 29, occupying 39.39%.

• Country 239, accounting for 33.33%.

• Countries 164, 53, and 89, constituting 9.09%.





![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149667836/a73ca6b4-f308-4da2-94a7-17cace01ea88)


I created three donut charts based on the total number of tickets, each representing different categories: urgency, impact, and priority.

Urgency Category:

Medium urgency tickets occupy the majority at 94.63%.
Low urgency tickets account for 2.62%.
High urgency tickets represent 2.75%.
Impact Category:

Medium impact tickets dominate with 94.74%.
Low impact tickets constitute 2.85%.
High impact tickets make up 2.41%.
Priority Category:

Medium priority tickets cover the highest proportion at 93.34%.
Low priority tickets comprise 2.96%.
High priority tickets represent 2.33%.
Critical priority tickets make up 1.53%.


I generated a comprehensive table providing detailed information about each ticket. The table includes the following fields:

Ticket Number: A unique identifier for each ticket.

Ticket Type: The category or type of the ticket.

Assignment To: The individual or department responsible for handling the ticket.

Opened At: The date and time when the ticket was initially reported or opened.

Resolved By: The entity or individual responsible for resolving the ticket.

Resolved At: The date and time when the ticket was successfully resolved.

Priority: The level of urgency or importance assigned to the ticket.

Closed At: The date and time when the ticket was officially closed.

Duration Per Closed Ticket: The time taken to resolve and close each ticket.











