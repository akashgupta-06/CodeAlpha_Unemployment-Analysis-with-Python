# Unemployment Analysis in India Using Python

## 📘 Overview

- This project explores unemployment trends across Indian states, with special focus on the Covid-19 pandemic period. Using Python-based Exploratory Data Analysis (EDA), interactive visualizations, and extracted insights, the project reveals labour market patterns, regional disparities, and temporal fluctuations in unemployment.

## 🎯 Objectives
- The main objective of this analysis is to understand India’s unemployment behaviour during the Covid-19 period. Specifically, we aim to:
- Analyze unemployment trends across Indian states over time
- Measure the impact of Covid-19 on unemployment and labour participation
- Compare regional variations across different states
- Identify seasonal or cyclical trends
- Create visual insights using Python libraries
- Provide data-driven insights that can support policy decisions

## 📊 Dataset Information

- This dataset contains unemployment-related metrics for multiple states of India.
- Features:
  - Region → Indian states
  - Date → Observation date
  - Frequency → Monthly observations
  - Estimated Unemployment Rate (%) → % of unemployed people
  - Estimated Employed → Total employed population
  - Estimated Labour Participation Rate (%) → Share of active labour force

## 🧮 Feature Engineering
- To enhance analysis and uncover deeper insights, we created several new features:
  - Month & Year → Extracted from Date
  - Total Working Population → Derived from LPR and employed values
  - Estimated Unemployed (%) → Share of unemployed individuals
  - Estimated Employed Percentage → Employment share in workforce
  - Estimated Employment Rate (%) → Refined employment rate per area

## 🔍 Key Insights
📌 Labour Participation Rate (LPR)
  - Approximately normally distributed
  - Outliers indicate unusual labour movements
  - Sharp dips and spikes during Covid lockdowns

📌 Unemployment Rate (UR)
  - Positively skewed
  - Significant surge from mid-2019 to mid-2020
  - Reflects the shock caused by Covid-19 restrictions

📌 Employment Rate (ER)
  - Mirrors unemployment rate but in reverse
  - Some states recovered faster than others
  - Uneven distribution reflects workforce vulnerability

📌 Regional Patterns
  - East & South → Higher fluctuations
  - West & North → Relatively stable
  - Indicates structural and policy-based differences

📌 Temporal Analysis
  - Lockdown months (Apr–May 2020) show severe unemployment spikes
  - Heatmaps reveal month-to-month instability
  - Line plots show a V-shaped recovery pattern post-lockdown

## 📈 Visualizations Used
- Distribution plots
- Heatmaps
- Line plots
- Bar charts
- Time-series trend analysis
- Regional comparisons

## 🧠 Key Takeaways
- Covid-19 caused an unprecedented shock to India's labour market
- Unemployment spiked, participation dropped, and recovery was uneven
- Regional disparities highlight vulnerable sectors and workforce groups
- Continuous data monitoring is essential for timely policy intervention

## 🛠️ Tech Stack
- Tools: Python
- Libraries:	Pandas, NumPy, Matplotlib, Seaborn, Plotly
- Environment:	Jupyter Notebook / VS Code
- Dataset:	Unemployment Data (Monthly, India)

## 🚀 Future Improvements
- Add forecasting using ARIMA / Prophet models
- Build an unemployment dashboard using Plotly Dash or Streamlit
- Perform clustering to identify labour market segments
- Include socio-economic indicators for deeper correlation analysis

  
