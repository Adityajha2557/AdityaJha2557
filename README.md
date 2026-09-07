<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:161B22&height=180&section=header&text=ADITYA%20JHA&fontSize=46&fontColor=58A6FF&fontAlignY=42&desc=AI/ML%20Engineer%20%7C%20Cloud-Native%20Systems&descAlignY=62&descColor=8B949E&animation=fadeIn" width="100%"/>

<a href="https://linkedin.com/in/aditya-jha">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=560&lines=Building+intelligent+systems+end+to+end;LLM+Integration+%7C+Structured+Output+%7C+RAG;Distributed+Data+%7C+PySpark+%2F+Hadoop;Cloud+Deployment+on+AWS+%7C+FastAPI+%2B+REST" alt="Typing SVG" />
</a>

</div>

<br/>

```
$ whoami
```

Final-year Computer Science student (Cloud Computing) who likes understanding AI systems end to end — not just the model, but the pipeline around it. I've built LLM-integrated systems that keep generative output honest by checking it against deterministic, code-based logic (JSON-schema-constrained generation, multi-model fallback with sub-second failover), trained and compared classical ML models on distributed data with PySpark/Hadoop, and shipped the FastAPI/REST layer that gets those models into production on AWS. I'm still deepening my grip on lower-level ML systems tooling — GPU profiling, inference runtimes — but I pick things up fast and enjoy the plumbing as much as the modeling.

<br/>

```
$ system_status --check
```

<div align="center">

| Component | Status |
|---|---|
| Machine Learning (PyTorch / TensorFlow / Scikit-learn) | 🟢 `ONLINE` |
| LLM Systems (Gemini · JSON-constrained output) | 🟡 `BUILDING` |
| Distributed Data (PySpark · Spark MLlib · Hadoop/HDFS) | 🟢 `ONLINE` |
| Cloud Infrastructure (AWS: EC2 / S3 / Lambda / IAM) | 🟢 `ONLINE` |
| Backend & Inference (FastAPI · REST APIs) | 🟢 `ONLINE` |
| GPU Profiling / Inference Runtimes | 🟠 `LEARNING` |

</div>

<br/>

## `> tech_stack`

<div align="center">

**AI / ML**
<br/>
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn" />

**Data & Distributed Systems**
<br/>
<img src="https://skillicons.dev/icons?i=hadoop,mongodb" /> &nbsp;
`PySpark` `Spark MLlib` `Pandas` `NumPy`

**Cloud & DevOps**
<br/>
<img src="https://skillicons.dev/icons?i=aws,azure,gcp,linux,git,github" />

**Backend & APIs**
<br/>
<img src="https://skillicons.dev/icons?i=fastapi,nodejs,ts,js" />

**Databases**
<br/>
<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb" />

**Visualization / BI**
<br/>
<img src="https://skillicons.dev/icons?i=powerbi" /> &nbsp;
`Tableau` `Excel`

</div>

<br/>

## `> featured_projects`

<table>
<tr>
<td width="50%" valign="top">

### 🔹 RevenueGuard AI
**AI-powered financial investigation platform**

`React` `Python` `Google Gemini` `JSON Schema-Constrained Output`

Combines LLM reasoning with deterministic backend logic — every dollar figure the model produces is cross-checked against code-based calculations, so financial output stays accurate even if the LLM's reasoning drifts. Runs parallel fallback across three Gemini variants (`Promise.any`) with tested sub-second failover, and automatically extracts structured fields from unstructured PDF/Word contracts to flag billing discrepancies.

</td>
<td width="50%" valign="top">

### 🔹 HealthPulse
**AI/ML outbreak prediction platform**

`Python` `NLP` `FastAPI` `AWS` `React`

A data pipeline combining NLP-based text classification with **48 time-series forecasting models** across 8 symptoms and 6 regions. Deployed behind REST APIs on AWS, tuned for sub-second inference latency under real-time query load, with a React dashboard for outbreak-risk visualization.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔹 Heart Disease Prediction
**Distributed ML pipeline**

`PySpark` `Spark MLlib` `Hadoop` `HDFS`

Distributed data-processing pipeline training and evaluating 5+ classification models (Logistic Regression, Random Forest, Gradient-Boosted Trees, MLP) on large-scale healthcare data stored in HDFS — compared on precision, recall, F1, and ROC-AUC rather than accuracy alone.

</td>
<td width="50%" valign="top">

