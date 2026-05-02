# Australia Energy Trade Analysis (1989–2024)

> **"What do 35 years of energy trade data tell us about Australia's strategic vulnerabilities — and what comes next?"**

A visual analytics project exploring Australia's energy import and export patterns from 1989 to 2024, with forecasting through 2029. Built with Tableau for UTS 32146 Data Visualisation and Visual Analytics (Autumn 2025).

---

## Key Findings

- **Petroleum accounts for 97%+ of Australia's energy imports** in 2023 — a single-point dependency with significant strategic risk
- **Coal and gas dominate exports** — Australia is a net energy exporter in fossil fuels overall, but critically dependent on imported petroleum
- **Four global crises left visible marks** on the data: Global Financial Crisis (2008), Oil Price Crash (2016), COVID-19 (2020), Russia-Ukraine War (2022)
- **Forecast (2025–2029):** Petroleum imports will remain elevated but may gradually decline, with uncertainty widening due to ongoing geopolitical volatility

---

## The Problem

Australia is one of the world's largest energy exporters — yet simultaneously one of its most import-dependent nations for petroleum. This project was built to answer: *Where is the structural risk in Australia's energy trade, how did global shocks reshape it, and what does the next five years look like?*

---

## Data & Preparation

**Source:** Australian Bureau of Statistics — Energy Trade Dataset (1989–2024)

Three structured Excel layers were built before visualization:

| Layer | Purpose |
|---|---|
| Raw Dollar | Cleaned absolute trade values (exports + imports) |
| Statistical Pattern | Ratio of each category to total (compositional analysis) |
| Analytical Pattern | Year-on-year change (% increase/decrease vs prior year) |

Note: 1988 was excluded — no prior year available for YoY calculation.

---

## Visualizations

| Chart Type | What It Answers |
|---|---|
| Stacked Bar (yearly) | How trade composition shifts across 35 years |
| Line Chart (petroleum) | Petroleum import trends and crisis-period spikes |
| Pie Chart | Import composition ratio: Petroleum vs Coal vs Gas |
| Treemap / Heatmap | Petroleum import volatility by year |
| Forecast Line (95% CI) | Projected petroleum imports, 2025–2029 |

---

## Insights

**On imports:** Machinery and Transport Equipment is Australia's largest import category overall, but within energy, Mineral Fuels (almost entirely petroleum) dominates.

**On exports:** Mineral Fuels lead Australia's export values — coal and gas. The asymmetry between energy exports (strength) and petroleum imports (vulnerability) is the central story.

**On crises:** Each of the four major global events produced a measurable shock — either a demand collapse (COVID-19) or a price spike (Russia-Ukraine). The 2022 spike was the sharpest in the 35-year record.

**Recommendation from analysis:** Diversify energy imports, reduce single-source petroleum dependency, accelerate domestic alternatives — the data makes the case clearly.

---

## Tech Stack

`Tableau` · `Microsoft Excel` (pivot, ratio calculations, YoY delta) · `Data storytelling`

---

## Files

| File | Description |
|---|---|
| `14487805_A3.twb` | Tableau workbook (all dashboards) |
| `14487805_A3-4.xlsx` | Cleaned data (Raw Dollar, Statistical Pattern, Analytical Pattern) |
| `14487805_A3-4.pdf` | Full report with figures and analysis |

---

## Context

Individual project. UTS Bachelor of IT — Data Analytics (Autumn 2025).
