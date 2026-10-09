# Repsol (REP) - Bear-Case Model Snapshot

This page summarizes selected outputs from my internal Repsol model. The purpose is to distinguish **2026 peak-cycle cash generation** from a more normalized mid-cycle earnings base.

## Macro Assumptions: Company vs. Internal Model

Repsol's early-2026 guidance assumed **$60–65/bbl Brent**, **$3.5–4/MMBtu Henry Hub**, and a **$6.5–7.5/bbl Refining Margin Indicator**. Management cited an additional **~$1.4/bbl budgeted refining premium**, roughly **$1.4–1.5/bbl** in my planning range. The March 2026 strategy update's central case was **$65 Brent, $4 Henry Hub, and $6.5/bbl Refining Margin Indicator**.

| Variable | Repsol's 2026 planning framework | My full-year 2026 scenario |
|---|---:|---:|
| Brent ($/bbl) | $60–65 (central $65) | **~$91.2** |
| Henry Hub ($/MMBtu) | $3.5–4 (central $4.0) | **~$4.0** |
| Refining Margin Indicator ($/bbl) | $6.5–7.5 (central $6.5) | **~$23.2** |
| Additional refining premium ($/bbl) | ~$1.4–1.5 | **~$8.4** |
| Full refining margin, **before** haircut ($/bbl) | ~$7.9–9.0 | **~$31.7** |
| **Haircut-adjusted sensitivity proxy ($/bbl)** | **$8.6 internal model base** | **~$29.5** |

The **~$23.2/bbl indicator and ~$8.4/bbl premium** are the four-quarter arithmetic averages of my 2026 model (including Q3 and Q4 estimates). They are not actual FY2026 reported averages.

The **indicator + premium** is the full economic refining margin, but I use a separate **haircut-adjusted cash-flow sensitivity proxy** in the workbook:

**Proxy = indicator + 0.75 × premium.**

I retain **75% of the premium**, corresponding to a **25% discount**, not a 50% discount (which would require a multiplier of 0.50). The premium comes from activities with different cash-flow conversion characteristics: heavy-crude discounts, product mix, increased kerosene yield, HVO / SAF, biofuel economics, logistics, trading and temporary optimization opportunities. Repsol's **€200m/bbl official CFFO sensitivity covers the Refining Margin Indicator**, so extending that sensitivity to even 75% of the premium is **my simplifying conservative assumption**, not an officially validated relationship. The $8.6 model base is kept unchanged to reproduce the original workbook; it is an internal comparison benchmark, **not the output of applying the same haircut to Repsol's planning assumptions**.

### Quarterly refining build-up

| Variable ($/bbl) | Q1 | Q2 | Q3 model | Q4 model |
|---|---:|---:|---:|---:|
| Refining Margin Indicator | 10.9 | 14.0 | 34.0 | 34.0 |
| Premium | 5.7 | ~10.0 | 9.0 | 9.0 |
| Full indicator + premium | 16.6 | ~24.0 | 43.0 | 43.0 |
| **Indicator + 0.75 × premium** | **15.2** | **21.5** | **40.8** | **40.8** |

**Q1 = 10.9 + 5.7 × 0.75 = 15.175/bbl.** Q2 uses an approximately **$10/bbl quarterly premium** reported by management, not a March premium: **14 + 10 × 0.75 = 21.5/bbl**. My H2 scenario extrapolates a **July 2026 company call reference of $34/bbl indicator + $9/bbl premium** through Q3 and Q4: **34 + 9 × 0.75 = 40.75/bbl** for each modeled quarter.

The July reference is a **scenario anchor**, not a published Q3 or Q4 average. Management said total unadjusted refining margin for FY2026 might still exceed **$20–21/bbl even if the Strait of Hormuz reopened**. That supports an elevated margin environment but does not imply H2 will necessarily reach my assumption.

### Other quarterly assumptions

