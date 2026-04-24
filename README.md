# Azure Data Factory (ADF) Pipeline Assignments

## 📌 Overview

This repository contains assignments and implementations using Azure Data Factory (ADF) for building data integration pipelines. It demonstrates core concepts like data ingestion, transformation, orchestration, and monitoring.

---

## 🧰 Tech Stack

* Azure Data Factory (ADF)
* Azure Data Lake Storage (ADLS)
* Azure Databricks
* SQL / PySpark

---

## 📂 Project Structure

```
├── pipelines/
│   ├── pipeline1.json
│   ├── pipeline2.json
│
├── datasets/
│   ├── source_dataset.json
│   ├── sink_dataset.json
│
├── linkedServices/
│   ├── adls_linked_service.json
│   ├── databricks_linked_service.json
│
├── triggers/
│   ├── schedule_trigger.json
│
├── notebooks/
│   ├── transformation_notebook.py
│
└── README.md
```

---

## 🚀 Key Features

* Built end-to-end data pipelines using ADF
* Implemented triggers (Schedule/Event-based)
* Integrated ADF with Azure Databricks notebooks
* Performed data transformations using PySpark
* Implemented parameterized pipelines for dynamic execution

---

## 🔄 Pipeline Workflow

1. Extract data from source (ADLS / SQL / APIs)
2. Perform transformations using Databricks notebooks
3. Load processed data into target storage
4. Trigger execution using schedule or event-based triggers
5. Monitor pipeline execution via ADF monitoring tools

---

## ⚙️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/adf-pipeline-assignments.git
   ```

2. Import pipelines into Azure Data Factory:

   * Go to ADF Studio
   * Use "Import ARM Template" or manually create pipelines using JSON

3. Configure linked services:

   * Update storage account details
   * Configure Databricks workspace and cluster

4. Trigger the pipeline:

   * Use Debug for testing
   * Use Trigger Now / Scheduled Trigger for execution

---

## 📊 Sample Use Cases

* Incremental data load using watermark
* File-based ingestion from ADLS
* Data transformation using Databricks
* Orchestration of multiple dependent pipelines

---

## 🛠️ Best Practices Followed

* Parameterization for reusability
* Modular pipeline design
* Error handling and logging
* Use of triggers for automation


---

## 👤 Author

Mourya S

---
n

Feel free to fork the repository and raise pull requests for improvements.