### 🔹 Customer Churn & Retention Analytics
**Explainable churn modeling**

`Scikit-learn` `XGBoost` `SHAP`

Segmented customers by risk and engagement, then built and compared Logistic Regression, Random Forest, and XGBoost models. Used SHAP to identify the strongest churn drivers and turned that into a ranked, plain-language list of retention actions.

</td>
</tr>
</table>

<div align="center">

**🔹 Biogas Yield Analysis — Explainable Predictive Analytics**
`Scikit-learn` `SVR` `SHAP` — Built a Support Vector Regression model (**R² = 0.9366**) on process data and used SHAP to explain which operating variables drove yield the most.

</div>

<br/>

## `> architecture_pattern`

*A shape common across my ML/data projects:*

```
  RAW DATA (structured + unstructured)
        │
        ▼
   INGESTION / ETL   ──  PySpark · Pandas · MongoDB
        │
        ▼
  FEATURE ENGINEERING
        │
        ▼
   MODEL / LLM LAYER  ──  PyTorch · Scikit-learn · Gemini (constrained output)
        │
        ▼
  VALIDATION LAYER    ──  deterministic checks on generative output
        │
        ▼
     INFERENCE API    ──  FastAPI · REST
        │
        ▼
   CLOUD DEPLOYMENT   ──  AWS (EC2 · S3 · Lambda · IAM)
```

<br/>

## `> experience`

**Freelance AI/ML & Cloud Developer** · *Jan 2025 – Jul 2026*
Built, tested, and deployed REST APIs (FastAPI) to serve trained ML models in production; validated inference reliability under real client workloads. Provisioned and managed AWS infrastructure (EC2, S3, Lambda, IAM), and automated deployment workflows with Linux/Bash/Git — cutting repetitive deployment effort by ~30%.
`FastAPI` `AWS` `Linux` `Bash` `Git`

**Data Analytics Intern — WTW (Willis Towers Watson)** · *May 2025 – Jul 2025*
Pulled and cleaned business data with SQL and Python (Pandas/NumPy); ran exploratory and statistical analysis, then built Power BI and Tableau dashboards to make findings actionable for the team.
`SQL` `Python` `Power BI` `Tableau`

**Program Support Intern — Plan International India Chapter** · *Jun 2025 – Jul 2025*
Collected and validated field-level program data across Anganwadi centers, synthesizing it with qualitative observations into documented insights for national reporting.

<br/>

## `> certifications`

<div align="center">

`AWS Certified AI Practitioner (AIF-C01)` · `AWS Solutions Architect – Associate (SAA-C03)` · `AWS Certified Cloud Practitioner (CLF-C02)`
`Azure DevOps Engineer Expert (AZ-400)` · `Oracle Cloud Infrastructure Foundations Associate` · `Google Cloud Computing Foundations` · `GitHub Copilot Certification (GH-300)`

</div>

<br/>

## `> currently_building`

```
$ currently_building   → hallucination-checked LLM pipelines (structured / JSON-constrained generation)
$ currently_exploring  → RAG & GraphRAG, GPU profiling, inference runtimes
```

<br/>

## `> github_analytics`

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=AdityaJha2557&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=F0F6FC" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdityaJha2557&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=F0F6FC" height="165"/>
</div>

<div align="center">
<img src="https://streak-stats.demolab.com/?user=AdityaJha2557&theme=github-dark-blue&hide_border=true&background=0D1117" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/AdityaJha2557/AdityaJha2557/output/github-contribution-grid-snake-dark.svg" />
</div>

<br/>

## `> contact`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-linkedin.com/in/aditya--jha-0D1117?style=flat-square&logo=linkedin&logoColor=58A6FF&labelColor=0D1117)](https://linkedin.com/in/aditya-jha)
[![GitHub](https://img.shields.io/badge/-github.com/AdityaJha2557-0D1117?style=flat-square&logo=github&logoColor=58A6FF&labelColor=0D1117)](https://github.com/AdityaJha2557)
[![Email](https://img.shields.io/badge/-adityeahrnc1@gmail.com-0D1117?style=flat-square&logo=gmail&logoColor=58A6FF&labelColor=0D1117)](mailto:adityeahrnc1@gmail.com)

</div>

<br/>

<div align="center">

`BUILD` · `DEPLOY` · `LEARN` · `REPEAT`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:161B22,100:0D1117&height=100&section=footer" width="100%"/>

</div>
