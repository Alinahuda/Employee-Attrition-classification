# Employee-Attrition-classification

## Intoduction
The goal of this project is to classify if an employee wouold leave a  company or not based on the data  provided by the HR department and the feedback given by the Employees. The dataset Employee_data.csv was taken from the Kaggle.Exploratory Data Analysis was performed to get the insights about the data and find the relevant features for modelling.

## Requirements
Pre-Requirement for running this file

 1. Install Ipython Jupyter Notebook using anconda installer.
 2. Make sure you have the following libraries installed and up-to-date 
   pandas, numpy, matplotlib.pyplot, sklearn.preprocessing, sklearn.model_selection, sklearn.metrix, scipi.

Running instructions:

  1. Open Anaconda Navigater -> launch Jupiter
  2. Upload ->  upload both dataset and notebook file(Employee_datat.csv, Employee Attrition.ipynb)
  3. Now open ML_Project.ipynb -> click “cell” from top menu -> click “run all” from the drop down menu
  
  ## Training and Evaluation
 The dataset consists of 15000 rows and 10 columns. First the model was split into training and test data and training data was trained using Logistic Regression ,Linear SVM ,KNN ,Random Forest, SVC, ADA Boost Classifiers. 
 F1 score and AUC scores were used a Evaluation metric. Random Forest produced the best scores with f1 score of 0.92 and AUC score of 0.98
