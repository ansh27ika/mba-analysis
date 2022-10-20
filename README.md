# Mba-Analysis

## Introduction 

 When you go to the supermarket, usually the first thing you do is grab a shopping cart. As you move up and down the aisles, you will pick up certain items and place them in your shopping cart. Most of these items may correspond to a shopping list that was prepared ahead of time, but other items may have been selected spontaneously.

•	We will be analyzing how to convert the consumer tastes and preferences into Association rules that are more insightful and actionable,from business perspective.

•	For example,if customers buy product A they also tend to buy product typically we can extract the relationship between products in the form of rules or we can say is the purchase of bread leads to the purchase of butter? 

## Dataset

The dataset that is used in this project is publicly available from Kaggle which contains the Transactions data from a bakery from 30/10/2016 to 09/04/2017. The data belongs to a bakery called "The Bread Basket" that serves coffee, bread, muffin, cookies and so on. It is located in the historic center of Edinburgh.

## `Insights`

#### Top 10 best-selling items rank by % and value : 
* Bar charts are used for visualization, it is clear that Coffee (26.7%) is the best-selling item in the bakery, follow by Bread (16.2%) and Tea (7.0%).

#### Time series chart of number of items sold by day : 
* As we can observe,this is the time series chart of number of items sold by day fluctuates a lot thoughout the 159 days of data.
 

#### time series chart of number of items by month : 
* Given that the beginning month (October 2016) and ending month (April 2017) are not full month, the total number of items sold by month for the five full month between November 2016 to March 2017 does not fluctuate too much.

#### Average Number by Items Sold by Hour of the Day : 
* Sales starts to pick up from 8am, till the busiest hour of the day at 11am, then slowly drops till the late afternoon. It can be observed that most of the sales transactions took place during the lunch hours of the day


#### Average Number of Items Sold by day of week : 
* Saturday is the busiest day of the week with the highest sales (101 items). This is an interesting insight, the owner of the Bakery should launch some promotion activities to boost up sales in the middle of the week when sales are slowest.

## `MBA ANALYSIS` RESULT
The output  shows the top 10 itemset sorted by confidence value and all item sets have support value 
Over 1% and lift value over 1. 
* The first itemset shows the association rule "if toast then coffee" with support
Value at 0.023666 means nearly 2.4% of all transactions have this combination of toast and coffee bought 
Together. 
* We also have 70% confidence that coffee sales happen whenever a toast is purchased. The lift
Value of 1.47 (greater than 1) shows that the purchase of coffee is indeed influenced by the purchase of 
Toast rather than coffee's purchase being independent of toast.
* The lift value of 1.47 means that toast’s
Purchase lifts the coffee's purchase by 1.47 times.
* Therefore, we can conclude that there is indeed evidence To suggest that the purchase of toast leads to the purchase of coffee.
The owner of the bakery "the bread basket" should consider bundling toast and coffee together as a breakfast set or lunch set, 
theStaff in the store should also be trained to cross-sell coffee to customers who purchase toast, knowing that They are more likely to purchase them together, thereby increasing the store's revenue.

## CONCLUSION 
increase sales and customer satisfaction,.It supports the retail sector in all areas,from predicting sales success to locating customers,it can used 
in various fields, such as marketing,bioinformatics,education-field,nuclear-science etc


