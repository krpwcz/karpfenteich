# _Diploma Exam_ - Topics

|Topic|Buzzwords, Hints...|
|-|-|
|Vocabulary|Of course you should be able to understand and explain common terms and their underlying concepts, e.g. Under-/Overfitting, Generalization, Classification vs. Regression, Hyperparameters...
|Preprocessing|How can you deal with missing values? Which types of categorical variables do you know, and how can they be encoded for using them in _ML_? Describe approaches for scaling data - i.e. Min-Max-Scaling, Standardization, robust scaling - and situations that require us to do so.|
|_kNN_|Describe the inner workings of the _kNN_-algorithm both for classification and regression problems. What hyperparameters can be adjusted and how can they lead to under-/overfitting? Why is scaling crucial for this algorithm? Briefly describe the idea of using a similar approach for generating data (_SMOTE_).|
|Performance Metrics|Describe (and calculate) the common metrics for evaluating the performance of classification models (i.e. accuracy, precision, recall, f1). Interpret a confusion matrix for binary classification. When can depending on accuracy pose a problem? Give examples on situations where precision and recall would be suitable metrics. Describe common metrics for evaluating regression models (i.e. MAE, MSE).|
|Training And Testing|Why do we need to split data? Describe (and visualize) common approaches for splitting a dataset (i.e. hold-out, cross-validation). Describe stratification in the context of splitting data. Given a training- and test-set: What do you need to consider when applying preprocessing methods?|
|Decision Trees And Random Forests|Describe the concepts of entropy/information gain and Gini impurity in the context of training a decision tree for classification problems. When does a decision tree overfit - and what can you do against it? How do random forests work and how do they compensate for overfitting trees?|
|Imbalanced Class Distributions|Why is accuracy not a good metric for evaluating algorithms with imbalanced class distributions? Why is stratification important when splitting data? Describe common strategies and their (dis-)advantages for resampling data - i.e. random undersampling, random oversampling, _SMOTE_.|

## Formulas To Know

### Metrics

$$\text{Accuracy} = \frac{\text{Number Of Correct Predictions}}{\text{Total Number Of Predictions Made}} $$

$$\text{Precision} = \frac{\text{True Positives}}{\text{True Positives} + \text{False Positives}}$$

$$\text{Recall} = \frac{\text{True Positives}}{\text{True Positives} + \text{False Negatives}}$$

### Standardization

$$x' = \frac{x - \bar{x}}{\sigma}$$

...with $\bar{x}$ being the mean and $\sigma$ being the standard deviation. N.B.: This will be no maths exam, but the formula is important for being able to describe the result and the differences to the `RobustScaler`.
