# Five-Year Financial Forecasting | Excel Financial Modelling

[![Excel](https://img.shields.io/badge/Model-Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)](Financial_Model.xlsx)
[![Certificate](https://img.shields.io/badge/Certificate-Verified_100%25-10b981?style=flat)](https://www.theforage.com/completion-certificates/HgpPSsyQpzob6HEh9/B5e3zaZCcEZNv8YCg_HgpPSsyQpzob6HEh9_6a61e6fdc75bcdab6ef5c512_1793714783563_completion_certificate.pdf)
[![Status](https://img.shields.io/badge/Status-Completed_(4%2F4_Tasks)-10b981?style=flat)](#task-breakdown--completion)

> **Programme Verification**: Completed the practical **Excel Skills for Business Finance Job Simulation** offered by **Forage**. Completed on **3 November 2026** by **Alwin Meniens**. This repository documents the practical five-year dynamic financial forecast, debt amortization waterfall, cash flow schedule, and executive presentation dashboard.

---

## 1. Programme Information & Verification

- **Programme**: Excel Skills for Business Finance Job Simulation
- **Provider**: [Forage]
- **Participant**: Alwin Meniens
- **Completion Date**: 3 November 2026
- **Status**: **Successfully Completed (100%)**
- **Official Certificate**: [View Completion Certificate](https://www.theforage.com/completion-certificates/HgpPSsyQpzob6HEh9/B5e3zaZCcEZNv8YCg_HgpPSsyQpzob6HEh9_6a61e6fdc75bcdab6ef5c512_1793714783563_completion_certificate.pdf)
- **Relevant Career Areas**: Financial Planning & Analysis (FP&A), Corporate Finance, Financial Analysis, Business Finance

---

## 2. Project Objective & Context

Completed a practical financial modelling simulation focused on building a fully connected five-year financial forecast (`FY2026E` – `FY2030E`) for an expanding business. 

The model tracks operating assumptions, volume expansion, dynamic pricing schedules, cost escalation, operating leverage, working capital movements, capital expenditure reinvestment, dividend distributions, an automated debt service waterfall, and visual executive presentation dashboards with dynamic KPI trend charts.

---

## 3. Task Breakdown & Completion

All four milestones have been completed:

| Milestone | Task Description | Status | Deliverable & Modelling Summary |
| :--- | :--- | :---: | :--- |
| **Task 1** | **Build Forecast Assumptions** | `Completed` | Translated business expectations into financial forecast inputs. Structured multi-year unit volume growth (10% tapering to 7%), annual 4% price escalation, inflation-indexed unit costs (+2%), OpEx inflation (+3%–5%), tax rate (21%), CapEx / D&A schedule, and 60% dividend policy. |
| **Task 2** | **Build a Profit and Loss Forecast** | `Completed` | Applied operating assumptions to forecast financial performance. Built multi-product revenue lines ($705K in FY26E to $1.14M in FY30E), direct cost schedules, gross margin expansion (64.1% to 66.8%), and EBITDA scaling ($227K to $495K). |
| **Task 3** | **Forecast Cash Flow and Debt** | `Completed` | Connected profitability to liquidity movements and financing. Integrated Operating Cash Flow, working capital adjustments (-1.0% rev), CapEx reinvestment, 60% dividend payout, dynamic debt sweep waterfall (`=MIN(MAX(0, CFBD), OpeningDebt)`), and net interest expense linkages back into the P&L. |
| **Task 4** | **Present the Forecast** | `Completed` | Translated completed financial model into clear executive outputs. Built the **`Forecast Summary`** dashboard synthesizing key forecast outputs, tabular metrics, and three dynamic trend charts (Revenue & Net Profit, EBITDA Margin %, Closing Debt & Cash trajectory). |

**Overall Progress: 4 of 4 Tasks Completed (100%)**

---

## 4. Financial Model Structure & Actual Model Outputs

The audited financial workbook [`Financial_Model.xlsx`](Financial_Model.xlsx) consists of 6 dedicated worksheets:

### Workbook Architecture
1. **`Business Information`**: Baseline parameters, operating guidance, and commercial context.
2. **`Forecast Assumptions`**: Clean driver architecture separating all growth rates, unit costs, pricing ladders, tax, and debt rates from calculations.
3. **`P&L Forecast`**: Dynamic multi-product operational income statement spanning FY2026E to FY2030E, fully connected to net interest calculations.
4. **`Cash Flow & Debt Forecast`**: Operating, Investing, and Financing cash flow schedules paired with a debt amortization schedule.
5. **`Forecast Summary`**: Executive presentation dashboard consolidating core outputs and visual trend charts.
6. **`Glossary`**: Core corporate finance terminology reference.

### Final 5-Year Financial Summary Table (from Actual Workbook Data)

| Metric (in USD) | FY2026E | FY2027E | FY2028E | FY2029E | FY2030E |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Total Revenue** | \$705,000 | \$806,520 | \$914,271 | \$1,026,909 | \$1,142,745 |
| *Revenue Growth %* | — | 14.40% | 13.36% | 12.32% | 11.28% |
| **Gross Profit** | \$452,000 | \$522,654 | \$598,669 | \$679,242 | \$763,300 |
| *Gross Margin %* | 64.11% | 64.80% | 65.48% | 66.14% | 66.80% |
| **EBITDA** | \$227,000 | \$287,604 | \$353,102 | \$422,670 | \$495,211 |
| *EBITDA Margin %* | 32.20% | 35.66% | 38.62% | 41.16% | 43.34% |
| **EBIT** | \$191,750 | \$249,294 | \$311,960 | \$379,026 | \$449,502 |
| **Net Interest Expense** | \$15,850 | \$13,909 | \$11,256 | \$7,821 | \$3,539 |
| **Profit Before Tax** | \$175,900 | \$235,386 | \$300,704 | \$371,206 | \$445,962 |
| **Tax Expense (21%)** | \$36,939 | \$49,431 | \$63,148 | \$77,953 | \$93,652 |
| **Net Profit** | \$138,961 | \$185,955 | \$237,556 | \$293,253 | \$352,310 |
| **Closing Debt** | \$351,466 | \$285,149 | \$199,269 | \$92,237 | **\$0** |
| **Closing Cash** | \$15,000 | \$15,000 | \$15,000 | \$15,000 | **\$52,259** |

### Key Modelling Observations & Insights
- **Pricing Power & Margin Expansion**: Consistent 4% annual price escalation outpacing 2% COGS inflation drives gross margins from 64.11% to 66.80%.
- **Operating Leverage**: As fixed/semi-variable OpEx scales moderately, EBITDA margin surges by +1,114 bps from 32.20% to 43.34%.
- **Debt Amortization Waterfall**: The initial $400,000 debt balance is completely repaid by FY2030E through positive operating cash flows post-dividends.
- **Liquidity Accretion**: After full debt retirement in FY2030E, surplus cash builds balance sheet liquidity to **$52,259** above the baseline $15,000 operational reserve.
- **Executive Visual Dashboard**: Task 4 integrates dynamic charts depicting the simultaneous revenue/profit acceleration, EBITDA margin expansion, and debt extinguishment.

---

## 5. Skills Practised & Demonstrated

- **Microsoft Excel**: Multi-sheet workbook architecture, dynamic cross-sheet linking, auditing keys, and presentation charting.
- **Financial Modelling & Forecasting**: 5-year integrated projections linking income statement, cash flow statement, and debt schedules.
- **Forecast Assumptions**: Parameter isolation, indexing, CAGR ladders, and driver schedules.
- **Profit and Loss Forecasting**: Topline unit-price drivers, COGS schedules, margin analysis, and tax provisioning.
- **Cash Flow Forecasting**: Non-cash reconciliation, working capital variance, and capital expenditure reinvestment.
- **Debt Modelling**: Principal repayment sweeps, dynamic bounds (`MIN`, `MAX`), and interest schedule synchronization.
- **Financial Analysis & Business Performance Presentation**: Executive dashboard structuring, KPI extraction, and visual trend presentation.

---

## 6. Accessing Deliverables

- **Excel Financial Model**: Download [`Financial_Model.xlsx`](Financial_Model.xlsx) directly.
- **Official Forage Certificate**: [View Verified Certificate PDF](https://www.theforage.com/completion-certificates/HgpPSsyQpzob6HEh9/B5e3zaZCcEZNv8YCg_HgpPSsyQpzob6HEh9_6a61e6fdc75bcdab6ef5c512_1793714783563_completion_certificate.pdf)
- **Official Programme Link**: [Forage Academy Simulation](https://www.theforage.com/simulations/forage/sponsored-content-excel-skills-for-busi-xue7)
