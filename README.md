# TASK4-CLASSIFICATICATION-WITH-LOGISTIC-REGRESSION
# Titanic Survival Prediction using Logistic Regression

This project builds a Logistic Regression model to predict whether a passenger survived the Titanic disaster, using the Titanic dataset.

## 📊 Dataset

We use the Titanic dataset from Seaborn, which includes features like:

- pclass: Passenger class (1st, 2nd, 3rd)
- sex: Gender
- age: Age of the passenger
- sibsp: Number of siblings/spouses aboard
- parch: Number of parents/children aboard
- fare: Ticket fare
- embarked: Port of Embarkation
- alone: Whether the passenger was alone

## 🧪 Steps Performed

1. *Data Loading*
   - Dataset loaded from Seaborn (sns.load_dataset('titanic')).

2. *Preprocessing*
   - Missing values handled using median/mode imputation.
   - Categorical features encoded using One-Hot Encoding.
   - Numeric features standardized.

3. *Train/Test Split*
   - Dataset split into 80% training and 20% testing.

4. *Model Training*
   - Logistic Regression model trained using scikit-learn.

5. *Model Evaluation*
   - Predictions evaluated using:
     - Confusion Matrix
     - Precision
     - Recall
     - ROC-AUC Score
   - Decision threshold tuned for best F1-score.

6. *Threshold Tuning*
   - ROC curve used to find the best threshold that maximizes F1 score.

## 📈 Output Metrics (Example)

At default threshold (0.50):

- Precision: 0.76
- Recall: 0.72
- ROC-AUC: 0.87

After tuning threshold for best F1-score, metrics improve for better balance.

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn
- Matplotlib (optional for plotting)

## 📌 How to Run

1. Open Jupyter Notebook or Google Colab.
2. Paste the provided code in a single cell.
3. Run the cell to see results and evaluation.

## 📚 Concepts Covered

- Binary Classification
- Logistic Regression
- Data Cleaning & Encoding
- Standardization
- Evaluation Metrics: Confusion Matrix, Precision, Recall, ROC-AUC
- Sigmoid Function & Threshold Tuning

---

*Author:* Sharmila L
*Date:*27 June 2025
