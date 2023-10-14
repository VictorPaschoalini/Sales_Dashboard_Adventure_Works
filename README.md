# Sales_Dashboard_Adventure_Works
The sales dashboard used the Adventure Works database, SQL to clean and select the data, and Power BI to make the dashboard.

The idea of the project was to make a classic sales dashboard, widespread in many companies and a reliable tool for making operational and strategic business decisions.

The database used was Adventure Works by Microsoft, a free complete base distributed by the company for people to try their software.
The steps used in this project were:

1) Data gathering and dashboard planning
2) Data cleaning and preparation (using SQL)
3) Making the dashboard (Power BI)

## 1) Data gathering and dashboard planning

The data is available at https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms
The data for the budget was made up for illustration purposes only.

To connect to it and use it I used Microsoft SQL Server Management Studio (full tutorial on how to make the connection on the link passed).

With the data at hand, the next step was to see what information I had, and how to best present it in the dashboard, I decided to use the Internet Sales Fact Table as the main data source.
Some dimension tables that would give good explanations/filters to the Internet Sales data were Calendar, Customers, and Products, so I decided to use them as well.

Now that I decided what data tables I would use, I created a first draft of how the final dashboard would look (using pencil and paper).

## 2) Data cleaning and preparation (using SQL)

The dataset was very clean and ready to use, I mainly used SQL to select what columns would be useful and do some data cleaning and transformation. 

Here are some snippets of the SQL queries used (also available in the git repo):

![image](https://github.com/VictorPaschoalini/Sales_Dashboard_Adventure_Works/assets/132787045/95e99f28-d733-4160-a606-4676fce1bf71)
![image](https://github.com/VictorPaschoalini/Sales_Dashboard_Adventure_Works/assets/132787045/2ef73b67-a56f-48c5-af9d-5c7a4a9699fe)

## 3) Making the dashboard (Power BI)

With the tables ready (all the data transformation needed was done in SQL), the only step left was to make the connections in Power BI and make the dashboard.

Here is the data model with all the connections between the tables:

![image](https://github.com/VictorPaschoalini/Sales_Dashboard_Adventure_Works/assets/132787045/eeeae38c-caf3-4533-ad91-b61b1013b17e)

Here are some snippets of the dashboard (also available in the git repo):

![image](https://github.com/VictorPaschoalini/Sales_Dashboard_Adventure_Works/assets/132787045/c0fb2f36-c85a-4d48-80b8-40239cc7ef3b)

![image](https://github.com/VictorPaschoalini/Sales_Dashboard_Adventure_Works/assets/132787045/b02ac96c-9f8b-4f5b-82e5-ca9cea167350)

![image](https://github.com/VictorPaschoalini/Sales_Dashboard_Adventure_Works/assets/132787045/c24d7af5-4376-4a77-8e34-fe2114d2d322)



