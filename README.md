# 🧠 Predictive Maintenance using Linear Regression for Remaining Useful Life (RUL) Prediction

## 📋 Project Overview
This project focuses on predicting the **Remaining Useful Life (RUL)** of industrial machinery using **Linear Regression**.  
By analyzing sensor data such as vibration, temperature, runtime, and load, the model helps anticipate equipment failure and schedule maintenance proactively to minimize downtime and operational costs.

---

## 🎯 Objectives
- Predict the Remaining Useful Life (RUL) of machines.
- Identify relationships between sensor readings and degradation patterns.
- Build an interpretable ML model for predictive maintenance.
- Visualize insights and model performance metrics.

---

## 🧩 Dataset
- **Rows:** 500  
- **Columns:** vibration_mm_s, temperature_C, runtime_hours, load, RUL_hours  
- **Type:** Simulated real-world industrial dataset created using Python.  
- Machines with **higher runtime, temperature, load, and vibration** show **shorter RUL**, aligning with real industrial trends.

---

## 🧹 Data Preparation
- Checked for missing and duplicate values.
- Verified data types and statistical summary.
- Explored feature correlations and distributions.
- Standardized numerical features using `StandardScaler`.

---

## 📊 Exploratory Data Analysis (EDA)
- **Boxplots** for outlier detection.  
- **Scatter plots** between independent variables and RUL.  
- **Heatmap** to visualize correlations.

Key Insights:
- `runtime_hours` showed a **strong negative correlation** with RUL.  
- Other variables like vibration and load had **moderate negative impacts**.  

---

## ⚙️ Model Development
- **Algorithm Used:** Linear Regression  
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib  
- Data split into **80% training** and **20% testing**.  
- Standardized input features before model training.  

---

## 📈 Model Evaluation
| Metric | Value | Interpretation |
|:--|:--|:--|
| **R² Score** | ~0.81 | Strong model fit |
| **MAE** | ~374 hours | Low average error |
| **RMSE** | ~443 hours | Stable predictive accuracy |

✅ The model explains **81% of the variance** in RUL and shows realistic predictive capability.

---

## 📉 Visualization
- **Actual vs Predicted Plot** → Model predictions closely match real RUL values.  
- **Residuals Plot** → Random distribution, confirming model assumptions.  
- **Residuals Histogram** → Approximates normal distribution.

---

## 🧠 Insights
- Machines with higher runtime, vibration, and load tend to degrade faster.  
- Linear Regression provided **explainable and stable** predictions.  
- Scaling improved model interpretability.

---

## 🚀 Future Enhancements
- Incorporate additional features (e.g., pressure, humidity, fault count).  
- Experiment with **Ridge, Lasso, or Random Forest** for non-linear patterns.  
- Deploy model using Flask or Streamlit for real-time monitoring.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Tools:** Jupyter Notebook, GitHub  

---

## 📜 Author
**Anuj Tiwari**  
Data Analyst | Power BI Developer | Machine Learning Enthusiast  
📧 [Your Email Here]  
🌐 [LinkedIn / Portfolio Link]  

---

> ⭐ *If you found this project helpful, don’t forget to star the repository!*
