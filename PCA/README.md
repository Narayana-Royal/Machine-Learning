# PCA
> It reduces the dimensions of the features in order to make features more optimised and select the ones which are essential to predict the target variable.

> This is useful when there are more number of features present in dataset and reduce the unwanted features.

> This will only apply to all the features except target feature. In other terms, X_train and X_test sets are used to reduce the features. We don't use PCA on  Y_train and Y_test set because this is a target feature which has only one column and no need of any reduction.

> After using PCA on X samples we use this updated X samples to train the model and test using the updated X test sample.


