<p align="center">
  <img src="../Revenue Optimization System/assests/banner.png" alt="Revenue Optimization System Banner" width="100%" />
</p>

<h1 align="center">🏆 Revenue Optimization System</h1>
<h3 align="center">Demand Forecasting · Pricing Intelligence · Profit Simulation</h3>

<p align="center">
  <i>Most companies rely on aggressive discounting to drive growth.<br>
  This system shows when discounts destroy profit — and how pricing drives sustainable growth.</i>
</p>

---

## 🎯 Business Problem

Retail businesses struggle with:

* **Unpredictable demand patterns**
* **Over-reliance on discounts**
* **Lack of data-driven pricing decisions**

This project answers:

* How can we forecast demand accurately?
* Which categories have pricing power?
* Do discounts actually increase profit?
* What pricing strategy maximizes both revenue **and** profit?

---

## 🛠️ Tech Stack

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/XGBoost-AA1E1E?style=for-the-badge" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" />
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge" />

</p>

---

## ⚙️ Methodology

### 1. Feature Engineering

* Built core KPIs: **revenue, cost, profit**
* Created pricing signals: **effective price, discount tiers**
* Extracted time features: **week, month, seasonality**

### 2. Demand Forecasting

* Daily aggregation with lag & rolling features
* Models: Ridge, Random Forest, Gradient Boosting, XGBoost
* Selected best model using **MAE on time-based split**

### 3. Pricing Intelligence (Elasticity)

* Log-log regression with controls
* Key insight: **price sensitivity is weaker than expected**

### 4. Discount & Profit Analysis

* Identified **profit erosion from high discounting**

### 5. Simulation Engine

* Scenario-based testing of pricing strategies
* Combines price + discount + demand response

### 6. Recommendation System

* Scenario-backed pricing strategies per category

---

## 📊 Key Insights

* **High discounts (>20%) destroy profit across all categories**
* Demand is driven more by **promotions than price changes**
* **Weak elasticity → opportunity for pricing optimization**
* Premium products show **strong pricing power**
* **Weekend demand spikes** → timing is critical

---

## 💡 Strategic Recommendations

* ❌ Eliminate blanket high-discount strategies
* 📈 Test **moderate price increases (3–5%)**
* 🎯 Shift to **targeted promotions**
* 🔬 Validate strategies using **A/B testing**
* 🔄 Combine **pricing + timing optimization**

---

## 🚀 Business Impact

This system identifies **significant profit improvement potential** by:

* Reducing unnecessary discounts
* Leveraging pricing power
* Optimizing promotion timing

> ⚠️ Results are directional — validate using controlled experiments

---

## 📂 Project Structure

```
revenue-optimization-system/
│
├── data/
├── notebooks/
├── outputs/
│   ├── plots/
│   └── results/
├── assets/
│   └── banner.png
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/revenue-optimization-system
cd revenue-optimization-system
pip install -r requirements.txt
jupyter notebook
```

---

## ⚠️ Limitations

* Elasticity estimates are **weak and unstable**
* Discount response is **approximate**
* No competitor or inventory effects included
* Synthetic dataset → requires real-world validation

---

## 🧠 Final Takeaway

The business is currently **over-reliant on discount-driven demand**, which erodes profitability.

Future growth should focus on:

➡️ Pricing discipline
➡️ Targeted promotions
➡️ Experiment-driven decisions

---
