🌍 COVID-19 Time Series Forecasting & Interactive Visualizations
<p align="center"> <img width="100%" src="https://readme-typing-svg.herokuapp.com?font=Roboto+Slab&weight=600&size=32&pause=1000&color=2E86C1&center=true&vCenter=true&width=900&lines=COVID-19+Time+Series+Forecasting;Interactive+World+Map+%7C+Prophet+%7C+Plotly;By+Darshan+Pakhale" /> </p> <p align="center"> <img src="https://img.shields.io/badge/License-MIT-green.svg" /> <img src="https://img.shields.io/badge/Python-3.10-blue.svg" /> <img src="https://img.shields.io/badge/Prophet-Forecasting-orange.svg" /> <img src="https://img.shields.io/badge/Plotly-Interactive-lightgrey.svg" /> <img src="https://img.shields.io/badge/Status-Production--Ready-blue.svg" /> </p>
📌 Executive Summary

This project performs end-to-end analysis, forecasting, and visualization of global COVID-19 data using cutting-edge time series techniques.
It combines:

Data engineering

Exploratory Data Analysis (EDA)

Facebook Prophet forecasting

Animated Plotly world maps

Clean modular Python code

The result is a complete data science case study.

🎯 Project Goals
✔️ Understand global COVID-19 trends
✔️ Build robust forecasting models
✔️ Visualize COVID spread across time and countries
✔️ Generate interactive animated maps
✔️ Deliver production-ready analysis notebooks
✔️ Provide clean and reusable code modules
📊 Dataset Information

Dataset Link : https://drive.google.com/file/d/1XTw0I6x8x0TBWm14MCcQwHVCgnbW0J_A/view?usp=sharing

Time span: January 2020 – December 2021

Granularity: Country-level

Features:

Confirmed

Deaths

Recovered

Active

🏗️ System Architecture
            ┌────────────────────┐
            │ Raw COVID Dataset  │
            └─────────┬──────────┘
                      │
                      ▼
        ┌────────────────────────────────┐
        │   Data Cleaning & Processing   │
        └────────────────────────────────┘
                      │
                      ▼
        ┌────────────────────────────────┐
        │ Exploratory Data Analysis (EDA)│
        └────────────────────────────────┘
                      │
                      ▼
         ┌─────────────────────────────┐
         │ Prophet Time Series Models  │
         └─────────────────────────────┘
                      │
                      ▼
     ┌────────────────────────────────────────┐
     │ Animated Plotly Visualizations (Maps) │
     └────────────────────────────────────────┘
                      │
                      ▼
            ┌───────────────────────┐
            │ Forecast Exports CSV  │
            └───────────────────────┘
📂 Folder Structure
COVID19-TimeSeries-Forecasting/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── data/
│   ├── raw/
│   │   └── Covid_19_Clean_Complete.csv
│   ├── processed/
│   │   ├── df_confirm.csv
│   │   ├── df_active.csv
│   │   ├── df_deaths.csv
│   │   └── df_recover.csv
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Prophet_Forecasting.ipynb
│   ├── 03_Animated_World_Map.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── prophet_models.py
│   ├── visualization.py
│   ├── animated_map.py
│   └── utils.py
│
├── outputs/
│   ├── plots/
│   ├── forecasts/
│   └── animations/
│
└── docs/
    └── report.md
🔍 Exploratory Data Analysis (EDA)

The EDA notebook includes:

Daily and cumulative trends

Country-wise comparison

Growth rate analysis

Lag and correlation plots

Multi-line trend graphs

Subplots for Recovered, Deaths, Active

🔮 Forecasting (Prophet)

Prophet is used to forecast:

Model	Target Variable
model_confirm	Confirmed Cases
model_active	Active Cases
model_deaths	Deaths
model_recover	Recovered

Each model produces:

Forecast plots

Confidence intervals

Component plots

Trend analysis

Exports are saved in:
/outputs/forecasts/

🌐 Animated World Map (Plotly)
Features:

2×2 facet grid of Confirmed, Deaths, Recovered, Active

Smooth time animation slider

Beautiful Viridis color scale

Hover tooltips for every country

Perfect for GitHub and dashboards

🛠️ Installation
git clone https://github.com/YOUR_USERNAME/COVID19-TimeSeries-Forecasting.git
cd COVID19-TimeSeries-Forecasting
pip install -r requirements.txt

▶️ Usage
notebooks/01_EDA.ipynb
Run Forecasting
notebooks/02_Prophet_Forecasting.ipynb

📈 Example Forecast Plot
yhat (forecast)
yhat_lower (lower bound)
yhat_upper (upper bound)


Prophet automatically handles:

Trend

Seasonality

Holiday effects

Noise smoothing

🚀 Future Improvements

Add LSTM + Prophet hybrid model

Add ARIMA / SARIMA comparison

Create dashboard using Streamlit

Add regional/state-level maps

Add anomaly detection

🧑‍💻 Author

Darshan Pakhale

Machine Learning & Data Science Enthusiast

Pune , India

🌐 GitHub: https://github.com/darshanpakhale250-gif

🔗 LinkedIn: https://www.linkedin.com/in/darshan-pakhale-a97b12329/

📜 License

This project is released under the MIT License.

India / Maharastra

