## DataMining

This repository is a copy of the Python Notebook my team used for a university assignment regarding Expedia's booking data. The goal was to predict the most relevant hotels given a novel user search. 

* We implemented **normalization** of all numerical features, **removal of outliers** and **imputation of missing values** with various scenarios. The given training data was heavily biased towards unclicked hotels, so we **balanced** the dataset to contain equal parts of clicked and unclicked hotels.
* We tested several models, including **Random Forest**, **XGBoost** and **AdaBoost Regressors**.
* Scores were **cross validated** on 10 folds

