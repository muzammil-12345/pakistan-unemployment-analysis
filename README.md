# 📊 Unemployment Analysis in Pakistan (1991–2024)

**Author:** Muzammil Zulfiqar  
**Date:** August 2025  
**Contact:** via [GitHub Profile](https://github.com/muzammil-12345)

---

## 📌 Overview
This project analyzes unemployment trends in Pakistan over a 33-year period (1991–2024).  
The analysis covers:
- Long-term trends in unemployment rates.
- The impact of the COVID-19 pandemic.
- Comparison between total and youth unemployment rates.
- Year-to-year changes and patterns.

The dataset was compiled from **World Bank (ILO estimates)** and includes both **total unemployment** and **youth unemployment (ages 15–24)** where available.

---

## 📂 Dataset Information
**Columns:**
- `year` – Year of observation.
- `unemployment_rate_total` – Total unemployment (% of total labor force).
- `unemployment_rate_youth` – Youth unemployment (% of labor force ages 15–24).

**Data Source:**  
World Bank – ILO Modeled Estimates of Labor Force Statistics

---

## ⚙️ Technologies Used
- **Python**
- **Pandas** – data cleaning and processing
- **Matplotlib & Seaborn** – visualizations
- **Jupyter Notebook** – analysis environment

---

## 📈 Analysis Steps
1. **Data Cleaning**
   - Checked for missing values.
   - Ensured numeric types for plotting.
   
2. **Exploratory Data Analysis**
   - Overall unemployment trend (1991–2024)
   - Pre- vs Post-COVID unemployment rate comparison
   - COVID-19 year-specific unemployment analysis
   - Year-to-year unemployment rate changes

3. **Visualization**
   - Line charts for long-term trends
   - Bar charts for COVID years
   - Change analysis using color-coded bars

---

## 🔍 Key Findings
- **COVID-19 Impact:** Unemployment rose noticeably in 2020–2021 compared to pre-pandemic years.
- **Youth Unemployment:** Consistently higher than the total unemployment rate.
- **Recovery:** Unemployment started to decline after 2022 but remains above pre-COVID levels.
- **Volatility:** The most significant changes occurred between 2019 and 2021.

---

## 🛠 Policy Implications
- Launch targeted **youth employment programs**.
- Strengthen **crisis-response mechanisms** for labor markets.
- Encourage **investment in labor-intensive industries**.
- Implement **regional monitoring** to address high-unemployment zones.
- Increase **data transparency** and **survey frequency**.

---

## 🚀 How to Run the Project
1. **Clone the repository** or download the files.
2. Ensure Python 3.x is installed.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
