# 📊 WQD7005 – Data Mining 

**Author:** Lorraine Wong (S2152880)  
**Course:** WQD7005 – Data Mining (Semester 2, 2024/2025)  
**University:** University of Malaya

---

## 📌 Project Overview

This repository presents an AI-assisted simulation, preprocessing, and analysis pipeline for synthetic inpatient monitoring data.  
The project leverages Generative AI (GenAI), Large Language Models (LLMs), and Small Language Models (SLMs) to generate clinically realistic data and automate insight extraction.

Key tasks include:
- Simulation of variable-length monitoring data using GPT-4o prompts  
- Exploratory data analysis (EDA) enhanced by LLM-generated summaries  
- Intelligent data preprocessing with SLMs/LLMs  
- Clinical note classification and trend summarization  
- Visualizations and reporting for insight communication  

---

## 🗂️ Repository Structure

├── Data
├── ├──data_output_P0001.txt ... P0500.txt
│── Documents
│   ├── WQD7005-Ass_v1.docx
│   │── WQD7005-Project_v1.docx
│── Notebook
│   ├── Assignment_patient_data_simulation.ipynb
│   └── Lab_Practice.ipynb
│── Preprocess
│   ├── generate_patient_dataset.csv
│   ├── preprocessing_generate_patient_dataset.csv
│   └── patient_summary.csv
│── Visualization
│   └── eda_patient_report.html
├── README.md

---

## 🧪 Key Features

### ✅ Synthetic Dataset Generation
- Simulates 500 patients with individualized monitoring durations (10–30 days)  
- Daily records include 6 vital signs and 1 clinical note  
- Built-in missingness introduced via prompt configuration  

### 📊 Exploratory Data Analysis (EDA)
- Statistical summaries and missing value profiling using `ydata-profiling`  
- Histograms of hospitalization durations, vital sign distributions  
- Time-series visualizations with clinical reference zones  
- LLM-generated trend summaries for each patient  

### ⚙️ Preprocessing Pipeline
- Blood pressure decomposition into systolic/diastolic columns  
- Median-based missing value imputation per patient  
- Z-score normalization for selected features  
- Zero-shot classification of clinical notes (Stable, Recovering, Deteriorating, Critical)

### 🤖 AI-Generated Insights
- Automated summarization of daily clinical records  
- Semantic labeling without manual annotation  
- Final cleaned and labeled dataset exported for further modeling

---

## 📈 Sample Visualizations

> *(Full interactive report available: `Visualization/eda_patient_report.html`)*

- **Monitoring Duration Histogram**
- **Time-Series Trends of Vital Signs**
- **Clinical Note Status Label Distribution**

---

## 🔍 Key Files

| File | Description |
|------|-------------|
| `generate_patient_dataset.csv` | Raw GenAI-generated dataset (6501 entries) |
| `preprocessing_generate_patient_dataset.csv` | Cleaned and structured dataset with note_status labels |
| `patient_summary.csv` | LLMs-generated patient-level summaries |
| `Assignment_patient_data_simulation.ipynb` | End-to-end notebook (simulation → preprocessing → EDA → LLM analysis) |
| `eda_patient_report.html` | Auto-generated EDA profiling report |
| `data_output_Pxxxx.txt` | Raw simulation outputs for each patient (unparsed) |

---

## 📚 Course Assignments and Project

### 📝 Assignment (Due: Week 7)
- Perform dataset simulation using GenAI.  
- Conduct exploratory data analysis (EDA) enhanced by LLMs.  
- Apply intelligent preprocessing techniques using SLMs/LLMs.  
- Draft a short AI-assisted summary report (2–3 pages).

> 📎 Document: `Documents/WQD7005-Ass_v1.pdf`  
> 📎 Notebook: `Notebook/Assignment_patient_data_simulation.ipynb`

---

### 🚀 Final Project (Due: Week 13) (TBC)
- Feature engineering via GenAI/LLMs for healthcare datasets.  
- Build predictive models: Random Forest, XGBoost, Neural Networks, Transformers.  
- Integrate textual feature extraction and model interpretation using SLMs/LLMs.  
- Deliver a comprehensive final report (5–7 pages) with performance evaluation.

> 📎 Document: `Documents/WQD7005-Project_v1.pdf`

---

### 🧪 Lab Practice
- Supplementary exercises focused on EDA, preprocessing, model experimentation.  
- Practice notebooks are not graded but highly recommended for project development.

> 📎 Notebook: `Notebook/Lab_Practice.ipynb`

---

## 📄 Summary Report Access

- Assignment AI-Assisted Summary Report located in `Documents/AI-Assisted Summary Report and Visualization.pdf`

---

## 📎 Notes

- GenAI simulation performed via Azure OpenAI (GPT-4o).  
- Clinical note classification using Hugging Face `facebook/bart-large-mnli`.  
- All steps aligned with WQD7005 assignment and project requirements.

---

## 📬 Contact

**Lorraine Wong**  
📧 Email: yiting.wong0630@gmail.com
🔗 GitHub: [@LorraineWong](https://github.com/LorraineWong)

---
