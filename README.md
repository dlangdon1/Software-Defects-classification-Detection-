# Software-Defects-classification-Detection-

The goal implements and evaluate various machine-learning models for the binary classification of software defects using dataset "Binary Classification with a Software Defects” take from Kaggle ‘s Playground Series - Season 3, Episode 23, available on Kaggle, contains 169,605 samples, each with 21 features and a binary label indicating the presence or absence of a defect.

Machine learning models allow us to predict whether software has defects in early detection phase to avoid catastrophic system failures, causing significant disruptions and financial losses after software is deployed.
Various models include Gaussian Naive Bayes, Bernoulli Naive Bayes, Decision Tree Classifier, K-Nearest Neighbors Classifier, Logistic Regression, Random Forest Classifier, Gradient Boosting Classifier, Histogram-based Gradient Boosting Classification Tree, Light Gradient Boosting Machine, Extreme Gradient Boosting, and CatBoost Classifier Training involve using cross validation in K folds variation of first the baseline of the models and then optimized those models.
Hypermeters used Gaussian Naive Baye Variance Smoothing for Gaussian Naive Bayes, Alpha for  Bernoulli Naive Bayes, Criterion and Max Tree Depth for Decision Tree, Neighbors for K Nearest Neighbor, Solvers, and C values for logistic regression, Max Tree Depth and Learning Rate for His Gradient Boosting, Max features and Max Tree Depth for Random Forest, Max Tree Depth and Max Number of Leaves for Light Gradient Boosting Machine, Max Tree Depth and Learning Rate for Extreme Gradient Boosting and lastly Max Tree Depth for Cat boosting

Both the Baseline and optimized models were evaluated all using ROC AUC Score, Average Training ROC AUC Score, Average Validation ROC AUC Score, Average Accuracy, and Average F1 Score as metrics. The held-out validation set was the test data which was labelled using each model.

The Software Defects Binary Classification .ipynb contains the code used to preprocess the training data, perform data exploration, preprocessing, train/val split, cross validation evaluate the various models, using metrices mentioned above and lastly label the validation dataset.

Software Defects Binary Classification Presentation.pptx contains the presentation which illustrates the process throughout this project.

The test_labelled.csv is the final outcome of this project. It contains the predicted labels for each test sample using each of the 11 models trained
