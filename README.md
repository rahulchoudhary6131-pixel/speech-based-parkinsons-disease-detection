# Speech-Based Parkinson's Disease Detection using LPC Coefficients and Residual Energy

## Overview
This project presents a machine learning approach for the early detection of Parkinson's disease using speech signal analysis. The system extracts Linear Predictive Coding (LPC) coefficients and residual energy features from speech recordings and uses them to classify subjects as Healthy or Parkinson's Disease (PD).

## Objectives
- Detect Parkinson's disease from speech signals.
- Extract LPC coefficients from speech recordings.
- Compute residual energy features.
- Train and evaluate a machine learning classifier.
- Analyze the effectiveness of speech-based biomarkers.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- SciPy
- Pandas
- Matplotlib
- Scikit-learn

## Project Structure

```
speech-based-parkinsons-disease-detection/
│
├── speechprocessing1.ipynb      # Main implementation
├── Demographics_age_sex.xlsx    # Dataset information
├── Report (3).pdf               # Project report
├── .gitignore
└── README.md
```

## Methodology

1. Speech Signal Acquisition
2. Speech Preprocessing
3. LPC Feature Extraction
4. Residual Energy Computation
5. Feature Vector Formation
6. Machine Learning Classification
7. Performance Evaluation

## Features Used
- LPC Coefficients
- Residual Energy
- Speech Signal Features

## Workflow

```
Speech Signal
      │
      ▼
Preprocessing
      │
      ▼
LPC Coefficient Extraction
      │
      ▼
Residual Energy Calculation
      │
      ▼
Feature Vector
      │
      ▼
Machine Learning Model
      │
      ▼
Healthy / Parkinson's Disease
```

## Dataset
The project uses speech recordings along with demographic information (Age and Gender) for Parkinson's disease detection.


## Results
The proposed approach uses LPC coefficients and residual energy extracted from speech signals for Parkinson's disease classification. Performance is evaluated using standard machine learning metrics such as Accuracy, Precision, Recall, and F1-score.

## Author

Rahul Choudhary

B.Tech, Electronics and Communication Engineering

Sardar Vallabhbhai National Institute of Technology (SVNIT), Surat

## License

This project is intended for educational and research purposes.
