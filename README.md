# Big-Mart-Sales-Prediction
The aim is to build a predictive model and find out the sales of each product at a particular store. Create a model by which Big Mart can analyze and predict the outlet production sales.

A perfect project to learn Data Analytics and apply Machine Learning algorithms (Linear Regression, Lasso Regression, Ridge Regression, Decision Tree Regressor, Random Forest Regressor, XG Boost Regressor, Extra Tree Regressor, AdaBoost Regressor, Support Vector Regressor and KNN Regressor) to predict the outlet production sales.

# Dataset Description
BigMart has collected sales data from the year 2013, for 1559 products across 10 stores in different cities. Where the dataset consists of 12 attributes like Item Fat, Item Type, Item MRP, Outlet Type, Item Visibility, Item Weight, Outlet Identifier, Outlet Size, Outlet Establishment Year, Outlet Location Type, Item Identifier and Item Outlet Sales. Out of these attributes response variable is the Item Outlet Sales attribute and remaining attributes are used as the predictor variables.

The data-set is also based on hypotheses of store level and product level. Where store level involves attributes like:- city, population density, store capacity, location, etc and the product level hypotheses involves attributes like:- brand, advertisement, promotional offer, etc.

# Dataset Details

The data has 8523 rows of 12 variables. Variable - Details are:

* Item_Identifier- Unique product ID
* Item_Weight- Weight of product
* Item_Fat_Content - Whether the product is low fat or not
* Item_Visibility - The % of total display area of all products in a store allocated to the particular product
* Item_Type - The category to which the product belongs
* Item_MRP - Maximum Retail Price (list price) of the product
* Outlet_Identifier - Unique store ID
* Outlet_Establishment_Year- The year in which store was established
* Outlet_Size - The size of the store in terms of ground area covered
* Outlet_Location_Type- The type of city in which the store is located
* Outlet_Type- Whether the outlet is just a grocery store or some sort of supermarket
* Item_Outlet_Sales - Sales of the product in the particulat store. This is the outcome variable to be predicted.

# Project Flow

* Loading Packages and Data
* Data Structure and Content
* Missing values treatment
* Variable Identification
* Outlier treatment
* Univariate Analysis
* Bi-variate Analysis
* Variable transformation
* Feature Engineering
* Encoding Categorical Variables
* Label Encoding
* PreProcessing Data
* Modeling
* Linear Regression, Lasso, Ridge, Decision Tree, Random Forest, XGBoost, Adaboost, Extra Tree, SVM and KNN
* Deployment

# Insights

* Item_Fat_Content: Most Items sold are low Fat.
* Item_Type: Distictly fruits & veg, snacks food are popular.
* Item_Type_Combined: Most Sold Item cateogory is food.
* Outlet_Identifier: Sold items are ditributed evenly amoung all stores, execpt OUT010 and OUT019.
* Outlet_Size: Bigmart Stores are mostly in medium size in this data.
* Outlet_Location_Type: Most comon type of location is Tier3
* Outlet_Type: By a wide mergin Most Store Types are SuperMarket Type1.
* Outlet_Age: Most Common Outlets are 35 year's old.
* Item_Visibility: Looks like it has negative correlation.
* Item_Weight: Not a particular Pattern, Data is very spreaded.
* Item_MRP: Items with higer MRP Sales tends to sell better.
* Item_Type_Combined: Based on Categories, Food has most Sells, But difference is very small.
* Outlet_Identifier: Outlet027 has most profitable, and Outlet019 and Outlet010 has least Sells.
* Outlet_Type: Most Sells are through SuperMarket Type3 surprisingly not Type1.
* Outlet_Size: Sells are mostly even in Medium and High size Stores.
* Outlet_Location_Type: Most sells are through Tier2, but difference with Tier1 and Tier2 is very small.
* Seafood is the most item_type sold in SuperMarket 2, Grocery store has less sales.
* Only Teir3 has all Outlet_Type, and SuperMarket type3 has most sales.
* Outlet_Location_Type has almost equal sales based on Item_Type_combined.
* Supermarket Type 1 outlet is present all the Outlet_Location.
* Item_Outlet_Sales is highly correlated with Item_MRP.
* Outlet_Age and Item_Visibility are negativaly correlated.
* Item_Weight and Outlet_Eastablishment_Year is also positive correlated.


# Predictive behavior modeling

1. Splitting data into train and test data in 80:20 ratio.
2. Model Building and training ten different regression models on the 80% training split: Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Regressor, Random Forest Regressor, XGBoost Regressor, Extra Tree Regressor, Ada Boost Regressor, Support Vector Regressor and KNN Regressor that will gives the sales prediction.
Making predictions from the model
Testing the performance of the model using MSE, MAE, RMSE and R2 Score.

# Choose the most Appropriate model

* The Support Vector Regressor provides the lowest MSE value: 0.27 and heighest R2 Score: 0.72. The Random Forest Regressor algorithm also provides the MSE value : 0.29 and R2 Score : 0.70.
* The Support Vector Regressor is best possible technique to predict the Bigmart sales.
