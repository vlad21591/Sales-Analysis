# Sales Analysis

## Project Overview:

### Introduction:
Pandas is a powerful and flexible open-source data manipulation and analysis tool, widely used in the data science and analytics community. This project serves as a template for performing data analysis tasks, and it can be a starting point for various data exploration and manipulation projects.

In addition we created dynamic visualizations with Tableau. Through interactive dashboards and concise charts, we can find sales trends, insights and make informed decisions to drive business growth.


## Key Highlights:

##### Data Cleaning and Preprocessing
Cleaning and preparing data is important for analyzing it. We use Pandas to do this effectively by fixing mistakes, handling missing data, transforming data and organizing variables for analysis.

##### Data Merging and Joining
We have combined 2 CSV files: List of Orders and Order Details wo achieve a larger data set to work with and more mensurable data.

##### Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) is a key step in understanding and analyzing data. It involves examining and visualizing the dataset to uncover patterns, trends, and insights. In our project, we use EDA to gain a deeper understanding of the data and inform subsequent analysis.

##### Data Visualization
I have prepared variuous visual formats like charts or graphs to make it easier to understand. It helps reveal patterns and trends in the data, making complex information more accessible and aiding in better decision-making.

Also I exported the data to Tablue and made several basic analysis graphs.

The project includes a well-documented Jupyter notebook, providing a step-by-step walkthrough of the data analysis process. Additionally, I have prepared a concise report summarizing key findings and insights derived from the analysis.

## Key Findings (pandas):
By grouping by category the summirized amount and profit helps us understand where the bulk of the revenew is coming from:

![](Charts/Pie%20Charts%20By%20Category.png)

We can see that the amount sold of goods is divided equally between the 3 categories, with Electronics accounting for 38.3%, Clothing for 32.2%, and Furniture for 29.5%.

When we look at the amount of profit those categories provided, there is a distinct difference. Although all categories are sold in equal amounts, the profits mainly come from Clothing (46.6%) and Electronics (43.8%), and lastly Furniture (9.6%).

My insight would be to focus on Electronics and Clothing and not invest in Furniture because its profitability is quite low to start with and would require a lot of resources to become profitable like the other categories. However, if the existence of Furniture is crucial, so perhaps increasing the prices of the items or tailoring them to a specific demographic could be considered.

We can group by same elements by a diffrent category and infer demographic insights:

![](Charts/BarChartCityProfit.png)


We can extract the "best" and "worse" clients the company addresses and add personalized service, exclusive offers and discounts or on the other hand add clear boundaries, escalation procedure, learning opportunities to help sturgling clients.

![](Charts/Customer%20Bar%20charts.png)

## Key Findings (Tableau):
We can conduct a comparable revenue analysis using Tableau, which enables us to apply more detailed filters to refine our observations and gain deeper insights, ultimately leading to better understanding.

In the initial two models, we can observe the distribution of various categories and their progression across months. Tableau also offers the flexibility to simultaneously filter both models by months or categories both parameters, enabling us to derive valuable insights from the data. 

#### General Distribution:
![](BI/Tablue%20Pics/1.png)

#### General Distribution by Month (November):
![](BI/Tablue%20Pics/2.png)

#### General Distribution by Profit category (Clothing):
![](BI/Tablue%20Pics/4.png)

#### General Distribution by Amount category (Furniture):
![](BI/Tablue%20Pics/7.png)

In these two models, we conducted a comparable analysis of Customer Segmentation, incorporating the element of time. Leveraging Tableau's capabilities, we explored customer segments based on demographic data, purchase behavior, or engagement metrics. This exploration allows us to tailor marketing strategies and enhance customer experiences effectively.

#### Distribution by Time:
![](BI/Tablue%20Pics/10.png)

#### Demographic Distribution by Month (November):
![](BI/Tablue%20Pics/11.png)

#### Amount and Profit Distribution by Demographic Selection:
![](BI/Tablue%20Pics/13.png)
------------
![](BI/Tablue%20Pics/14.png)




