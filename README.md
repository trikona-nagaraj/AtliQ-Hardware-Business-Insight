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
 
Key metrics like net profit and net profit% along with net sales and gross margin are analyzed in terms of products and market which are drilled down to sub categories further individually.

Scatter plot: 
 
Where gm% and np% are provided on y axis which can be switched according to the analysis requirements. 
On x-axis, Net sales is shown.
segment, category and value are taken as values which show the bubbles which can be drill down and up, division as legend, gm% as tool tip (hovering mouse will show this value), NS as size of the bubble.


Donut chart:
-	Gross margin and the total cogs costs are shown.

Note:
-	Net profit, gm and the operational cost are to be shown but net profit is in negative value so we are using waterfall chart to show that.

Waterfall chart:


-	This chart shows the amount of gross margin received from total net sales and the operating cost. Also it shows the net profit obtained.

.
