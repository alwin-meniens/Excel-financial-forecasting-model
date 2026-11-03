# Financial Modelling Methodology & Statement Mechanics

This document provides technical financial commentary on the structure, relationships, and quantitative mechanics embedded in the 5-year forecast model (`FY2026E` – `FY2030E`), incorporating all four completed simulation tasks.

---

## 1. Topline & Operational Mechanics

### Revenue Architecture
Revenue is generated across three distinct operational segments:
- **Baked Goods**
- **Frozen Desserts**
- **Beverages**

For each segment:
$$\text{Revenue}_t = \text{Volume}_t \times \text{Average Selling Price}_t$$

- **Volume Growth Driver**: Starts at +10% year-over-year in FY2027E and tapers downward by 100 bps annually (+9% in FY2028E, +8% in FY2029E, +7% in FY2030E), capturing market maturation.
- **Pricing Ladder**: All product segments implement a continuous +4.0% price increase year-over-year.

### Cost of Goods Sold (COGS) & Gross Margin Accretion
- Direct unit costs increase at a stable +2.0% per annum across all lines.
- Because price inflation (+4.0%) consistently exceeds unit cost inflation (+2.0%), Gross Margins experience steady positive accretion:
  - **FY2026E Gross Margin**: 64.11%
  - **FY2030E Gross Margin**: 66.80%

---

## 2. Operating Expenses & Profitability

- **Staff Costs**: Scaled at +5.0% annually.
- **Occupancy Costs**: Scaled at +3.0% annually.
- **Marketing Costs**: Scaled at +5.0% annually.
- **Other Costs**: Scaled at +5.0% annually.
- **EBITDA**: Gross Profit minus Operating Expenses. Demonstrates pronounced operational leverage, expanding from **$227,000** (32.2% margin) in FY2026E to **$495,211** (43.3% margin) in FY2030E.

---

## 3. Cash Flow Waterfall & Debt Amortization

The cash flow statement connects net profit back to liquidity through a standard three-part structure:

### A. Operating Cash Flow (OCF)
$$\text{OCF} = \text{Net Profit} + \text{D&A} + \Delta\text{NWC}$$
- **D&A Re-addition**: Non-cash depreciation begins at 5.00% of revenue in FY2026E, gradually moderating by 0.25% per year to 4.00% by FY2030E.
- **Change in Net Working Capital**: Modeled as an operating cash outflow equal to -1.0% of revenue annually.

### B. Investing Cash Flow (CapEx)
- **Capital Expenditure (CapEx)**: Set equal to D&A rates (-5.00% of revenue in FY2026E moderating to -4.00% in FY2030E), modeling consistent capital reinvestment.

### C. Financing Cash Flow & Debt Waterfall
- **Dividend Policy**: Constant 60.0% payout of annual net profit.
- **Cash Flow Before Debt (CFBD)**:
$$\text{CFBD} = \text{Operating Cash Flow} + \text{Investing Cash Flow} + \text{Dividends}$$
- **Debt Service Logic**:
$$\text{Debt Repayment} = \min(\max(0, \text{CFBD}), \text{Opening Debt})$$
This ensures debt is only amortized when post-dividend cash generation is positive, and will never pay down more than remaining principal.
- **Debt Extinguishment**: The initial debt of **$400,000** is systematically reduced to **$0 balance in FY2030E**.
- **Net Interest Expense Feedback Loop**: With the finalized debt balance schedule, actual net interest expense feeds dynamically back into the P&L row 36, driving true final Net Profit to **$352,310** in FY2030E.
- **Liquidity Accretion**: Post-debt cash flow accumulates in FY2030E, lifting ending cash from the $15,000 operational reserve to **$52,259**.

---

## 4. Executive Presentation Dashboard (Task 4 Deliverable)

The **`Forecast Summary`** worksheet consolidates the 5-year forecast into an executive-ready format featuring:
1. **Consolidated Financial Summary Table**: Revenue, Net Profit, EBITDA, EBITDA Margin, Closing Debt, and Closing Cash.
2. **Visual KPI Trend Charts**:
   - **Revenue and Net Profit (Column Chart)**: Displays simultaneous topline growth and net earnings expansion.
   - **EBITDA Margin % (Line Chart)**: Highlights progressive margin accretion from 32.20% to 43.34%.
   - **Closing Debt and Cash (Bar / Column Chart)**: Illustrates the complete debt paydown trajectory and FY2030E liquidity accumulation.
