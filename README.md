# Explainable Insider Threat Detection Using TinyLlama

## Project Title
Explainable Root Cause Analysis of Windows Event Log Incidents 
Using Fine-Tuned LLaMA for Insider Threat Detection

## Dataset
CERT Insider Threat Dataset r1 — Carnegie Mellon University
- logon.csv — 849,579 rows
- device.csv — 65,668 rows

## Models Used
- TinyLlama 1.1B — zero-shot classification
- XGBoost — baseline
- Random Forest — baseline
- Isolation Forest — baseline

## Explainability
- SHAP — feature importance
- LIME — local explanation

## Results
- Behavior-based labeling: 11.7% threat users
- Train/Val/Test split: 70/15/15

## How to Run
1. Open insider_threat_detection.ipynb in Google Colab
2. Upload logon.csv and device.csv
3. Run all cells in order

## Environment
- Google Colab T4 GPU
- Python 3.10
- TinyLlama 1.1B
Name:- Swati Gouda
