# UCI_Retail_II_and_UCI_Gas_Sensor_Data

## UCI Retail_II

This Jupyter Notebook presents an in-depth Exploratory Data Analysis (EDA) of the UCI Online Retail II dataset, which contains transactional data from a UK-based online retailer. The goal of this analysis is to uncover customer purchasing behavior, product trends, and business insights that can drive decision-making.

**Dataset**

[UCI_Retail_II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

**Dataset Overview**

Source: UCI Machine Learning Repository

Records: 10,67,371 transactions

Time Frame: 01/12/2009 and 09/12/2011.

Key Fields:
InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, 
CustomerID, Country

**Key Objectives of EDA**

* Understand the data structure, quality, and missing values.
* Analyze sales patterns across time, geography, and customers
* Identify top products by revenue, quantity, and frequency
* Compute key business metrics (Revenue, Recency, Frequency, Monetary - RFM)
* Segment customers using K-Means Clustering based on RFM scores

**Techniques Used**

* Data Cleaning & Preprocessing
* Handling missing values
* Removing invalid transactions (e.g., negative quantities)
* Feature Engineering
* TotalPrice = Quantity × UnitPrice
* Recency calculation from latest invoice date
* Visualization Tools
* Matplotlib, Seaborn
* Customer Segmentation
* RFM analysis
* K-Means Clustering with Elbow Method and silhouette score.

**Business Insights**

* Identified high-value customers using RFM analysis
* Helped stakeholders to identify potential buyers with the analysis.


## UCI_Gas sensor array under dynamic gas mixtures

**Dataset**

[UCI_Gas_Sensor_Array](https://archive.ics.uci.edu/dataset/322/gas+sensor+array+under+dynamic+gas+mixtures)


This Jupyter Notebook presents a machine learning-based regression analysis on the UCI_Gas_Sensor_Array dataset. The objective is to predict the concentrations of two gases **Ethylene and Methane** using the readings from 16 chemical sensors under dynamic gas mixtures.

**Objective**

To develop and evaluate regression models that can accurately estimate the concentrations of:

* Ethylene
* Methane

from real-time sensor data using various ML algorithms.

**A Breif overview of dataset**

* Features: 16 chemical sensor readings (time-series)
* Targets: Concentration levels of Ethylene and Methane gases
* Data Type: Multivariate time-series under dynamic environmental conditions

**Machine learning and Deep learning Models Used**

The notebook explores both traditional and advanced ML models:

* Linear Regression
* Polynomial Regression on Linear Model
* Random Forest Regressor
* Polynomial Regression on Random Forest
* Multi-Layer Perceptron (MLP) Regressor

**Evaluation Metrics**

To evaluate model performance for both target gases, the following metrics are used:

* R² Score
* Mean Squared Error (MSE)

All scores are compiled into a final comparison table to highlight the best-performing models.

**Highlights & Insights**

* Sensor data was preprocessed and normalized for better learning.
* Polynomial regression improved baseline linear performance.
* MLP showed competitive accuracy with deeper representation.
* Comparison shows trade-offs between interpretability and performance.

