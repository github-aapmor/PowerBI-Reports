# **Telangana State Election Data Analysis For The Year 2014 and 2018** :
This Documentations is all about the Detailed election results for the year of **2014** and **2018** assembly elections in **Telangana State** Includes: All candidates vote share, votes and voters for each constituency and candidate along with Party and their respective vote share Percentages.

## **Data Source** (Domain: Electoral):
We have obtained this electoral data from the **Open City Urban Data Portal** for analysis purposes, which is an open platform.

**https://data.opencity.in/dataset/telangana-assembly-elections-2018**



**https://data.opencity.in/dataset/telangana-assembly-elections-2014**

![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/0ad45939-f5cd-4291-b191-1b997caa2752)


## Analysis Process:
After importing the dataset with the help of Power Query, We performed data **cleansing**, data **wrangling**, data **modification**, data **transformation**, data **manipulation**, and **Data Modeling** as per the requirements to draw appropriate conclusions. We achieved this by using calculated **measures**, calculated columns, and **DAX (Data Analysis Expressions)**. Additionally, We created **relationships** between tables by utilizing primary keys and foreign keys. For visualization, We used various charts and value cards for **KPI presentation(Key Performance Indicator).**

In this analysis process, We have included a total of 119 constituencies. we have used three separate dashboard pages for displaying the data visualizations for the **2014** and **2018** elections. In another dashboard, We compared both datasets, showing constituency-wise votes, vote share, along with party-wise votes and vote share percentages for better clarity. This allowed us to identify the leading party with a significant vote share percentage within each constituency and by party.

## Visualizations For the Year 2014:

![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/c202b80d-9e1a-4bb0-a7db-8a29625c980e) 

•	In the **2014** election dashboard, with the help of a single card, We visualized that **68** different parties participated with **1664** individual candidates across **3** constituency categories. Out of **28** million people, **19** million individuals participated in this assembly election as electors to support their respective parties across **119** constituencies.

•	In terms of gender-wise participation, **92.01%** of male candidates participated, whereas only **7.99%** of female candidates took part in this assembly election. If we look at the numbers, there were **1531** male candidates, while female candidates numbered **133**.

•	If we consider the constituency type or category to segregate candidate participation, we can clearly see that out of the total number of candidates, which is **1664**, **1312** participated under the **General** Category, accounting for **78.61%**. There were **230** candidates who participated under the **SC** category, representing **13.78%**, and 127 candidates participated under the **ST** category, with a percentage of **7.61%**.

•	In the accounting of constituency-wise total number of votes, **Lal Bahadur Nagar** is the top leader with **7,274,708** votes and falls under Rangareddy District. **Kukatpally** is the second most leading constituency with **6,734,931** votes and is located in **Hyderabad** District, while **Quthbullapur** is the third top leading constituency with **6,679,614** votes under the **Medchal-Malkajgiri** district. This vote share comparison is visualized by constituency with column Chart.

•	Using a customized map and the available data, this visualization illustrates the vote share of **119** constituencies across 10 districts, sourced from the **Open City Urban Data Portal**.

The color gradient represents the vote share among all 10 districts based on the number of constituencies. 
•	With the slicer, we can filter by Constituency Name, Party Name, and District Name. This allows us to visualize our data based on the selected filters


## Visualization For the Year 2018:



![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/70928e4f-0763-4d57-9089-164e3240c506)


•	In the **2018** election dashboard, with the help of a single card, We visualized that **92** different parties participated with **1816** individual candidates across 3 constituency categories. Out of **28** million people, **20** million individuals participated in this assembly election as electors to support their respective parties across **119** constituencies.


•	In terms of gender-wise participation, **92.2%** of male candidates participated, whereas only **7.69%**  of female candidates took part in this assembly election. In terms of numbers, there were **1679** male candidates, **140** female candidates, and 1 candidate in the **'Other Gender'** category. Only one candidate from the **'Other Gender'** category participated in the **2018** assembly election.


•	If we consider the constituency type or category to segregate candidate participation, we can clearly see that out of the total number of candidates, which is **1664**, **1447** participated under the **General** Category, accounting for **79.46%**. There were **234** candidates who participated under the **SC** category, representing **12.85%**, and **140** candidates participated under the **ST** category, with a percentage of **7.69%**.

•	In the accounting of constituency-wise total number of votes, **Malkajgiri** is the top leader with **8,798,958** votes and falls under **Medchal-Malkajgiri** District. **Lal Bahadur Nagar** is the second most leading constituency with **8,551,445** votes and is located in **Rangareddy** District, while **SerelingamPally** is the third top leading constituency with **8,114,345** votes under the **Rangareddy** district. This vote share comparison is visualized by constituency with column Chart.


## Point Of Analysis:




![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/54355e16-7447-4e08-9fd0-7b90a80cfdff)





If we compare the **sex ratio** participation between **2014** and **2018**, we can observe an increase in candidate participation from **2014** to **2018**. In addition to **male** and **female** candidates, candidates from the **'Other Gender'** category also participated in **2018**. Looking at the numbers, we see that the percentage of male candidates increased from **92.01%** to **90.2%**, while the percentage of female candidates decreased from  **7.99%**  to **7.69%**. The 'Other Gender' category increased to 0.11%.


In **2014**, **68** parties participated, and in **2018**, **92** parties participated. If we consider these parties together, we can observe that the top **5** parties are **TRS**, **INC**, **TDP**, **BJP**, and **IND**. **TRS** is the top party with the highest number of elector supporters in both **2014** and **2018**. In **2014**, it had **6.6** million supporters, and in **2018**, it had **9.7** million.


We have also visualized the top **5** constituencies with a valid number of votes by combining the **2014** and **2018** data. We visualized the candidates with vote share percentages between **2014** and **2018**.


After careful consideration, we have determined that **Lal Bahadur Nagar**, **Malkajgiri**, **Uppal**, **Serilingampally**, and **Quthbullapur** were the top **5** constituencies when we calculated their vote share for the years **2014** and **2018**. Now, let's take a closer look at the number of votes in each of these constituencies:

In **Lal Bahadur Nagar** constituency, there were **7,274,708** votes in 2014 and **8,551,445** votes in **2018**.
**Malkajgiri** constituency had **5,308,929** votes in **2014** and **8,798,958** votes in **2018**.
**Uppal** constituency recorded **6,100,245** votes in **2014** and **7,976,465** votes in **2018**.
**Serilingampally** constituency had **5,941,824** votes in **2014** and **8,114,345** votes in **2018**.
**Quthbullapur** constituency received **6,679,614** votes in **2014** and **5,787,360** votes in **2018**.
This data reflects the vote share and the number of votes in these constituencies for the years **2014** and **2018**.








