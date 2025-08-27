# COVID-19 Exploratory Data Analysis (EDA)

## 📌 Project Overview
This repository contains an **Exploratory Data Analysis (EDA)** of the **COVID-19 dataset provided by the World Health Organization (WHO)**. The aim of this project is to clean, process, and analyze the data to uncover patterns, trends, and insights into global and regional COVID-19 trends, including confirmed cases and deaths progress.

The dataset contains daily reported COVID-19 cases and deaths from **4th January 2020 to 3rd August 2025**.

## 📂 Dataset
- **Source:** [WHO COVID-19 Data](https://data.who.int/dashboards/covid19/data)  
- **Format:** CSV that is converted to Excel (`COVID-19 Dataset.xlsx`)  
 
The dataset includes the following columns:

- `Date_reported`: The date of reporting
- `Country`: Name of the country
- `WHO_region`: WHO designated region
- `New_cases`: New COVID-19 cases reported
- `Cumulative_cases`: Total cases reported till date
- `New_deaths`: New COVID-19 deaths reported
- `Cumulative_deaths`: Total deaths reported till date

> **Note:** Some countries have never reported COVID-19 cases or deaths.

## Objective
The main objectives of this EDA are:

1. Identify countries and regions most affected by COVID-19.
2. Analyze trends in cases and deaths over time.
3. Compare death ratios among different WHO regions.
4. Highlight countries with no reported COVID-19 cases or deaths.
5. Visualize insights through graphs like line plots, bar plots, pie charts, and heatmaps.

## Key Insights
- The **USA** recorded the highest number of COVID-19 cases and deaths.
- **Europe** reported the most cases regionally, while the **Americas** accounted for the highest deaths.
- Several countries have never reported any COVID-19 cases or deaths.
- Global death ratios vary significantly across WHO regions.

## Tools & Libraries
- Python (Pandas, NumPy)
- Matplotlib & Seaborn (Data Visualization)
- Jupyter Notebook (for analysis and reporting)

## 🔍 EDA Highlights
The analysis includes:  
- ✅ Data Cleaning & Preprocessing (handling missing values, formatting, standardization)  
- 📊 Trend Analysis (cases, deaths progress)  
- 🌍 Regional & Country-Level Comparisons  
- 📈 Time Series Visualization of case/death trends  
- 🧮 Statistical summaries and correlation checks  

## 📊 Visualizations
The EDA generates meaningful plots to understand the spread and impact of COVID-19:  
- Global and regional case trends  
- Daily vs cumulative case progression  
- Top affected countries analysis  
- Heatmaps, bar charts, and line plots  

*(Sample plots will be visible in the Jupyter Notebook provided in this repo.)*  

## 🛠️ Tools & Libraries
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook** for interactive analysis  

## 🚀 How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/sarthakdiwan01/covid-19-eda.git

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

3. Open the Jupyter Notebook to explore the analysis:  
   ```bash
   jupyter notebook


## 📌 Conclusion
This EDA provides a clearer picture of how COVID-19 evolved globally and regionally, and highlighting critical patterns progress. The analysis can serve as a foundation for further machine learning models or policy-based research.


---

Thank you for visiting my repository!  
Feel free to explore, learn, and connect with me.  
Your feedback and collaboration are always welcome!

---

## 🤝 Connect with Me  
- GitHub: [Sarthak Diwan](https://github.com/sarthakdiwan01)  
- LinkedIn: [Sarthak Diwan](https://www.linkedin.com/in/sarthakdiwan01)