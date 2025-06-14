
# DS-MARKET

This project represents the final result of my journey to becoming a Data Scientist. Here, I present a comprehensive solution for managing the products across the stores of a company, addressing their specific requests and business needs.

## Objectives:
* Analyze the state of each store, identifying sales trends of products and their evolution, sliced by country and other key factors.
* Detect and group similar products to understand how many groups exist and what they represent.
* Provide accurate forecasts of future sales.
* Forecast inventory demand to ensure optimal supply levels.
* In addition to these objectives, I aim to develop comprehensive visualizations that effectively communicate the analysis conducted, ensuring that insights are clearly   understood and actionable for decision-makers

## Sprint 1: Data Exploration and Preparation

I received three key datasets containing company information: (item_prices, item_sales, and daily_calendar_with_events).
I began with data cleaning and a thorough analysis of the datasets, gaining an understanding of the variables and their structure. I used tools such as Python alongside libraries like "like `numpy`,`pandas`,`matplotlib`,`seaborn`  in development environments like `Visual Studio Code` & `Jupiter notebooks`.
I conducted extensive preprocessing to build the main dataset. This dataset were utilized to develop visualizations that provide a comprehensive view of the company's current status, highlighting the behavior of cities, stores, products, and their categories. 


### * Cities current status
<br><br>
![Alt text](utils/General_analysis_Dashboard.png)
<br><br>
As we can see in the picture there are some slicers at the bottom so make easier to explore de data

There are also Kpis that modify their values where I navigate through data

### * Shops current status
<br><br>
![Alt text](utils/stores_analysis.png)
<br><br>

### * Products behavior
<br><br>
![Alt text](utils/product_analysisII.png)
<br><br>
I tried to identify behavior of products before clustering
<br><br>

![Alt text](utils/product_analysis.png)
<br><br>
In this table we can see top 20 of best income products. Some of them arrived later than others. The slicers help us to navigate throgh data

## Sprint 2: Clustering 

I applied clustering techniques, specifically the K-means algorithm, to identify groups of similar products.
In addition, I created clear and insightful visualizations that helped me better to understand the behavior and composition of these clusters


### * Cluster overview
<br><br>
![Alt text](utils/cluster.png)

The scatter plot illustrates the 4 clusters, where each point represents a product, positioned according to its sales (X-axis) and income (Y-axis). This allows us to identify different performance patterns across products.

Ring charts were used to analyze the category composition of each cluster, focusing on Supermarket, Home and Garden, and Accessories. These charts reveal the proportion of each category in each cluster, helping us understand product behavior and category trends.

### * Cluster groups
<br><br>
![Alt text](utils/cluster_groups.png)

This slide presents a bar chart displaying the 4 clusters based on their average price and the revenue they generate. The comparison clearly highlights the differences in price ranges and income levels among the clusters.

Alongside, there's a table summarizing the key metrics for each group, with columns for: Articles, Min Price, Max Price, Units Sold, and Revenue.

Hormiga Products: Represent 1,914 out of 3,049 total products, with low prices but high sales volume, generating around €102M off €230M in revenue.

Estandard Products: This group consists of 887 items, featuring mid to high prices, contributing €59M 

Estrella Products: 88 products in this cluster have average prices and strong sales, producing €48M.

Premium Products: With very high prices and lower sales volumes, this group comprises fewer items but still generates €21.5M of the total revenue.

## Sprint 3: Predictive Modeling
I developed a comprehensive visual report to highlight the key insights derived from our data analysis. After evaluating various forecasting models, including ARIMA and skforecast from Sklearn, we selected the most accurate and appropriate approach for the business. Using the chosen model, I implemented sales forecasts to support future planning.


### * Income forecasting
<br><br>
![Alt text](utils/income_forecasting.png)

### * supply forecasting
<br><br>
![Alt text](utils/supply_forecasting.png)


## Results:

Through this project, I achieved:

Clear identification of well-defined product clusters, providing greater clarity on consumption trends.
Accurate sales forecasts that enable efficient product supply planning.
I crafted a storytelling narrative that clearly and effectively communicates the results, emphasizing their relevance for strategic decision-making in the company.

 



