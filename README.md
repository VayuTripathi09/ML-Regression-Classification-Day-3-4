# Machine Learning - Day 3 & Day 4  
**Linear Regression & Logistic Regression Projects**  

## 📌 Overview
This repository contains the implementation of:
- **Day 3:** Linear Regression  
- **Day 4:** Classification with Logistic Regression  

The projects use flight price data to:
1. Predict ticket prices using Linear Regression.
2. Classify flights into Economy or Business using Logistic Regression.

---

## 📂 Files in Repository
- `Day3_Linear_Regression.ipynb` → Implements simple & multiple linear regression.
- `Day4_Logistic_Regression.ipynb` → Implements binary classification using logistic regression.
- `airlines_flights_data.csv` → Dataset (optional, or provide download link).
- `README.md` → Project documentation.

---

## ⚙️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Day 3 - Linear Regression
- **Objective:** Predict flight prices based on days left & duration.
- **Steps:**
  1. Load and clean dataset.
  2. Select features (`days_left`, `duration`) and target (`price`).
  3. Train & test multiple linear regression model.
  4. Evaluate with R² score and Mean Squared Error (MSE).

---

## 🧠 Day 4 - Logistic Regression
- **Objective:** Classify flights into Economy or Business.
- **Steps:**
  1. Encode `class` as 0 (Economy) and 1 (Business).
  2. Select features (`price`, `days_left`, `duration`).
  3. Train Logistic Regression model.
  4. Evaluate with classification report & confusion matrix.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ML-Regression-Classification-Day-3-4.git
   cd ML-Regression-Classification-Day-3-4
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
