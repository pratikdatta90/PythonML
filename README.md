# PythonML
**Exploratory Data Analysis and Building Price Predictive Model**

**Introduction: reason behind the work**
In today's fast-paced world, the way we travel and seek accommodations has undergone a remarkable transformation, thanks to platforms like Airbnb. This dynamic marketplace has empowered property owners and travelers, offering a diverse range of lodging options. However, one enduring challenge is setting the right price for a listing. Hosts aspire to optimize their earnings while ensuring competitive pricing, while guests seek value for their money. Balancing these interests can be intricate, and that's where the motivation for Airbnb price prediction comes in.

**Motivation: contribution of the work**

To harness the power of data science and machine learning to provide more accurate and data-driven pricing strategies for Airbnb hosts and guests. By developing predictive models that factor in myriad variables such as location, property type, and market dynamics. The objective is to help hosts maximize their income and guests find fair deals. In this exploration of Airbnb price prediction, we will delve into methodologies, data sources, and emerging trends. Shedding light on how technology is enhancing the overall Airbnb experience for both hosts and travelers.

**Objectives: finding the right price**

The task is to generate an ML based solution that can be used to suggest appropriate listing prices to the property owner when they try to list a property out for rent.

**Steps undertaken to reach the final goal of the project:**

Data Understanding and feature creation
Data Quality and checks
Variable profiling and checking relationships between variables
Modelling and insights

**Tools used: python(jupyter notebook)**

**Basic packages used for data cleaning, merging and preliminary visualization:**
NumPy (For exploratory data analysis)
Pandas
Matplotlib (For Visualization)
Seaborn

**Packages used for building data model using the predictor variable in the data:**
scikit-learn (used for encoding, and performing linear and random forest regression)
XGBoost (used for XGBoost Regression)

**Challenges: data preparation works**

**Basic Challenges faced with the raw data and measures taken to overcome those:**
Missing value inspection in the target variables and imputing appropriately
Changing the date format to datetime in order to perform further analysis
Renaming columns to reflect appropriate field name
Removing field from different source files that may not be required building model
Joining and merging different data sources to a single data frame for analysis
Using the seaborn and matplotlib libraries basic exploratory data analysis (EDA)
Segregating the numeric and categorical fields before performing the encoding
Using the sci-kit learn package to perform encoding (Label Encoder from preprocessing)

**finding the right model to predict**

Not approaching a classification or clustering model as aim is to predict price

**Experimenting with linear regression techniques : Multiple Linear Model**
Identifying the predictor variables by discarding remaining to predict price
Initially trying with simple linear regression by choosing single predictor variable

**Experimenting with Random forest Regressor Model and XGBoost Regressor:**
The idea is to generate prediction using different models and the compare accuracy
Deciding the final model will be based on the metrics: MSE, MAE, R2, Adj R2 etc.

**Approaches undertaken to implement**

After removing the irrelevant features and subsequently encoding the data, the next step is to experiment with different models.
The predictor variables are property type, room type, accommodates, bathrooms, bedrooms and beds. The target variable is nothing but the price.
Using the train_test_split feature of sci-kit learn’s model selection, the data is segregated between the training and testing data
The ratio between training and testing data is kept at a standard 80:20 ratio.
The same ratio is kept while trying and testing between different models like the linear regression, random forest and XGBoost regressor.
In the final stage, data is fitted in different models & predicted the target variables.
Finally, the test results are found and subsequently compared between each other.























