# Neural Networks and Deep Learning
**Use of simple neural networks with lean architecture to solve classification problems.**

A Neural Network(NN) is a computer program, loosely inspired by the structure of neuron in the brain. It consists of a large number of very simple interconnected elements which takes numeric inputs, computes a simple function over the inputs. 
Deep Learning(DL) is a subfield of Machine Learning(ML), which is a vibrant research area in Artificial Intelligence(AI). DL is a class of algorithmic methods for ‘tuning’ Neural Nets based on data. These techniques merely strengthens the connections in neural networks. This paradigm is quite general. It has been highly successful in applications ranging from self-driving cars and speech recognition to anticipating airfare fluctuations and much more.

**Optimizing parameters for DL models**
Optimize the model

Some important parameters to look out for while optimizing neural networks are:

1) Type of architecture
2) Number of Layers
3) Number of Neurons in a layer
4) Regularization parameters
5) Learning Rate (0.1 - 0.0001)
6) Type of optimization / backpropagation technique to use (SGD,ADAM, NADAM,AdaGrad, etc.)
7) Activation functions (Sigmoid, tanh, relu, etc.)
9) Dropout rate
10) Weight sharing


**Project-1: Bank_Custmer_Churn_Modeling**

_Objective:_

Given a Bank’s customer information, can we build a classifier which can determine whether they will leave or not?

_Context:_

Businesses like banks which provide service have to worry about problem of 'Churn' i.e. customers leaving and joining another service provider. It is important to understand which aspects of the service influence a customer's decision in this regard. Management can concentrate efforts on improvement of service, keeping in mind these priorities.

_Data Description:_

https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

The dataset contains 10,000 sample points with 14 distinct features such as CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance, Exited etc.

