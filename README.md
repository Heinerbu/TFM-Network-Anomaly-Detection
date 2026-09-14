# Network Traffic Anomaly Detection Using Unsupervised Machine Learning

Master's Thesis Project

**Author:** Heiner Fernando Buitrago

## Overview

This repository contains the implementation, experiments, and evaluation conducted for a Master's Thesis focused on anomaly detection in network traffic using unsupervised machine learning techniques.

The project investigates the feasibility of identifying anomalous network behaviors through the analysis of connection flow data and the application of machine learning models capable of detecting deviations from normal traffic patterns.

## Research Objectives

- Process and transform network traffic flow data.
- Extract and prepare relevant features for machine learning.
- Train and evaluate unsupervised anomaly detection models.
- Analyze the effectiveness of different approaches for identifying anomalous network behavior.
- Provide a reproducible experimental framework for future research.

## Dataset

The experimental evaluation is based on the **IoT-23** dataset, a publicly available collection of benign and malicious IoT network traffic scenarios.

Due to dataset size considerations, the original files are not distributed through this repository.

Information about dataset acquisition is available in the `datasets` directory.

## Repository Structure

TFM-Network-Anomaly-Detection/
│
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_anomaly_detection_models.ipynb
│   └── 03_results_and_evaluation.ipynb
│
├── datasets/
│   ├── README.md
│   └── DATASET_STRUCTURE.md
│
├── docs/
│   └── README.md
│
├── requirements.txt
├── LICENSE
└── README.md

## Methodology

The proposed workflow consists of the following stages:

1. Data acquisition and preprocessing.
2. Feature selection and transformation.
3. Construction of machine learning datasets.
4. Training of anomaly detection models.
5. Performance evaluation and results analysis.
6. Interpretation of findings and discussion.

## Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Reproducibility

To reproduce the experiments:

```bash
pip install -r requirements.txt
```

Then execute the notebooks in sequential order:

1. `01_data_preparation.ipynb`
2. `02_anomaly_detection_models.ipynb`
3. `03_results_and_evaluation.ipynb`

## Research Contributions

- Design of a complete anomaly detection workflow for network traffic analysis.
- Application of unsupervised machine learning techniques to connection flow data.
- Experimental evaluation using a publicly available cybersecurity dataset.
- Reproducible implementation through Jupyter/Colab notebooks.

## License

This project is distributed under the MIT License.

## Contact

**Heiner Fernando Buitrago**

Master's Thesis Project
