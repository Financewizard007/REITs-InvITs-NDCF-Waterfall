# 💧 NDCF Waterfall Calculator

> **From EBITDA to Distribution. Every Step. Explained.**  
> The only free tool that calculates the complete NDCF waterfall for Indian REITs and InvITs — the way institutional investors model it.

🔗 **Live:** [financewizard007.github.io/ndcf-calculator](https://financewizard007.github.io/ndcf-calculator/)

---

## What Problem Does This Solve?

Most retail investors evaluate REITs and InvITs using **EBITDA or revenue** — and get the yield calculation completely wrong.

Here's why that matters:

```
EBITDA:  ₹3,116 Cr   ← what most people use
Interest: ₹674 Cr    ← deducted
Amort:    ₹350 Cr    ← deducted (most people miss this)
Capex:    ₹95 Cr     ← deducted
WC:       +₹45 Cr    ← added back

NDCF:    ₹2,042 Cr   ← what actually reaches you
```

The gap between EBITDA and NDCF is **₹1,074 Cr** in this example. That's the money that never reaches your account. This calculator shows you exactly where it goes.

---

## Two Tabs

### ⚡ Calculator Tab
Enter any REIT or InvIT's numbers and see the full NDCF waterfall — step by step, in real time.

**Inputs:**
| Input | What It Is |
|-------|-----------|
| Gross Revenue | Total rental / toll / tariff income |
| Operating Expenses | Property management, admin, maintenance |
| Total Debt | Outstanding borrowings |
| Interest Rate | Weighted average cost of debt |
| Scheduled Amortisation | Mandatory principal repayment |
| Asset AUM / GAV | Gross Asset Value (for leverage check) |
| Maintenance Capex | Capex to maintain existing assets |
| Working Capital | Net WC movement |
| Units Outstanding | Total units in the trust |
| Distribution Payout % | % of NDCF distributed (min 90% by SEBI) |
| Unit Price (CMP) | Current market price per unit |

**Outputs:**
- ✅ **DPU** — Distribution Per Unit per year
- ✅ **Yield %** — at your entered price
- ✅ **DSCR** — Debt Service Coverage Ratio
- ✅ **Leverage %** — vs SEBI limit
- ✅ **Full 7-step waterfall** — with bar visualization
- ✅ **Investor Interpretation** — plain English verdict
- ✅ **Sensitivity Table** — DPU across interest rate × occupancy scenarios

**Pre-loaded Presets:**

| Trust | Type | Yield |
|-------|------|-------|
| Embassy Office Parks | REIT | ~7% |
| Mindspace Business Parks | REIT | ~7% |
| Brookfield India REIT | REIT | ~7.5% |
| Nexus Select Trust | REIT | ~6.5% |
| IndiGrid Infrastructure Trust | InvIT | ~9% |
| PowerGrid InvIT | InvIT | ~8% |
| NDR InvIT Trust | InvIT | ~9% |
| Raajmarg InvIT | InvIT | ~8.5% |

---

### 🏛️ Structure Guide Tab

A complete visual education on how REITs and InvITs actually work — for investors who want to understand the structure before investing.

**REIT section covers:**
- Visual entity diagram — Unitholders → Trust → SPVs → Tenants
- 6 key parties — Trustee, Sponsor, Manager, Valuer, SEBI, SPV
- 12 SEBI regulatory rules with values
- REIT vs InvIT comparison table
- How distributions are taxed (Interest / Dividend / Return of Capital)
- Why NDCF ≠ EBITDA — with a clear worked example

**InvIT section covers:**
- 7 asset class types — Highway Toll, Highway Annuity, Power Transmission, Renewable Energy, Gas Pipeline, Telecom Towers, Warehousing
- Revenue model, key risk, and typical yield for each

---

## The Key Insight This Tool Teaches

> *"The distribution yield is 7% based on EBITDA."*  
> ❌ **This is wrong.**

Three mandatory deductions sit between EBITDA and what reaches your account:

1. **Scheduled Amortisation** — principal repayment is a real cash outflow that EBITDA ignores
2. **Maintenance Capex** — assets need investment to remain leasable; depreciation adds back, capex takes it back
3. **Working Capital** — deposits, advance rents, WC movements all affect actual cash

Always evaluate REITs and InvITs on **NDCF yield** — not EBITDA yield.

---

## SEBI Rules at a Glance

| Rule | Value |
|------|-------|
| Minimum distribution | 90% of NDCF |
| Distribution frequency | Quarterly |
| REIT leverage limit | 49% of AUM |
| InvIT leverage limit | 49% (listed) · 70% (unlisted debt) |
| Minimum income-producing assets | 80% of portfolio |
| Sponsor lock-in | 15% for 3 years |

---

## Tech Stack

- Pure HTML + CSS + JavaScript — zero dependencies
- Single file — works offline after download
- No frameworks, no backend, no build step
- Hosted on GitHub Pages

---

## Related Projects

- 🏢 [REITs & InvITs Decoded](https://financewizard007.github.io/reit-invit-decoded/) — Visual business model breakdowns of all 15 listed REITs and InvITs
- ⚡ [PE Return Machine](https://financewizard007.github.io/pe-return-machine/) — Decompose PE / P/FFO returns into earnings growth and multiple re-rating
- 📊 [Nifty 250 Decoded](https://financewizard007.github.io/nifty250-decoded/) — Business models of India's top 250 companies
- 🗺️ [India Inc Knowledge Graph](https://financewizard007.github.io/india-inc-graph/) — How India's top companies connect

---

## About

Built by **The Finance Lens** ([@financelensin](https://youtube.com/@financelensin))  
Building tools that make institutional finance accessible to everyone.

> *Not financial advice. Data as of 2026. Built for learning.*

---

⭐ Star this repo if you find it useful · Share with anyone evaluating REIT or InvIT investments
