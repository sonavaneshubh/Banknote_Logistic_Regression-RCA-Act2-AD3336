# Banknote Authentication Using Logistic Regression

## Project Overview
This project uses **Logistic Regression**, a machine learning algorithm, to classify banknotes as genuine or forged based on their numerical features.

It is a **Binary Classification** problem because the model predicts one of two classes:
- `0` – Genuine Banknote
- `1` – Forged Banknote

## Dataset
- **Name:** Banknote Authentication Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/267/banknote+authentication)
- **Total Records:** 1,372
- **Features:** 4
- **Target:** Class (0 or 1)

### Input Features
1. Variance
2. Skewness
3. Curtosis
4. Entropy

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Workflow
1. Load and understand the dataset.
2. Check missing values and duplicate records.
3. Visualize the class distribution.
4. Split the dataset into training and testing sets (80:20).
5. Apply feature scaling using StandardScaler.
6. Train the Logistic Regression model.
7. Predict banknote classes and probabilities.
8. Evaluate the model using classification metrics.
9. Compare different decision thresholds.
10. Plot the ROC curve.

## Evaluation Metrics
- Confusion Matrix
- Accuracy
- Precision
- Recall
- Specificity
- F1-Score
- ROC-AUC Score
- Classification Report

## How to Run
1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the `.ipynb` file.
4. Run all cells in order.

## Objective
The main objective is to understand how Logistic Regression performs binary classification and how different evaluation metrics and decision thresholds affect model predictions.

## Conclusion
This project demonstrates how Logistic Regression can be used to distinguish genuine and forged banknotes using four numerical features. It also provides practical understanding of probability prediction, classification thresholds, and model evaluation.

## Author
**Sandesh Kondikire**  
B.Tech – Artificial Intelligence and Data Science
**
