# SoFi Technologies (NASDAQ: SOFI) - FARMSA Stock Pitch Competition

**FARMSA Fall 2025 Stock Pitch Competition**  
*Dhruv Joshi & Jaineel Patel | Honours Mathematics (Co-op), University of Waterloo*

---

## Overview

A comprehensive equity research analysis of SoFi Technologies, featuring quantitative peer comparison, Monte Carlo valuation modeling, and fundamental analysis. This project combines Python-based financial modeling with investment thesis development.

---

Key Findings

Can be found on the presented slide deck. Presented in front of 50+ individuals.

---

## Analysis Components

### 1. Peer Comparison (Risk-Adjusted Performance)
Compares SOFI against fintech peers (UPST, LC, AFRM, PYPL) using:
- Annualized Return & Volatility (3-year)
- Sortino Ratio & Omega Ratio
- Maximum Drawdown
- Market Cap-weighted bubble visualization

### 2. Monte Carlo DCF Valuation

**_50,000_** simulation model incorporating:
- **Segment-level projections:** Lending (55%), Financial Services (35%), Tech Platform (10%)
- **Triangular distributions** for growth rates, margins, and discount rates
- **Dual terminal value methods:** EV/EBITDA and EV/Revenue
- **Output:** Mean valuation $12.17B, 95% CI: $9.65B - $15.07B

### 3. Sensitivity Analysis
Three-scenario framework (Bull/Base/Bear) with WACC and terminal growth sensitivity tables.

---

## Technologies Used

- **Python 3.x** — Core analysis
- **yfinance** — Market data retrieval
- **pandas / numpy** — Data manipulation & calculations
- **matplotlib / seaborn** — Visualization
- **Google Colab** — Development environment

---

## Quick Start

```bash
# Clone repository
git clone https://github.com/[username]/sofi-equity-research.git

# Install dependencies
pip install pandas numpy yfinance matplotlib seaborn

# Run notebook
jupyter notebook sofi_analysis.ipynb
```

---

## Investment Thesis Summary

| Factor | Detail |
|--------|--------|
| **Structural Advantage** | Full-stack model lowers funding costs, increases margins |
| **Macro Tailwinds** | Rate normalization + consumer credit strength |
| **Valuation Asymmetry** | DCF and scenario analysis show clear upside with controlled downside |

### Key Risks & Mitigants
- **Credit Risk** → Prime borrower focus (avg FICO >740)
- **Rate Risk** → Non-lending segments buffer compression
- **Competitive Risk** → Multi-product switching costs create natural moat

---

## Authors

- **Dhruv Joshi** — Honours Mathematics (Co-op), University of Waterloo
- **Jaineel Patel** — Honours Mathematics (Co-op), University of Waterloo

---

*Disclaimer: This analysis is for educational purposes only and does not constitute professional investment advice.*
