# 🍷 Exploring Global Wine Trends: Data Manipulation & Visualization with Python  
**Expensive Doesn't Always Mean Better: What 130K Wine Reviews Reveal About Price & Quality**  
**Dataset:** [Wine Reviews Dataset](https://www.kaggle.com/datasets/zynicide/wine-reviews)  
**Analyze 130K wine reviews to uncover regional patterns, price-quality dynamics, and actionable insights for building a global wine marketplace.**

---

## 📊 Project Overview  
This project focuses on analyzing a dataset of **130,000 wine reviews**, including details about wine variety, origin, vineyard, price, and description.  
The goal is to explore the data and extract insights that could inform the creation of a **global wine marketplace**, connecting **small local producers** with **buyers worldwide**.  

A key methodological choice was splitting the dataset into two: `df_wr_full` (all records, used for country-level analysis) and `df_wr` (province-complete records only, used for regional deep dives) — ensuring accuracy at both global and local levels.

Through **Python, Pandas, FuzzyWuzzy, and data visualization tools**, this analysis identifies price trends, quality benchmarks, and consumer preferences.

---

## 🎯 Objectives  
- **Country-Level Insights:** Understand global wine performance by calculating average scores and prices per country.  
- **Italian Market Focus:** Deep dive into Italy's regional data to explore price distributions, correlations, and provincial differences.  
- **European Context:** Map wine production across Europe to highlight major producers and grape varieties.  
- **Price–Quality Relationship:** Measure correlations to determine whether higher prices truly align with better quality.  

---

## 🧠 Key Insights  
- **All analyzed countries score above 80 points** on average — signaling a global trend toward excellence in wine production.
- **Switzerland has the highest average wine price**, driven by high cost of living and limited variety; France, Italy, and Portugal offer better value across a broader range.
- **Italian wine average price: €39.66**, but the **median is €28** — a positively skewed distribution caused by high-end outliers (variance: 1,447.99), confirming a market that spans from everyday to luxury.
- **Piedmont has the highest average price** among Italian provinces; **Tuscany** follows closely — yet all provinces consistently score **around 90 points**, suggesting price reflects prestige and demand rather than quality gaps.
- **Tuscany accounts for 30%** of bottles sold nationally, confirming its dominant global brand.
- **Moderate correlation (0.42)** between price and quality — price does not guarantee excellence.

---

## 🧰 Tools & Libraries  
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, FuzzyWuzzy  
- **Environment:** Jupyter Notebook  

---

## 🗂️ Dataset  
- **Source:** [Wine Reviews Dataset](https://www.kaggle.com/datasets/zynicide/wine-reviews) (130,000 rows)  
- **Main Columns:** `country`, `province`, `variety`, `vineyard`, `price`, `points`, `description`

---

## 📈 Visualizations  
1. Average Wine Score by Country (Bar Chart)  
2. Average Wine Price by Country (Bar Chart)  
3. Distribution of Italian Wine Prices (KDE Plot with mean, median, std dev)  
4. Average Price and Score by Italian Province (Grouped Bar Chart)  
5. Bottles Sold by Province in Italy (Donut Pie Chart)  
6. Correlation Between Price and Score (Heatmap)  
7. European Wine Production Map (Choropleth)  

---

## 🔍 Conclusions  
The analysis reveals **widespread excellence** in the international wine industry, with **Italy leading** both in production and diversity.  
Regional disparities highlight opportunities for **market segmentation** — from high-end producers in Piedmont and Tuscany to accessible, high-quality wines from Southern Italy and Sicily.  
The weak-to-moderate price–quality correlation (0.42) is a key finding for marketplace design: **quality can be found at every price point**, making it possible to build a curated selection that serves both budget-conscious and premium buyers.

---

## 📎 Files in this Repository  
| File | Description |
|------|--------------|
| `Wine_Review_Data_Manipulation_Visualization.ipynb` | Main analysis in Python (data cleaning, exploration, visualization). |
| `Wine_Review_Marketplace_Presentation.pdf` | Project presentation and key takeaways. |
| `README.md` | Project overview, context, and insights. |
