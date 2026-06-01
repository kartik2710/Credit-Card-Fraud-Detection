# Credit Card Fraud Detection using Machine Learning

## Problem Statement

Credit card fraud is a significant challenge in the financial industry, resulting in substantial monetary losses and security concerns. The objective of this project is to build a machine learning model capable of accurately identifying fraudulent transactions while minimizing false positives. Due to the highly imbalanced nature of fraud datasets, special attention is given to handling class imbalance and selecting appropriate evaluation metrics.

---

## Data Collection

The dataset used in this project contains anonymized credit card transaction records, including both legitimate and fraudulent transactions. Each transaction is represented by multiple numerical features along with a target variable indicating whether the transaction is fraudulent (1) or legitimate (0).

### Dataset Features

* Transaction-related numerical attributes
* Anonymized features for privacy protection
* Target variable: Fraudulent or Non-Fraudulent transaction

---

## Data Analysis & Visualization

Exploratory Data Analysis (EDA) was performed to gain insights into the dataset and understand transaction patterns.

### Key Activities

* Examined dataset structure and feature distributions
* Analyzed class distribution to identify imbalance
* Visualized feature correlations
* Detected potential outliers and anomalies
* Generated histograms, box plots, and correlation heatmaps

### Observations

* The dataset is highly imbalanced with significantly fewer fraudulent transactions.
* Most features are already transformed and standardized.
* Certain features exhibit distinct patterns between fraudulent and non-fraudulent transactions.

---

## Data Preprocessing

Several preprocessing techniques were applied to prepare the data for machine learning models.

### Steps Performed

* Checked and handled missing values
* Feature scaling and normalization where required
* Train-test data splitting
* Addressed class imbalance using class weighting strategies
* Ensured consistent preprocessing across training and testing datasets

---

## Model Training

Multiple classification algorithms were trained and evaluated to identify the most effective model for fraud detection.

### Models Implemented

* Decision Tree Classifier
* Random Forest Classifier
* HistGradientBoosting Classifier

Cross-validation was used to assess model stability and generalization performance.

---

## Model Selection and Optimization

To identify the best-performing model, stratified k-fold cross-validation was employed.

### Optimization Techniques

* Stratified K-Fold Cross Validation
* Class-weight balancing
* Performance comparison across multiple models
* Evaluation using Precision-Recall metrics

The model demonstrating the highest and most consistent performance across validation folds was selected as the final model.

---

## Evaluation Results

Since fraud detection datasets are highly imbalanced, traditional accuracy metrics can be misleading. Therefore, model evaluation focused on metrics better suited for imbalanced classification.

### Evaluation Metrics

* Precision
* Recall
* F1-Score
* Precision-Recall AUC (PR-AUC)
* Confusion Matrix

### Results

* Successfully identified fraudulent transactions with strong recall performance.
* Class balancing techniques improved fraud detection capability.
* Ensemble-based models achieved superior performance compared to baseline approaches.
* Precision-Recall AUC provided a reliable measure of model effectiveness on the imbalanced dataset.

---

## Conclusion

This project demonstrates the application of machine learning techniques for detecting fraudulent credit card transactions. Through data preprocessing, exploratory analysis, class imbalance handling, and rigorous model evaluation, an effective fraud detection system was developed. The resulting model can assist financial institutions in reducing fraudulent activities and improving transaction security.
