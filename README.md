# Customer-Lifetime-Value-Prediction
The task is to understand the concept of Customer Lifetime Value and provide a data-driven solution through data methodologies.To understand customer behaviour and to find out the profitable customers and predict the lifetime valuation of a customer to facilitate target marketing. CLV is the total worth to a business of a customer over the whole period of their relationship. It’s an important metric as it costs less to keep existing customers than it does to acquire new ones, so increasing the value of your existing customers is a great way to drive growth.

We have used R programming for carrying out the project. The results are presented with the help of `R markdown`.

## Dataset
The dataset used in this project is available in [kaggle](https://www.kaggle.com/pankajjsh06/ibm-watson-marketing-customer-value-data). The features and their descriptions are provided in `Marketing CLV Analysis - Data Dictionary.pdf`. The dataset contains 23 features and the target variable - *Customer Lifetime Value*. The dataset doesn't have any missing values.

## Workflow
The aim is to understand customer demographic, buying behaviour and to model customer lifetime value. The steps taken are listed below:
* Exploratory Data Analysis.
* Statistical tests to understand the influence of different categorical variables on the response variable.The code used to perform the tests are provided in `Kruskal_wallace_tests.Rmd` and the final results are summarised in `Kruskal_wallace_tests.pdf`.
* Data transformation and Feature extraction.
* Building Machine learning models. We have explored different models to arrive at the best model - Stepwise linear regression, polynimial regression, Ridge and lasso regression, XGBoost.
* Based on the performance of the models and the feature selection results, a final linear regression model was selected as the final model.
* Suggestions for better customer targeting.

The code used for the entire process is available in `CLV_Report.Rmd` and the results are summarised in the form of a final report which is provided in `CLV_Report.pdf` and `CLV_Report.html`.

***
