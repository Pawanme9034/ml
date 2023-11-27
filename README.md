# ml
**Bias-Variance Tradeoff.ipynb**
Understanding train and test data
The train-test split is a technique for evaluating the performance of a machine learning algorithm. It can be used for classification or regression problems and can be used for any supervised learning algorithm.
The procedure involves taking a dataset and dividing it into two subsets. The first subset is used to fit the model and is referred to as the training dataset. The second subset is not used to train the model; instead, the input element of the dataset is provided to the model, then predictions are made and compared to the expected values. This second dataset is referred to as the test dataset.
Train Dataset : Used to fit the machine learning model.
Test Dataset : Used to evaluate the fit machine learning model.
The objective is to estimate the performance of the machine learning model on new data: data not used to train the model. This is how we expect to use the model in practice. Namely, to fit it on available data with known inputs and outputs, then make predictions on new examples in the future where we do not have the expected output or target values.

![image](https://github.com/Pawanme9034/ml/assets/122411441/6ee1cfea-6a13-4ee9-8e12-ba3aa15f21eb)


