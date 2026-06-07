# Machine Learning–Based Predictive Models for Healthcare Resource Allocation

Developed a supervised machine learning framework to support healthcare resource allocation through demand forecasting, resource planning, and data-driven decision support using healthcare records. The project included an end-to-end ML pipeline for data ingestion, categorical and label encoding, feature transformation, PCA-based dimensionality reduction, hybrid metaheuristic feature selection using Pelican Optimization and Coati Optimization, model training, hyperparameter tuning, and evaluation. Multiple models, including Random Forest, SVM, ANN, and a proposed hybrid optimization model, were compared using accuracy, ROC analysis, sensitivity, specificity, F-measure, MCC, and comparative performance analysis. The proposed hybrid model achieved an accuracy of 98.75%, demonstrating strong predictive performance and robustness for healthcare decision-support applications.

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
