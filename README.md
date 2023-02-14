# Sales-Report
Power BI is a unified and scalable self-service and enterprise business intelligence (BI) platform. Connect to and visualize any data, then effortlessly integrate the visualizaIntroductiontions into the programs you use every day.  Organizations can bring together data to analyze in seconds and reveal new insights with built-in AI capabilities.

**Introduction**

In the context of becoming a data analyst, Microsoft Excel isn't the only tool used for analysis and visualization; Microsoft Power Business Intelligence (Power BI) is also a crucial tool used by data analysts.

According to Wikipedia, Power BI is an interactive data visualization software application developed by Microsoft with a primary focus on business intelligence. It's a component of the Microsoft Power Platform. Power BI is a set of software services, apps, and connectors that work together to transform disparate data sources into cohesive, visually immersive, and interactive insights. Data can be obtained by reading directly from a database, a webpage, or structured files such as spreadsheets, CSVs, XMLs, and JSONs.

In addition to a desktop-based interface named "Power BI Desktop," Power BI offers cloud-based BI (business intelligence) services under the name "Power BI Services." It provides data warehouse functionality such as data preparation, data discovery, and interactive dashboards. Microsoft launched Power BI Embedded on the Azure cloud platform in March 2016. The ability to import bespoke visualizations is one of the product's key differentiators.

Power BI's original version was built on the Microsoft Excel add-ins Power Query, Power Pivot, and Power View. Microsoft also introduced many other features over time, such as Question and Answers, enterprise-level data integration, and security choices via Power BI Gateways. On July 24, 2015, Power BI was made available to the general public for the first time. It offers desktop, web, and mobile app versions, among others.

The following are key components of the Power BI ecosystem:
- Microsoft Power BI Desktop: The Windows desktop program for PCs and desktops is mostly used for developing and publishing reports to the Service.
- Microsoft Power BI Service: The internet service is SaaS-based (software as a service). This was previously known as Power BI for Office 365, but it is now known as PowerBI.com, or just Power BI.
- Mobile Power BI Apps:Power BI Mobile applications are available for Android, iOS, and Windows phones and tablets. (From Microsoft Power BI (2023, February 3)) Microsoft Power BI (https://en.wikipedia.org/wiki/Microsoft Power BI).

**IN THE DATASET**

During my training, I was given a financial data set to explore my data analysis skills using Power BI.In summary, the dataset consists of twenty-two (22) columns and over 5000 rows labeled as Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, and Profit Margin.

**CLEANING THE DATASET**

As previously discussed in my previous project, the importance of data cleaning cannot be overstated in order to achieve a suitable result upon visualization.My cleaning procedure in Excel comprises deleting blanks and duplicates and converting to a table with color formatting.

After launching my Power BI Desktop, which I downloaded from its website, I entered the data into the program using the acquire data option, where I can use power query to make some additional changes, such as grouping relevant columns together (such as location, city, state, region, post code, country, amongst other grouped columns), adding and deleting columns where appropriate, separating fact tables from dimension tables, identifying primary keys (i.e. the one with the lowest value in each group), and so on.

![Screenshot (251)](https://user-images.githubusercontent.com/124578882/218732046-033a9427-82ac-407b-9e3d-b5546b4b31df.png)
                                      Figure 1: fact and dimension table in Data view

After importing my dataset into Power BI, I was able to see the link between my fact table and dimension table using the model view.
![Screenshot (251b)](https://user-images.githubusercontent.com/124578882/218754081-526c4b20-de9d-4172-b5fd-ea8297952922.png)
Figure 2: Model view; Relationship between fact and dimension tables

**DATA ANALYSIS**

Since visualization is sometimes referred to as the "face of every study," a lot of work has been spent on it, including in terms of page formatting, visual formatting, visual layout, and many other areas.

**Front Page:**  This page includes the firm name, kind of report, and who developed the report, which was created using PowerPoint.
![Screenshot (264)](https://user-images.githubusercontent.com/124578882/218758548-eeacdd49-9d6a-4b4f-995c-55141587bd03.png)
Figure 3: Front page

 
**Overview page:**  This page displays total sales, total profit, the number of states, and product categories.
![Screenshot (255)](https://user-images.githubusercontent.com/124578882/218763119-f8e2cfa9-5ab6-4d5c-9088-bbfe4e7e7a9f.png)
Figure 4.1: Overview page

![Screenshot (256)](https://user-images.githubusercontent.com/124578882/218763466-a6fa286e-3c4d-4bed-8c46-c1b6edba9976.png)
Figure 4.2: Line chart & Bar Chart

![Screenshot (263)](https://user-images.githubusercontent.com/124578882/218763609-cfc2a3a9-f76a-4090-808c-715aa9165c76.png)
Figure 4.3: Pie Chart & Stacked Area Chart
