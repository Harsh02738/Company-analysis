# 📊 Jindal Stainless Ltd. – Financial Analysis Project

This project performs a comprehensive financial evaluation of **Jindal Stainless Ltd.** using modern valuation models and capital structure theories. The analysis combines real-world financial data, stock market metrics, and academic frameworks including:

- CAPM (Capital Asset Pricing Model)
- DDM (Dividend Discount Model)
- DCF (Discounted Cash Flow)
- Bond Yield Approach
- Optimal Capital Structure Modeling

---

## 🧑‍💼 Group Members

| Name             | ID Number       |
|------------------|-----------------|
| Shah Harsh Dhaval | 2022A7PS0174P |
| Harsh Shah        | 2022A7PS0169P |
| Vairaj Desai      | 2022A4PS0545P |

> **Disclaimer**: All financial data used is publicly available and used for educational purposes only.

---

## 📁 Sheet-Wise Breakdown

### 🔹 `CAPM`
- Regression of JIST stock against NIFTY 50
- Calculation of Beta (Levered & Unlevered), Risk-Free Rate, Market Risk Premium
- Final Cost of Equity `Ke(Levered)` computed using:
  \[
  K_e = R_f + \beta \cdot (R_m - R_f)
  \]

### 🔹 `DDM (Dividend Discount Model)`
- Historical dividend data and ROE trends
- Calculated:
  - Retention ratio
  - 5-year growth rate: `27.18%`
  - Infinite growth rate: `7.6%`
- Price per share estimated using DDM formula:
  \[
  P_0 = \frac{D_0(1 + g)}{K_e - g}
  \]
- Result: `P₀ ≈ ₹707.05`

### 🔹 `DCF (Discounted Cash Flow)`
- Net income, depreciation, capex, and working capital changes used to compute:
  - FCFE (Free Cash Flow to Equity)
- Terminal value added to obtain final price per share:
  \[
  P₀ ≈ ₹686.15
  \]

### 🔹 `Bond Yield + Risk Premium`
- Used interest paid and debt values to calculate cost of debt
- Combined with `Ke` to estimate WACC (Weighted Average Cost of Capital)

---

## 📊 Final Valuation Summary

| Method     | Price per Share |
|------------|------------------|
| CAPM       | Based on Ke ≈ 10.47% |
| DDM        | ₹707.05          |
| DCF        | ₹686.15          |
| Reported CMP | ₹651 (approx)   |

---

## 🧾 Part III – Final Report Card

| Evaluation Criteria                                                   | Score | Criteria Met |
|------------------------------------------------------------------------|--------|---------------|
| Ability to handle financial obligations                               | 3.5    | ❌ No         |
| Consistency in returns to shareholders                                | 4.0    | ✅ Yes        |
| Stability in capital structure and operational efficiency             | 4.5    | ✅ Yes        |
| Sound investment strategy based on cost of capital vs. returns        | 4.0    | ✅ Yes        |
| Overall Alignment with shareholder wealth maximization                | 5.0    | ✅ Yes        |

> **Final Conclusion**: The company has a sound valuation, and the market undervaluation offers a potential upside for long-term investors.

---

## 📈 Tools & Data Sources

- **Excel Modeling**: Financial statements, formulas, and regression outputs
- **Yahoo Finance**, **Screener.in** for historical data
- **Google Finance API** (for market comparisons)

---

## 🧮 Core Concepts Used

- Weighted Average Cost of Capital (WACC)
- Modigliani & Miller Capital Structure Theorem
- Risk-Adjusted Return Analysis
- Earnings vs. Cash Flow-Based Valuation

---

## 📌 License

MIT License – For academic and educational use only.

---

## 🙌 Contributions

Contributions are welcome!  
Please fork the repo, suggest improvements, or raise issues.

---