| Variable | Q1 | Q2 | Q3 model | Q4 model | Full-year model average |
|---|---:|---:|---:|---:|---:|
| Brent ($/bbl) | 81.1 | 103.8 | 90.0 | 90.0 | **~91.2** |
| Henry Hub ($/MMBtu) | 5.1 | 2.9 | 4.0 | 4.0 | **~4.0** |
| **Haircut-adjusted refining proxy ($/bbl)** | **15.2** | **21.5** | **40.8** | **40.8** | **~29.5** |

*Q3 and Q4 are model assumptions. Repsol's provisional October 6 Q3 data reported $97 Brent, $3.0 Henry Hub and a $36.2/bbl indicator (not directly comparable with my premium-adjusted proxy).*

### Macro impact on CFFO: model sensitivity, not company guidance

| Driver | Internal model base | 2026 modeled average | Modeled incremental CFFO |
|---|---:|---:|---:|
| Brent | $65.0/bbl | ~$91.2/bbl | **~€656m** |
| Henry Hub | $4.0/MMBtu | ~$4.0/MMBtu | **~€0m** |
| Haircut-adjusted refining proxy | $8.6/bbl internal base | ~$29.5/bbl | **~€4,184m** |
| **Total** | | | **~€4,839m** |

These are the outputs in my screenshot (component amounts rounded; total from unrounded inputs). The workbook uses **€250m per $10 Brent**, **€130m per $0.5 Henry Hub**, and **€200m per $1 change in my haircut-adjusted refining proxy**. The published 2026–2028 Brent sensitivity is **€285m per $10**, not €250m. The published refining sensitivity applies to the **Refining Margin Indicator for Spanish industrial complexes**; applying it to all-in margin including premium is only a simplifying scenario assumption. Repsol confirmed at its March 2026 Capital Markets Day that **about 50% of its U.S. gas output for 2026** was hedged through a **$3.2–3.3/MMBtu floor and $5.2–5.3/MMBtu cap** collar. This does not mean 50% of group-wide gas volumes are hedged. My modeled hedge adjustment is only about **+€11m of CFFO and +€13m of EBIT**, so I deliberately show **~€0m of incremental Henry Hub CFFO** in the high-level macro bridge; the small hedge effect is not material to the conclusions and is not Repsol guidance.

Consequently **~€4.84bn is a directional, linear uplift**, not reported CFFO, not Repsol's own earnings forecast, and not an exact bridge to the adjusted CFFO in my valuation model.

## Cash-Flow Scenarios

| Metric | Normalized / Planning Case | 2026 High-Price Case |
|---|---:|---:|
| Adjusted CFFO | **~€6.0bn** | **~€10.2bn** |
| Net Capex | **~€3.9bn** | **~€3.9bn** |
| Lease / other cash adjustments | **~€0.65bn** | included in model |
| FCF | **~€2.1bn** | **~€6.3bn** |
| FCF / Share | **~€1.9** | **~€5.7** |

At a share price around **€29–€30**, the high-price case implies only around **5x FCF**.

The bearish thesis is that this multiple is misleading because the underlying commodity and refining assumptions are far above normalized levels.

## Normalized Valuation

Using approximately **€1.9/share** of normalized FCF:

| Multiple | Implied Value |
|---|---:|
| 10x P/FCF | **~€19/share** |
| 11x P/FCF | **~€21/share** |
| 12x P/FCF | **~€23/share** |

My normalized thesis target is **below €22/share**, anchored around the 10x–11x FCF cases (~€19–€21/share). The 12x result (~€23/share) is retained as a higher-multiple sensitivity, not part of my target range.

Using the **October 6, 2026 close of €28.76/share** and the **€1.051/share total cash dividend paid in 2026**:

| Reference | Price Return | Dividend Contribution* | Illustrative Total Return* |
|---|---:|---:|---:|
| **€22/share** | **-23.5%** | **+3.7%** | **~-19.9%** |

\*Illustrative one-year bridge using the 2026 cash dividend as the dividend reference.

