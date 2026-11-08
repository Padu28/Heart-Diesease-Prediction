Heart Disease Prediction

A machine learning project that predicts the likelihood of heart disease from patient health and clinical data. Built in Python with Pandas and Scikit-learn, covering data preprocessing, exploratory visualization, feature selection, model training and evaluation.

Overview

Heart disease is one of the leading causes of death worldwide, and early risk screening can help prioritise patients for further tests. This project trains classification models on patient attributes (such as age, sex, blood pressure, cholesterol and ECG results) to predict whether a patient is likely to have heart disease.

Dataset
Source: [Dataset name and link, e.g. UCI / Kaggle Heart Disease dataset]
Size: [number of rows] patients, [number of features] features
Target: [name of target column], where 1 = heart disease present and 0 = absent
Approach
Data cleaning and preprocessing: checked for missing values and duplicates, handled outliers, encoded categorical variables and scaled numeric features.
Exploratory data analysis: visualised feature distributions, class balance and correlations between features and the target.
Feature selection: kept the features most relevant to the target, based on [correlation / feature importance / other method you used].
Model training: split the data into train and test sets and trained the following models:
[Logistic Regression]
[Random Forest]
[Other models you tried, e.g. KNN, SVM, Decision Tree]
Evaluation: compared models on accuracy, precision, recall, F1-score and the confusion matrix.
Results
Model	Accuracy	Precision	Recall	F1-score
[Model 1]	[xx%]	[xx%]	[xx%]	[xx%]
[Model 2]	[xx%]	[xx%]	[xx%]	[xx%]

Best model: [model name], with [xx%] accuracy on the test set.

Key takeaway: [one line, e.g. which features mattered most, or which metric you prioritised for a medical screening use case and why].

Tech Stack
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Jupyter Notebook / Google Colab
How to Run
Clone the repository:
bash
   git clone https://github.com/Padu28/Heart-Disease-Prediction.git
   cd Heart-Disease-Prediction
Install the dependencies:
bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
Open Heart_Disease_Prediction.ipynb in Jupyter Notebook, or upload it to Google Colab, and run all cells.
How I Built This
AI tools used: [e.g. ChatGPT / Claude / Copilot], used for [e.g. debugging errors, suggesting preprocessing steps, explaining evaluation metrics].
What the AI got wrong: [One real example, e.g. it suggested scaling before the train/test split, which leaks test data into training. I caught this by checking the pipeline order and fixed it by fitting the scaler on the training set only.]
How I checked the output: [e.g. compared results against the raw data and re-ran metrics manually].
Limitations and Future Work
The dataset is small, so results may not generalise to other populations.
This is a learning project and is not a medical diagnostic tool.
Possible next steps: hyperparameter tuning, cross-validation, and deploying the model as a simple web app.
Author

Padmashree Shah, B.Tech Computer Science and Engineering LinkedIn | GitHub

License

This project is licensed under the MIT License. See the LICENSE file for details.
