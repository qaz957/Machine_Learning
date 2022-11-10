# Machine Learning

## Overview

Evaluate credit card data using multiple machine learning models to evaluate their efficacy at predicting credit risk. We are using scikit-learn and imbalanced-learn libraries to employ 6 differrent learning models to our data and will determine accuracy through a balanced accuracy score and recall metrics.

## Analysis

### - Naive Random Oversampling
Balanced Accuracy: 65.2%

Precision: 99%

Recall: 68%


![Naive_Random_Over](https://user-images.githubusercontent.com/108296899/201088901-368fe4fa-d540-4747-82aa-4475323a7207.png)

### - SMOTE Oversampling
Balanced Accuracy: 62.4%

Precision: 99%

Recall: 74%

![SMOTE_Over](https://user-images.githubusercontent.com/108296899/201088916-16d07fc4-3939-4e8f-bd55-3ca3d92e2e05.png)

### - Undersamling
Balanced Accuracy: 52.9%

Precision: 99%

Recall: 45%

![Under](https://user-images.githubusercontent.com/108296899/201088968-2c8a3ba4-a388-419b-8928-8f21e368bd8b.png)

### - Combination (Over and Under) Sampling
Balanced Accuracy: 63.8%

Precision: 99%

Recall: 58%

![Combination](https://user-images.githubusercontent.com/108296899/201088983-0e51e8af-335f-4862-9763-2e057ee5a3ed.png)

### - Balanced Random Forst Classifier
Balanced Accuracy: 56.4%

Precision: 99%

Recall: 91%

![BalancedRandomForest](https://user-images.githubusercontent.com/108296899/201089022-ec892f5f-d133-4169-bd7d-9939fce646fe.png)

### - Easy Ensemble AdaBoost Classifier
Balanced Accuracy: 93.1%

Precision: 99%

Recall: 94%

![EasyEnsemble](https://user-images.githubusercontent.com/108296899/201089036-2c63995b-6601-406a-91a6-36d5bf0de84a.png)
