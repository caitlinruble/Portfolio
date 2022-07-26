# Patient Diagnosis with Machine Learning

Data containing patients' symptoms and associated diagnosis were used to build supervised machine learning models to predict diagnosis in future patients. 
The top performing models were Random Forest, XGBoost, SVC with RBF kernel, Gradient Boosting which all performed equally by yielding 100% accuracy, F1 score, precision and recall on the held-out testing data.

An analysis of the source for this too-good-to-be-true accuracy uncovered that the data were of unknown origin (no documentation on source) and largely contained duplicate values. This early-career data scientist learned an important lesson on ensuring data quality as a pre-requisite for continuing on project development! However, because the project was already developed, I decided to still maintain this repository as a an example of the work I can do, with the very large caveat that a high-quality data source must be used with this code in order to make any real conclusions.

Ultimate model selection was based on balancing the time to train each model with the time it took each to predict an individual patient's diagnosis.
By this criteria the Random Forest model proved to be the most computationally and temporally efficient. The model metrics file can be found [here](https://github.com/caitlinruble/Portfolio/blob/2461a7ea010151c572ab1c75a2c206ac52f9fdaf/Patient%20Diagnosis%20with%20Machine%20Learning/Report/Model%20Metrics.md).


The data can be found at: ["Disease Prediction Using Machine Learning"](https://user-images.githubusercontent.com/96548036/178046872-f5a4753a-3b53-4bb0-8f38-b773f5a6812d.png) on Kaggle. 
 
Some topics covered in this end-to-end project are:

 - Problem Framing and Definition of Success
 - Data Cleaning and Wrangling
 - EDA and Predictive Power Score
 - Data Preprocessing with Label Encoding
 - Building Classification Models Using Supervised Machine Learning Methods in SKLearn (Entropy-Based Decision Tree, Gini-Impurity-Based Decision Tree, AdaBoost, Gradient Boost, XGBoost, and SVC with RBF Kernel)
 - Model Evaluation through Cross-Validation, Analysis of Feature Importances and Training/Prediction Time

A report and slide deck summarizing the process and findings can be found in the respective folders. Please feel free to reach out with any additional questions, ideas for extensions, constructive criticism, and collaboration discussions at caitlinoruble@gmail.com.
