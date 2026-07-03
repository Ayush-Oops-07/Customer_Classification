# 🧠 Customer Churn Classification Project (dL)

## 📌 Objective

This project aims to predict customer churn based on demographic and behavioral attributes using a **Logistic Regression** model. Churn is defined as customers likely to leave based on their income and purchase frequency.

---

## 📊 Dataset

A synthetic dataset was generated with the following features:

- `Age`: Customer's age
- `Gender`: 0 = Female, 1 = Male
- `Income`: Annual income (in thousands)
- `PurchaseFrequency`: Number of purchases per month
- `Churn`: 1 = Likely to churn, 0 = Not likely to churn

Customers with **Income < $40k** and **Purchase Frequency < 3** are labeled as likely to churn.

---

## 🧰 Tools & Libraries

- **Language**: Python
- **Libraries**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 🤖 Machine Learning Model

- **Model Used**: Logistic Regression (`sklearn.linear_model.LogisticRegression`)
- **Train-Test Split**: 80% training / 20% testing

---

## 📈 Evaluation Metrics

- **Accuracy Score**: ~90.67%
- **Confusion Matrix**
- **Classification Report**:
  - Precision
  - Recall
  - F1-Score

Confusion matrix is visualized using a heatmap for interpretability.

---

## 📂 Files Included

- `Customer_Classification.ipynb` — Jupyter notebook with full code and analysis.
- `customers.csv` — The synthetic dataset used for training/testing.
- `README.md` — This project documentation file.

---

## 🚀 How to Run

1. Clone or download the project files.
2. Open the notebook `Customer_Classification.ipynb` in Jupyter or Google Colab.
3. Run all cells to generate data, train the model, and view results.

---

## 📬 Contact

For questions or suggestions, feel free to open an issue or reach out!
