# Predicting the Past - Photometric Redshift Estimation on SDSS Data
The project was part of the finals project in BIA 678 - Big Data Technologies at Stevens Institution of Technology. The project explores the use of big data techniques to get faster and accurate measurements of photometric redshift of galaxies using the Sloan Digital Sky Survey dataset. My main objective was to see how scaling up (increasing data) and scaling out (increasing worker nodes) affects the training speed of the four different machine learning models: Linear Regression, Decision Tree Regression, Random Forest Regression, and Gradient Boosted Tree Regression. 

To achieve my objective, I first trained the entire dataset and performed hyperparameter tuning to find the best hyperparameters for all the four models and then apply scaling out technique to get my results. The following models were used:
- 1 Master, 2 Workers
- 1 Master, 4 Workers
- 1 Master, 6 Workers

For this Project, Google Dataproc was used to create the VMs and the results could be found in the pdf file.
