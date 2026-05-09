# 🧩 Customer Segmentation Analysis

> RFM-based K-Means clustering dashboard to segment customers by behavior and demographics.

🔗 **Live Demo:** [https://piyush-kumar-768.github.io/customer-segmentation-analysis](https://piyush-kumar-768.github.io/customer-segmentation-analysis)

---

## 📌 Project Overview

This project segments customers into distinct groups based on their purchasing behavior using **RFM Analysis** (Recency, Frequency, Monetary) combined with **K-Means Clustering** logic. The interactive dashboard helps businesses identify high-value customers, at-risk users, and dormant segments — enabling targeted marketing strategies.

---

## 🎯 5 Customer Segments Identified

| Segment | Description | Strategy |
|---|---|---|
| 🔴 Champions | High spend, frequent, recent buyers | Reward with VIP perks |
| 🔵 Loyalists | Consistent buyers, moderate spend | Upsell & cross-sell |
| 🟢 At-Risk | Previously active, now fading | Win-back campaigns |
| 🟡 New Customers | Recent first-time buyers | Onboarding & welcome offers |
| 🟣 Dormant | Long inactive, low engagement | Last-chance discount |

---

## ✨ Key Features

- **RFM Scoring** — Recency, Frequency, Monetary value analysis
- **K-Means Clustering** — 5 distinct customer segments
- **Interactive Scatter Plot** — Spend vs Purchase Frequency by segment
- **Radar Chart** — Behavioral profile comparison across segments
- **Segment Distribution** — Donut chart with customer share
- **Revenue Bar Chart** — Avg customer lifetime value per segment
- **Feature Importance** — Which variables drive segmentation most
- **Actionable Insights** — Business recommendations per segment
- **Customer Table** — Individual records with segment filter
- **CSV Upload & Export** — Bring your own data or export results

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| HTML / CSS / JavaScript | Frontend & UI |
| Chart.js | Data visualisation (scatter, radar, donut, bar) |
| PapaParse | CSV file parsing & upload |
| Python (scikit-learn) | K-Means clustering logic (referenced) |
| RFM Methodology | Customer scoring framework |

---

## 📊 Dataset

The dashboard ships with **500 auto-generated customers** across 5 regions, 6 product categories, and varied purchase histories. You can also upload your own CSV with these columns:

```
id, age, gender, region, recency, frequency, spend, category
```

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/piyush-kumar-768/customer-segmentation-analysis.git

# Navigate into the folder
cd customer-segmentation-analysis

# Open in browser
open index.html
```

No installation needed — runs entirely in the browser.

---

## 📁 Project Structure

```
customer-segmentation-analysis/
│
├── index.html        # Main dashboard (all-in-one)
└── README.md         # Project documentation
```

---

## 📈 Business Insights Generated

- **Champions** drive ~40% of total revenue despite being ~15% of customers
- **At-Risk** customers can be recovered with targeted win-back emails within 30 days
- **New Customers** need strong onboarding to convert into Loyalists
- **Dormant** segment should receive a final re-engagement offer before removal

---

## 👤 Author

**Piyush Kumar**
B.Tech CSE (AI & ML) — Guru Jambheshwar University of Science & Technology

- 📧 piyushkumar768x@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/piyush-kumar2908)
- 🐙 [GitHub](https://github.com/piyush-kumar-768)

---

## 🏆 Acknowledgements

- Built as part of a Data Analytics internship project submission
- RFM methodology referenced from industry-standard customer analytics frameworks
- Clustering approach inspired by scikit-learn's KMeans implementation
