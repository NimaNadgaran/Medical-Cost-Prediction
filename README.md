# Medical Cost Prediction (Linear Regression)

This project predicts **medical insurance charges** based on factors such as **age, BMI, smoking status, number of children, region, and more**.  

It contains **two implementations**:

1. **From Scratch (Manual Implementation)**  
   - Implements data preprocessing, normalization, gradient descent, and linear regression manually.  
   - Useful for learning the math and internals of regression.  

2. **Using Libraries (Scikit-Learn, Pandas, Matplotlib)**  
   - Uses `LinearRegression` from `scikit-learn` for a faster and cleaner implementation.  
   - Optimized, easier to maintain, and production-ready.  

---

## 📂 Project Structure
Medical-Cost-Prediction/
│── README.md

│── LICENSE

│── requirements.txt

│
├── from_scratch/

│ ├── insurance_regression_raw.py # Manual gradient descent & regression

│ └── explanation_raw.md # Step-by-step explanation

│
├── with_libraries/
│ ├── insurance_regression_libs.py # Using sklearn & pandas
│ └── explanation_libs.md # Walkthrough of library-based solution
│
└── data/
└── Medical-Insurance.csv # Dataset (MIT Licensed, see LICENSE)

---

## 🚀 How to Run

1. Clone the repo:  
   ```bash
   git clone https://github.com/NimaNadgaran/Medical-Cost-Prediction.git
   cd Medical-Cost-Prediction

2. Install requirements:
   pip install -r requirements.txt


3. Run either implementation:

   # From scratch
   python from_scratch/insurance_regression_raw.py  

   # With libraries
   python with_libraries/insurance_regression_libs.py


   ---

## 📜 License

This project uses the **Medical Insurance dataset** released under the [MIT License](./LICENSE).  
Copyright (c) 2013 Mark Otto, 2017 Andrew Fong.  

The code in this repository is also released under the MIT License.  
