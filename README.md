# Business-Insight-360



Problem Statement: 
-----------------

AtliQ Hardware is a consumer goods electronics company having operations in various countries. Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights. Also due to the lack of effective analytics the company faced a major loss in Latin America. Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work.

Objective:
---------

A dashboard considering different sections such as Finance view, Sales view, Marketing view, Supply Chain, Executive View such that stakeholders can unlock insights and enable data driven decision making.


.

### The Document further will be elaborated in terms of Overall picture of each View/department dashboard follwed by the description. Further key Insights from Each View are illustrated.

.

Home Page
---------

![Home Page](https://user-images.githubusercontent.com/78613343/227519364-04fb1853-7b05-48a7-90ee-99d62435fd75.png)

.

Navigation to each View is enabled through icons provided along with the tool tip when hovered on it. Also a Dynamic data refresh Date is provided to have knowledge about latest data refresh.

.


Problem Statement
-----------------

![Problem statement1](https://user-images.githubusercontent.com/78613343/227520891-bd2d6c87-7af2-4c56-b654-0d6dcc78e562.png)

.


Finance View
------------

![Finance View](https://user-images.githubusercontent.com/78613343/227523117-64cf117f-fbfe-4df7-8346-865de95595d3.png)

.

To Summarize P&L statements and monitor Net sales, gross margin and net profit with respect to regions, customers and products.
-	 In the present finance view we have 3 scorecards for key metrics like Net sales, gross margin % and Net profit percentage.
-	 A table viewing the P&L statement having values of selected year, benchmark value ( LY / Target), Chg between both in dollars and in percentage. 
-	A line chart showing the performance trend of each P&L Values over time considering the fiscal year. The fiscal year of the company starts from September and ends in August. 
-	Two matrix visuals have been included to view top and bottom customers and products with respect to the selected P&L value.

.



Sales View
------------

![sales View](https://user-images.githubusercontent.com/78613343/227524211-b9d43911-e55b-4228-b477-9d87a73e14fd.png)
.

Sales department is focused on the Net sales achieved and the gross margin received from the sales done with each customer also considering the product sales.

-	A table visual with customers and a matrix visual consisting Products with key metrics Net sales, Gross margin and the gross margin % is shown on the left
-	To the right of the dashboard, we have a Scatter chart showing different quadrants with respect to Net sales on X-axis and Gross margin % on Y-axis. This visual lets us know the market’s & customer’s growth in terms of the metrics giving a detailed understanding of the growth stage of the business.
-	The slicer lets us know the customers whose gm variance % is greater than or equal to the value we have set in the slicer. 
-	Below to the Quadrant scatter visual made we have two donut charts one representing the amount of post and pre-Invoice discounts are provided to obtain a certain number of Net sales. And the next donut chart shows the Gross margin obtained from the Net sales and the Total cost of goods sold to receive the gross margin. Thisinsight can be seen for each customer.


.


Marketing View
------------

![Marketting View](https://user-images.githubusercontent.com/78613343/227524920-02089cc1-a8d0-47bd-b4cf-7dae0de74b70.png)
.

Marketing view FOCUSES ON PRODUCTS, running ads and doing marketing for those products. This section will focus on Net Profit because they should not spend much on marketing so that net profit does not impacting. 


Matrix visual:
 
- Key metrics like net profit and net profit% along with net sales and gross margin are analyzed in terms of products and market which are drilled down to sub categories further individually.

Scatter plot: 
 
- Where gm% and np% are provided on y axis which can be switched according to the analysis requirements. 
On x-axis, Net sales is shown.
segment, category and value are taken as values which show the bubbles which can be drill down and up, division as legend, gm% as tool tip (hovering mouse will show this value), NS as size of the bubble.


Donut chart:
-	Gross margin and the total cogs costs are shown.

Note:
-	Net profit, gm and the operational cost are to be shown but net profit is in negative value so we are using waterfall chart to show that.

Waterfall chart:


-	This chart shows the amount of gross margin received from total net sales and the operating cost. Also it shows the net profit obtained.

.

Supply chain  View
------------

![Supply chain View](https://user-images.githubusercontent.com/78613343/227525642-02e4c17c-f97f-43db-be04-bd6a913e0edb.png)
.

supply chain team will make sure that there is enough inventory in the manufacturing to meet the demand.
Clustered Column Chart:
-	Shows the combination line and column visuals of net error each month in selected year and the last year.

Table & Matrix:
-	A tabular visual data listing customers and key metrics like forecast accuracy and net error also a column describing the inventory stage if it is excess or out of stock for the customer. The same matrics with the product segment categories.

-	3 scorecards showing the forecast accuracy, net error and absolute error.

.

Executive View
------------

![Executive View](https://user-images.githubusercontent.com/78613343/227526353-06df734a-ab3c-4217-8f78-139b77107589.png)
.

To Summarize Major insights of all department dashboards and major look into overall growth of Atliq company.

-	4 scorecards which show the growth number of Net sales, Gross margin%, Net Profit % and forecast accuracy.
-	Key insights by subzone w.r.t the metrics above are shown in a table visual.
-	Two donut charts to represent revenue by division and by channel.
-	A Combined line & and clustered column chart to view the yearly trend by revenue, Gross margin %, Net profit % and atliq market share percentage by Fiscal year description.
-	A ribbon chart to view the market share percentage.
-	Two tables have been introduced to know the top 5 customers and products by revenue.


.


Insights
--------

.

Finance View:
-----------
.

Net Sales: 
.

Net sales of the company had a steady growth from 29.11 million in 2018 to 3.74 billion in 2022 showing a hike each year this indicates extra-ordinary growth of the company. However, When compared to the targets to be achieved in the year 2022 the company was lagging behind by 1.86% in achieving the target provided. 

-	The trend in sales over the years indicates, the company always had higher Net sales from Oct to Dec every year. Therefore, management should look into factors which made the sales increase in this period and should try to implement accordingly. Also, decrease in sales each year from the start of December is seen each year the reason behind this should be found and taken care to prevent. 
-	Sales in each region had exceptional growth overtime except ‘Latin America’ where all sub-regions especially ‘columbo’  had least sales.
-	When looked into the products Networking Segment Product sales are declining over the past 3 year’s.
 ![image](https://user-images.githubusercontent.com/78613343/227529372-d31b7a32-2be3-4c41-a2ba-183138da71ad.png)

 
.

Gross Margin %:

- Gm% has been stable over the years with a clearance of ± 5. The company was 0.66% behind in achieving the overall gross margin %. 

.

Net Profit %:
NP Obtained is decreasing every year and had experienced profit only in the year 2019 with 2.21% of net sales. The company is expanding as we notice greater sales thus we can assume that the company at its initial face focuses on getting into the market rather than making profits. Also the company had a target of having a loss no more than 14.19% which has been achieved. 


![image](https://user-images.githubusercontent.com/78613343/227529447-a1f68634-0ab1-4ef3-a12f-3ebb8dc057a8.png)

 .
 
- In 2022 est, the networking segment P&L Values are declining, upon examining the Market, EU Regions like France, Netherlands and Austria etc are the major areas of low business. These regions should be focused more in terms of networking segment Products.

![image](https://user-images.githubusercontent.com/78613343/227529640-00f71bb6-a64d-43c0-a679-278513bc9d21.png)


.


Sales View:
-----------
.

-	Lowest net sales continued for the customer ‘Nova’ from year 2020 to 2022 but had around 25 to 30% of gross margin every year. Also, in 2022 the gross margin % was the lowest among other customers, this lets us know that sales department is giving more discount to the customer but sales remain low.
-	Networking products have always been the lowest net sales category each year.
-	From the scatter chart we see that below are the customers whose gross margin is lagging more than 10% of the target value.
-	
![image](https://user-images.githubusercontent.com/78613343/227637905-b866fab6-1957-4ce7-bd4a-998f92868cf3.png)
-
-	Below donut chart to the left shows the amount of pre-invoice and total post invoice discounts percentage to obtain 50.69% of net sales. Almost 49% of discounts had to be offered to generate 50% of net sales in year 2022.
-	The donut chart to the right shows 61.92% of Total cost of goods sold is included to obtain 38.08% of gross margin in the year 2022.
-
![image](https://user-images.githubusercontent.com/78613343/227638032-ffbffbec-f7c5-4fcc-b708-7cfb01233aaf.png)

.


