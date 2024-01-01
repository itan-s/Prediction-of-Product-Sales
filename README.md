# prediction-of-product-sales

## Introduction

This project is a sales prediction for food items sold at various stores. The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales. The dataset is from the Big Mart Sales Practice Problem at Analytics Vidhya.

## Exploratory Data Analysis

### Correlation of item outlet sales (target variable) with the numerical features in the dataset

![Heatmap](https://github.com/itan-s/Prediction-of-Product-Sales/assets/151743020/c431ec22-60bb-4828-a95e-31012d054db5)

Observations:
* There is a moderate positive correlation between the Item_MRP and Item_Outlet_Sales with a correlation coefficient of 0.57.
* The positive relationship between the item MRP and outlet sales can be an expected result since a higher MRP may lead to higher outlet sales.
* Surprisingly, the visibility of the items in stores does not significantly correlate with the outlet sales.


### Distribution of the item outlet sales

![hist and boxplot](https://github.com/itan-s/Prediction-of-Product-Sales/assets/151743020/1bf8213f-7de3-4ca1-9a08-b4b3b1eaea11)

![box1](https://github.com/itan-s/Prediction-of-Product-Sales/assets/151743020/4845ab4a-b841-45ef-a6ce-338c7f8dc63e)

![box2](https://github.com/itan-s/Prediction-of-Product-Sales/assets/151743020/d320207d-29fe-4911-ad02-1247eccbf81f)


Observations:
* The mean item outlet sales in all stores is ~2181 currency units with a maximum of ~13,000 currency units and high variability.
* Overall, over 75% of item sales data were within < 5000 currency units across all the store types. See the graph of the Distribution of Item Outlet Sales.
* In detail, grocery stores have the lowest item sales figures (< 2000 units) with a median of less than 1000 currency units. This may be because groceries are relatively smaller, with probably limited items for sale compared to supermarkets. In contrast, supermarkets have higher item sales figures mostly, ranging from 0 to ~13,000 units. See the graph of the Distribution of Item Outlet Sales by Outlet Type.
* Meanwhile, the median of outlet item sales data in Supermarket Type 3 is higher than in Type 1 and Type 2. This means that the sales amount per item in Type 3 supermarkets has relatively larger values, though this does not necessarily mean that Type 3 has the highest total sales. Total sales look into the sum of the sales of all items in each store type, which will give more advantage to store types in which a larger variety of items are being sold. See the graph of the Distribution of Item Outlet Sales by Outlet Type.
* Supermarkets located at Tier 3 locations have the highest item sales (> 10,000 currency units). Nevertheless, the distribution of outlet item sales data is almost similar among different store location tiers. See the Distribution of Item Outlet Sales by Outlet Location Type.


### Total and average outlet sales per outlet type and outlet location type

![bar1](https://github.com/itan-s/Prediction-of-Product-Sales/assets/151743020/0daade9f-0c56-49d3-bf5d-d90b92a14113)

![bar2](https://github.com/itan-s/Prediction-of-Product-Sales/assets/151743020/f297df29-edb4-49d2-b84d-ede5de446445)

Observations:
* Supermarket Type 3 earned the highest average sales, but Supermarket Type 1 got the highest total item outlet sales. This is because Supermarket Type 1 has more Item_Outlet_Sales records than Type 3. Grocery stores earned the lowest, which may be due to their relatively smaller size and limited stocks of items.
* Stores in tier 2 and 3 locations have notably higher total and average item outlet sales than those of tier 1 locations, hinting that Tier 1 locations may have fewer customers, low customer patronage, or small purchases per item.


### Number of items sold per item type

![count 1](https://github.com/itan-s/Prediction-of-Product-Sales/assets/151743020/a0b02d11-8e7d-4206-a62e-8e1bb00349df)

Observations:
* Fruits and vegetables are the abundant items sold in all stores, followed by snack foods and household items.
* This trend is consistent in all store types: groceries and supermarkets of all types.






