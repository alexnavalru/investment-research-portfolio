# Rackspace Technology (RXT) — Valuation & Dilution Model Snapshot

**As of:** October 15, 2026  
**Reference stock price:** $3.15 (October 14, 2026 close)  
**Time frame:** illustrative future/run-rate EBITDA toward 2028–2029  
**Valuation method:** EV/adjusted EBITDA sensitivity with a single static capital-structure assumption  

## Capital structure assumptions

I model **$2.7bn of net debt**, rounded from the Q2 2026 carrying-value debt of **$2,786.7m** less **$110.6m** of cash (~$2,676m). This is a **working valuation assumption**, not an estimate of actual 2028–2029 debt or a lease-adjusted enterprise-claims calculation. The debt burden **could grow as GPU infrastructure is funded**.

For completeness, the Q2 10-Q reports **$2,571.3m principal amount outstanding**, a different concept from debt carrying value; mixing it mechanically with an accounting-based net-debt calculation would change the equity bridge.

### Modeled share count

| Component | Millions of shares |
|---|---:|
| Outstanding at June 30, 2026 | 251.7 |
| Palantir consideration shares, issued July 6 | +2.2 |
| Shares sold under ATM through August 7 | +1.0 |
| **Documented subtotal after these issuances** | **254.9** |
| Potential shares excluded as anti-dilutive in the Q2 loss-per-share calculation | +25.2 |
| **Hypothetical future ATM: ~$246m / $3.22** | **+~76.4** |
| **Modeled shares (rounded)** | **356.5** |
| **Share-count estimate** | **~356.5 (or ~357)** |

Assumption detail:

1. The company announced an ATM equity program of up to **$250m**.
2. As reported through August 7, approximately **1.0m shares** had been sold, producing **$4.1m net** after fees. For this sensitivity I round remaining authorized ATM to **~$246m**. The limit is based on gross offering value; the calculation deliberately approximates net and gross amounts.
3. I assume the **entire remaining amount** is issued at **$3.22/share**, a **September 14, 2026 reference share price** supplied for modeling, *not* the observed execution price of those future securities.
4. The **25.2m potential common shares** were excluded from GAAP diluted EPS as anti-dilutive. Including all 25.2m here is deliberately conservative and does not mean all are vested or certain to be issued. This figure should not automatically be described as exclusively employee compensation; potentially issuable shares can involve equity awards and other contingent securities.
5. The documented subtotal of **254.9m** is reconstructed from identified issuance disclosures, **not a certified total outstanding on October 15**. More recent SEC filing data could supersede it.

**Shares modeled = 251.7 + 2.2 + 1.0 + 25.2 + (246 / 3.22) = 356.5 million.**

## Valuation equation

**EV = future annual/run-rate EBITDA × selected EV/EBITDA multiple.**

**Residual common equity = max(0, EV − $2,700m net debt).**

**Implied price per share = residual common equity / 356.4975m modeled shares.**

This is a static normalized-earnings **scenario sensitivity**, not a cash-flow discount model and not an automatic target price. No separate value is awarded for unrealized partnerships, and the calculation does not forecast net debt or share changes through 2028.

## Valuation table: 8x and 10x

All enterprise values are in **USD millions**. Equity-price outputs are in **USD/share**.

| Future EBITDA | EV @ 8x | Price @ 8x | EV @ 10x | Price @ 10x |
|---|---:|---:|---:|---:|
| $275m | $2,200m | ~$0.00 | $2,750m | $0.14 |
| $300m | $2,400m | ~$0.00 | $3,000m | $0.84 |
| $400m | $3,200m | $1.40 | $4,000m | $3.65 |
| **$500m** | **$4,000m** | **$3.65** | **$5,000m** | **$6.45** |
| $600m | $4,800m | $5.89 | $6,000m | $9.26 |
| $700m | $5,600m | $8.13 | $7,000m | $12.06 |
| **$800m** | **$6,400m** | **$10.38** | **$8,000m** | **$14.87** |
| $900m | $7,200m | $12.62 | $9,000m | $17.67 |

**Worked example, $500m EBITDA at 10x:** EV = 500 × 10 = $5,000m; equity = 5,000 − 2,700 = $2,300m; share price = 2,300 / 356.5 ≈ **$6.45**.

**Worked example, $800m EBITDA at 8x:** EV = 800 × 8 = $6,400m; equity = 6,400 − 2,700 = $3,700m; share price = 3,700 / 356.5 ≈ **$10.38**.

The smallest EBITDA cases create little or no residual value for equity because the modeled debt claim consumes most or all of EV. A theoretical nil equity value should not be confused with a literal forecast of the traded share price.

## Net-debt sensitivity: holding the same share count

This cross-check demonstrates how sensitive common-equity value is to financing the AI expansion.

| EBITDA / Multiple | Debt $2.7bn | Debt $3.2bn | Debt $3.7bn |
|---|---:|---:|---:|
| $500m / 8x | $3.65 | $2.24 | $0.84 |
| $500m / 10x | $6.45 | $5.05 | $3.65 |
| $800m / 8x | $10.38 | $8.98 | $7.57 |
| $800m / 10x | $14.87 | $13.46 | $12.06 |

Every **$356.5m increase in net debt** translates to approximately **$1.00/share lower value** in a case where residual equity remains positive. Debt may also fall if ATM proceeds are preserved or FCF is used for repayment; those favorable outcomes are not embedded in the headline table.

## Capex and FCF sanity check

Management's announced initial **~2 MW / ~$75m capex** implies **~$37.5m/MW** for that *specific* deployment. Extending it without mix changes to 30 MW implies **~$1.125bn** of investment, but this is **not an official total project capex forecast**. Equipment financing, hardware obsolescence, power/network upgrades, interest and eventual replacement costs prevent the projected $225–300m+ AI adjusted EBITDA from automatically becoming common-equity FCF.

The company guides to **$285–295m adjusted FY2026 EBITDA**. A purely illustrative additive bridge of **~$290m baseline + $225–300m at full 30 MW** gives **~$515–590m** before changes to legacy operations, reinvestments and potential overlaps. **$800m of consolidated EBITDA requires far more than simply achieving the announced minimum AI unit economics.**

## Questions to revisit each quarter

- Actual common shares outstanding and ATM amount remaining (update the denominator rather than assuming it stays at 356.5m).
- Debt principal, accounting carrying value, lease claims, net debt and available liquidity.
- Contracted, operating and planned AMD MW: do not treat announced MW as recognized revenue.
- Revenue and unit margin for GPU-as-a-service, managed inference and other AI contracts.
- CFO; cash capex; finance-lease additions; hardware-backed borrowings; principal amortization; replacement capex.
- Status of refinancing and covenant headroom ahead of the 2028 maturity wall.

> **Methodology warning:** Fixed $2.7bn net debt plus hypothetical completed ATM issuance is intentionally a **simplified and asymmetric sensitivity**: it recognizes potential new shares without automatically reducing debt by potential ATM cash proceeds, because those proceeds may be deployed in GPUs or working capital. Recalculate consistently once real sources and uses of funds are reported.

> Independent analytical sensitivity for educational and professional research; not investment advice.
