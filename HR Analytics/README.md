 # **HR Analytics Report Between The Year Of 2011 to 2019**
 

This documentation provides comprehensive data on HR analytics, encompassing all employee-related activities on a yearly, quarterly, and monthly basis from 2011 to 2019. It includes comparative analyses to enhance clarity and understanding.
 
## **Analysis Process**:
 

After collecting data from three datasets: **Employee table**, **Department table**, and **Promoted Employee table**, we applied **data wrangling** techniques to **cleanse**, **transform**, and **modify** the data in line with our analysis requirements. Using primary keys and foreign keys, we established **relationships** between the tables, enabling a **smooth filter** path direction.

Additionally, we harnessed calculated columns and **measures**, employing **DAX (Data Analysis Expression)** to calculate employee experience, age, the total number of terminated employees, and categorized terminations as **voluntary** or **non-voluntary**. For **KPI (Key Performance Indicator)** presentations, we utilized Single cards.

![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/2f4c10da-13f9-46fe-be60-a6b7f03bdbde)

 
## **HR Dashboard Visualization**


![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/59b1613f-1d75-4f6d-a617-d52a17ed11b9)


![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/8958e15c-2bbc-4492-a14a-908e7ec75dbe)

**In the Left hand side we have Updated some filter slicer so as per Date Hierarchy, Department, Position,Employee Category, Manager we can filter the data which is available on all the pages.**




We created a column chart to analyze the number of employees as per age group, based on the dashboard that shows the data of **90** employees from **7** departments and **3** employee categories.


We created a pie chart to show the wholesome percentage department-wise distribution of employees, with **sales** having the largest share of **54.44%**, followed by marketing with **18.89%**, **IT** with **10**%, **HR** with **8.89%**, and **accounts** with **6.67%**.

We created a line area chart to analyze employee experience levels, ranging from fresher to 10 years. The chart shows that the highest number of employees have 7 years of experience (14 employees), followed by 5 years (13 employees) and 8 years (10 employees). The lowest number of employees have 10 years of experience (2 employees), followed by 9 years (6 employees) and 3 years (3 employees). Additionally, 6 employees have 1 year of experience, 4 have 2 years, and 8 have no prior experience.

 
We created a pie chart to show the gender-wise distribution of employees, with **male** having largest share **62.22%**,**Female** have **37.78%**


## Promoted Employee Dashboard:



![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/cd5bbe30-d23a-4913-b627-9e9a553222fe)




Out of **90** employees, **5** employees were promoted from the marketing department. In terms of gender ratio, there were **2** male candidates, accounting for **40**%, and **3** female candidates, accounting for 60%. All of them reported to **Phillip**, who managed both the **Marketing** and **Accounts** departments.

Of the **5** employees who were promoted, **3** employees were promoted in 2014, making up **60**% of the promotions, and **2** employees were promoted in **2012** and **2013**, each accounting for **20**% of the promotions for those respective years.

Considering position-wise promotion, **2** employees were promoted from the **account analyst** position, accounting for 40%. One employee was promoted from the **administrative analyst** position, making up **20**%, and one employee was promoted from the marketing **analyst position**, also at **20**%. Additionally, one employee was promoted from the personnel analyst position, contributing **20**%.

  we created a column chart for the education levels of the promoted employees. The chart shows that **2** employees have a **major**, **1** employee has a **bachelor’s degree**, 1 employee has a **doctorate**, and **1** employee has a **master’s degree**.

  

## Terminated Employees Dashboard:




![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/a1aeae83-0ed0-4549-b71b-dfcc3b4cf309)




If we observe the Terminated dashboard, we can see that out of **90** employees, **26** employees were terminated through **voluntary** and **non-voluntary** procedures between **2011** and **2019**.

If we consider the months between the years **2011** and **2019**, we can see that **January**, **June**, and **October** are the top **3** months with the highest number of employees who were terminated. The numbers for January are **6**, for February **4**, and for October **4**.

If we calculate the number of employees terminated by department, we can see that in the Sales department, out of **26** terminated employees, 13 employees were terminated, accounting for **50**% of the total. The remaining **50%** is distributed among all the other departments. In the **Marketing** department, **5** employees were terminated, representing **19.23%.** In the **IT** department, **4** employees were terminated, making up **15.38%**  of the total. In the **Accounts** department, **2** employees were terminated, accounting for **7.69%**. In the HR department, **1** employee was terminated, representing **3.85%.** Finally, in the **Legal** department, **1** employee was terminated, also at **3.85%**.

When we examine the gender-wise distribution, we can observe that **61.54%** of terminated candidates were **male**, while **38.46%** were **female** employees. Regarding position-wise terminations, out of the **26** employees, **19** employees were terminated from staff positions, constituting **73.08%** of the total. Additionally, **4** contractual employees were terminated, representing **15.38%**, and **3** trainee employees were terminated, making up **11.54%**.

When considering age groups, we found that the highest number of terminated employees fell within the **31** to **40** years age group, with a total of **10** employees terminated. The second-highest number of terminations occurred among employees aged **41** to **50**, with a total of **7**. For the **21** to **30** age group, **6** employees were terminated, while in the **51** to **60** age group, **3** employees were terminated.

 After careful consideration and taking experience into account in terms of terminations, we found that the highest number of terminated individuals, **8** in total, had **0** years of experience. **6** employees were terminated with **1** year of experience, and **3** employees were terminated with **2** years of experience. Additionally, **3** employees were terminated with **3** years of experience. Upon careful observation, we noticed that the termination rate is **inversely proportional** to experience; in other words, **more experience is associated with fewer terminations**.


 ## Point Of Analysis:
 

![image](https://github.com/github-aapmor/PowerBI-Reports/assets/149660927/f84bcd20-28b2-4aa1-8331-d60df288b6c6)


When comparing the terminated employees and promoted employees between **2011** and **2019**, we can clearly conclude that in the years **2016** and **2018**, the number of terminations was high. In both **2016** and **2018**, **5** employees were terminated. In **2012**, **4** employees were terminated, while in the marketing department, **1** employee was promoted. In **2014**, the number of terminated employees was the same as the number of promoted employees, which was **3**.


When comparing the terminated employees, promoted employees, and the total number of employees across **four quarters**, we can clearly conclude that the highest activity quarter is the **2nd quarter**. In this quarter, **26** employees were hired simultaneously, **9** employees were terminated, and **2** employees were promoted. In the **1st quarter**, **24** employees were hired simultaneously, **9** employees were terminated, and **1** employee was promoted. In the **4th quarter**, **24** employees were hired simultaneously, **6** employees were terminated, and **2** employees were promoted.



When examining the gender-wise comparison, it's clear that **16** male employees were terminated, while **10** female employees were terminated. The total number of promoted male employees was **2**, but for females, it was **3**. So, in terms of promotions, **female** employees **outnumbered** males, while in the case of terminations, more **male** employees were **affected** compared to female employees.

Out of the **26** terminated employees within the years between **2011** to **2019**, **11** employees resigned **voluntarily**, categorized as voluntary termination. The remaining **15** people were terminated due to company policies, categorized as **non-voluntary** termination. In the **sales** department, there were **6** cases of voluntary termination and **6** cases of non-voluntary termination. The second-highest in voluntary termination was the **IT** department with **3** cases, while in the case of non-voluntary termination, the **marketing** department had the highest number at **4**.




