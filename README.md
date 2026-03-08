# Titanical-Survival

Predicting passenger survival on the Titanic using Machine Learning.

---

## Project Overview
The Titanic disaster is one of the most infamous maritime tragedies. This project predicts whether a passenger survived using historical data. It demonstrates **data exploration, preprocessing, visualization, and model building**.

---

## Dataset
The dataset is based on the **Titanic Dataset** from [Kaggle](https://www.kaggle.com/c/titanic/data).  
- **Number of records:** 891 passengers  
- **Columns used:**
  - `sex` – Passenger gender
  - `age` – Passenger age
  - `fare` – Ticket fare
  - `Pclass` – Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
  - `survived` – Survival status (0 = No, 1 = Yes)

---

## How to Run
1. Open `code.ipynb` in **VS Code** or **Jupyter Notebook**.  
2. Ensure `Titanic_Survival.csv` is in the same folder.  
3. Run the cells step by step to see **data preprocessing, visualizations, and predictions**.  

---

## Data Visualization
The project produces several graphs to explore and understand the data:

- Survival count plot  
- Survival by gender  
- Age distribution  
- Fare vs Survival  
- Correlation heatmap  
- Confusion Matrix & ROC Curve  
- Feature Importance

---

## Model
**Algorithm:** Decision Tree Classifier (Gini criterion)  
**Features used:** `sex`, `age`, `fare`, `Pclass`  
**Evaluation Metrics:**  
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  
- 5-Fold Cross-Validation  

**Example prediction:**

| Sex   | Age | Fare   | Pclass | Predicted Survival |
|-------|-----|--------|--------|------------------|
| Male  | 9   | 20.525 | 3      | 1 (Survived)     |

---

## Results
The Decision Tree model achieved:

- **Train Accuracy:** ~79%  
- **Test Accuracy:** ~79%  
- **Precision:** 0.72  
- **Recall:** 0.78  
- **F1 Score:** 0.75  
- **ROC-AUC:** 0.80

> Cross-validation ensures the model generalizes well to unseen data.
