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
Item_Type - The category to which the product belongs
Item_MRP - Maximum Retail Price (list price) of the product
Outlet_Identifier - Unique store ID
Outlet_Establishment_Year- The year in which store was established
Outlet_Size - The size of the store in terms of ground area covered
Outlet_Location_Type- The type of city in which the store is located
Outlet_Type- Whether the outlet is just a grocery store or some sort of supermarket
Item_Outlet_Sales - Sales of the product in the particulat store. This is the outcome variable to be predicted.

# Project Flow

* Loading Packages and Data
Data Structure and Content
Exploratory Data Analysis
Missing Value Treatment
Feature Engineering
Encoding Categorical Variables
Label Encoding
PreProcessing Data
Modeling
Linear Regression
RandomForest Regressor
XGBoost
Deployment
