# Machine-Learning-with-Python

# Mutagenicity Prediction using kNN

## Overview
This project applies a k-Nearest Neighbors (kNN) model to predict the mutagenicity of chemical compounds based on molecular descriptors. The dataset is derived from Ames test results.

## Objective
- Classify compounds as mutagenic or non-mutagenic.
- Optimize the k value using GridSearchCV.
- Evaluate using F1-score, precision, recall, and accuracy.

## Key Features
- Data preprocessing with feature scaling and selection.
- Used descriptors: TPSA, Molecular Weight, Balaban J Index, Valence Electrons.
- Optimal k = 13; best performance achieved with distance-based weighting (k=16).

## Results
- Accuracy: 72.25%
- Precision: 74.48%
- Recall: 77.23%
- F1-score: 75.83%

## Conclusion
The kNN model effectively predicts mutagenicity with good performance, especially when using distance-based weighting. Future work can explore other algorithms and advanced feature engineering.
