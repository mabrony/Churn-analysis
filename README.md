# Churn-analysis
![image](https://github.com/mabrony/Churn-analysis/assets/160124278/fb538db5-3e6b-46e4-9047-eef4b8abe333)

**Business Objective:** The primary objective of Vodafone Corporation is to reduce customer churn, a prevalent issue across many industries, especially in the telecommunications sector. The ultimate goal is to predict the likelihood of a customer discontinuing their service, identify the main factors contributing to customer churn, and develop strategies to retain customers and mitigate this issue.

`Key Performance Indicators (KPIs)` for this objective could include the churn rate, customer lifetime value, and customer retention rate.

**Understanding the Current Situation:** Currently, Vodafone has access to a wealth of customer data, supplied by the business development unit and the marketing and sales team. This data will be leveraged to build machine learning models capable of predicting customer churn. The current churn rate serves as a benchmark for measuring the effectiveness of the implemented strategies.

**Data Mining Goals:** The aim of data mining in this context is to develop a classification model that can predict whether a customer is likely to churn. This is a supervised learning problem where the model will be trained on the provided data and then used to make predictions on new data. The model should also be able to identify the key features or indicators that lead to customer churn. The accuracy, precision, recall, and F1 score of the model can serve as KPIs for this goal.

**Project Plan:** The project plan involves several steps. First, the data will be prepared for analysis, which may include cleaning the data, handling missing values, and encoding categorical variables. Next, appropriate machine learning algorithms will be selected for model construction. The model will then be trained and tested using the prepared data. The model’s performance will be evaluated using suitable metrics, such as accuracy, recall, precision, and F1 score. Finally, the model will be deployed for predicting customer churn. The key indicators identified by the model can then be used to devise effective strategies for customer retention. The impact of these strategies can be measured using KPIs such as the reduction in churn rate and increase in customer retention rate.

By aligning these steps with the overall business strategy, the company can ensure a data-driven approach to tackling customer churn, ultimately leading to improved customer retention and business growth.

**Data for the Project:**

The data for this projects has been divided into 3. The first 2 data sets are for training and evaluation the machine learning model  while the last data set is for testing the model. 
The first 3000 records of the dataset can be found in a database which will have to be accessed remotely.
The second part of the data is hosted on this GitHub Repository in a file called LP2_Telco-churn-second-2000.csv. Whiles the final data set needed for this project can be found in OneDrive.

`Target:`
- Churn — Whether the customer churned or not (Yes, No)

`Numeric Features:`

- Tenure — Number of months the customer has been with the company
- MonthlyCharges — The monthly amount charged to the customer
- TotalCharges — The total amount charged to the customer

`Categorical Features:`

- CustomerID
- Gender — M/F
- SeniorCitizen — Whether the customer is a senior citizen or not (1, 0)
- Partner — Whether customer has a partner or not (Yes, No)
- Dependents — Whether customer has dependents or not (Yes, No)
- PhoneService — Whether the customer has a phone service or not (Yes, No)
- MulitpleLines — Whether the customer has multiple lines or not (Yes, No, No Phone Service)
- InternetService — Customer’s internet service type (DSL, Fiber Optic, None)
- OnlineSecurity — Whether the customer has Online Security add-on (Yes, No, No Internet Service)
- OnlineBackup — Whether the customer has Online Backup add-on (Yes, No, No Internet Service)
- DeviceProtection — Whether the customer has Device Protection add-on (Yes, No, No Internet Service)
- TechSupport — Whether the customer has Tech Support add-on (Yes, No, No Internet Service)
- StreamingTV — Whether the customer has streaming TV or not (Yes, No, No Internet Service)
- StreamingMovies — Whether the customer has streaming movies or not (Yes, No, No Internet Service)
- Contract — Term of the customer’s contract (Monthly, 1-Year, 2-Year)
- PaperlessBilling — Whether the customer has paperless billing or not (Yes, No)
- PaymentMethod — The customer’s payment method (E-Check, Mailed Check, Bank Transfer (Auto), Credit Card (Auto))

Data Understanding
The data for this project is in a  format. The following table describes the columns present in the data:

Exploratory data analysis:
Analyze data to identify patterns, correlations, and potential churn indicators.


Hypothesis testing
`Null Hypothesis (H0):` Longer tenure does not impact the likelihood of customer churn.

`Alternative Hypothesis (H1):`There is a correlation between longer tenure and the likelihood of customer churn.

`Null Hypothesis (H0):` There is no significant correlation between contract type and customer churn.

`Alternative Hypothesis (H0):` There is a significant correlation between contract type and customer churn.

Churn prediction modeling:
Develop predictive models using machine learning algorithms to forecast customer churn.
