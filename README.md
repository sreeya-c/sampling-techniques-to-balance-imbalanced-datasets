# sampling-techniques-to-balance-imbalanced-datasets
Technology: Python, ML
Using machine learning, supervised issues like classification may be solved accurately and consistently.
In the actual world, during the dataset construction, there may be a class imbalance where the number of data samples in a class is not equal to the other class.
Such events provide atypical prediction outcomes.
To address the issue of class imbalance, Along with experimental investigation of four different datasets from various domains, 
the paper outlines numerous external ways to balance datasets.
The datasets are balanced using two undersampling methods (Random Undersampling and Near Miss) and four oversampling methods (SMOTE, ADASYN, Cluster SMOTE, and K-means SMOTE).
Additionally, a mix of undersampling and oversampling approaches, primarily ADASYN and neighborhood cleaning rule (NCL), was used.
For the job of binary classification, these datasets are employed.
To compare the performances, three machine learning classification algorithms—logistic regression, random forest, and decision tree—are applied to unbalanced and balanced datasets.
It has been discovered that the undersampling approach misses a lot of crucial data points and predicts poorly as a result. 
For all of the datasets, it is noted that the ADASYN oversampling strategy offers some respectable predictions and a combination of the two strategies offers faster runtime, 
usage of less training data samples, fewer storage issues and yields a respectable ROC-AUC score which is preferred over other metrics such as accuracy or F1-score when dealing with imbalanced datasets with the right amount of balance.
