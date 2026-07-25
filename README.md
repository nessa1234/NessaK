Below is a professional README.md that you can directly copy into your GitHub repository.

🌍 Global Economic Growth Prediction and Financial Risk Analysis Using World Bank Data
📌 Project Overview

This project aims to analyze global economic indicators and predict GDP Growth (Annual %) using Machine Learning techniques. In addition to GDP prediction, a Financial Risk Score was developed to compare the financial stability of selected countries based on key macroeconomic indicators such as inflation, government debt, and GDP growth.

The project demonstrates the complete Machine Learning workflow, including data collection, preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and visualization.

🎯 Objectives
Predict GDP Growth (Annual %) using economic indicators.
Analyze relationships between macroeconomic variables.
Develop a Financial Risk Score for country comparison.
Compare the performance of Linear Regression and Random Forest Regression models.
Visualize economic trends using professional charts.
📂 Dataset

Source: World Bank Open Data – World Development Indicators (WDI)

The dataset contains economic indicators for multiple countries from 2010 to 2025.

🌎 Countries Included
Argentina
Australia
Brazil
Canada
China
France
Germany
India
Indonesia
Italy
Japan
Mexico
Russia
Saudi Arabia
South Africa
South Korea
Turkey
United Kingdom
United States
Vietnam
📊 Features Used

The following indicators were selected for model building:

Year
GDP (Current US$)
Gross Capital Formation (% of GDP)
Gross Savings (% of GDP)
Inflation, Consumer Prices (Annual %)
Exports of Goods and Services (% of GDP)
Imports of Goods and Services (% of GDP)
Foreign Direct Investment (% of GDP)
Current Account Balance (% of GDP)
Real Interest Rate (%)
Domestic Credit to Private Sector (% of GDP)
Central Government Debt (% of GDP)
Population Growth (Annual %)
Population
Unemployment Rate
🎯 Target Variable

GDP Growth (Annual %)

🧹 Data Preprocessing

The following preprocessing steps were performed:

Loaded the World Bank dataset.
Replaced missing values (..) with NaN.
Removed invalid and duplicate records.
Converted the dataset from wide format to long format using melt().
Reshaped the data using pivot_table().
Converted columns to appropriate numeric data types.
Handled missing values using the Median Imputer.
Prepared the dataset for Machine Learning.
📈 Exploratory Data Analysis (EDA)

The following visualizations were created:

GDP Growth Distribution
Average GDP Growth by Country
Inflation vs GDP Growth Scatter Plot
Correlation Heatmap
Financial Risk Score by Country
Financial Risk Level Distribution
Random Forest Feature Importance
Actual vs Predicted GDP Growth
⚙️ Feature Engineering

A custom Financial Risk Score was created using the following formula:

Risk Score =
(0.4 × Inflation)
+
(0.3 × Government Debt)
-
(0.3 × GDP Growth)

Based on the Risk Score, countries were classified into:

Low Risk
Medium Risk
High Risk
🤖 Machine Learning Models

The following regression models were implemented:

Linear Regression
Simple baseline regression model.
Used for predicting GDP Growth.
Random Forest Regression
Ensemble learning algorithm.
Captures non-linear relationships.
Used to improve prediction accuracy.
📏 Model Evaluation

The models were evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score

The Random Forest model produced better predictive performance than the baseline Linear Regression model.

🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Data Transformation
(Melt & Pivot)
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Feature Scaling
        │
        ▼
Model Building
        │
        ▼
Model Evaluation
        │
        ▼
Visualization & Conclusions



Key Findings
Inflation and Government Debt significantly influence financial risk.
Higher GDP Growth generally corresponds to lower financial risk.
The Random Forest model captured complex relationships between economic indicators more effectively than Linear Regression.
The custom Financial Risk Score provides an intuitive way to compare countries based on economic stability.

📌 Conclusion

This project successfully demonstrates an end-to-end Machine Learning pipeline using real-world World Bank data. By combining economic indicators with predictive modeling, the project provides insights into GDP Growth trends and financial risk across countries. The results highlight the usefulness of Machine Learning in economic analysis and support data-driven decision-making.

📚 Future Improvements
Include more countries and longer historical time periods.
Incorporate additional macroeconomic indicators.
Experiment with advanced regression algorithms such as XGBoost and Gradient Boosting.
Build an interactive dashboard using Power BI or Streamlit.
Deploy the trained model as a web application.
👩‍💻 Author

Nessa Kallikkad Madhu

Mini Project: Global Economic Growth Prediction and Financial Risk Analysis Using World Bank Data
