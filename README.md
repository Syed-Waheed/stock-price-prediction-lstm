<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=260&section=header&text=Stock%20Market%20Prediction&fontSize=70&animation=fadeIn&fontAlignY=38&desc=LSTM%20•%20Deep%20Learning%20•%20Time-Series%20Forecasting&descAlignY=55&descAlign=50" alt="Stock Market Prediction Header" />

  <br />

  <p>
    <a href="https://waheed-stock-price-prediction-lstm.streamlit.app/">
      <img src="https://img.shields.io/badge/Streamlit-Live_App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit App" />
    </a>
    <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/TensorFlow-LSTM-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  </p>

  <h3>🚀 Forecasting the Future with Deep Learning</h3>
  
  <p align="center">
    <i>"An automated end-to-end pipeline leveraging LSTM neural networks to predict stock market trends with high accuracy."</i>
  </p>
</div>

---

## 📈 Overview

This project addresses the challenging task of **stock market prediction** by leveraging the power of **Recurrent Neural Networks (RNNs)**. 

We utilize a **Long Short-Term Memory (LSTM)** architecture trained on historical data (2015–Present) to identify complex temporal patterns and forecast the next day’s closing price. The entire pipeline—from **data acquisition** to **model training** and **deployment**—is automated.

---

## 📸 Demo & Output

### 🎯 Live Prediction Dashboard
<div align="center">
  <img src="Results/Output.png" alt="Streamlit Output" width="800" style="border-radius: 10px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);" />
</div>

<br />

### 📊 Comprehensive Model Plots
<div align="center">
  <img src="Results/all_stock_plots.png" alt="All Stock Plots" width="800" style="border-radius: 10px;" />
</div>

---

## ✨ Key Features

- 🧠 **Deep Learning Core**: Robust LSTM neural network optimized for time-series forecasting.
- 🤖 **Automated Pipeline**: Single script handles fetching, preprocessing, and training for **20+ stocks**.
- 🌐 **Interactive Web Interface**: Clean, responsive Streamlit dashboard for real-time user interaction.
- 📊 **Instant Inference**: Select any stock ticker to get immediate next-day price predictions.
- 📈 **Visual Analytics**: Interactive Plotly graphs comparing Predicted vs. Actual values.
- 🔁 **Reproducibility**: Fixed random seeds ensure consistent training results every run.

---

## 🛠 Technology Stack

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Language** | ![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=python) | Core logic and scripting |
| **Modeling** | ![TensorFlow](https://img.shields.io/badge/-TensorFlow-black?style=flat-square&logo=tensorflow) | Building LSTM Architecture |
| **Frontend** | ![Streamlit](https://img.shields.io/badge/-Streamlit-black?style=flat-square&logo=streamlit) | Web Application Interface |
| **Data Ops** | ![Pandas](https://img.shields.io/badge/-Pandas-black?style=flat-square&logo=pandas) | Data manipulation & Preprocessing |
| **Source** | ![Yahoo](https://img.shields.io/badge/-yFinance-black?style=flat-square) | Real-time Stock Data API |
| **Viz** | ![Plotly](https://img.shields.io/badge/-Plotly-black?style=flat-square&logo=plotly) | Interactive Charts |

---

## 📊 Model Performance

The models were trained on historical data with an **80/20 train-test split**. Below is the performance summary ranked by accuracy (R² Score):

| Rank | Stock Ticker | R² Score | RMSE (₹) | Performance Verdict |
|:---:|:---|:---:|:---:|:---|
| 🥇 | **WIPRO.NS** | **94.37%** | ₹7.38 | 🟢 **Excellent** |
| 🥈 | **ICICIBANK.NS** | **94.19%** | ₹40.52 | 🟢 **Excellent** |
| 🥉 | **ASIANPAINT.NS** | **94.11%** | ₹88.09 | 🟢 **Excellent** |
| 4 | INFY.NS | 92.88% | ₹51.28 | 🟢 Excellent |
| 5 | LT.NS | 92.61% | ₹79.49 | 🟢 Excellent |
| 6 | HCLTECH.NS | 90.98% | ₹66.22 | 🟢 Very Good |
| 7 | BAJFINANCE.NS | 90.88% | ₹27.04 | 🟢 Very Good |
| 8 | TCS.NS | 90.54% | ₹112.43 | 🟢 Very Good |
| 9 | HINDUNILVR.NS | 89.85% | ₹52.49 | 🟢 Very Good |
| 10 | DMART.NS | 89.64% | ₹163.88 | 🟢 Very Good |
| 11 | SBIN.NS | 88.48% | ₹33.15 | 🟡 Good |
| 12 | KOTAKBANK.NS | 88.01% | ₹52.00 | 🟡 Good |
| 13 | AXISBANK.NS | 87.87% | ₹30.05 | 🟡 Good |
| 14 | MARUTI.NS | 87.63% | ₹358.22 | 🟡 Good |
| 15 | HDFCBANK.NS | 86.10% | ₹64.62 | 🟡 Good |
| 16 | BHARTIARTL.NS | 84.78% | ₹132.57 | 🟡 Decent |
| 17 | ITC.NS | 84.13% | ₹11.30 | 🟡 Decent |
| 18 | RELIANCE.NS | 80.20% | ₹53.19 | 🟡 Decent |
| 19 | TITAN.NS | 77.09% | ₹99.99 | 🟠 Fair |
| 20 | ULTRACEMCO.NS | 73.44% | ₹652.85 | 🟠 Fair |

---

## ⚙️ Local Setup

Follow these steps to run the project locally on your machine:

```bash
# 1. Clone the repository
git clone [https://github.com/Syed-Waheed/stock-price-prediction-lstm.git](https://github.com/Syed-Waheed/stock-price-prediction-lstm.git)

# 2. Navigate to the directory
cd stock-price-prediction-lstm

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit App
streamlit run app.py
```
---

## 👤 Author

<div align="left">
  <img src="https://github.com/Syed-Waheed.png" width="100" align="left" style="margin-right: 20px; border-radius: 50%;" alt="Syed Abdul Waheed" />

  **Syed Abdul Waheed**  
  *Data Science Enthusiast | Python Developer | Automation Explorer*

  Passionate about bridging the gap between data and actionable insights through Deep Learning.

  <br />

  <a href="https://www.linkedin.com/in/syed-abdul-waheed/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Syed-Waheed">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
</div>

<br clear="left"/>

<div align="center">
  <p>If you found this project useful, please ⭐ the repository!</p>
</div>

---


