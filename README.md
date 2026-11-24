# L&T Integrated Financial Model

An integrated 3-statement financial model, valuation analysis, and presentation deck for **Larsen & Toubro Limited** (NSE: `LT`, BSE: `500510`), built entirely from **publicly available data** — no internal, proprietary, or confidential information was used.

> **Basis:** Audited consolidated financial statements, stock exchange filings, investor relations disclosures, and credit-rating agency reports. See [Data Sources](#data-sources) below.

---

## What's in This Repo

| File | Description |
|---|---|
| [`LT_Financial_Model.xlsx`](./LT_Financial_Model.xlsx) | The core model — 14 linked tabs, 855 formulas, fully editable |
| [`LT_Model_Presentation.pptx`](./LT_Model_Presentation.pptx) | 16-slide presentation deck summarizing the model for stakeholder review |
| [`docs/LT_Model_Report.docx`](./docs/LT_Model_Report.docx) | 7-page summary report |
| [`docs/LT_Model_Detailed_Report.docx`](./docs/LT_Model_Detailed_Report.docx) | 27-page detailed report with full methodology, assumptions, and validation walkthrough |

---

## Coverage

- **History:** FY2015-16 → FY2025-26 (11 years, audited)
- **Projections:** FY2026-27E → FY2030-31E (5 years)
- **Currency:** ₹ Crore, consolidated basis

## Key Outputs

| Metric | FY2025-26A | FY2030-31E (Base Case) |
|---|---|---|
| Revenue from Operations | ₹2,85,874 Cr | ₹5,22,579 Cr |
| EBITDA Margin | 11.5% | 10.7% |
| Owners' PAT | ₹16,084 Cr | ₹31,642 Cr |
| EPS | ₹116.92 | ₹229.96 |
| DCF-Implied Value/Share | — | ₹2,213 (base case) |

## Model Structure

The workbook is organized into four functional groups across 14 tabs:

- **Foundation** — Cover, Assumptions, Historical Trends
- **Core Financials** — Income Statement, Balance Sheet, Cash Flow Statement, Segment Analysis (fully linked; balance sheet ties to ₹0 across all 11 years)
- **Business Context** — Order Book & Backlog, Credit Profile
- **Valuation & Risk** — Ratios Dashboard, DCF Valuation, Relative Valuation, Scenario Analysis, Sensitivity Analysis

Every projected cell is formula-driven from the `Assumptions` tab — nothing downstream of FY2025-26 actuals is hardcoded.

## Data Sources

- [L&T Investor Relations](https://investors.larsentoubro.com/Financials.aspx) — 10-year financial trends
- L&T audited consolidated results (Q4 FY2025-26), filed with BSE/NSE
- L&T 81st Integrated Annual Report & Board's Report, FY2025-26
- ICRA rating rationale — order book composition, working capital metrics
- CRISIL, India Ratings, S&P Global, Fitch — public credit ratings
- [Screener.in](https://www.screener.in) — peer company financials (Siemens, ABB India, BHEL, Thermax)
- NSE / BSE — shareholding pattern, reference market price

Full source list and validation methodology are in the [detailed report](./docs/LT_Model_Detailed_Report.docx).

## Validation

- **Balance Check:** Total Assets − Total Equity & Liabilities = ₹0 across all 11 years, including all 5 projected years
- **Formula integrity:** 855 formulas, 0 errors
- **Historical back-testing:** Four derived metrics (PBDIT, Capital Employed, Return on Net Worth, Book Value/Share) were reverse-engineered and validated against L&T's own disclosed FY2024-25 figures before being trusted for FY2025-26 — accuracy ranged from 99.97% to exact matches

## Appropriate Use

✅ External investor communication / equity valuation, competitive benchmarking, strategic scenario planning, financial-modeling practice

❌ Internal project-level P&L tracking, debt covenant monitoring, monthly/quarterly variance analysis, board-level capital allocation decisions — these require internal data this project does not have access to by design

## Limitations

This model is built entirely on public data, which means:
- Annual granularity only (no monthly/quarterly tracking)
- No debt maturity ladder (not publicly disclosed)
- Simplified expense structure in projection years (segment-result bridge, not full line-item build-up)
- Order-book geographic/segment mix reflects the most recently available disclosure (~March 2025), not necessarily current composition
- Bear/Bull scenarios are illustrative, author-constructed cases — not company guidance

Full limitations and disclaimers are documented in Section 13 of the [detailed report](./docs/LT_Model_Detailed_Report.docx).

---

## Disclaimer

This model and its outputs do not constitute investment advice, a fairness opinion, or a substitute for professional equity research. All valuation outputs are illustrative analytical exercises built from public information.
