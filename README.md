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

**Project-2: MNIST_Neural_Net_Kaggle**

_Competition Description:_

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. This competition is the perfect introduction to techniques like neural networks using a classic dataset including pre-extracted features.

_Dataset:_

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

