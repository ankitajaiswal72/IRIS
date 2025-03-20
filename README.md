# IRIS Flower Classification
## Overview
This project develops a machine learning model to classify Iris flowers into three species based on sepal and petal measurements. The dataset used is the classic Iris dataset, and the model is built using **Random Forest Classifier**.

## Features
- **Data Preprocessing**: Standardization of features and label encoding for species.
- **Model Training**: A RandomForestClassifier is used for classification.
- **Evaluation**: Accuracy score and classification report.
- **Feature Importance**: SHAP values provide insights into significant features.
- **Interactive Visualization**: SHAP summary plots to analyze feature impact.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas scikit-learn seaborn matplotlib shap
```

## Usage
1. Clone the repository:
```bash
git clone <repository_url>
cd iris-classification
```
2. Run the script:
```bash
python iris_classification.py
```
3. The script will output the model accuracy, classification report, and feature importance visualization.

## File Structure
- **IRIS.csv**: Dataset file.
- **iris_classification.py**: Main script for training and evaluation.
- **README.md**: Documentation.

## Results
The model achieves high accuracy, with **petal length** and **petal width** being the most significant features for classification.

## License
MIT License.

