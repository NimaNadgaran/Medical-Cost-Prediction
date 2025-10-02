# Medical Insurance Dataset 📊

This dataset contains information about individuals and their corresponding **medical insurance charges**.  
It is often used to study **linear regression, health economics, and predictive modeling**.

---

## 📂 Dataset Details

- **File Name:** `Medical-Insurance.csv`  
- **Rows:** ~1,300 entries (each representing a person)  
- **Columns:** 7 features (independent variables) + 1 target (dependent variable)  

---

## 📑 Columns Description

1. **Age** *(integer)*  
   - Age of the primary beneficiary (in years).  
   - Typically ranges from **18 to 64** in this dataset.  

2. **Sex** *(categorical: male/female)*  
   - Gender of the insured individual.  
   - Encoded as **Male** or **Female**.  

3. **BMI (Body Mass Index)** *(float)*  
   - Objective index of body weight using height and weight:  
     \[
     BMI = \frac{weight(kg)}{height(m)^2}
     \]  
   - A BMI between **18.5 and 24.9** is considered healthy.  
   - Higher BMI may correlate with higher medical costs.  

4. **Children** *(integer)*  
   - Number of children/dependents covered by health insurance.  
   - Ranges from **0 to 5**.  

5. **Smoker** *(categorical: yes/no)*  
   - Whether the individual is a smoker.  
   - Smoking has a **strong impact on insurance charges**.  

6. **Region** *(categorical: northeast, northwest, southeast, southwest)*  
   - The residential region of the insured within the United States.  
   - Can help identify regional cost differences.  

7. **Charges** *(float, USD)*  
   - The **target variable** — annual medical insurance costs billed by the insurance provider.  
   - Ranges widely, from a few thousand dollars to over **$60,000**.  

---

## 🧾 Example Row

| Age | Sex   | BMI   | Children | Smoker | Region    | Charges   |
|-----|-------|-------|----------|--------|-----------|-----------|
| 19  | Female| 27.9  | 0        | Yes    | Southwest | 16,884.92 |

---

## 🔍 Insights

- **Age** → Insurance cost generally increases with age.  
- **BMI** → Higher BMI may increase costs due to health risks.  
- **Smoker** → Smokers tend to have **significantly higher charges** than non-smokers.  
- **Children** → More dependents slightly increase costs.  
- **Region** → Some regional differences exist but are less significant.  

---

## 📜 License

The dataset is released under the **MIT License**:  
- Copyright (c) 2013 Mark Otto  
- Copyright (c) 2017 Andrew Fong  

See [LICENSE](../LICENSE) for details.  

---

## ✨ Usage

This dataset is widely used for:  
- Linear Regression & Gradient Descent exercises  
- Machine Learning practice with Scikit-learn  
- Data preprocessing, feature engineering, and visualization projects  

---
