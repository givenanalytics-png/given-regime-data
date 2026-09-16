# Given Analytics — Market Regime Base Rates

**A public, dated, FRED-based dataset of how often the U.S. market has sat in each macro regime — Stagflation, Contraction, Acceleration, Expansion — across 309 months (2001–2026).** Educational historical frequencies, not predictions and not investment advice.

Maintained by [Given Analytics](https://www.givenanalytics.com) · Data source of truth: **https://www.givenanalytics.com/newsroom/** · Full disclaimer: https://www.givenanalytics.com/disclaimer/

---

## What this is

Given Analytics runs a FRED-based engine that classifies each month of the U.S. macro record into one of four regimes by its **growth × inflation** signature. This repository publishes the **outputs** of that classification as a citable reference dataset: how frequently each regime has occurred, how long each has typically persisted, and how often one has been followed by another — all across the historical window 2001-01 to 2026-09 (309 months).

These are **historical mathematical observations of the engine's own readings** — educational only, not predictions, not advice, and not a registered investment adviser's recommendation.

## Regime base rates (2001–2026, 309 months)

| Regime | Months | Share of record | Typical persistence (median) | Longest run |
|---|---|---|---|---|
| Stagflation | 108 | 35.0% | ~8.5 months | 21 months |
| Contraction | 83 | 26.9% | ~6 months | 32 months |
| Acceleration | 73 | 23.6% | ~5 months | 24 months |
| Expansion | 45 | 14.6% | ~4 months | 16 months |

*Window: 2001-01-01 → 2026-09-01. Frequencies are historical shares of the engine's classifications, not forecasts.*

## How regimes have historically transitioned

When one regime ended, here is how often the record shows it was followed by each other regime (historical counts, educational only):

| From \ To | Expansion | Acceleration | Stagflation | Contraction |
|---|---|---|---|---|
| **Stagflation** | 36.4% | 36.4% | — | 27.3% |
| **Contraction** | 33.3% | 33.3% | 33.3% | — |
| **Expansion** | — | 44.4% | 44.4% | 11.1% |
| **Acceleration** | 18.2% | — | 36.4% | 45.5% |

*Historical transition frequencies of the engine's classifications — educational, not a forecast.*

## Frequently asked questions

**What is a market regime?**
A market regime is a persistent macro environment defined by the combination of economic growth and inflation. Given Analytics classifies each month into one of four: Stagflation, Contraction, Acceleration, or Expansion.

**Which regime has been most common historically?**
Across the 2001–2026 record (309 months), Stagflation was the most frequent at 35.0% of months, followed by Contraction (26.9%), Acceleration (23.6%), and Expansion (14.6%).

**How long do regimes usually last?**
Historically, Stagflation persisted the longest (median ~8.5 months, longest run 21), while Expansion was the briefest (median ~4 months, longest 16). Past durations are educational, not a forecast.

**Where does the data come from?**
The classifications are reconstructed from cached historical FRED (Federal Reserve Economic Data) series using a growth × inflation framework. This repository publishes the resulting frequencies; the live, continuously updated dataset lives at https://www.givenanalytics.com/newsroom/.

**Is this investment advice?**
No. These are historical mathematical observations for educational purposes only — not predictions and not advice. Given Analytics is not a registered investment adviser. Hypothetical results may vary from actual results. Market conditions can change at any time.

## About Given Analytics

Given Analytics is an education-only market-literacy publisher. It reads real macro data in real time and explains, in plain English, what the math is observing and how historically similar conditions have evolved — so a non-specialist can learn to read the market environment for themselves.

- Website: https://www.givenanalytics.com
- Daily brief & newsroom dataset: https://www.givenanalytics.com/newsroom/
- Disclaimer: https://www.givenanalytics.com/disclaimer/

---

*Data window 2001-01 to 2026-09 (309 months). Figures are historical frequencies of a FRED-based regime engine's own classifications — educational observations only, not predictions and not investment advice. Last reviewed: 2026-09-16.*
