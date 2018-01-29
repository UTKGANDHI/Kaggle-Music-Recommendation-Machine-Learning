# Kaggle-Music-Recommendation-Machine-Learning


The goal of this project was to build a best music recommendation system. This project is posted as a challenge on Kaggle ML community. This dataset is provided by KKBOX, Asia’s leading music streaming service, holding the world’s most comprehensive Asia-Pop music library with over 30 million tracks. In this project, we are supposed to predict the chances of a user listening to a song repetitively after the first observable listening event. For this project, train and test data were provided from the listening history of the user for a given time period.

A total of six attributes are present in the datasets which are mostly recordable and practically applicable in real life. The number of rows in training and testing dataset was around million. A precise data analysis was done by creating Histograms, bar plots, Co-relation matrix plot, box plot and whisker plot. 

- Performed pre-processing on the dataset including PCA
- Performed k-fold cross validation for generating training and a validation dataset.
- Fitted the training data in model built using various classifiers like SVM, DT, KNN, LGBM, ANN, Deep Learning and XGBoost
- Plotted ROC curve and calculated AUC 
- Generated classification report and confusion matrix for getting evaluation metrics like precision, recall and F-1 score. 
- Submitted predictions from the testing dataset to the Kaggle for getting the testing accuracy.
- Got best accuracy of 69.62% with LGBM classifier which resulted in Top 100 position on the Kaggle competition Leaderboard.

Programming Language: Python (Jupyter Notebook)
Libraries used: SciKit-learn, numpy, pandas, Keras
