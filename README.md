# Multi-Class CT-Based Stroke Diagnosis

Deep learning research workflow for multi-class brain stroke diagnosis from CT imaging data. The project explores medical-image preprocessing, model training, and evaluation for stroke-classification support.

## Project Overview

Stroke diagnosis from brain CT images is a high-impact medical-imaging task. This repository contains a notebook-based workflow for classifying CT scans into multiple stroke-related classes using deep learning methods.

## Key Work

- Prepared CT imaging data for multi-class classification experiments.
- Built a deep learning pipeline for stroke-diagnosis research.
- Applied image preprocessing and model-evaluation workflows.
- Produced notebook-based experiments suitable for academic reporting.
- Supported research documentation for medical AI analysis.

## Repository Contents

```text
Multi-Class-CT-Based-Stroke-Diagnosis.ipynb   Main training and evaluation notebook
```

## Technical Focus

- Medical image classification
- Brain CT analysis
- Deep learning
- Multi-class model evaluation
- Research notebook reproducibility

## Suggested Environment

```bash
python -m venv .venv
.venv\Scripts\activate
pip install numpy pandas matplotlib scikit-learn opencv-python tensorflow keras
```

Update dataset paths inside the notebook before running the workflow.

## Future Improvements

- Move reusable preprocessing and model utilities into a `src/` package.
- Add train/validation/test split documentation.
- Add confusion matrix, per-class precision/recall, and ROC/AUC summaries to the README.
- Add sample non-sensitive output figures.

## Clinical Disclaimer

This project is for research and educational purposes only. It is not intended for clinical use and does not replace radiologist or physician judgment.
