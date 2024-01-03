# Machine-learning-model
**📖 Introduction**
A major challenge for large retailers is to address the needs of the consumers more effectively on a local level, while maintaining the efficiencies of central distribution. As the demand for mass customization by consumers grows, methods focused on store level optimization increase in value. Prediction of sales is an important application of machine learning in the retail space. Given accurate predictions, retailers can manage dynamic pricing, staff rostering and inventory so as to maximize profit and improve the customer experience.

An accurate forecast of sales allows retail outlets to answer questions such as:

Can we use dynamic pricing to maximize our profit?
Do we have enough stock to satisfy demand without being overstocked?
What are the most important factors that affect sales, and how can we optimize them?

**📖 Problem Statement**
Data provided by Rossmann gives various information of about 3,000 drug stores in 7 European countries. Currently, Rossmann store managers were tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

We are provided with historical sales data for 1,115 Rossmann stores. Our task is to forecast the "Sales" column for the test set with the help of given datasets.

**📖 Data Description**
This dataset was originally used in a Kaggle competition The dataset contains information about the stores and its sales. Two datasets are provided.

stores_data.csv - historical data including Sales
store.csv - supplemental information about the stores

**📖 Approach**
Loading our dataset and importing all the useful libraries
Data preprocessing and Feature Engineering
Scaling numeric features to a (0,1) range
Exploratory Data Analysis
Merging of Datasets
Encoding of categorical columns as one hot vectors
Feature Selection
Standardization of features
Machine Learning Data Modeling (for our Prediction)

**📖 Algorithms Used**
Linear Regression
XGBoost Regressor
Decision Tree
Random Forest

**📖 Conclusion**
Out of the four methods, Random Forest proved to be most accurate, achieving a R2_Score of 0.986449, MAE of 270.752379 and RMSE of 449.331705.
So, now we can say that the Rossmann store person can now implement the Random Forest Model and utilize the feature importance data for predicting the sales for next six months.
