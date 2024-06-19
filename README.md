# Symptom-Based-Disease-Detection 

## Overview
This project focuses on detecting diseases based on symptoms using NLP and machine learning techniques. The goal is to train a Support Vector Classifier (SVC) model to accurately classify diseases based on the provided symptoms.

## Data
The project uses a CSV file containing symptoms as text and diseases as labels. The dataset is structured to provide a mapping between symptoms and diseases.

## Folder Structure
```
Symptom-Based-Disease-Detection/
│
├── datasets/
│ ├── Symptom2Disease.csv
│ └── lookup.csv
│
├── model/
│ ├── Disease_detection.ipynb
│ ├── model.pkl
│ └── scaler.pkl
│
├── LICENSE
└── README.md
```

## Usage
- **Data Preparation**: Ensure the `Symptom2Disease.csv` file is in the correct format and preprocess it for model training.
- **Vector Embedding**: Convert the symptoms text data into numerical vectors.
- **Model Training**: Use the provided Jupyter notebook (`Disease_detection.ipynb`) to train the SVC model on the embedded data.
- **Evaluation**: Evaluate the model's performance on the test data using metrics such as accuracy, precision, recall, and F1-score.
- **Model Saving**: Save the trained model (`model.pkl`) and the scaler (`scaler.pkl`) using pickle for future use.

## Results
The project aims to achieve high accuracy in predicting diseases based on symptoms. The model's performance will be evaluated and documented to ensure its effectiveness.

## Contributor
Unnati Agarwal
