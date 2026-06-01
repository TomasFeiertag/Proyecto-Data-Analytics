<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4285F4,100:0d1117&height=180&section=header&text=Argentina%20Internet%20Analytics&fontSize=38&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Telecom%20Market%20Analysis%20%7C%20ENACOM%20Data%20%7C%20Power%20BI%20Dashboard&descAlignY=60&descSize=17&descColor=a0c4ff" />

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 📌 Overview

End-to-end data analytics project analyzing the **evolution of internet access in Argentina** over the last decade using ENACOM public data. Includes full ETL pipeline, exploratory data analysis, KPI definition, and an interactive Power BI dashboard to support strategic decisions.

**Role:** Data Analyst (solo project)  
**Context:** Simulated consulting engagement for ENACOM (Argentina's telecommunications regulator)

---

## 🎯 KPIs Defined

| KPI | Target | Formula |
|---|---|---|
| **Internet access per 100 households** | +2% growth per quarter, per province | `(New Access - Current Access) / Current Access × 100` |
| **Internet access per 100 individuals** | +4.2% growth per quarter, per province | Same formula, per-capita basis |

---

## 🔍 Key Findings

### 📡 ADSL Technology Access
Distribution shows high concentration at low values with notable outliers — asymmetric distribution skewed toward lower connectivity areas.

![Acceso a la tecnología](Imagenes/Accesos_tecnologia.png)

### 👤 Access per 100 Individuals
Consistent quarterly growth throughout the decade, with a **notable spike in 2020–2021** driven by COVID-19 pandemic (remote work + distance learning). Peak values reached in 2023.

![Acceso por 100 habitantes](Imagenes/Evolucion_Acceso_cada_100_Habitantes.png)

### 🏠 Access per 100 Households by Province
Significant regional disparities: **Buenos Aires and Córdoba** show highest connectivity medians; **Formosa and Santiago del Estero** lag significantly behind.

![Acceso por 100 hogares](Imagenes/Porcen_Accesos_cda_100_hogares.png)

---

## 🔄 Pipeline

```
ENACOM Raw Data ──► ETL (Python + Pandas) ──► EDA + KPI Analysis ──► Power BI Dashboard
```

- Full ETL pipeline: cleaning, normalization, type conversion
- EDA with trend analysis and outlier detection
- Interactive Power BI dashboard with provincial-level KPIs

---

## ⚒️ Tech Stack

| Layer | Tools |
|---|---|
| **Processing** | Python, Pandas |
| **Analysis** | Jupyter Notebook, Matplotlib |
| **Visualization** | Power BI |

---

## ▶️ How to Run

```bash
git clone https://github.com/TomasFeiertag/Proyecto-Data-Analytics.git
cd Proyecto-Data-Analytics
pip install -r requirements.txt
# Open notebooks/ in Jupyter, then open the .pbix in Power BI Desktop
```

---

## 👤 Author

**Tomás Feiertag** — Data Scientist · NLP & LLMs @ Movistar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/tfeiertag/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/TomasFeiertag)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:4285F4&height=100&section=footer" />
