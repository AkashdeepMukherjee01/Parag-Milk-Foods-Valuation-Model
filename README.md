# Parag-Milk-Foods-Valuation-Model

## 📌 Project Overview
This repository contains a fully integrated, institutional-grade 3-statement financial model and valuation for Parag Milk Foods. Built to support a formal equity research investment thesis, the model analyzes 5 years of historical performance to project dynamic revenue, working capital, and depreciation schedules, forecasting top-line expansion from ₹34.3B to ₹57.5B over a 5-year forecast period (FY26–FY31).

## ⚙️ Valuation Methodologies & Mechanics
The analysis triangulates the company's intrinsic and relative value using three primary approaches:

* **Discounted Cash Flow (DCF):** Unlevered Free Cash Flow (UFCF) discounted at a calculated WACC of **13.16%**, utilizing a **5.0%** terminal growth rate to arrive at an implied share price of **₹221**.
* **Comparable Company Analysis (Comps):** Relative valuation benchmarking EV/EBITDA multiples against key industry peers, including Hatsun Agro, Heritage Foods, and Dodla Dairy, yielding an implied share price of **₹407**.
* **Exit Multiple Method (EMM):** Applied a **7.55x EV/EBITDA** multiple to calculate a Terminal Enterprise Value of ₹32.3B. This was bridged to an implied Equity Value of ₹39.3B (implied share price: **₹330**) by accurately adjusting for outstanding debt and cash equivalents.

## 📊 Valuation Summary (as of April 2026)
* **Current Market Price (CMP):** ₹222.66
* **Implied Share Price (DCF):** ₹220.96 
* **Implied Share Price (EMM):** ₹329.74 *(~48% Implied Upside)*
* **Implied Share Price (Comps):** ₹407.25 *(~82% Implied Upside)*
* **Conclusion:** While the perpetuity growth DCF aligns closely with current market pricing, the EMM and Comps analyses indicate significant potential upside, suggesting the stock may be mispriced by the broader market.

## 🛠️ Model Integrity & Architecture
* **Dynamic Schedules:** Built with fully integrated working capital and fixed asset roll-forwards.
* **Zero Variance:** Features rigorous, automated error-checking protocols. The Balance Sheet balances perfectly across all historical and projected years without the use of manual "plug" figures.
* **Cash Reconciliation:** Net Income seamlessly reconciles with Cash Flow from Operations, and period-end cash perfectly matches the Balance Sheet.

## 📂 Files Included
* `Parag Milk Foods 3 statement Model + DCF.xlsx`: The master working model.
