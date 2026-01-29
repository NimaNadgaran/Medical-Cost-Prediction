# Comparison of Implementations ⚖️

This project provides **two approaches** for predicting medical insurance costs:  

1. **From Scratch (Manual Implementation)**  
2. **Using Libraries (Scikit-Learn, Pandas, Matplotlib)**  

Both use the same dataset, but they differ in **execution time, code complexity, and learning value**.  

---

## ⏱ Performance

| Approach           | Execution Time (full run) |
|--------------------|---------------------------|
| From Scratch       | **4 minutes 51 seconds** |
| With Libraries     | **2.5 seconds**           |

✅ The library-based implementation is **~116x faster** than the raw version.  

---

## 📑 Code Complexity

### From Scratch
- Implements **normalization, gradient descent, cost function, and regression manually**.  
- Requires explicit loops and mathematical calculations.  
- Provides **deep insight into how linear regression works internally**.  
- Much longer and harder to maintain.  

### With Libraries
- Uses **Scikit-learn’s `LinearRegression`** for training.  
- Handles normalization, fitting, and prediction with just a few lines of code.  
- More concise, readable, and **production-ready**.  
- Easier to extend (e.g., adding regularization, scaling, or cross-validation).  

---

## 📊 Results & Accuracy

- Both implementations **converge to similar predictions**.  
- Visualizations (scatter plots, actual vs predicted) look almost identical.  
- The main difference is **speed and ease of use**.  

---

## 🎯 Learning Value

- **From Scratch Version** → Excellent for **students and beginners** who want to *see the math in action*.  
- **Library Version** → Ideal for **practitioners and real-world projects**, where speed and reliability matter more.  

---

## 📝 Conclusion

- If your goal is to **learn the fundamentals** → use the **from-scratch version**.  
- If your goal is to **build a real ML pipeline quickly** → use the **library version**.  

👉 Both approaches complement each other:  
- One gives you **knowledge of the core mechanics**.  
- The other gives you **efficiency and practicality**.  

---
