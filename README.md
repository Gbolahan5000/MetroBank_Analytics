# 🏦 MetroBank Customer & Performance Analytics
**Excel Analytics Project | Excel · PivotTables · Data Modeling · Dashboard Design**

---

## 📌 Project Overview

Banks generate enormous volumes of customer, account, and transaction data — but most of that data never turns into a decision. It just sits in a system.

This project is an end-to-end analysis of **MetroBank**, a fictional financial institution, built entirely in Excel across five focus areas: customer segmentation, account and credit health, transaction behavior, branch performance, and risk. Each week took on a different role and a different business question, moving from *"who is the customer?"* all the way to *"where is the bank exposed to risk?"*

> **The goal:** turn raw customer, account, transaction, branch, and complaint data into a set of dashboards that a bank's leadership team could actually act on.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data cleaning, PivotTables, calculated fields, dashboard build |
| Excel Charts & Slicers | Interactive visuals and filtering |
| Excel Formulas | KPI calculations (AVERAGEIFS, SUMIFS, COUNTIFS, etc.) |

---

## 📂 Repository Structure

```
metrobank-analytics/
│
├── workbooks/
│   ├── W3.xlsx
│   ├── mb w2.xlsx
│   ├── mb.xlsx
│   ├── w4.xlsx
│   └── w5.xlsx
│
├── assets/
|   |── dash1.png/
│   |── dash2.png/
│   |── dash3.png/
│   |── dash4.png/
│   └── dash5.png/
|
└── README.md
```

---

## ⚙️ Project Pipeline

```
Phase 1 → Data Loading & Understanding
Phase 2 → Data Cleaning (Excel)
Phase 3 → Structuring & Calculated Fields
Phase 4 → PivotTable & Formula-Based KPIs
Phase 5 → Dashboard Design & Layout
Phase 6 → Insights & Recommendations
```

Each of the five weeks below followed this same pipeline, applied to a different dataset and business question.

---

## 📊 Week 1 — Customer Profiling & Segmentation
**Role:** Marketing Analyst · **Question:** *Who is the MetroBank customer?*

| Metric | Value |
|---|---|
| Total Customers | 500 |
| Average Income | $114,398.82 |
| Gender Split | 51% Female / 49% Male |
| Largest Region | South (137) |
| Largest Segment | Retail (286) |
| Largest Tenure Group | Established, 3–5 yrs (170) |

**Regional distribution:** South (137) → East (133) → North (120) → West (110)
**Segments:** Retail (286) → Corporate (169) → Private (45)

**Insight:** The customer base is dominated by Retail, but is only slightly skewed by region — meaning marketing strategy needs to be segment-led rather than region-led.

---

## 💳 Week 2 — Accounts & Financial Relationships
**Role:** Relationship Management Analyst · **Question:** *What does the bank's financial relationship with its customers look like?*

| Metric | Value |
|---|---|
| Total Deposit Balance | $212,341,134 |
| Total Approved Loans | $3,677,399 |
| Average Credit Score | 580 |
| Customers with 2+ Products | 195 |

**Product ownership:** Savings (235) → Checking (190) → Credit Card (143) → Loan (81)

**Key findings:**
- Private customers hold the highest *average* balance per customer, but Retail holds the highest *total* deposits simply due to volume.
- Millennials and Gen Z customers hold higher balances than older generations.
- The top 5 customers each carry balances over $1.7M.
- Bankers, doctors, and engineers hold the largest deposit balances by occupation.

---

## 💸 Week 3 — Transaction Behavior & Patterns
**Role:** Operations Analyst · **Question:** *How do customers actually use the bank day to day?*

| Metric | Value |
|---|---|
| Total Transactions | 5,000 |
| Total Value | $25,066,089 |
| Average Value | $5,013.22 |

**Findings & recommendations:**

| # | Finding | Recommendation |
|---|---|---|
| 1 | High average transaction value suggests low-value, high-frequency activity is underrepresented | Expand microtransaction / digital wallet support |
| 2 | Withdrawals ($6.39M) slightly exceed deposits ($6.20M) — a net outflow risk | Incentivize deposits (higher savings rates); promote transfers and bill pay |
| 3 | ATM ($6.31M) and Branch ($6.31M) dominate, driving up maintenance cost | Push migration to online ($6.08M) and mobile channels |
| 4 | Merchant spend concentrated in digital services and travel (Airbnb, Apple); local retail lags | Expand local merchant partnerships and loyalty rewards |
| 5 | Customers *without* credit cards transact more on payment-type activity | Reposition credit cards as the primary payment tool (e.g. cashback on bills); target non-card holders |

---

## 🏢 Week 4 — Branch Performance & Efficiency
**Role:** BI / Branch Operations Analyst · **Question:** *Which branches are actually worth investing in?*

| Metric | Value |
|---|---|
| Total Revenue | $59.42M |
| Total Cost | $21.17M |
| Total Profit | $38.25M |
| Profit Margin | 64% |
| Avg. Revenue per Staff | $30.46K |

**By region:**

| Region | Verdict |
|---|---|
| North & West | Highest efficiency and margins — West has the highest revenue per staff. **Invest.** |
| South | Strongest raw revenue, but high operating costs. **Optimize costs.** |
| East | Weakest financial performer. **Reassess / restructure.** |

---

## ⚠️ Week 5 — Customer Experience & Risk Intelligence
**Role:** Strategic Analyst (reporting to CCO & CRO) · **Question:** *Where is the bank exposed, and why are customers unhappy?*

| Metric | Value |
|---|---|
| Total Complaints | 800 |
| Total Fraud Cases | 142 |
| Average Resolution Time | 31 days |
| Cases Resolved | 59% |

**Complaint breakdown:** Charges Dispute (184) → Others (167) → Service Delay (159) → Technical Issues (148) → Fraud (142)

**Key insight:** Retail customers account for 58% of all reported issues — more than Corporate and Private combined.

**Recommendations:**
1. Strengthen real-time risk profiling to catch behavioral red flags earlier.
2. Use personalized financial-literacy messaging to engage medium-risk customers.
3. Introduce credit support / restructuring programs for high-risk customers to reduce default exposure.

---

## 🎯 What I Focused On

| Focus Area | Approach |
|---|---|
| Data structuring | Clean, consistent Excel tables ready for PivotTables |
| KPI design | Metrics chosen to answer a specific business question per week, not just report numbers |
| Cross-week narrative | Each week builds on the last — demographics → financial relationship → behavior → branch economics → risk |
| Storytelling | Every finding paired with a concrete recommendation |

---

## 📄 Deliverables

| Deliverable | Description |
|---|---|
| `workbooks/*.xlsx` | Excel workbooks for each of the five analytical areas |
| `assets/dashboard_screenshots/` | Dashboard views for each week |
| `README.md` | Full project documentation |

---

## 👤 Author

**Lawal Yusuf Gbolahan**
Data Analyst · Analytical Engineering

*A five-week deep dive into a fictional bank's customers, accounts, transactions, branches, and risk — built entirely in Excel.*
