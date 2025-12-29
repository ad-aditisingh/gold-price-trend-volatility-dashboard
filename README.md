# Indian Gold Price Trend & Volatility Analysis (Power BI)

This project presents a **data-driven analysis of historical gold prices** using **Power BI**, with a focus on understanding **price trends** and **market volatility** rather than prediction or trading advice.

The dashboard is designed as a **business intelligence and decision-support analysis**, highlighting how gold prices have behaved over time and how stable or unstable different periods were.

---

##  Project Objectives

- Analyze long-term **gold price trends** using time-series data  
- Smooth short-term fluctuations using a **30-day moving average**  
- Measure and visualize **price volatility** to identify unstable periods  
- Present insights clearly through professional Power BI dashboards  

This project intentionally avoids forecasting or buy/sell recommendations and focuses purely on **interpretation and insight**.

---

## Dataset Description

The dataset consists of **daily historical gold market data**, including:

- Date  
- Open price  
- High price  
- Low price  
- Closing price  
- Trading volume  
- Daily percentage change  

The data is stored in CSV format and imported directly into Power BI for analysis.

---

##  Dashboard Pages & Analysis

###  Trend Analysis

**Purpose:**  
To understand the overall direction of gold prices over time.

**What is shown:**
- Daily gold prices plotted over time  
- A **30-day moving average** to smooth short-term noise  
- Comparison between raw prices and the underlying trend  

**Key insight:**  
The moving average helps reveal the long-term price direction by reducing daily fluctuations.

---

###  Volatility Analysis

**Purpose:**  
To understand how **stable or unstable** gold prices were across different periods.

**What is shown:**
- Monthly average price volatility calculated using the **High–Low daily range**  
- Aggregation to monthly level to improve readability and reduce noise  

**Key insight:**  
Periods of heightened volatility often correspond to broader market uncertainty, while flatter sections indicate more stable pricing environments.

---

## Tools & Technologies Used

- **Power BI Desktop** – Data modeling, visualization, and analysis  
- **DAX** – Moving average and volatility calculations  
- **CSV (Time-Series Data)** – Historical gold price data  
- **GitHub** – Project hosting and documentation  

---

##  Repository Structure
gold-price-trend-volatility-dashboard/
│
├── data/
│ └── gold_price_india.csv
│
├── dashboard/
│ └── gold.pbix
│
├── screenshots/
│ ├── trend_analysis.png
│ └── volatility_analysis.png
│
└── README.md

---

##  Dashboard Access

Due to **organizational Power BI tenant restrictions**, the **Publish to Web** feature is disabled.

- The **full interactive dashboard** is provided as a `.pbix` file in this repository  
- The report can be opened locally using **Power BI Desktop**  
- Screenshots are included for quick preview of the visuals  

This is a common limitation in work/school Power BI environments and does not affect the analysis itself.

---

##  Disclaimer

This project is created **strictly for academic and analytical purposes**.  
It does **not** provide financial advice, investment recommendations, or price predictions.

---

##  Key Learning Outcomes

- Working with time-series data in Power BI  
- Implementing rolling averages using DAX  
- Understanding the difference between **trend** and **volatility**  
- Choosing appropriate data aggregation levels for readability  
- Communicating insights through clean, professional dashboards  

---

##  Author

This project was developed as a **self-learning data analysis project** to build skills relevant to **data analytics, business intelligence, and MBA-oriented roles**.


