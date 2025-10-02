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
```bash
Medical-Cost-Prediction/
├── README.md                  # Project overview (this file)
├── requirements.txt           # Python dependencies
│
├── from_scratch/              # Manual implementation
│   ├── insurance_regression_raw.py
│   └── explanation_raw.md
│
├── with_libraries/            # Library-based implementation
│   ├── insurance_regression_libs.py
│   └── explanation_libs.md
│
└── data/                      # Dataset & documentation
    ├── Medical-Insurance.csv
    ├── LICENSE                # License for dataset + code
    └── README.md              # Dataset description
```

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
