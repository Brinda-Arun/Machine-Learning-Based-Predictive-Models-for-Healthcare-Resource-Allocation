# Machine Learning–Based Predictive Models for Healthcare Resource Allocation

Addressed healthcare resource allocation challenges by developing a supervised predictive
modelling framework to support demand forecasting, resource planning, and data driven
decision support from healthcare records.
• Built an end-to-end ML pipeline covering dataset ingestion, categorical encoding, label
encoding, feature transformation, dimensionality reduction, feature selection, model training,
hyperparameter tuning, and evaluation.
• Applied PCA based dimensionality reduction to reduce feature redundancy, handle correlated
healthcare variables, preserve high variance components, and improve computational
efficiency.
• Implemented hybrid metaheuristic feature selection using Pelican Optimization and Coati
Optimization to optimize predictor subset selection, reduce noise, and improve model
robustness.
• Compared and evaluated Random Forest, SVM, ANN, and the proposed hybrid optimization
model across ensemble learning.
• Evaluated model performance using accuracy, ROC analysis, sensitivity, specificity, F-measure,
MCC, and comparative analysis, with the proposed hybrid model achieving 98.75% accuracy.

## Overview
Efficient allocation of healthcare resources such as hospital beds, staff, and medical supplies is critical. This project uses a Random Forest classifier to build predictive models that support data-driven decision-making and improved operational efficiency.

## Approach
- Data preprocessing and feature selection
- Training predictive models using Random Forest
- Evaluation using stored performance metrics
- Analysis of results and visual outputs

## Repository Structure
- `Healthcare Resource Allocation.ipynb` – Main implementation
- `dataset/` – Input data (Excel/images)
- `Results/` – Model outputs and visualizations
- `requirements.txt` – Project dependencies

## Technologies Used
- Python
- scikit-learn
- pandas
- NumPy
- matplotlib
