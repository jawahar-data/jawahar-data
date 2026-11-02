<h1 align="center">Jawahar R</h1>

<p align="center">
  <b>Data Engineering Student</b> · B.Tech Artificial Intelligence & Data Science<br/>
  Dhanalakshmi Srinivasan Engineering College, Perambalur, Tamil Nadu
</p>

<p align="center">
  I build and ship data pipelines: ingestion, transformation, orchestration, validation, and serving,<br/>
  with a focus on reliability and clean data modeling.
</p>

<p align="center">
  <a href="https://jawahar-portfolio-theta.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Live-brightgreen?style=flat-square&logo=vercel" /></a>
  <a href="https://flowmarics.streamlit.app"><img src="https://img.shields.io/badge/FlowMatrix-Live%20Dashboard-blue?style=flat-square&logo=streamlit" /></a>
  <a href="https://linkedin.com/in/jawahar-r-2114a932b"><img src="https://img.shields.io/badge/LinkedIn-Jawahar%20R-0A66C2?style=flat-square&logo=linkedin" /></a>
  <a href="mailto:j26219096@gmail.com"><img src="https://img.shields.io/badge/Email-j26219096%40gmail.com-red?style=flat-square&logo=gmail" /></a>
</p>

---

## Featured Project: [FlowMatrix](https://github.com/jawahar-data/flowmatrix-pipeline)

An end-to-end e-commerce data pipeline modeled on the public Olist dataset as a proxy for Rakuten Ichiba. It combines a streaming ELT pipeline with an AWS data lake, and serves a [live Streamlit dashboard](https://flowmarics.streamlit.app).

| | |
|---|---|
| **Orders in the AWS lake** | 99,441 (Olist), with order counts reconciled across bronze and silver |
| **Streaming run** | 1,247 events through Kafka and PySpark |
| **Transformation** | 7 dbt models, 34 automated data-quality tests (100% passing) |
| **Orchestration** | 6-task Airflow DAG with retry logic, under 2 minutes end to end |
| **Query efficiency** | ~17.6 MB scanned on raw CSVs vs. under 1 KB on a gold table |

**How it fits together**

- **Streaming path:** Kafka → PySpark → dbt → PostgreSQL, orchestrated by Airflow and validated with Great Expectations. Runs locally with Docker.
- **Lake path:** S3 bronze (raw CSV) → silver (typed Parquet) → gold (pre-aggregated), built with idempotent Athena SQL, provisioned with Terraform, and checked by GitHub Actions on every push.
- **Serving:** the Streamlit dashboard reads the gold layer through a least-privilege, read-only IAM identity.

---

## Other Projects

- **[Weather ETL Dashboard](https://github.com/jawahar-data/weather-etl-dashboard)**: client-side ETL pulling live weather and AQI data for 5 global cities, with no backend. [Live](https://jawahar-data.github.io/weather-etl-dashboard/)
- **[Kisan Sahayak](https://github.com/jawahar-data/Kisan-Sahayak)**: multilingual AI agricultural assistant (Tamil, Hindi, English) delivering crop prices and farming advice. Built for the national AI For Bharat Hackathon.
- **[Real-Time 3D Asset Pipeline](https://github.com/jawahar-data/Real-Time-3D-Asset-Data-Pipeline-Serving-API)**: FastAPI serving layer with thread-safe caching for binary 3D assets. [Live](https://jawahar-data.github.io/Real-Time-3D-Asset-Data-Pipeline-Serving-API/)

---

## Tech Stack

| | |
|---|---|
| **Languages** | Python, SQL, JavaScript |
| **Data engineering** | Apache Kafka, PySpark, Apache Airflow, dbt, Great Expectations |
| **Cloud and infrastructure** | AWS (S3, Athena, IAM), Terraform, Docker, GitHub Actions, PostgreSQL (Neon) |
| **Serving** | FastAPI, Streamlit |

---

## Experience

- **Data Analytics Virtual Internship**: AICTE + EduSkills, supported by Google Cloud (Jun to Aug 2026, 8 weeks)
- **AI-ML Virtual Internship**: AICTE + EduSkills, supported by Google for Developers (Oct to Dec 2025, 10 weeks)

---

## Certifications

| Credential | Issuer |
|---|---|
| CS50: Introduction to Databases with SQL | Harvard University (edX) |
| Google Cloud Data Analytics Certificate | Google Cloud |
| Python Project for Data Engineering | IBM / Coursera |
| Python for Data Science, AI & Development | IBM / Coursera |
| Introduction to Data Engineering | IBM / Coursera |
| Computer Architecture & Organization | NPTEL / IIT Kharagpur |
| AWS Cloud Practitioner Essentials (training course) | Amazon Web Services |

---

## Currently

- Working through the IBM Data Engineering Professional Certificate
- Practicing data structures and algorithms on LeetCode

---

## Seeking

Data Engineering internships, remote or hybrid, where I can work on real pipelines and data infrastructure. Open to Summer and Fall 2027 roles.

---

<p align="center">
  <a href="https://jawahar-portfolio-theta.vercel.app">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/jawahar-r-2114a932b">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:j26219096@gmail.com">Email</a>
</p>
