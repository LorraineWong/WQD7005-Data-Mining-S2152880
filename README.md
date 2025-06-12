# 📊 WQD7005 – Data Mining | AI-Assisted Patient Monitoring and Coursework Repository

**Author:** Lorraine Wong (S2152880)  
**Course:** WQD7005 – Data Mining (Semester 2, 2024/2025)  
**University:** University of Malaya

---

## 📌 Project Overview

This repository contains coursework and project submissions for the WQD7005 Data Mining module at University of Malaya.  
It includes two main components:

- **Assignment**: AI-assisted patient monitoring project featuring GenAI simulation, EDA, preprocessing, and LLM-based insights.  
- **Final Project**: Predictive modeling project involving feature engineering, supervised learning models, Transformer-based models, and comprehensive evaluation.

The repository integrates the use of Generative AI (GenAI), Large Language Models (LLMs), and Small Language Models (SLMs) to enhance data simulation, preprocessing, and analysis workflows.

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

### 🤖 AI-Generated Insights and Modeling
- Automated summarization of daily clinical records  
- Semantic labeling without manual annotation  
- Final cleaned and labeled dataset exported for predictive modeling  
- Supervised learning models: Random Forest, XGBoost, MLP Neural Network  
- Transformer-based models: BERT-base, BioBERT, DeBERTa  
- Model interpretability using LLM-assisted summarization of results

---

## 🔍 Key Files

| File | Description |
|------|-------------|
| `Preprocess/generate_patient_dataset.csv` | Raw GenAI-generated dataset (6501 entries) |
| `Preprocess/preprocessing_generate_patient_dataset.csv` | Cleaned and structured dataset with note_status labels |
| `Preprocess/patient_summary.csv` | LLMs-generated patient-level summaries |
| `Notebook/Assignment_patient_data_simulation_clear_output.ipynb` | Assignment notebook (simulation → preprocessing → EDA → LLM analysis) |
| `Notebook/Project_health_deterioration_model_clear_output.ipynb` | Final project notebook (feature engineering → model training → evaluation → AI-assisted interpretation) |
| `Report/AI-Assisted Summary Report and Visualization.pdf` | Assignment final report (with figures and findings) |
| `Report/Comprehensive AI-Assisted Final Report.pdf` | Final project report (with modeling, analysis, and LLM-assisted interpretation) |

---

## 📚 Course Assignments and Project

### 📝 Assignment (Week 7)
- Perform dataset simulation using GenAI  
- Conduct exploratory data analysis (EDA) enhanced by LLMs  
- Apply intelligent preprocessing techniques using SLMs/LLMs  
- Draft a short AI-assisted summary report (2–3 pages)

> 📎 Notebook: `Notebook/Assignment_patient_data_simulation_clear_output.ipynb`  
> 📎 Colab link: [👉 Open in Colab](https://colab.research.google.com/drive/1AlG6-XxHVNyOP6qH56rwvGLGuAfcNkl-?usp=sharing)  
> 📎 Report: `Report/Comprehensive AI-Assisted Final Report.pdf`

---

### 🚀 Final Project (Week 13)
- Feature engineering via GenAI/LLMs for healthcare datasets  
- Build predictive models: Random Forest, XGBoost, Neural Networks, Transformers  
- Integrate textual feature extraction and model interpretation using SLMs/LLMs  
- Deliver a comprehensive final report (5–7 pages) with performance evaluation  
- Provide full code and reproducible results

> 📎 Notebook: `Notebook/Project_health_deterioration_model_clear_output.ipynb`  
> 📎 Colab link: [👉 Open in Colab](https://colab.research.google.com/drive/1Ljp7JaFCAvhpyPQkolrWn2ZkvWI_9OeA?usp=sharing)  
> 📎 Report: `Report/Comprehensive AI-Assisted Final Report.pdf`

---

## 📬 Contact

**Lorraine Wong**  
📧 Email: yiting.wong0630@gmail.com  
🔗 GitHub: [@LorraineWong](https://github.com/LorraineWong)

---

