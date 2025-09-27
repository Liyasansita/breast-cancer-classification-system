Breast Cancer Classification using Logistic Regression

This project demonstrates how to build a machine learning model to classify breast cancer tumors as Malignant or Benign using the Breast Cancer Wisconsin Dataset (from sklearn.datasets). The classification is performed with Logistic Regression, and the model is evaluated using accuracy metrics.


⚙️ Workflow
Load Dataset – Load the Breast Cancer dataset using Scikit-learn.
Data Exploration – Check shape, info, missing values, and descriptive statistics.
Preprocessing – Separate features (X) and target labels (Y).
Train-Test Split – Split dataset into training and testing sets.
Model Training – Train a Logistic Regression model on the training set.
Model Evaluation – Evaluate accuracy on training and testing sets.
Prediction System – Test the model with a custom input to predict whether the tumor is malignant or benign.
📊 Results
Training Accuracy: ~95% (varies slightly due to randomness in splitting).
Testing Accuracy: ~93% (varies with each run).
🛠️ Requirements

Install the following dependencies before running the code:

pip install numpy pandas scikit-learn
