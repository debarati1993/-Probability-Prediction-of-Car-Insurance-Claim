## -Probability-Prediction-of-Car-Insurance-Claim

---
### 1. Project Objective

#### The goal of this project is to develop a predictive model that assesses the probability of a claim being filed for car insurance policies. By identifying the factors that influence claim frequency and severity over a six-month period, this model enables insurance companies to:

#### 1. Better assess risk profiles for potential and current policyholders.
#### 2. Determine appropriate and competitive premiums.

### 2. Dataset Overview

#### The dataset contains **58,592 rows** and **44 columns**.

#### **Target Variable:** `is_claim` (Binary: 1 if a claim was made, 0 otherwise).
#### **Feature Categories:**
#### **Policy & Policyholder:** Tenure and age of the policyholder.
#### **Geographic Risk:** Area cluster and population density.
#### **Car Specifications:** Age, make, model, fuel type, engine type, and transmission.
#### **Performance:** Torque, power output, turning radius, and gross weight.
#### **Safety Features:** NCAP rating, number of airbags, and presence of safety indicators like ESC, TPMS, and Brake Assist.



### 3. Tech Stack

#### The project is implemented in Python using the following libraries:

#### **Data Manipulation:** `pandas`, `numpy`.
#### **Visualization:** `matplotlib`, `seaborn`.
#### **Machine Learning:** `scikit-learn`, `xgboost`.
#### **Statistical Analysis:** `statsmodels`, `scipy`.

### 4. Methodology

#### The notebook follows a standard data science workflow:

  #### 1. **Data Processing:** Checking for missing values (none found in the dataset).
  #### 2. **Exploratory Data Analysis (EDA):** Visualizing claim percentages and feature distributions.
  #### 3. **Handling Imbalance:** Utilizing SMOTE to address the significant class imbalance (approx. 93.6% non-claims vs. 6.4% claims).
  #### 4. **Modeling:** Training various classifiers including
  #### * Logistic Regression.
  #### * K-Nearest Neighbors (KNN).
  #### * Decision Trees and Random Forests.
  #### * XGBoost.
  #### 5. **Evaluation:** Assessing performance using Accuracy, Precision, Recall, F1-score, and ROC-AUC.


