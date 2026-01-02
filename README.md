# Property Address Classifier

A machine learning project to classify and standardize property addresses from raw address data. This repository includes data, model training notebook, best model weights, evaluation results, and documentation on the approach.

## Repository Structure

```
property-address-classifier/
├── best_model/                 # Trained model artifacts
├── results/                    # Evaluation summaries & plots
├── property_classifier.ipynb   # Main notebook for data cleaning, training & evaluation
├── task_dataset.xlsx           # Address dataset used for training/testing
├── approach.txt                # High-level approach and methodology
└── README.md 
```

## Project Overview

Address data often contains variations, typos, and inconsistent formatting. This project builds a classifier to:

- **Clean and preprocess raw addresses**
- **Train a machine learning model to classify address components**
- **Evaluate model performance**
- **Export the best model for future predictions**

## Tech Stack

- Python (Jupyter Notebook)
- Scikit-Learn / TensorFlow / PyTorch *(update based on actual implementation)*
- Pandas & NumPy for data processing
- Excel dataset (`task_dataset.xlsx`)

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/MeghnaP0705/property-address-classifier.git
cd property-address-classifier
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the main notebook

```bash
jupyter notebook property_classifier.ipynb
```
Run through the cells for:

- data loading

- preprocessing

- training

- evaluation

## Results

Evaluation results and visualizations are available in the results/ folder. They show metrics such as:

- Accuracy

- Confusion matrix

- Classification reports

## Model Artifacts

The best trained model files are stored in best_model/. You can load and use these artifacts for inference on new address data.


