# 📈 Sales Forecasting Dashboard

Forecasting future sales trends using historical retail data with **Python** and **Google Colab**.



## 📁 Dataset

* **Source**: Retail sales dataset (daily, weekly, or monthly).
* **Description**: Contains historical sales records used for building a **time series forecasting model**.



## 🎯 Project Overview

* **Task**: Build a dashboard that predicts **future sales trends** using historical data.
* **Skills Gained**:

  * ⏳ Time Series Forecasting
  * 📊 Regression Analysis
  * 🔄 Trend & Seasonality Analysis
  * 📉 Data Visualization in Colab
* **Deliverable**: A forecasting model with **interactive plots and visualizations** showing predicted trends, seasonality, and forecast results.



## 🛠 Tools & Libraries Used

* **Python** → `Prophet`, `scikit-learn`, `pandas`, `numpy`
* **Visualization** → `matplotlib`, `seaborn`
* **Platform** → Google Colab



## ⚙️ Steps Followed

<details>  
<summary>📌 1. Data Preparation</summary>  

* Loaded retail sales dataset.
* Converted date column to `datetime` format.
* Resampled data (daily/weekly/monthly).
* Handled missing values and outliers.

</details>  

<details>  
<summary>📊 2. Exploratory Data Analysis (EDA)</summary>  

* Visualized **sales trends** over time.
* Identified **seasonal patterns** (weekly/monthly cycles).
* Checked effect of **holidays/events** on sales.

</details>  

<details>  
<summary>🤖 3. Model Building</summary>  

* Implemented **Prophet** for time series forecasting.
* Compared with regression-based models (`LinearRegression`, `RandomForestRegressor`).
* Generated predictions for future sales.

</details>  

<details>  
<summary>📏 4. Model Evaluation</summary>  

* Metrics used:

  * MAE (Mean Absolute Error)
  * RMSE (Root Mean Squared Error)
  * MAPE (Mean Absolute Percentage Error)
* Prophet outperformed regression models in **trend & seasonality detection**.

</details>  

<details>  
<summary>📊 5. Visualization in Google Colab</summary>  

* Forecast plots with confidence intervals.
* Trend and seasonality decomposition using Prophet.
* Interactive matplotlib/seaborn plots for analysis.

</details>  

## 📊 Key Results

* ✅ **Prophet captured seasonal and trend components effectively.**
* 📈 Forecasts showed **increasing sales in festive/holiday months**.
* 📉 Certain months showed **predictable dips**, useful for planning.
* 🚀 Colab notebooks provided **interactive plots for decision-making**.


## 📌 How to Run

### ▶️ Run in Google Colab

1. Upload the dataset to Colab.
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn prophet
   ```
3. Run the notebook:

   * Open `Sales_Forecasting.ipynb` in **Google Colab**.
   * Execute cells step by step to generate results and visualizations.

✨ This project combines **time series forecasting + interactive visualization** in Google Colab to provide actionable insights into sales performance.

