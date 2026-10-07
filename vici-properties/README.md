# VICI Properties — REIT Fundamental Analysis & Valuation

**Case type:** Fundamental Equity Research / REIT  
**Primary skills:** AFFO, leverage, capital allocation, per-share analysis, P/AFFO, NAV, SOTP, EV/EBITDA

## Objective

The purpose of this model is to evaluate VICI as a long-duration real-estate cash-flow business rather than relying on headline EPS.

For a REIT, the analytical focus shifts toward:

- AFFO and AFFO per share;
- leverage and refinancing capacity;
- dividend coverage and capital allocation;
- dilution and per-share compounding;
- valuation relative to recurring cash flow and asset value.

## Current Valuation Snapshot — October 2026

VICI closed at approximately **$22.73/share on October 6, 2026**. The latest quarterly dividend is **$0.46/share**, or **$1.84 annualized**, implying a current dividend yield of approximately **8.1%**.

Using the latest reported portfolio and capital structure from Q2 2026:

- Annualized contractual real-estate rent: **$3.312bn**
- Annualized income from loans and securities: **$285.7m**
- Loan and securities principal balance: **$3.030bn**
- Total debt: **$17.218bn**
- Cash: **$288m**
- Common shares + third-party partnership units: approximately **1.114bn**

### NAV Approach

Using a **7.0% capitalization rate** on the current annualized real-estate rent:

**Real-estate value = $3.312bn / 7.0% ≈ $47.3bn**

Adding the loan and securities portfolio at principal value, cash, land and development assets, then subtracting total debt produces an estimated equity NAV of approximately:

**NAV ≈ $30.1/share**

At $22.73, that implies approximately **32.4% price upside + 8.1% current dividend yield = ~40.5% total return potential**, assuming the annual dividend remains at **$1.84/share** over an approximately one-year holding period.

This highlights that the investment case is not based only on NAV re-rating; investors are also paid a substantial cash yield while waiting.

### Sum-of-the-Parts Approach

For a more granular SOTP, I separate the rental portfolio by asset type/geography and apply different illustrative cap rates:

- Las Vegas Strip gaming rent: **6.75% cap rate**
- Regional gaming rent: **7.5% cap rate**
- International gaming rent: **8.0% cap rate**
- Other experiential rent: **8.0% cap rate**
- Loans and securities: valued at **principal balance**

These assumptions reflect the higher quality and scarcity of the Las Vegas Strip portfolio while remaining broadly consistent with recent VICI gaming acquisitions completed around **7.5%–8.0% cap rates**.

The resulting estimated equity value is approximately:

**SOTP ≈ $29.3/share**

At $22.73, that implies approximately **28.9% price upside + 8.1% current dividend yield = ~37.0% total return potential**, assuming the annual dividend remains at **$1.84/share** over an approximately one-year holding period.

> Q3 2026 results have not yet been released, so the NAV and SOTP use the latest available Q2 2026 balance sheet and rent roll, combined with the October 6, 2026 share price.

## Total Return Potential

To compare the valuation methods on the same basis, I use the **$22.73 current share price** and the **8.1% current dividend yield**. The primary valuation methods are NAV and SOTP; P/AFFO, EV/EBITDA and P/Book are secondary cross-checks.

| Valuation Method | Key Assumption | Implied Price | Price Upside / (Downside) | Current Dividend Yield | Illustrative Total Return* |
|---|---|---:|---:|---:|---:|
| **NAV** | 7.0% cap rate | **$30.10** | **+32.4%** | **+8.1%** | **~+40.5%** |
| **SOTP** | Segment-specific cap rates | **$29.30** | **+28.9%** | **+8.1%** | **~+37.0%** |
| **P/AFFO** | **~$2.41 2026E AFFO/share × 11.0x** | **$26.54** | **+16.8%** | **+8.1%** | **~+24.9%** |
| **EV/EBITDA** | **$3.456bn 2026E EBITDA × 12.0x − $16.8bn net debt; / 1.090bn diluted shares** | **$22.63** | **-0.4%** | **+8.1%** | **~+7.7%** |
| **P/Book** | **$27.06 2026E book value/share × 0.9x** | **$24.35** | **+7.1%** | **+8.1%** | **~+15.2%** |

\*Illustrative one-year framework: **price return to the implied valuation + current 8.1% dividend yield**, assuming the annual dividend remains **$1.84/share**. The methods are cross-checks, not targets to be averaged mechanically.

## Public Model Snapshot

I rebuilt the core outputs from my personal Excel workbook into a clean public snapshot that can be reviewed directly in GitHub:

[Open the VICI model snapshot](./MODEL_SNAPSHOT.md)

The model focuses on:

- historical and forecast operating data;
- AFFO and AFFO/share;
- net debt / EBITDA;
- share dilution and per-share compounding;
- P/AFFO, NAV, SOTP, EV/EBITDA and P/Book valuation cross-checks.

## Key Questions

### 1. Is AFFO per share compounding?

Absolute growth is not enough for a REIT that regularly accesses external capital. The model therefore tracks AFFO per share alongside diluted shares.

### 2. Is leverage sustainable?

Net debt / EBITDA is tracked directly to assess whether growth is being financed at a level that remains consistent with the business model.

### 3. Is the dividend supported by recurring cash flow?

At the current annualized dividend of **$1.84/share**, VICI offers an approximately **8.1% dividend yield** at a $22.73 share price. I treat that yield as an important part of the expected return while waiting for a potential re-rating, and evaluate its sustainability through AFFO coverage rather than accounting earnings alone.

### 4. What valuation framework is appropriate?

I use several cross-checks:

- **P/AFFO**
- **NAV**
- **Sum-of-the-Parts**
- **EV/EBITDA**
- **P/Book**

No single method is treated as the answer. The point is to understand what each method implies and whether they tell a consistent story.

## What This Case Demonstrates

The VICI case is intended to show a more traditional modeling process than the Lionsgate special situation. It demonstrates my ability to work through historical financials, identify the right sector-specific metric, forecast per-share economics and connect operating assumptions to valuation.

### Sources

- [VICI Q2 2026 Supplemental Financial Information](https://investors.viciproperties.com/static-files/4bd1c7f3-8a07-4af9-ae2d-b8da7d7ba208)
- [VICI September 2026 dividend announcement](https://investors.viciproperties.com/news-releases/news-release-details/vici-properties-inc-increases-regular-quarterly-dividend-2)
- [Golden Entertainment transaction overview — 7.5% acquisition cap rate](https://investors.viciproperties.com/static-files/0fb2943a-42fe-48b2-8a8e-7661051d2440)
- [Gamehost transaction overview — 8.0% acquisition cap rate](https://investors.viciproperties.com/news-releases/news-release-details/vici-properties-inc-announces-sale-leaseback-canadian-portfolio)

> The public snapshot is rebuilt from my personal working model. Raw filing and transcript tabs were intentionally excluded. Valuation assumptions are illustrative and do not constitute investment advice.
