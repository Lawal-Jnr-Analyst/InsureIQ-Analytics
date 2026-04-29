# 🛡️ InsureIQ Analytics

An interactive insurance analytics dashboard built with **Power BI**, analysing policyholder demographics, BMI risk profiles, and charge patterns across US regions.

---

## 📊 Live Dashboard

👉 **[View the Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMzlmYTg4NDktZGQ0OS00N2Q0LWJkNmEtYzU4YmUzZTM2ZTVmIiwidCI6IjA3M2U1ODhkLTI4NmMtNDAwNS04ZmYwLWYyYWMzYzhlYTRkMyJ9)**

---

## 📁 Project Structure

```
InsureIQ-Analytics/
│
├── insurance.csv                   # Source dataset (1,338 records)
├── InsureIQ_Analytics.pbit         # Power BI template file
├── InsureIQ_Analytics.jpg          # Dashboard preview image
└── README.md
```

---

## 🗂️ Dataset Overview

**Source file:** `insurance.csv` — 1,338 policyholders

| Column | Type | Description |
|---|---|---|
| `age` | Integer | Policyholder age |
| `sex` | String | Gender (male / female) |
| `bmi` | Float | Body Mass Index |
| `children` | Integer | Number of dependants |
| `smoker` | String | Smoking status (yes / no) |
| `region` | String | US region (northeast, northwest, southeast, southwest) |
| `charges` | Float | Annual insurance charge (USD) |

---

## 📈 Dashboard Features

### KPI Cards
- **Total Policyholders** — 1,338
- **Avg Annual Charge** — $13,270.42
- **Avg BMI** — 30.66
- **Highest Charging Region** — Southeast

### Visuals
| Visual | Insight |
|---|---|
| Avg Charge by Region | Southeast leads at ~$14.7K; Southwest lowest at ~$12.3K |
| Smoker Distribution (Donut) | 20.48% smokers vs 79.52% non-smokers |
| Smoker vs Non-Smoker Avg Charge | Smokers pay ~$32K vs ~$8.4K for non-smokers — a **3.8× premium** |
| Age Distribution | Relatively even spread; 45–54 age band is the largest group (287) |
| Avg Charge by BMI Category | Obese policyholders average $16K vs $9K for underweight |
| BMI vs Charge Scatter | Clear charge uplift for smokers at every BMI level |

### Filters / Slicers
- **Gender** — Female / Male toggle
- **Region** — Northeast / Northwest / Southeast / Southwest

---

## 🔑 Key Insights

1. **Smoking is the single strongest cost driver** — smokers are charged nearly 4× more than non-smokers, regardless of BMI or age.
2. **BMI compounds risk for smokers** — the scatter plot shows smoker charges accelerate sharply above BMI 30.
3. **Southeast is the highest-cost region** on average, while Southwest is the most affordable.
4. **Age distribution is broadly even**, suggesting this dataset represents a cross-sectional population sample rather than a skewed risk pool.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard design, DAX measures, report layout |
| Power Query (M) | Data loading and type standardisation |
| CSV (insurance.csv) | Raw data source |

---

## 🚀 How to Use

1. **Clone this repository**
   ```bash
   git clone https://github.com/Lawal-Jnr-Analyst/InsureIQ-Analytics.git
   cd InsureIQ-Analytics
   ```

2. **Open the template in Power BI Desktop**
   - Open `InsureIQ_Analytics.pbit`
   - When prompted, point the data source to `insurance.csv` in the repo root

3. **Or view the live published dashboard directly**
   👉 [Live Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMzlmYTg4NDktZGQ0OS00N2Q0LWJkNmEtYzU4YmUzZTM2ZTVmIiwidCI6IjA3M2U1ODhkLTI4NmMtNDAwNS04ZmYwLWYyYWMzYzhlYTRkMyJ9)

---

## 📷 Preview

![InsureIQ Analytics Dashboard](InsureIQ_Analytics.jpg)

---

## 📄 Licence

This project is for portfolio and educational purposes. The dataset is publicly available via [Kaggle – US Health Insurance Dataset](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset).

---

## 👤 Author

**Lawal Jamiu**
Data Analyst | SQL · Power BI · Python

- 🔗 [LinkedIn](https://linkedin.com/in/lawal-jnr-analyst)
- 🐙 [Lawal-Jnr-Analyst](https://github.com/Lawal-Jnr-Analyst)
