### Analysis on the Relational Database - AdventureWorks2019 by Microsoft

#### This study is on the relational database of the fictitious company AdventureWorks created by Microsoft for analysis and visualisation purposes. For analysing the data we have used the tools SQL Server and Python. The preliminary data manipulation is done using SQL (Cleaning and Joining tables) and then combined with Python (Creating Views) and the secondary data manipulation and visualisation of the insights is done in Python (NumPy & Pandas).

#### With the use of specific data found in Adventure works the following have been analysed :

#### 1. Regional sales in the best performing country -
Based on the total Sales by country, US sales is 5 times higher than the other countries with the Southwest region of US topping in the case of revenue generated from sales. The best performing country is considered as US with a $25M sales and Southwest the best performing region in US with over $10M sales.

![image](https://user-images.githubusercontent.com/73156793/192147610-5b1c4611-bde1-4a9d-8934-dd5f5f18571b.png). 
![image](https://user-images.githubusercontent.com/73156793/192147631-9114391a-1578-43b2-9b7c-99361c4e1858.png).


#### 2. Relationship between annual leave taken and bonus -
There is a positive correlation between the two variables though weak. The correlation is shown using the correlation co-efficient.
![image](https://user-images.githubusercontent.com/73156793/192147804-126777bc-8348-4bc8-ae13-bdcb7d0863f8.png)

#### 3. Relationship between Country and Revenue - 
Though US has 5 times higher sales compared to other countries, a more granular look shows that if average revenue generated in relation to the number of stores in each country, UK can be considered as the best.
![image](https://user-images.githubusercontent.com/73156793/192147983-15a1d0d7-b05d-4e39-8315-69f23c2cba1c.png)
![image](https://user-images.githubusercontent.com/73156793/192147992-943c9666-1cf0-43e6-a66c-f7ea459eb98b.png)

#### 4. Relationship between sick leave and Job Title - 
There is no correlation between job title and sick leave taken but its interesting to note that more than 90% of the employees in the manager positions have more than 40 hours of sick leave and there is no one with less than 20 hours of sick leave.
![image](https://user-images.githubusercontent.com/73156793/192148678-7195f89b-bf38-47c7-a133-4555f7f27dd0.png)
![image](https://user-images.githubusercontent.com/73156793/192148696-12814d24-e467-4ad0-a061-91795243bf98.png)

#### 5. Relationship between store trading duration and revenue - 
The Average Revenue might not have direct causality with the age of the stores and are not dependent on one another.   But to make the data more insightful, a deeper digging is done to find the ‘number’ of store openings in a year on which our average revenue figure is based. And what is found is quite a revelation, a quick look at the US Economy growth between 1970 to 2001 highlights the trend observed where the store openings follows closely the growth and fall of the US Economy.The dips in store opening closely follows the Impact of economic crises across the US, for e.g., the 1973 Oil Crisis, Recessions during early 1990 and global recession of 2000 clearly visible. 
![image](https://user-images.githubusercontent.com/73156793/192149251-f5b3be60-6336-4113-a491-ca3ff6551826.png)

#### 6. Relationship between the size of the stores, number of employees and revenue - 
It is observed that increasing store size has no drop off in the rate of increase of revenue.The number of employees also appropriately increases in relation to the store size and revenue.
![image](https://user-images.githubusercontent.com/73156793/192149447-4cf49cc0-c4a0-41c8-88ff-8fbc5f18a3de.png)

