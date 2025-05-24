# Credit-Card-Fraud-Detection 

This project focuses on detecting fraudulent transactions using a dataset of customer purchases and behavioral patterns. It applies end-to-end data analysis, feature engineering, and machine learning classification techniques to identify and predict potential fraud cases.

## 🔧 Tools & Technologies Used

- **Languages & Libraries**: Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- **SQL**: MySQL for initial data exploration and filtering
- **Machine Learning Models**: Logistic Regression, Random Forest
- **EDA Techniques**: Boxplots, Heatmaps, Countplots, Histograms
- **Feature Engineering**: Datetime extraction, Age group segmentation, Category encoding

---

## 📌 Project Overview

- Performed thorough **Exploratory Data Analysis (EDA)** on both numerical and categorical variables to understand spending and fraud behavior.
- Engineered new features from date of birth and transaction timestamps such as **customer age**, **transaction hour**, and **age groups**.
- Visualized data patterns to identify key fraud trends by:
  - **Category** (`shopping_net` had the highest fraud rate)
  - **Hour of day** (fraud peaked around 10 PM–12 AM)
  - **Age group** (60+ more vulnerable to fraud)
- Built classification models using:
  - **Logistic Regression** (Accuracy: ~84%)
  - **Random Forest** (Accuracy: ~99%)  
  > Note: High accuracy may indicate **overfitting**. Currently exploring model validation and balancing techniques like **cross-validation**, **SMOTE**, and **undersampling**.

---

## 🧠 Key Insights

- **Grocery POS** transactions had the highest average amount.
- **Shopping Net** category showed the **highest fraud count**.
- Fraud transactions were more frequent during **late evening hours**.
- **Elderly customers (60+)** had a higher fraud rate.
- **New York (NY)** state recorded the most number of fraud cases.

---

## ✅ Model Evaluation

### Logistic Regression
- Accuracy: `~84%`
- Balanced performance across fraud and non-fraud classes.

### Random Forest
- Accuracy: `~99%`
- Very high precision and recall; further validation required to confirm generalization.

---

## 📁 Repository Structure

