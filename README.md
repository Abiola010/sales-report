**Sales-Report** 

Assuming a Sales manager or analyst was asked to present to senior management, stakeholders, or other relevant parties a sales report relating to a company’s sales performance. The purpose of the report presentation is to provide a overview of the sales data, highlight trends and patterns, identify areas of improvement, and make recommendations for future sales strategies.

**Introduction**

In the context of becoming a data analyst, Microsoft Excel isn’t the only tool used for analysis and visualization; Microsoft Power Business Intelligence (Power BI) is also a crucial tool used by data analysts.

Power BI is an interactive data visualization software application developed by Microsoft with a primary focus on business intelligence. It’s a component of the Microsoft Power Platform. Power BI is a set of software services, apps, and connectors that work together to transform disparate data sources into cohesive, visually immersive, and interactive insights. Data can be obtained by reading directly from a database, a webpage, or structured files such as spreadsheets, CSVs, XMLs, and JSONs. (From Microsoft Power BI (2023, February 3)) Microsoft Power BI

**IN THE DATASET**

During my training, I was given a financial data set to explore my data analysis skills using Power BI. In summary, the dataset consists of twenty-two (22) columns and over 5000 rows labeled as Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, and Profit Margin.

**CLEANING THE DATASET**

As previously discussed in my previous project, the importance of data cleaning cannot be overstated in order to achieve a suitable result upon visualization. My cleaning procedure in Excel comprises deleting blanks and duplicates and converting them into a table with color formatting.

After launching my Power BI Desktop, which I downloaded from its website, I load the data into the application program using the get data option, where I can use power query to make some additional changes, such as grouping relevant columns together (such as location, city, state, region, postcode, country, amongst other grouped columns), adding and deleting columns where appropriate, separating fact tables from dimension tables, identifying primary keys (i.e. the one with the lowest value in each group), and so on.

![image](https://user-images.githubusercontent.com/124578882/222845029-d70a9bab-98fc-4ae3-92c9-a1b7d1dc751a.png)
Figure 1: fact and dimension table in Data view

After importing my dataset into Power BI, I was able to see the link between my fact table and dimension table using the model view.

![image](https://user-images.githubusercontent.com/124578882/222846498-87ac1989-ba95-4abd-b2ee-219c4f0d0b1c.png)
Figure 2: Model view; Relationship between fact and dimension tables

**DATA ANALYSIS**

Since visualization is sometimes referred to as the “face of every study,” a lot of work has been spent on it, including in terms of page formatting, visual formatting, visual layout, and many other areas.

Overview page: This page displays total sales of over two million with total profit of over two hundred thousand from forty nine states, on three product categories.

![image](https://user-images.githubusercontent.com/124578882/222846964-31c63597-95b8-49fa-99df-611899ff78c1.png)
Figure 3: Overview page

Regional Discount: Customers from Central region were given more discount, those in the Eastern, Western and Southern region follows.
![image](https://user-images.githubusercontent.com/124578882/222847105-a6a7b3ad-9147-4666-8028-7ffe554b992e.png)
Figure 4: Discount by Region in Bar chart

Categorical Profit: The goods sold were categorized into three; Technology, office supplies, Furniture with 50.79, 42.77 and 6.44 with profit percent respectively.
![image](https://user-images.githubusercontent.com/124578882/222847182-404d2901-92e5-46c6-a493-6b28601feb22.png)
Figure 5: Profit by Category on Pie Chart

Sub-Categorical sales: Goods sold were sub-categorized into different sections. Phones, Storage, Binders, Furnishings and Papers with over 300K, 200K,90K and 80K sales respectively were the top 5 selling goods.
![image](https://user-images.githubusercontent.com/124578882/222848054-5f01dc1f-e79a-482b-98fc-aaeac90e2f12.png)
Figure 6: Top 5 Sub-categorical sales in bar Chart

Regional Supply: About more than 50 percentage of the quantities were supplied to the west.
![image](https://user-images.githubusercontent.com/124578882/222848271-ed4dcf0d-3977-44f7-bc58-7f1ba5fea0b9.png)
Figure 6: Regional Supply on Stacked Area Chart

Profit by City: New York city, Los Angeles, Seattle, San Francisco and Detroit took the lead of the cities by profit.
![image](https://user-images.githubusercontent.com/124578882/222848344-21d11f83-7a80-43a6-8235-8ae83198206b.png)
Figure 7: Total profit made by city on Stacked Area Chart

Recommendations: More discount offers should be allocated the western customers so as to boost sales although they get more supplies which is also a go of making more sales

![image](https://user-images.githubusercontent.com/124578882/222848474-c7928a33-fecf-4a30-8317-71648b04dc84.png)

In summary, Being in a 21st Century, technology especially phone had shown that it can be a front-line for other products by making about 33,000 sales. About 20.5% profit was made in the west, particularly in New York city, even with less quantity supplied.
