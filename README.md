# tadiwaben.github.io

## 📁 Featured Projects
---

## ⚽ The ZimPSL Ultimate Entertainers: Sports Analytics & Web Scraping
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Web Scraping](https://img.shields.io/badge/Web%20Scraping-BeautifulSoup4-FF6F00?style=flat)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Engineering-150458?style=flat&logo=pandas&logoColor=white)
![Data Scope](https://img.shields.io/badge/Data%20Scope-2017--2024-10B981?style=flat)

A sports analytics pipeline engineered to look beyond standard points tables and mathematically measure spectator value ("entertainment index") across 8 seasons of the Zimbabwe Premier Soccer League (ZimPSL).

### 📊 Project Highlights
* **Automated Data Scraping**: Built custom Python extractors parsing 101 team-season records from historical league tables (2017–2024).
* **Feature Engineering**: Standardized goal rates, match volatility, and defensive risk metrics into a unified **Chaos & Entertainment Index**.
* **Tactical Profiling**: Mapped team playstyles into tactical quadrant matrices to isolate high-stakes, entertaining sides from low-volatility defensive teams.

### 🖼️ Visual Insights Preview
<p main="center">
  <img src="tactical-quadrant.png" alt="ZimPSL Tactical Quadrant" width="100%" style="border-radius: 8px; border: 1px solid #334155;">
</p>

### 🛠️ Tech Stack
`Python` • `BeautifulSoup` • `Pandas` • `NumPy` • `Matplotlib / Seaborn`

[📊 Read Full Analysis Report](./zimpsl-entertainment-analysis.md) | [💻 View Scraper Code](./zimpsl_scraper.ipynb)

---

### ZimAuto Valuation Engine
## 🚗 ZimAuto: End-to-End Car Valuation & Negotiation Engine
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-v1.7+-22C55E?style=flat)
![Gradio](https://img.shields.io/badge/Gradio-UI-FF7C00?style=flat&logo=gradio&logoColor=white)
![R2 Score](https://img.shields.io/badge/R%C2%B2-0.790-blue)

An institutional machine learning application designed to resolve pricing opacity and asymmetry in the Zimbabwean secondary automobile market. The system automatically scrapes marketplace listings, models non-linear vehicle depreciation with target log scaling, and serves interactive bargaining guidance.

### 📊 Performance Highlights
* **Variance Explained ($R^2$)**: **0.790** (~79% of cross-market price variance explained)
* **Predictive Accuracy (MAE)**: **~$5,112 USD** average baseline dollar error across all vehicle segments
* **Dataset Scope**: 3,000+ cleaned vehicle records scraped across regional classifieds (*ZimAuto*, *ZimClassifieds*)
* **Statistical Governance**: Real-time residual Z-score filtering ($\pm3\sigma$) to catch data anomalies and structural risks

### 🛠️ Key Technologies
`Python` • `BeautifulSoup` • `XGBoost` • `Optuna` • `Scikit-Learn` • `Gradio` • `Render`
👉 [Read Full Analysis](zimauto-evaluation-engine.md) | [Live Demo](zimauto-valuation-engine.onrender.com)
