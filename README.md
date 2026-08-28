# Hi, I'm Sergio 👋

**Grid operations → data engineering.** I spent four years operating Spain's
national electricity transmission grid in real time. Now I build the kind of
data pipelines I used to depend on in the control room.

🎯 **Looking for:** Data Engineer / Analytics Engineer roles in **Switzerland**
(Zurich · Basel · Bern · Swiss-remote)
🇪🇺 **EU citizen (Spanish)** : no work permit needed for Switzerland; based in Switzerland

---

## 🔭 What I'm building

### [solar-analytics](https://github.com/sergio-corredor-llopis/solar-analytics) : end-to-end solar performance analytics platform

An ELT pipeline over **14M+ rows** of photovoltaic telemetry: **13 PV systems,
10 years of readings (Feb 2013 – Dec 2023)**.

**S3 → Airflow → dbt → BigQuery → Streamlit**

- **Ingestion:** raw telemetry landed in S3, orchestrated with Airflow
- **Transformation:** dbt Cloud with staging → intermediate → marts layering, plus dbt tests
- **Warehouse:** BigQuery — time-grain-aggregated fact tables (daily / monthly / annual), 50+ calculated metrics per daily row
- **Performance engineering:** solar KPIs computed per **IEC 61724**
- **Validation:** results checked against a university benchmark : **0.003% deviation**, with 5 data-quality bugs caught and fixed along the way
- **Front-end:** Streamlit dashboard

## ⚡ Where I come from

**Transmission Operator (Data & Analytics Focus) at Red Eléctrica (REE)** : Spain's national grid
operator (TSO) for 4 years. Real-time operation of high-voltage grid
telemetry: load curves, generation schedules, balancing, cross-border
exchanges, across 1,500+ substations under ENTSO-E discipline. I also built
internal operations tooling that my colleagues used daily, which is what
pulled me from operating data systems to engineering them.

Why it transfers: grid operations is data work where being wrong is not an
option. Validation, lineage, and observability aren't best practices there :
they're survival. That's the instinct I bring to data engineering.

## 📜 Certifications

- **AWS Certified Solutions Architect : Associate** (Feb 2026)
- **dbt Fundamentals** (Mar 2026)

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Cloud-FF694B?logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?logo=amazons3&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?logo=googlebigquery&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## 🗣️ Languages

Spanish (native) · English (C2) · French (B1) · German (A2, actively studying)

## 📫 Contact

- LinkedIn: [linkedin.com/in/sergio-corredor-llopis](https://www.linkedin.com/in/sergio-corredor-llopis)

*BSc Electrical Engineering, Universidad Politécnica de Madrid (UPM) · Based in Basel*
