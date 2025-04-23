# Drug Repurposing to Identify Potential FDA-Approved Drugs Targeting Three Main Angiogenesis Receptors Through a Deep Learning Framework

This repository contains the source code, datasets, and trained models used for identifying multi-target angiogenesis inhibitors through a deep learning-based. The study focuses on compounds that simultaneously inhibit VEGFR2, FGFR2, and EGFR — key targets in tumor angiogenesis and cancer treatment.

## 🧪 Project Objectives

- Predict potential inhibitors for VEGFR2, FGFR2, and EGFR.
- Develop deep learning classification models for each target.
- Combine models into an ensemble predictor to identify multi-target inhibitors.
- Facilitate reproducibility by sharing data and code.

## 📁 Repository Structure
Multi-target-Angiogenesis-Inhibitors
│ ├── Database
  │ └── Classification
  │ ├── VEGFR2.csv
  │ ├── FGFR2.csv 
  │ └── EGFR.csv 
│ ├── Deep_Model
  │ ├── VEGFR2_model.h5 
  │ ├── FGFR2_model.h5 
  │ └── EGFR_model.h5 
│ ├── Prediction.ipynb # Notebook for prediction on new compounds 
├── requirements.txt # Python dependencies 
└── README.md


## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt

Main dependencies include:

Python 3.8+

TensorFlow / Keras

Pandas, NumPy, Scikit-learn

RDKit (for chemical descriptors)

git lfs install
git clone https://github.com/Ghasemi-SmartDrug/Multi-target-Angiogenesis-Inhibitors.git

Open Prediction.ipynb to predict potential new compounds.
