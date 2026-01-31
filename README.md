
---

# 🔗 Data Integration & Business Intelligence Analysis

**Technical Evaluation Hackathon – Innomatics Research Lab**

---

## 📌 Project Overview

This repository contains my solution to the **Technical Evaluation Hackathon** conducted by **Innomatics Research Lab** as part of their internship selection process.

The challenge focused on a **real-world data engineering + analytics problem**:

> **Integrate multiple heterogeneous datasets into a single source of truth and extract business-ready insights from it.**

The complete workflow—from raw data ingestion to business intelligence analysis—was implemented using **Python and Jupyter Notebook**, following clean, reproducible data science practices.

---

## 🎯 Problem Statement

The task involved:

* Working with **three different datasets**, each in a **different file format**
* Cleaning, transforming, and **integrating them into one unified dataset**
* Treating the integrated data as a **Single Source of Truth (SSOT)**
* Performing analysis to **answer business intelligence questions**
* Demonstrating **clarity of thought, correctness of logic, and analytical maturity**


---

## 🧠 Solution Approach (High Level)

I approached the problem in **five deliberate stages**:

1. **Data Understanding & Ingestion**
2. **Data Cleaning & Quality Handling**
3. **Schema Alignment & Transformation**
4. **Dataset Integration (SSOT creation)**
5. **Business Intelligence Analysis & Insights**

Each step is documented and implemented inside the Jupyter Notebook.

---

## 🗂️ Repository Structure

```
├── data/
│   ├── raw/            # Original datasets (multiple formats)
│   ├── processed/      # Cleaned and transformed intermediate data
│   └── integrated/     # Final unified dataset (single source of truth)
│
├── notebooks/
│   └── analysis.ipynb  # End-to-end data integration & BI analysis
│
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
```


---

## 🛠️ Tech Stack

* **Python 3.x**
* **Pandas** – data manipulation, joins, transformations
* **NumPy** – numerical operations
* **Matplotlib / Seaborn** – visual analytics
* **Jupyter Notebook** – interactive development and explanation

---

## 📊 Datasets Description

The project integrates **three independent datasets**, each with different schemas and formats:

* Dataset formats include combinations of **CSV / SQL/ JSON**
* Each dataset represents a **partial view of the business**
* Common identifiers were identified and standardized to enable joins



---

## 🔄 Data Integration Workflow

### 1️⃣ Data Loading

* Loaded datasets using format-specific Pandas readers
* Performed schema inspection and sanity checks

### 2️⃣ Data Cleaning

* Removed duplicates
* Standardized:

  * Date formats
  * Categorical values
  * Numerical columns

### 3️⃣ Data Transformation

* Renamed columns for semantic consistency
* Created derived features where required
* Ensured uniform data types across datasets

### 4️⃣ Dataset Integration

* Identified reliable join keys
* Performed controlled merge operations
* Verified row counts and referential integrity
* Produced a **single consolidated dataset (SSOT)**

### 5️⃣ Validation

* Checked for data loss after joins
* Re-validated business logic assumptions
* Ensured analytical readiness of final data

---

## 📈 Business Intelligence Analysis

Using the unified dataset, I answered **business-oriented analytical questions**, focusing on:

* Trend identification
* Comparative performance analysis
* Distribution and segmentation insights
* Relationship and correlation analysis

All analysis is backed by **visual evidence**, not assumptions.

---

## 💡 Key Insights (Examples)

* Identified patterns that were **not visible in isolated datasets**
* Demonstrated how integration improves **decision-making accuracy**
* Highlighted data quality issues that could impact business metrics
* Converted raw data into **actionable intelligence**


## 📊 Visual Analytics

The notebook includes:

* Bar charts for comparisons
* Line plots for trends
* Heatmaps for correlations
* Distribution plots for understanding spread and skew

Each visualization directly supports a business question.



## 🚀 How to Run This Project

### Prerequisites

* Python 3.x
* Jupyter Notebook / JupyterLab

### Setup Instructions

```bash
# Clone the repository
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

Open `notebooks/analysis.ipynb` and run cells sequentially.

---

## 📚 Key Learnings & Skills Demonstrated

This project demonstrates my ability to:

* Integrate heterogeneous datasets into a unified model
* Handle real-world data quality challenges
* Design a clean, reproducible data workflow
* Think analytically from a **business intelligence perspective**
* Communicate insights through clear visualizations
* Write structured, readable, evaluation-ready code

---


## 👤 Author

**Mrittika Srinivasan**

* GitHub: [https://github.com/your-username](https://github.com/your-username)
* LinkedIn: [https://linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)


---

## 📄 License

This project was developed **solely for educational and evaluation purposes** as part of the Innomatics Research Lab .

---


