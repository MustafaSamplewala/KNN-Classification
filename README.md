# KNN-Classification
## 🎯 Objective
This project is part of the AI & ML Internship Task 6, focusing on the implementation of the **K-Nearest Neighbors (KNN)** algorithm using the **Iris dataset**. The main goal is to understand instance-based learning, evaluate different values of K, and visualize decision boundaries.

## 📦 Dataset
- **Source**: UCI Machine Learning Repository
- **File**: `Iris.csv`
- The dataset contains 150 samples from 3 species of Iris flowers (`Setosa`, `Versicolor`, `Virginica`) with 4 features each:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm

## 🧰 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## 🔍 Features
1. **Normalization**: Standardized the features using `StandardScaler`.
2. **Modeling**: Applied `KNeighborsClassifier` from `scikit-learn`.
3. **Evaluation**: 
   - Tested different values of **K** (from 1 to 10).
   - Evaluated performance using **accuracy score** and **confusion matrix**.
4. **Visualization**:
   - Plotted decision boundaries for the first two features to visualize class separation.
5. **Best K**: Automatically determined the value of K with the best performance.

## 📊 Outputs
- Accuracy for each K value printed in console.
- Confusion matrix plotted for the best-performing K.
- Decision boundary visualization using a meshgrid and color-coded regions.

## 📂 Files Included
- `KNN_Classification.ipynb`: Jupyter Notebook with code and outputs.
- `Iris.csv`: Dataset used.
- `README.md`: This file.

## 🚀 How to Run
1. Make sure you have the required libraries:
```bash
pip install pandas matplotlib scikit-learn
```
2. Open and run `KNN_Classification.ipynb` using Jupyter Notebook or any Python IDE.

## 📝 Learnings
- KNN is an instance-based, non-parametric learning method.
- Feature normalization significantly improves KNN performance.
- The value of **K** impacts model complexity and accuracy.
- KNN handles multi-class classification using majority voting.
