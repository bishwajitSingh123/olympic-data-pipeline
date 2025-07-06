# 🏅 Olympic Data Engineering Pipeline

This is an **end-to-end Azure-based data engineering project** where we built a scalable Olympic data analytics solution using:

- **Azure Data Factory** (ADF)
- **Azure Data Lake Storage (ADLS Gen2)**
- **Azure Databricks with Delta Lake**
- **Apache Spark using PySpark**
- **CI/CD with Azure DevOps**
- **Bronze-Silver-Gold Layered Architecture**

---

## 📌 Project Architecture
ADF → Bronze (Parquet) → Databricks Cleaning → Silver → Transformations → Gold → Analytics


---

## 🚀 Tools & Technologies Used

| Tech Stack          | Purpose |
|---------------------|---------|
| Azure Data Factory  | Orchestration & Ingestion |
| ADLS Gen2           | Data Storage |
| Databricks (PySpark)| Transformation & Processing |
| Delta Lake          | Lakehouse format |
| Azure DevOps        | CI/CD pipelines |

---

## 🧱 Project Layers

### 🔸 Bronze Layer
- Raw data ingested via ADF pipeline
- Stored in ADLS in Parquet format

### ⚪ Silver Layer
- Data cleaned using PySpark (null handling, type casting)
- Stored as managed Delta tables

### 🟡 Gold Layer
- Aggregated tables (Top countries, coaches, events)
- Ready for visualization or business reporting

---

## 📂 Project Structure (GitHub Files)

```bash
├── notebooks/
│   └── databricks_notebook.ipynb
├── arm_templates/
│   └── adf_pipeline_arm.json
├── screenshots/
│   └── bronze_ingestion.png
│   └── silver_gold_transform.png...
├── README.md
└── LICENSE (Apache 2.0)



🔁 DevOps Workflow
Feature branch created for ingestion

Lookup + ForEach + If Condition + CopyData

Pull Request → Merge to main

Published & ARM templates created

🎯 Outcomes
Full data lifecycle automation

Scalable Lakehouse model

Clean CI/CD practices

🙏 Author
Bishwajit Singh
🛠️ Aspiring Data Engineer | Passionate about building data pipelines
📍 Kolkata, India
- [🔗 LinkedIn](https://www.linkedin.com/in/bishwajitsingh/)
- [📧 Email](mailto:bishwajit.1804@gmail.com)

🌟 Show Your Support!
If you liked the project, don’t forget to ⭐ the repo and share it on LinkedIn 🚀
