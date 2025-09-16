# breast_cancer-
This Jupyter Notebook outlines a machine learning project for classifying breast cancer tumors as either malignant or benign. It uses the well-known Wisconsin Breast Cancer dataset, which is included in the scikit-learn library.

Here is a summary of the steps taken in the notebook:

**1. Data Loading and Preparation**
The project begins by importing essential libraries for data analysis and visualization, including pandas, NumPy, and scikit-learn.
The breast cancer dataset is loaded and converted into a pandas DataFrame. This DataFrame includes 30 different features (like mean radius, mean texture, etc.) and a target column, which indicates whether a tumor is malignant (0) or benign (1).

**2. Data Splitting**
The dataset is split into two parts:
Training data: Used to teach the machine learning model the patterns in the data.
Testing data: Used to evaluate how well the model performs on new, unseen data.

**3. Model Training**
A Logistic Regression model is chosen for this classification task. This is a common and effective algorithm for binary classification problems.
The model is trained on the training dataset, where it learns the relationships between the tumor features and the diagnosis.

**4. Model Evaluation**
After training, the model's performance is evaluated using the test data.
The notebook calculates the accuracy of the model, which measures the percentage of correct predictions.
A confusion matrix is also generated to provide a more detailed look at the model's performance, showing the number of true positives, true negatives, false positives, and false negatives. This helps to understand where the model is making mistakes.
