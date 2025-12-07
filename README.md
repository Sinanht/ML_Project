# Intrusion Detection System with Machine Learning (CICIDS2017)

This project implements a Machine Learning–based Intrusion Detection System (IDS) using the **CICIDS2017** dataset. It was developed as part of the Machine Learning course project (2025).

## 🚀 Project Overview
The goal is to classify network traffic as **benign** or **malicious** using supervised learning.  
The CICIDS2017 dataset includes realistic attacks such as DDoS, brute force, botnet, and web exploits.

The project follows a full ML pipeline:
- Data cleaning and preprocessing  
- Feature selection and scaling  
- Baseline model evaluation  
- Hyperparameter tuning (Random Forest)  
- Model comparison and final selection  

## 📊 Methods
Models implemented:
- Logistic Regression  
- Linear SVM (Calibrated)  
- Random Forest  
- Gradient Boosting  

Best-performing model: **Tuned Random Forest**

Metrics evaluated:
- Accuracy  
- Precision (macro)  
- Recall (macro)  
- F1-score (macro)  

## 📁 Repository Structure
├── CICIDS2017_notebook.ipynb/ # Jupyter notebook with full workflow
├── ML_Project_Report.pdf/ # Final PDF report (LaTeX)
└── README.md


## 📦 Dataset
The dataset is not included due to size.  
Download here: https://www.unb.ca/cic/datasets/ids-2017.html

## ▶️ How to Run
Run the notebook in Jupyter Notebook or Google Colab and execute all cells. Depending on your hardware, this step may take a significant amount of time.

## 👥 Authors

Nguyen LE NGUYEN
Sinan HASAN TAWFIQ
Jethendiran VELU
