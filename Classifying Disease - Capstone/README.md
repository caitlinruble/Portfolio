# Patient Diagnosis with Machine Learning

Data containing patients' symptoms and associated diagnosis were used to build supervised machine learning models to predict diagnosis in future patients. 
The top performing models were Random Forest, XGBoost, SVC with RBF kernel, Gradient Boosting which all performed equally by yeilding 100% accuracy, F1 score, precision and recall on the held-out testing data.

Ultimate model selection was based on balancing the time to train each model with the time it took each to predict an individual patient's diagnosis.
By this criteria the Random Forest model proved to be the most commputationally and temporally efficient. The model metrics file can be found (here)


The data can be found at: ["Disease Prediction Using Machine Learning"](https://user-images.githubusercontent.com/96548036/178046872-f5a4753a-3b53-4bb0-8f38-b773f5a6812d.png) on Kaggle. 
 
Some topics covered in this end-to-end project are:

 - Problem Framing and Definition of Success
 - Data Cleaning and Wrangling
 - EDA and Predictive Power Score
 - Data Preprosseing with Label Encoding
 - Building Classification Models Using Supervised Machine Learning Methods in SKLearn (Entropy-Based Decision Tree, Gini-Impurity-Based Decision Tree, AdaBoost, Gradient Boost, XGBoost, and SVC with RBF Kernel)
 - Model Evaluation through Analysis of Feature Importances and Training/Prediction Time

A report and slide deck summarizing the process and findings can be found in the respective folders. Please feel free to reach out with any additional questions, ideas for extensions, constructive criticism, and collabortion discussions at caitlinoruble@gmail.com.
