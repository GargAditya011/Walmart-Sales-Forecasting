# Walmart Weekly Sales Forecasting 🛒📈

## Project Overview
This project focuses on predicting weekly sales for **Walmart** stores across multiple departments. By leveraging historical sales data and external factors (like holidays and economic indicators), the goal is to provide a robust forecasting model that helps in inventory management and labor planning.

The project follows a complete Data Science lifecycle:  
**Data Cleaning** → **EDA** → **Feature Engineering** → **Model Diagnostics** → **Forecasting**

---

## 📊 Key Insights & Results
* **Seasonality:** Sales show significant spikes during the **Q4 holiday season** (specifically Thanksgiving and Christmas), with notable dips immediately following.
* **Model Performance:** The diagnostic plots (Residuals, Q-Q, and ACF) confirm that the model effectively captured the time-series patterns.
* **Impact of Holidays:** Integrated holiday flags to account for the "Super Bowl," "Labor Day," "Thanksgiving," and "Christmas" sales surges.

---

## 🛠️ Technical Stack
* **Language:** Python 3.x
* **Data Analysis:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Statistical Modeling:** `Statsmodels` (SARIMA/ARIMA modeling)
* **Environment:** Jupyter Notebook

---

## 📁 Repository Structure
* `Final_Walmart_Project.ipynb`: The main execution file containing code, visualizations, and model training.
* `Walmart Sales project- Problem Statement.pdf`: Detailed project documentation, problem statement, and methodology.

---

## 🧪 Model Diagnostics
The project utilizes advanced diagnostic checks to ensure forecast reliability:
* **Standardized Residuals:** Checked for constant mean and variance (White Noise).
* **Histogram + KDE:** Verified that residuals are approximately normally distributed.
* **Normal Q-Q Plot:** Confirmed the distribution of errors aligns with theoretical quantiles.
* **Correlogram (ACF):** Validated that no leftover patterns exist in the residuals.

---

## 🚀 How to Run
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/walmart-sales-forecasting.git](https://github.com/your-username/walmart-sales-forecasting.git)

2. **Install dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels

3. **Execute the notebook:**
   Open Final_Walmart_Project.ipynb in Jupyter or VS Code and run all cells.


## 👨‍💻 Author

**Aditya Garg**

* **Education:** B.Tech in CSE (Data Science) | Ajay Kumar Garg Engineering College , Ghaziabad (AKGEC)
* **Certification:** Professional Data Science & Artifical Intelligence Certified from Drishti CPS IIT Indore

---
