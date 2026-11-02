# Financial Model: 5-Year Forecast & Debt Schedule (Job Simulation)

[![Excel](https://img.shields.io/badge/Model-Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)](Financial_Model.xlsx)
[![Simulation](https://img.shields.io/badge/Forage-Job_Simulation-003366?style=flat)](https://www.theforage.com/simulations/forage/sponsored-content-excel-skills-for-busi-xue7)
[![Status](https://img.shields.io/badge/Progress-75%25_(3%2F4_Tasks)-orange?style=flat)](#task-breakdown--progress)

> **Simulation Disclaimer**: This project represents completed coursework for the **Excel Skills for Business Finance** job simulation provided by **Forage Academy**. It does not constitute professional commercial employment, an internship, or client advisory work.

---

## 1. Programme Information

- **Programme**: Excel Skills for Business Finance
- **Provider**: [Forage Academy](https://www.theforage.com/simulations/forage/sponsored-content-excel-skills-for-busi-xue7)
- **Duration**: 6–7 hours
- **Level**: Intermediate
- **Format**: Self-Paced Job Simulation
- **Core Focus**: Financial Planning & Analysis (FP&A), Corporate Finance, Three-Statement Integration, Debt & Cash Modelling

---

## 2. Project Objective & Context

Completed a practical financial modelling simulation focused on building a connected five-year financial forecast (`FY2026E` – `FY2030E`) for an expanding multi-product enterprise (Baked Goods, Frozen Desserts, and Beverages).

The model reflects dynamic operating assumptions, cost escalation, operational scaling, depreciation & reinvestment (CapEx), dividend distributions, debt service schedules, and ending liquidity forecasting.

---

## 3. Task Breakdown & Progress

| Milestone | Task Description | Status | Deliverable Details |
| :--- | :--- | :---: | :--- |
| **Task 1** | **Build Forecast Assumptions** | `Completed` | Modeled unit volume trajectories, CAGR pricing ladders, inflation-adjusted COGS drivers, operating expense schedules, CapEx, D&A rates, and dividend policy. |
| **Task 2** | **Build a Profit & Loss Forecast** | `Completed` | Structured dynamic revenue streams ($705K in FY26E to $1.14M in FY30E), direct cost schedules, gross margin expansion (64.1% to 66.8%), OpEx scaling, EBITDA ($227K to $495K), and initial profitability. |
| **Task 3** | **Forecast Cash Flow and Debt** | `Completed` | Integrated operating cash flow, working capital headwinds (-1.0% of rev), capital expenditure, 60% dividend policy, debt repayment waterfall, cash interest income, and net debt extinguishment. |
| **Task 4** | **Present the Forecast** | `Pending` | Convert model outputs into an executive dashboard with scenario metrics, visual KPI trends, and board presentation slides. |

**Current Progress**: **3 of 4 Tasks Completed (75%)** *(Task 4 pending final submission and review)*.

---

## 4. Financial Model Structure & Key Observations

The underlying workbook [`Financial_Model.xlsx`](Financial_Model.xlsx) consists of 5 dedicated worksheets built following strict financial modelling principles:

### A. Workbook Architecture
1. **`Business Information`**: Raw historical inputs, commercial context, operational guidelines, and baseline parameters.
2. **`Forecast Assumptions`**: Dedicated input driver schedule separating all growth rates, unit costs, pricing ladders, tax, and debt rates from calculations.
3. **`P&L Forecast`**: Dynamic multi-product operational income statement spanning FY2026E to FY2030E.
4. **`Cash Flow & Debt Forecast`**: Operating, Investing, and Financing cash flow statements coupled with an automated debt amortization schedule and interest calculation engine.
5. **`Glossary`**: Core corporate finance and financial forecasting terminology.

### B. Key Financial & Operational Trends (from Actual Workbook Data)
- **Topline Expansion**: Total Revenue scales from **$705,000** (FY2026E) to **$1,142,745** (FY2030E) driven by tiered unit volume increases (10% tapering to 7%) and consistent 4% annual price increases.
- **Gross Margin Enhancement**: Gross Margin expands from **64.11%** to **66.80%**, reflecting price growth (4.0% p.a.) outpacing COGS escalation (2.0% p.a.).
- **Operating Leverage**: EBITDA rises from **$227,000** (32.20% margin) to **$495,211** (43.34% margin) as fixed and semi-variable operational expenses (staff at 5%, rent at 3%) grow slower than gross profits.
- **Deleveraging & Cash Sweep**:
  - The business begins FY2026E with **$400,000 in debt** and **$15,000 in opening cash**.
  - Positive Cash Flow Before Debt allows accelerated principal amortization:
    - FY2026E repayment: **$48,534** (Ending Debt: $351,466)
    - FY2027E repayment: **$65,703** (Ending Debt: $285,762)
    - FY2028E repayment: **$84,428** (Ending Debt: $201,334)
    - FY2029E repayment: **$104,495** (Ending Debt: $96,840)
    - FY2030E repayment: **$96,840** (**Debt fully retired to $0**)
- **Liquidity Inflection**: After full debt retirement in FY2030E, residual post-dividend cash builds the closing cash balance to **$43,767** (up from the steady state $15,000 liquidity buffer).
- **Net Interest Expense Tapering**: As debt balance amortizes, gross interest expense decreases from **$16,000** to **$3,874**, decreasing borrowing drag on bottom-line net profit.

---

## 5. Skills Practised & Demonstrated

- **Financial Modelling & Forecasting**: Built fully linked multi-year forward-looking statements.
- **P&L & Cash Flow Modelling**: Handled non-cash charges (D&A), Working Capital adjustments, and reinvestment cash flows.
- **Debt Waterfall & Debt Amortization**: Implemented debt repayment constraints utilizing dynamic logical functions (`MIN`, `MAX`).
- **Separation of Assumptions**: Designed a clean architecture ensuring no hardcoded assumptions inside core calculation logic.
- **Spreadsheet Design Best Practices**: Applied consistent unit labelling, audit keys, and dynamic cell cross-referencing.

---

## 6. Repository Structure

```text
excel-skills-business-finance-forecast/
├── README.md                      # Comprehensive project summary & model documentation
├── project-overview.md            # Deep-dive finance methodology & statement mechanics
├── Financial_Model.xlsx           # Audited financial forecast workbook (Tasks 1–3 completed)
└── screenshots/                   # Architecture & statement previews
```

---

## 7. How to Inspect & Use the Model

1. Download [`Financial_Model.xlsx`](Financial_Model.xlsx) directly or clone this repository.
2. Open with Microsoft Excel 2016 or newer.
3. Review `Forecast Assumptions` to examine the driver table.
4. Modify volume or pricing assumptions to observe real-time recalculation across the P&L and Cash Flow schedules.