This is an illustrative scenario at the upper threshold of my below-€22 target, not a precise final target. The dividend-inclusive bridge illustrates the equity-holder return; a short position would instead have to account for dividends owed, borrow fees and other costs. The purpose is to avoid capitalizing peak-cycle FCF as if it were permanent.

## Official Sensitivities

Repsol's 2026–2028 sensitivity framework estimates approximately:

- **±€285m CFFO** for each **±$10/bbl Brent**;
- **±€130m CFFO** for each **±$0.5/MMBtu Henry Hub**;
- **±€200m CFFO** for each **±$1/bbl refining-margin indicator**;
- **±€50m CFFO** for each **±1% USD appreciation vs EUR**.

The **~$29.5/bbl haircut-adjusted proxy** in my high-price scenario is far above the **$8.6/bbl internal model base**. The corresponding average **unadjusted indicator + premium is ~$31.7/bbl**. However, the premium component must be separated from the official refining-margin indicator before using company sensitivities as a precise forecast.

## Cash-Flow Accounting Adjustment

Repsol's consolidated cash-flow statement does not line-by-line consolidate the underlying operating cash flows of equity-accounted affiliates.

The company changed its segment reporting model at the end of 2025 so that joint ventures are accounted for using the **equity method**, reflecting the increasing relevance of minority shareholders and JVs.

My model therefore does not rely mechanically on headline consolidated CFO. It reconciles reported CFFO with:

- interest / lease cash items;
- net capex and divestments;
- transactions with non-controlling interests where economically relevant;
- equity-affiliate economics and distributions.

The purpose is comparability across changes in ownership structure and reporting perimeter.

## Cycle Context

2026 is an unusually strong energy year:

- Brent traded around **$100/bbl in early October**;
- H1 2026 Brent averaged about **$92/bbl**;
- refining margins and premiums were far above Repsol's strategic assumptions;
- Middle East and Russia/Ukraine disruptions supported oil and product prices.

This is exactly the environment in which a cyclical company can look cheapest on trailing or current earnings.

### Public Sources

- [Repsol 2026–2028 assumptions and sensitivities](https://www.repsol.com/en/accionistas-inversores/informacion-economica-financiera/index.cshtml)
- [Repsol FY2025 earnings-call transcript: budgeted refining premium](https://www.repsol.com/content/dam/repsol-corporate/es/accionistas-e-inversores/resultados/2025/4t/transcripcion-webcast-4t25.pdf)
- [Repsol Q1 2026 presentation: 2026 outlook and sensitivities](https://www.repsol.com/content/dam/repsol-corporate/en_gb/accionistas-e-inversores/cnmv/2026/ori30042026-presentation-on-results-first-quarter-2026.pdf)
- [Repsol Q1 2026 earnings call: $5.7/bbl premium](https://uk.investing.com/news/stock-market-news/earnings-call-transcript-repsols-q1-2026-earnings-rise-amid-strong-industrial-gains-93CH-4640994)
- [Repsol Q2 2026 call: $10/bbl Q2 premium and July $34 + $9 reference](https://earningsapi.io/transcripts/repsol-s-a_rep_earnings_call_transcript_2026-07-23)
- [Repsol March 2026 Capital Markets Day: 50% U.S. gas hedging collar](https://www.repsol.com/content/dam/repsol-corporate/es/conocenos/documentos-conocenos/transcripcion-webcast-capital-markets-day.pdf)
- [Repsol Q3 2026 trading statement: provisional market data](https://www.repsol.com/content/dam/repsol-corporate/en_gb/accionistas-e-inversores/cnmv/2026/ori06102026-trading-statement-3q26.pdf)
- [Repsol FY2025 results / reporting model](https://www.repsol.com/content/dam/repsol-corporate/es/accionistas-e-inversores/rif/2026/rif19022026-press-release-results-year-2025.pdf)
- [Repsol Q2 2026 results](https://www.repsol.com/en/shareholders-and-investors/financial-information/quarterly-results/index.cshtml)

> Figures labeled as internal/model values come from my own workbook and assumptions. This is a research snapshot, not investment advice.
