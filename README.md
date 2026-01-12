# Travel-package-purchase-using-GradientBoosting-Classification
##  Project Overview
This project focuses on predicting whether a customer will purchase a travel package
using machine learning classification techniques. The model is built using the
**Gradient Boosting Classifier** to capture complex, non-linear relationships
in customer data.

---

##  Objective
To build a reliable classification model that predicts travel package purchase behavior
based on customer demographics, interaction history, and marketing attributes.

---

## 🗂 Dataset Description
The dataset contains customer-related features such as:
- Age
- Gender
- Occupation
- Monthly Income
- Number of Trips
- Duration of Pitch
- Product Pitched
- Number of Follow-ups
- Preferred Property Rating
- Past Purchase History

**Target Variable:**  
- `ProdTaken` (1 → Purchased, 0 → Not Purchased)

---

##  Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib & Seaborn  
- Scikit-learn  

---

##  Workflow
1. Data Loading and Exploration  
2. Handling Missing Values  
3. Feature Encoding (Categorical Variables)  
4. Feature Scaling  
5. Train-Test Split  
6. Model Training using Gradient Boosting Classifier  
7. Model Evaluation  

---

##  Machine Learning Model
- **Algorithm:** Gradient Boosting Classifier  
- **Reason:**  
  - Handles non-linear patterns effectively  
  - Reduces bias and variance through boosting  
  - Works well with structured/tabular data  

---

##  Model Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)  

---

##  Results
The Gradient Boosting model achieved strong predictive performance,
effectively distinguishing between customers likely and unlikely
to purchase the travel package.
