# Fraudulent_Claim_Detection_Case-Study

## Problem Statement

Global Insure, a leading insurance company, processes thousands of claims annually. However, a significant percentage of these claims turn out to be fraudulent, resulting in considerable financial losses. 

The company’s current fraud detection process relies on **manual inspections**, which are time-consuming and inefficient. Fraudulent claims are often identified too late—after substantial payouts have already been made. 

To **minimize financial losses** and **streamline the claims process**, Global Insure aims to enhance fraud detection using **data-driven insights** to classify claims as fraudulent or legitimate **early in the approval process**.

## Business Objective

The primary goal of this project is to **build a predictive model** that classifies **insurance claims** as either **fraudulent** or **legitimate** using historical claim details and customer profiles.

Key features like **claim amounts, customer details, and claim types** will be used to identify fraudulent patterns before approval.

### Key Questions:
- How can we analyze historical claim data to detect **patterns of fraudulent behavior**?
- Which features are most **predictive of fraud**?
- Can we **predict the likelihood of fraud** for an incoming claim based on past data?
- What actionable **insights** can be drawn from the model to **improve fraud detection**?

## Methodology

### 1. **Data Preparation**
- Import necessary libraries and load the dataset.

### 2. **Data Cleaning**
- Handle **missing values**.
- Remove **redundant features**.
- Fix **data types** for consistency.

### 3. **Train-Validation Split**
- Define **features** and **target variables**.
- Split data into **training** and **validation** sets.

### 4. **Exploratory Data Analysis (EDA)**
- Perform **univariate analysis**.
- Conduct **correlation analysis**.
- Check **class balance**.
- Perform **bivariate analysis**.

### 5. **Feature Engineering**
- Apply **resampling techniques**.
- Create **new features** for better model performance.
- Remove **redundant columns**.
- Group **categorical variables** effectively.
- Generate **dummy variables**.
- Perform **feature scaling**.

### 6. **Model Building**
- Perform **feature selection**.
- Build a **logistic regression model**.
- Identify the **optimal cutoff** for classification.
- Build a **random forest model**.
- Conduct **hyperparameter tuning**.

### 7. **Predictions and Model Evaluation**
- Make predictions on validation data using:
  - **Logistic Regression Model**
  - **Random Forest Model**
- Evaluate model performance using appropriate metrics.

---

## Next Steps
- Fine-tune model parameters for better accuracy.
- Explore additional ML algorithms to improve fraud classification.
- Deploy the model into production for real-time fraud detection.

---

This project aims to **automate fraud detection**, **reduce financial losses**, and **optimize claims processing** for Global Insure. 🚀
