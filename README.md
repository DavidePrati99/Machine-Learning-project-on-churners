# Machine-Learning-project-on-churners

The aim of the project is to try to deal with the phenomenon of customer attrition, predicting customers who are likely to drop off.

The source of the data is https://www.kaggle.com/datasets/anwarsan/credit-card-bank-churn

Data are prepared and preprocessed by machine learning algorithms: categorical values of attributes are encoded to numerical ones and checked for missing values, then the features that have the most impact on the target are selected and the problem of an unbalanced dataset is solved exploiting an undersampling strategy.

To predict the value of the attribute regarding customer attrition, many machine learning models were developed: Random Forest, Logistic Regression, SVM and Naive Bayes. All of them have been implemented in Knime, also adding a Weka version with the Weka predicting node. 

To evaluate and compare the performances of the models, some criteria were used, such as accuracy, precision, recall and F1-measure. ROC curve and AUC were evaluated too.
