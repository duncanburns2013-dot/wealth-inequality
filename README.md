# How Federal Policy Engineered Wealth Inequality

**An interactive data dashboard cross-referencing 7 official federal sources to show how QE, ZIRP, COVID spending, and government debt systematically transferred wealth upward.**

🔗 **[View the Dashboard](https://duncanburns2013-dot.github.io/wealth-inequality/)**

---

## The Question

**Who did Federal Reserve and government fiscal policy actually help?**

## The Answer (from their own data)

| Metric | Value | Source |
|--------|-------|--------|
| Top 1% Net Worth | **$54.8 Trillion** | Fed DFA, Q3 2025 |
| Top 1% Wealth Share | **31.7%** (up from 23.6% in 1989) | Fed DFA |
| Bottom 50% Wealth Share | **2.6%** | Fed DFA |
| Per-Household Wealth Ratio | **610:1** (Top 1% vs Bottom 50%) | Fed DFA |
| Federal Debt | **$36.2T** (121% of GDP) | Treasury/OMB |
| M2 Money Supply | **$21.5T** (+152% since 2008) | Federal Reserve |
| Labor Share of GDP | **42.7%** (down from 51.6% in 1970) | BEA |
| Purchasing Power Decline | **-94.7%** since 1968 peak | BEA/BLS |

---

## The Policy Mechanisms

### 1. Money Printing (QE)
The Fed expanded its balance sheet from $900B to $8.97T, buying bonds from banks who invested in financial assets — not Main Street. The top 1% own 54% of all equities; the bottom 50% own 1.3%.

### 2. Zero Interest Rates (ZIRP)
14 years of near-zero rates (2008–2022) destroyed returns for savers while enabling $7T+ in corporate stock buybacks, inflating share prices and executive compensation.

### 3. COVID Response ($5.2T)
The most aggressive monetary + fiscal expansion in history. The Fed's balance sheet doubled. M2 grew 40% in two years. The S&P 500 doubled from March 2020 to December 2021. The top 1% gained $12T in two years.

### 4. Structural Deficits
Federal debt grew from $5.6T to $36.2T. Annual interest payments now exceed $1T — flowing to bondholders, while inflationary effects erode worker purchasing power.

---

## Dashboard Sections

1. **Overview** — Key metrics and the question
2. **Money Printing** — M2, Fed balance sheet, CPI correlation
3. **ZIRP** — Federal funds rate history, winners and losers
4. **Debt & Deficits** — Federal debt, debt/GDP, annual deficits
5. **COVID** — Timeline, spending totals, acceleration of inequality
6. **Who Benefited** — Fed DFA wealth shares, equity ownership, wealth levels
7. **Who Got Left Behind** — Labor share, purchasing power, wages, median income
8. **Synthesis** — Cumulative growth indexed to 2007, the full transmission mechanism

---

## Data Sources (Official Only)

| Source | Series | Period |
|--------|--------|--------|
| **Federal Reserve DFA (Z.1)** | WFRBST01134, WFRBSB50215, WFRBLT01026 | Q3 1989 – Q3 2025 |
| **Federal Reserve Board** | WALCL, FEDFUNDS, M2SL | 2003 – Jan 2026 |
| **U.S. Treasury / OMB** | GFDEBTN, GFDEGDQ188S, FYFSGDA188S | 1966 – Q3 2025 |
| **BEA** | W270RE1A156NBEA (Labor Share) | 1948 – 2024 |
| **BLS** | PRS85006173, CPIAUCSL | 1947 – Q3 2025 |
| **Atlanta Fed** | Wage Growth Tracker (all breakdowns) | 1997 – Dec 2025 |
| **Census Bureau** | MEHOINUSA672N, MEHOINUSMAA672N | 1984 – 2024 |

Every chart uses non-partisan federal data. No think tanks. No opinion pieces. Just government numbers.

---

## Deployment

This is a single-file HTML dashboard. To deploy on GitHub Pages:

1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages**
3. Set Source to **Deploy from a branch** → `main` → `/ (root)`
4. Your dashboard will be live at `https://duncanburns2013-dot.github.io/wealth-inequality/`

---

## Technical Details

- **Single-file HTML** — no build step, no dependencies to install
- **Chart.js 4.4.1** — loaded from CDN for interactive charts
- **Lazy loading** — charts render only when scrolled into view
- **Dark theme** — Instrument Serif + DM Sans typography
- **15 interactive charts** across 8 sections
- **~127KB total** — all data embedded in JavaScript

---

## Key Findings

### The Transmission Mechanism

1. **Fed creates money** → buys bonds from banks → banks invest in financial assets
2. **Asset prices rise** → stocks +213%, real estate +60% since 2007 → top 1% captures majority
3. **ZIRP kills saving** → 0% returns → workers lose purchasing power
4. **Corporations lever up** → borrow at 0% → buy back $7T+ in stock → exec comp soars
5. **Government deficit spends** → $36T debt → $1T/year interest → paid to bondholders
6. **Inflation hits** → food, rent, healthcare up 20-40% → erodes real wages
7. **Labor share declines** → 8.9pp drop = ~$2.6T/year shifted from workers to capital
8. **Result:** Top 1% wealth +213% vs median household income +15% since 2007

---

*Updated February 2026*
