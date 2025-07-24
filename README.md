# ML-AtmosStarter  
🌏 ML Starter Kit for Atmospheric Applications  

## 📘 Introduction

This starter package is developed around the methodology and code from the study:

> **"Mao, J., Tai, A. P. K., Yung, D. H. Y., Yuan, T., Chau, K. T., and Feng, Z.: Multidecadal ozone trends in China and implications for human health and crop yields: a hybrid approach combining a chemical transport model and machine learning, Atmos. Chem. Phys., 24, 345–366, https://doi.org/10.5194/acp-24-345-2024, 2024"**

It is designed to assist new future learners interested in applying **machine learning (ML)** techniques to **atmospheric science problems**, especially related to air pollution prediction.

---



## 📦 Overview

A beginner-friendly package demonstrating machine learning applications in atmospheric science.  
It covers the full workflow: data preprocessing, model training, evaluation, and application — using ozone trend data as an example.


| Folder / File          | Description                                   |
|-----------------------|------------------------------------------------|
| `1_quick_start/`       | Quick example code and sample data            |
| `2_basic_tools/`       | Utility scripts and visualization tools       |
| `3_CDO_tutorial/`      | Tutorial on NetCDF processing using CDO       |
| `reference/`           | Papers, literature, and related resources     |
| `ML-AtmosStarter.pdf`  | An tutorial: ML basics and instructions       |
| `environment.yml`      | Conda environment setup file                  |
| `README.md`            | This file                                     |

---

## ⚙️ Requirements
- Python 3.8 or above
- Key Python packages: numpy, pandas, scikit-learn, xgboost, matplotlib, shap, etc. (see environment.yml for details)
- CDO (Climate Data Operators) command-line tool (see 3_CDO_tutorial/ for installation and usage)

## 🚀 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/maojia527/ML-AtmosStarter.git
cd ML-AtmosStarter
```

2. **Set up the Conda environment:**
```bash
conda env create -f environment.yml
conda activate atmos-ml
```

3. **Run the quick start notebook:**

In Jupyter Notebook or JupyterLab to walk through the full ML workflow: _**1_quick_start/model_building_workflow.ipynb**_



