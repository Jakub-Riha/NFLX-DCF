# 📽️ Discounted Cash Flow Valuation of Netflix (NFLX)

A standalone DCF valuation model built in Excel to assess the intrinsic value of Netflix Inc. (NASDAQ: NFLX), as part of a university stock pitch (2024 UTEFA Stock Pitch).

---

## 📄 Project Description

This repository contains an Excel-based financial model that forecasts Netflix’s revenue, margins, reinvestment needs, and derives intrinsic equity value using unlevered free cash flows and terminal value analysis. The model includes historical financials, forward projections, and sensitivity switches. It also contains the stock pitch presentation PDF file.

The project was completed using public data, and structured in the style of a buy-side analyst’s DCF model. It is designed to be reusable and auditable.

---

## 🗂️ Files

- `DCF Netflix.xlsx` — Core financial model with the following sheets:
  - `Assumptions`: key operating drivers, WACC inputs, valuation setup  
  - `Income Statement`: historical and projected operating performance  
  - `Cashflow`: unlevered free cash flow calculation  
  - `CDF`: cumulative discount factors and valuation bridge
 
- `Netflix_Presentation.pdf` — Stock Pitch presentation

> *Note:* All values are based on illustrative estimates and publicly available data as of the model creation date.

---

## 💻 Model Features

- Revenue growth and margin forecasts tied to operating assumptions  
- Capex, working capital, and tax rate assumptions modeled explicitly  
- Terminal value calculated using both perpetual growth and exit multiple approaches  
- Intrinsic value per share estimate with sensitivity tables  
- Transparent, editable structure suitable for future reuse  

---

## 🔁 How to Use

1. Open `DCF Netflix.xlsx` in Excel (Microsoft 365 recommended)  
2. Begin in the `Assumptions` sheet to view or modify key inputs  
3. Navigate to `CDF` for valuation mechanics  
4. Use the sensitivity switch to change assumption values to analyse the impact of different scenarios  

---

## ⚙️ Dependencies

- **Software:** Microsoft Excel (Office 2019 or later recommended)  
- **Macros:** None — all calculations are formula-based  

---

## ⚠️ Limitations

- The model is static and based on dated public information; no real-time data is integrated  
- It does not incorporate comparable company analysis or trading multiples
- Not investment advice; built for educational and illustrative purposes only
- This project was completed while I was in my third year in undergrad.
