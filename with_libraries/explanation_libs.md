# Library-Based Implementation (Scikit-Learn)

This version uses **pandas**, **matplotlib**, and **scikit-learn** for a faster, cleaner, and production-ready solution.

---

## ⚡ Steps Implemented

1. **Data Preprocessing**
   - Used pandas to clean missing data.
   - Converted categorical variables (like smoker/region) using one-hot encoding if needed.

2. **Train/Test Split**
   - Used `train_test_split` from sklearn.
   - Ensures a proper random split.

3. **Normalization (optional)**
   - Used `StandardScaler` from sklearn for scaling.

4. **Model Training**
   - Used `LinearRegression` from sklearn.
   - Fit model on training data in just one line.

5. **Evaluation**
   - Predicted on test data.
   - Calculated MSE and R² score.
   - Plotted Actual vs Predicted charges.

---

## 📊 Results

- Model trains instantly compared to manual gradient descent.
- Predictions are more stable and accurate.
- Sklearn provides useful metrics like R² score out of the box.

---

## 📌 Learning Outcome

- Difference between **manual vs. library-based** approaches.
- Why production systems should use optimized libraries.
- How to evaluate ML models effectively using sklearn.
