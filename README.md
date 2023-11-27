# ml
**Bias-Variance Tradeoff.ipynb**
Understanding train and test data
The train-test split is a technique for evaluating the performance of a machine learning algorithm. It can be used for classification or regression problems and can be used for any supervised learning algorithm.
The procedure involves taking a dataset and dividing it into two subsets. The first subset is used to fit the model and is referred to as the training dataset. The second subset is not used to train the model; instead, the input element of the dataset is provided to the model, then predictions are made and compared to the expected values. This second dataset is referred to as the test dataset.
Train Dataset : Used to fit the machine learning model.
Test Dataset : Used to evaluate the fit machine learning model.
The objective is to estimate the performance of the machine learning model on new data: data not used to train the model. This is how we expect to use the model in practice. Namely, to fit it on available data with known inputs and outputs, then make predictions on new examples in the future where we do not have the expected output or target values.

![image](https://github.com/Pawanme9034/ml/assets/122411441/6ee1cfea-6a13-4ee9-8e12-ba3aa15f21eb)
\
Understanding underfitting and overfitting
In machine learning and pattern recognition, there are many ways (an infinite number, really) of solving any one problem. Thus it is important to have an objective criterion for assessing the accuracy of candidate approaches and for selecting the right model for a data set at hand. We’ll discuss the concepts of under- and overfitting and how these phenomena are related to the statistical quantities bias and variance. Finally, we will discuss how these concepts can be applied to select a model that will accurately generalize to novel scenarios/data sets.
![image](https://github.com/Pawanme9034/ml/assets/122411441/ee9d1ba4-a2a7-48a5-886f-61a89188d14c)

Expected Prediction Error and the Bias-variance Tradeoff
For a given estimator  g(x)  fit to a data set of  x−y  pairs , we would like to know, given all the possible datasets out there, what is the expected prediction error we will observe for a new data point  x∗ ,  y∗=f(x)+ϵ . If we define prediction error to be the squared difference in model prediction  g(x∗)  and observations  y∗ , the expected prediction error is then:

E[(g(x∗)−y∗)2]  =  E[(g(x∗)−E[g(x∗))2]  +  (E[(g(x∗)]−f(x∗))2 +  E[(y∗−f(x∗))2] 

Error=Variance+Bias2+Irreducible error 
The first term is the variance of the estimator introduced above.
The second term is the squared bias of the estimator, also introduced above.
The third term is the variance of the observation noise and describes how much the observations  y  vary from the true function  f(x) . Notice that the noise term does not depend on the estimator  g(x) . This means that the noise term is a constant that places a lower bound on expected prediction error, and in particular is equal to the variance the noise term  σ2ϵ

![image](https://github.com/Pawanme9034/ml/assets/122411441/588b9e77-f5a4-4974-b64e-089ddfcaa7fa)





