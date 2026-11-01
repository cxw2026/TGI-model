# TGI-model# TGI-model

### A Radiomics-Based Prediction Model for Thyroid Gland Invasion in Laryngeal and Hypopharyngeal Cancer

## Overview

**TGI-model** is a radiomics-based machine learning framework designed to investigate and predict thyroid gland invasion (TGI) in patients with laryngeal and hypopharyngeal cancer.

The project focuses on extracting and analyzing intratumoral and peritumoral radiomic features from medical imaging data, followed by feature selection and machine learning model development.

The ultimate goal is to develop a reproducible computational framework to assist in the preoperative assessment of thyroid gland invasion.

## Workflow

The current project includes two major radiomics pipelines:

1. **Intratumoral Radiomics (INTRA)**
   - Extraction of radiomic features from the intratumoral region.
   - Feature normalization and statistical analysis.
   - Feature correlation analysis and selection.
   - LASSO-based feature selection.
   - Machine learning model development and evaluation.

2. **Peritumoral Radiomics (PERI)**
   - Extraction of radiomic features from the peritumoral region.
   - Feature normalization and statistical analysis.
   - Feature correlation analysis and selection.
   - LASSO-based feature selection.
   - Machine learning model development and evaluation.

## Model Development

The current implementation includes the following procedures:

- Radiomic feature extraction using PyRadiomics through the Onekey framework.
- Z-score normalization.
- Statistical feature analysis.
- Pearson correlation-based feature reduction.
- LASSO-based feature selection.
- Machine learning classification using:
  - Logistic Regression
  - Support Vector Machine
  - Random Forest
  - Extra Trees
  - XGBoost
- Model performance evaluation using ROC curves, AUC, accuracy, confusion matrices, and decision curve analysis (DCA).

## Requirements

The project is implemented in Python and Jupyter Notebook.

The main dependencies include:

- Python
- NumPy
- Pandas
- Scikit-learn
- PyRadiomics
- Matplotlib
- Seaborn
- XGBoost
- Onekey

The exact software versions and installation instructions will be provided after environment validation.

## Usage

1. Prepare the medical imaging data and corresponding segmentation masks.
2. Organize the images and masks according to the required directory structure.
3. Prepare the clinical labels in CSV format.
4. Run the intratumoral radiomics pipeline.
5. Run the peritumoral radiomics pipeline.
6. Perform feature selection and model development.
7. Evaluate model performance.

Please refer to the individual Jupyter notebooks for detailed implementation.

## Data Availability

Patient-level medical imaging data and clinical information are not included in this repository due to patient privacy and data protection considerations.

Researchers should prepare their own appropriately de-identified datasets and ensure compliance with applicable ethical and institutional requirements.

## Disclaimer

This project is intended for scientific research and methodological investigation only. It is not intended to replace clinical judgment or serve as a standalone clinical diagnostic tool.

## Citation

If you use this code in your research, please cite the corresponding publication when available.

## Contact

For questions regarding the code or research collaboration, please open a GitHub Issue.
