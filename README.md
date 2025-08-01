# stock-dashboard# 📊 Stock Market Dashboard | Power BI Project

This Power BI project is a comprehensive **Stock Market Dashboard** that enables interactive exploration of historical stock data for multiple top Indian companies over the years 2019–2024. It is designed to aid in visual analytics, pattern discovery, and comparative performance tracking across stocks.

---

## 📁 Project Summary

This dashboard lets users:

- Select and analyze individual stock performance from a wide list of companies.
- Track **Open**, **Close**, **High**, and **Low** prices annually and over time.
- Visualize historical data using **bar charts**, **area/line graphs**, and **detailed tables**.
- Gain quick insights with **KPI cards** for selected stock symbols.

---

## 🏦 Companies Included

The dashboard includes stock data for the following companies (as seen in the slicer panel):

- HDFCBANK
- AXISBANK
- BANKBARODA
- HEROMOTOCO
- HONDAPOWER
- ICICIBANK
- INFY (Infosys)
- MARUTI
- RELIANCE
- SBIN (SBI)
- TATAMOTORS
- TCS
- WIPRO


---

## 📊 Key Visuals

- **Slicer Panel** to switch between companies dynamically.
- **KPI Cards** showing total:
  - Open price
  - Close price
  - High price
  - Low price
- **Bar Charts**:
  - Year-wise comparison of Open vs Close.
  - Year-wise comparison of High vs Low.
- **Area/Line Chart** showing trends from 2019 to 2024.
- **Tabular View** listing daily data (Open, Close, High, Low) with totals.

---

## 🧮 Dataset

The dashboard uses a structured dataset, loaded via the following tables:

- `Stocks_Data` – Contains fields: Date, Symbol, Open, Close, High, Low.
- `Date_Category_Table` – Supports time-based aggregation.
- `Color Sheet` – Provides the color theme used in the visuals.

---

## ⚙️ Built With

- [Power BI Desktop](https://powerbi.microsoft.com/desktop)
- DAX (Data Analysis Expressions) for calculations
- Custom themes and UI formatting for consistency

---


## 🚀 How to Use

1. Clone or download this repository.
2. Open `Stock Trading Report.pbix` using Power BI Desktop.
3. Use the slicer on the left to select a company.
4. Interact with the charts and tables for deep insights.
5. Optionally, extend the dataset or add calculated measures (e.g., moving average, % change).

---

## 📌 Future Improvements

- Integrate live stock data using APIs (e.g., NSE/BSE or Yahoo Finance).
- Add more companies dynamically using parameterized datasets.
- Include technical indicators and predictive trends.
- Enable export options (PDF, Excel).

---



