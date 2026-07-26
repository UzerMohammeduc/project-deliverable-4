# project-deliverable-4
# Breast Cancer Prediction Using Machine Learning
 
## Overview
 
This project applies data mining and machine learning techniques to the Wisconsin Breast Cancer Diagnostic Dataset to classify breast tumors as **malignant** or **benign**. The analysis includes data preprocessing, exploratory data analysis (EDA), feature engineering, classification, clustering, association rule mining, and model evaluation. The project demonstrates how machine learning can support healthcare decision-making by improving diagnostic accuracy.
 
## Dataset
 
- **Dataset:** Wisconsin Breast Cancer Diagnostic Dataset
- **File:** `wisconsin_breast_cancer_raw (1).csv`
- **Records:** 569
- **Features:** 32
- **Target Variable:** `diagnosis` (Malignant or Benign)
 
## Project Objectives
 
- Load and preprocess the dataset.
- Perform exploratory data analysis.
- Standardize numerical features.
- Train multiple machine learning classification models.
- Compare model performance.
- Perform K-Means clustering.
- Generate association rules using the Apriori algorithm.
- Visualize results and identify the best-performing model.
 
## Machine Learning Models
 
The following classification algorithms are implemented:
 
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Naïve Bayes
 
## Clustering
 
- K-Means Clustering
- Elbow Method
- Silhouette Score
 
## Association Rule Mining
 
- Apriori Algorithm
- Association Rules (Support, Confidence, and Lift)
 
## Libraries Used
 
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- mlxtend
 
## Installation
 
Install the required libraries before running the project:
 
```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend
```
 
## How to Run
 
1. Place the dataset file `wisconsin_breast_cancer_raw (1).csv` in the project directory.
2. Open the notebook or Python script in Google Colab, Jupyter Notebook, or VS Code.
3. Run all cells sequentially.
4. Review the generated tables, evaluation metrics, and visualizations.
 
## Project Workflow
 
1. Import required libraries.
2. Load the dataset.
3. Explore the dataset.
4. Preprocess the data.
5. Perform exploratory data analysis.
6. Train classification models.
7. Evaluate model performance.
8. Perform feature importance analysis.
9. Apply K-Means clustering.
10. Generate association rules.
11. Compare models and identify the best-performing classifier.
 
## Output
 
The project generates:
 
- Dataset summary
- Missing value analysis
- Correlation heatmap
- Histograms
- Boxplots
- Classification reports
- Confusion matrix
- ROC curve
- Feature importance plot
- Elbow method graph
- Model accuracy comparison
- Association rules
- Best-performing model
 
