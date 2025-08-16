# 📊 Customer Churn Analysis & Prediction  

This project analyzes **customer churn patterns** using the Telco dataset and builds a machine learning model to predict churn.  

The goal is to identify **key factors driving customer churn** and create a predictive model that can help telecom companies improve retention strategies.  

---

## 🚀 Project Workflow  

1. **Data Loading & Cleaning**  
   - Loaded Telco dataset (7,043 records, 21 features).  
   - Handled missing values and corrected data types.  
   - Cleaned and standardized column names.  

2. **Exploratory Data Analysis (EDA)**  
   - Churn distribution and churn by contract type, internet service, and monthly charges.  
   - Correlation heatmap of numerical features.  

3. **Feature Engineering**  
   - Encoded categorical variables with one-hot encoding.  
   - Dropped irrelevant features (e.g., `customerID`).  

4. **Model Building**  
   - Train-test split (80/20).  
   - Logistic Regression model (`sklearn`) trained with max_iter=1000.  
   - Achieved **~79% accuracy** on test set.  

5. **Model Evaluation**  
   - Accuracy Score: `0.787`  
   - Confusion Matrix & Classification Report provided.  

---

## 📈 Results  

- Customers on **month-to-month contracts** are most likely to churn.  
- **Higher monthly charges** are strongly correlated with churn.  
- Logistic Regression baseline achieved ~79% accuracy.  

---

## 🛠️ Libraries Used  

- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `matplotlib` – Visualizations  
- `seaborn` – Advanced visualizations  
- `scikit-learn` – Machine learning (train-test split, logistic regression, metrics)  



