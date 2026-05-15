# 💰 Discounted Cash Flow (DCF) Model — Unilever PLC

A professional-grade **DCF valuation model** built in Excel to estimate the intrinsic value of **Unilever PLC**, one of the world's largest consumer goods companies. The model uses a 5-year unlevered free cash flow projection with both a **Perpetual Growth** and an **EV/EBITDA exit multiple** terminal value approach.

---

## 📌 Overview

The model computes Unilever's intrinsic equity value per share and compares it to the current market price to generate a **Buy/Sell signal** and estimate the **margin of safety**.

---

## 🏢 Company

| Field | Detail |
|-------|--------|
| **Company** | Unilever PLC |
| **Model Type** | Leveraged Buyout / DCF Hybrid |
| **Transaction Date** | 2026 (Entry) |
| **Fiscal Year End** | 2026 |
| **Currency** | GBP (£m) |

---

## 🔢 Key Assumptions

| Parameter | Value |
|-----------|-------|
| Tax Rate | 26.0% |
| Discount Rate (WACC) | 6.72% |
| Perpetual Growth Rate | 3.00% |
| EV/EBITDA Exit Multiple | 12.1x |
| Current Share Price | £49.50 |
| Shares Outstanding | 2,184m |
| Net Debt | £27,333m |
| Cash | £4,200m |
| Annual Capex | £1,500m |

---

## 📊 Projection Period: 2025–2030

| Year | EBIT (£m) | Unlevered FCF (£m) | PV of FCF (£m) |
|------|-----------|-------------------|----------------|
| 2025 (Entry) | 11,200 | 7,713 | 7,713 |
| 2026 | 11,536 | 7,989 | 7,486 |
| 2027 | 11,882 | 8,274 | 7,265 |
| 2028 | 12,239 | 8,567 | 7,049 |
| 2029 | 12,606 | 8,869 | 6,838 |
| 2030 (Exit) | 12,984 | 9,180 | 6,632 |

---

## 🏁 Terminal Value

| Method | Terminal Value (£m) |
|--------|---------------------|
| Perpetual Growth (Gordon Growth) | 254,188 |
| EV/EBITDA Exit Multiple (12.1x) | 157,105 |
| **Average (Used in Model)** | **205,647** |

---

## 💼 Valuation Summary

### Intrinsic Value (DCF)

| Item | Value (£m) |
|------|-----------|
| Enterprise Value | 183,826 |
| Plus: Cash | 4,200 |
| Less: Debt | (27,333) |
| **Equity Value** | **160,693** |
| **Equity Value / Share** | **£73.58** |

### Market Value

| Item | Value |
|------|-------|
| Market Cap | £108,108m |
| Enterprise Value (Market) | £131,241m |
| Share Price | £49.50 |

---

## 📈 Return Analysis

| Metric | Value |
|--------|-------|
| Target Price Upside | **48.6%** |
| Internal Rate of Return (IRR) | **14.9%** |
| Upside to Intrinsic Value | £24.08 / share |
| **Signal** | ✅ **BUY** |

---

## 🗂️ Model Structure

### Sheet: `DCF`

| Section | Description |
|---------|-------------|
| **Assumptions Block** | Tax rate, WACC, growth rates, balance sheet items |
| **DCF Projection Table** | 5-year EBIT, FCF build, and PV of FCFs (2025–2030) |
| **Terminal Value** | Dual-method terminal value (Gordon Growth + EV/EBITDA) |
| **Intrinsic Value Build** | Bridge from Enterprise Value → Equity Value → Per Share |
| **Market Value Comparison** | Market cap and EV benchmarked against intrinsic value |
| **Rate of Return** | Upside %, IRR, and Buy/Sell recommendation |

---

## ⚙️ How to Use

1. **Open** `DCF_Model-_Unilever.xlsx` in Microsoft Excel or LibreOffice Calc.
2. **Update the Assumptions block** with the latest figures:
   - WACC, Tax Rate, Perpetual Growth Rate
   - Current share price, debt, cash, capex
3. **Extend or revise EBIT projections** in the DCF table for updated forecasts.
4. All FCFs, PV calculations, terminal values, and the Buy/Sell signal will **recalculate automatically**.
5. Compare the **Equity Value/Share (intrinsic)** to the **current market price** to assess the investment case.

---

## 📋 Data Sources

| Data | Source |
|------|--------|
| EBIT & Financial Figures | Unilever Annual Reports / Bloomberg |
| Share Price | London Stock Exchange (LSE) |
| WACC | Analyst estimate / Bloomberg |
| EV/EBITDA Multiple | Sector consensus / FactSet |

---

## 📁 File

```
DCF_Model-_Unilever.xlsx
```

---

## ⚠️ Disclaimer

This model is for **educational and analytical purposes only** and does not constitute financial advice. All projections are estimates based on assumptions and may not reflect future performance.
