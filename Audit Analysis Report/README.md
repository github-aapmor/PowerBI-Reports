# Audit Reports For User Agent Login

This dashboard reflects user behavior when accessing the web. It contains information about controllers, actions, durations, start times, end times, and user agents.

## Data Source:
We collected the dataset from the **Kaggle** platform.



https://www.kaggle.com/datasets/gongetes/auditlog/

## Data Transformation:
After collecting the dataset using **MSSQL**, We stored it in a database. With the help of a '**With** **Clause**,' We calculated start time, end time, and duration by considering action time, storing these in a '**View**,' essentially a virtual table. Finally, using the SQL Server connector, We connected the View by writing a query in the advanced options of **Power** **BI** to **SQL**. There, We performed certain transformations.

## Dashboard Visualization:


![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/2d3a1b38-3848-4cc6-b5e4-912e4d544326)


With the help of a Donut Chart, We visually presented the time duration used by the controllers between the start time and end time. It's evident that **Pengiriman** consumed the highest amount of time at **27.2**%, followed by **Site** at **23.85**%, Loket at **20.35**%, **Penarikan** at **17.72**%, **Customer** at **10.6**%, and **Profile** with the least amount of time duration at 0.27%. Looking at the actual time in minutes, Pengiriman used 303,750 minutes, Site used 266,312 minutes, Loket used 227,225 minutes, Penarikan used **197,884** minutes, Customer used **118,400** minutes, and Profile used **3,070** minutes.

Utilizing an area chart, we visually represented the time duration (in minutes) used between the date range from **September 2022** to **June 2023**. Notably, there is a significant **trend** in time usage observed from 9th October 2022 to 16th December 2022, with 29th November marking **120,842** minutes and 11th October at **71,004** minutes as the peak durations.

In the year **2023**, January 30th recorded **94,440** minutes, and March 26th observed **123,475** minutes as the peak durations. To allow for a more detailed view, I've implemented a zoom slider enabling the examination of each segment within the date hierarchy.

We've identified **659** unique user agents controlled by **6** controllers, involving **15** actions in this web access process. As part of the analysis, we've visually presented the time duration used per user agent and the actions involved.
