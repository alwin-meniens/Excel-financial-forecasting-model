# Financial Modelling Methodology & Statement Mechanics

This document provides technical financial commentary on the structure, relationships, and quantitative mechanics embedded in the 5-year forecast model (`FY2026E` – `FY2030E`).

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

### Cost of Goods Sold (COGS) & Gross Margin Expansion
- Direct unit costs increase at a stable +2.0% per annum across all lines.
- Because price inflation (+4.0%) consistently exceeds unit cost inflation (+2.0%), Gross Margins experience positive expansion over the projection window:
  - **FY2026E Gross Margin**: 64.11%
  - **FY2030E Gross Margin**: 66.80%

---

## 2. Operating Expenses & Profitability

- **Staff Costs**: Scaled at +5.0% annually, representing headcount retention and cost-of-living adjustments.
- **Occupancy Costs**: Scaled at +3.0% annually, modeling contractual lease escalation.
- **Marketing Costs**: Scaled at +5.0% annually to sustain sales expansion.
- **Other Costs**: Scaled at +5.0% annually.
- **EBITDA**: Gross Profit minus Operating Expenses. Demonstrates pronounced operational leverage, expanding from **$227,000** (32.2% margin) in FY2026E to **$495,211** (43.3% margin) in FY2030E.

---

## 3. Cash Flow Waterfall & Capital Allocation

The cash flow statement connects the net profit figure back to liquidity through a standard three-part structure:

### A. Operating Cash Flow (OCF)
$$\text{OCF} = \text{Net Profit} + \text{D&A} + \Delta\text{NWC}$$
- **D&A Re-addition**: Non-cash depreciation begins at 5.00% of revenue in FY2026E, gradually moderating by 0.25% per year to 4.00% by FY2030E.
- **Change in Net Working Capital**: Modeled as an operating cash outflow equal to -1.0% of revenue annually.

### B. Investing Cash Flow (CapEx)
- **Capital Expenditure (CapEx)**: Linked directly to D&A rates (-5.00% of revenue in FY2026E moderating to -4.00% in FY2030E), modeling steady reinvestment in productive equipment and facilities.

### C. Financing Cash Flow & Debt Waterfalls
- **Dividend Policy**: Constant 60.0% payout of annual net profit.
- **Cash Flow Before Debt**:
$$\text{CFBD} = \text{Operating Cash Flow} + \text{Investing Cash Flow} + \text{Dividends}$$
- **Debt Service Logic**:
$$\text{Debt Repayment} = \min(\max(0, \text{CFBD}), \text{Opening Debt})$$
This formula guarantees that debt is only amortized when operating cash flow post-dividends is positive, and will never pay down more than the remaining debt principal.
- **Debt Extinguishment**: The initial debt of **$400,000** is systematically reduced and reaches **$0 balance in FY2030E**.
- **Liquidity Build**: Once debt is completely retired in FY2030E, the surplus cash of **$28,767** flows directly to balance sheet liquidity, raising closing cash from the minimum operational buffer of **$15,000** to **$43,767**.

---

## 4. Summary Table of Financial Results

| Metric (in USD) | FY2026E | FY2027E | FY2028E | FY2029E | FY2030E |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Total Revenue** | \$705,000 | \$806,520 | \$914,271 | \$1,026,909 | \$1,142,745 |
| *Revenue Growth %* | — | 14.40% | 13.36% | 12.32% | 11.28% |
| **Gross Profit** | \$452,000 | \$522,654 | \$598,669 | \$679,242 | \$763,300 |
| *Gross Margin %* | 64.11% | 64.80% | 65.48% | 66.14% | 66.80% |
| **EBITDA** | \$227,000 | \$287,604 | \$353,102 | \$422,670 | \$495,211 |
| *EBITDA Margin %* | 32.20% | 35.66% | 38.62% | 41.16% | 43.34% |
| **EBIT** | \$191,750 | \$249,294 | \$311,960 | \$379,026 | \$449,502 |
| **Net Interest Expense** | \$15,850 | \$13,909 | \$11,280 | \$7,903 | \$3,724 |
| **Net Profit (P&L)** | \$138,961 | \$184,421 | \$233,927 | \$286,909 | \$342,585 |
| **Operating Cash Flow** | \$167,161 | \$214,665 | \$265,927 | \$320,284 | \$376,867 |
| **CapEx** | (\$35,250) | (\$38,310) | (\$41,142) | (\$43,644) | (\$45,710) |
| **Dividends Paid** | (\$83,377) | (\$110,653) | (\$140,356) | (\$172,146) | (\$205,551) |
| **Debt Repaid** | \$48,534 | \$65,703 | \$84,428 | \$104,495 | \$96,840 |
| **Closing Debt** | \$351,466 | \$285,762 | \$201,334 | \$96,840 | **\$0** |
| **Closing Cash** | \$15,000 | \$15,000 | \$15,000 | \$15,000 | **\$43,767** |
