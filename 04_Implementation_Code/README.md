# UAV MT-DNN Implementation

## Project Title
Multi-Task Deep Neural Network for Emergency Message Priority
and Semantic-Loss Tolerance Prediction in UAV Networks

## Objective
To predict emergency message priority and semantic-loss tolerance
simultaneously using a Multi-Task Deep Neural Network.

## Dataset
FANET Dataset: UAV Communication Scenarios in NS-3.40

Source: https://zenodo.org/records/19373220

Dataset used: Link_Stability_For_ML_Scenario1.csv

Dataset size: 12,339 rows and 25 columns.

## Technology
- Python
- Google Colab
- TensorFlow
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Methodology
1. Load FANET dataset.
2. Perform data preprocessing.
3. Derive project-specific classification labels.
4. Select relevant input features.
5. Split data into training and testing sets.
6. Apply feature scaling.
7. Train the Multi-Task Deep Neural Network.
8. Evaluate priority and semantic-loss predictions.
9. Compare priority classification with baseline models.

## Outputs
- Message Priority: Low / Medium / High
- Semantic-Loss Tolerance: Low / High
- Accuracy, Precision, Recall and F1-score
- Confusion Matrices
- Model Comparison Graphs

## How to Run
1. Open UAV_MT_DNN_Implementation.ipynb in Google Colab.
2. Download and extract the FANET dataset.
3. Upload the required CSV file to Colab.
4. Update the dataset path in the notebook if needed.
5. Run all cells.

## Note
The original FANET dataset does not directly contain
emergency message priority or semantic-loss tolerance labels.
These labels are derived from link lifetime and SNR as
project-specific proxies.
