---

### 2. **from_scratch/explanation_raw.md**  

markdown
# From Scratch Implementation (Manual Gradient Descent)

This version of the project is built **without ML libraries** to understand the internals of linear regression.

---

## ⚡ Steps Implemented

1. **Data Preprocessing**
   - Replaced invalid entries with column mean values.
   - Converted dataset into lists for manual processing.

2. **Normalization**
   - All features and targets are scaled to the range [0, 1].
   - Prevents features with large values (like charges) from dominating.

3. **Visualization**
   - Scatter plots for each feature vs insurance charges.
   - Helps to understand which features strongly correlate with costs.

4. **Linear Regression with Gradient Descent**
   - Implemented functions:
     - mat_mul()` → manually multiply weights & features.
     - mse()` → mean squared error calculation.
     - gd()` → gradient descent update.
   - Iterated thousands of times until weights converged.

5. **Evaluation**
   - Computed MSE on both training and test sets.
   - Compared actual charges vs predicted charges.

---

## 📊 Results

- The model learns weights slowly but converges after ~50,000 iterations.
- Predictions are reasonable but not as accurate as scikit-learn’s optimized version.
- Great for understanding how **gradient descent** works behind the scenes.

---

## 📌 Learning Outcome

- How gradient descent minimizes error step by step.
- Why normalization is necessary.
- How to manually build regression without external ML libraries.
