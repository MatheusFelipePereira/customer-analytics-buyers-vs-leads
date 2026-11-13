<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:F2C811,100:E37400&height=120&text=Customer%20Analytics&fontSize=42&fontColor=1b1b1b&desc=Buyers%20vs%20Leads&descAlignY=78&descSize=16&fontAlignY=42" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20Query%20(M)-217346?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Google%20Analytics-E37400?style=for-the-badge&logo=googleanalytics&logoColor=white" />
  <img src="https://img.shields.io/badge/Meta%20Ads-0467DF?style=for-the-badge&logo=meta&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/period-Feb%202025%20→%20Mar%202025-555?style=flat-square" />
  <img src="https://img.shields.io/badge/org-Data%20Mundo-555?style=flat-square" />
  <img src="https://img.shields.io/badge/area-Marketing-555?style=flat-square" />
</p>

<p align="center"><img src="cover.jpg" width="85%" alt="Customer Analytics dashboard" /></p>

## 🎯 The question

> *Who is the best target audience for our next campaigns?*

A report built for the **marketing area** of a digital product. It analyzes **buyer** and **lead** data to find the ideal audience for upcoming campaigns, highlighting the **direct correlation between leads and buyers** and how to leverage that relationship to attract new customers.

## 🔎 What the report answers

- 👥 Who are the **leads** and who actually **buys**?
- 🔗 How strongly do lead characteristics correlate with purchase?
- 📣 Which channels (**Meta Ads**, **Google Analytics** traffic) bring the best leads?
- 🎯 Which profile should the next campaign target?

## 🏗️ Pipeline

```mermaid
flowchart LR
    A[Meta Ads] --> C[Power Query - M<br/>ETL]
    B[Google Analytics] --> C
    L[Leads & buyers data] --> C
    C --> D[Data model + DAX measures]
    D --> E[Power BI report<br/>Customer Analytics]
```

## 🛠️ What I did

- **ETL** with Power Query (M) to bring the sources together
- **Data modeling** and **DAX** measures for the lead → buyer analysis
- **Report design** focused on a marketing audience
- Data source: a **CSV refreshed daily** with **Google Analytics 4 (GA4)** extractions

## 🚀 Results

| | |
|---|---|
| 📈 **+10%** | lead conversion through clustering by behavior and traffic source |
| 🎯 **Better targeting** | lead profiles with the highest propensity to convert identified |

## 📸 Dashboard gallery

<table>
  <tr>
    <td width="50%" align="center"><img src="img/01.png" /><br/><sub><b>Home</b> · navigation: Buyers, Leads, Correlations</sub></td>
    <td width="50%" align="center"><img src="img/02.png" /><br/><sub><b>Buyers</b> · states, gender, age, income, education</sub></td>
  </tr>
  <tr>
    <td width="50%" align="center"><img src="img/03.png" /><br/><sub><b>Leads</b> · states, retention, age, region map</sub></td>
    <td width="50%" align="center"><img src="cover.jpg" /><br/><sub><b>Correlations</b> for new leads</sub></td>
  </tr>
</table>

---

<sub>👤 Part of <a href="https://github.com/MatheusFelipePereira">Matheus Felipe Pereira's portfolio</a> · <a href="https://www.linkedin.com/in/matheus-felipe-p/">LinkedIn</a></sub>
