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


**Project-3: SVHN_Dataset_CV_DL**

Recognizing multi-digit numbers in photographs captured at street level is an important component of modern day map making. A classic example of a corpus of such street-level photographs is Google’s Street View imagery comprised of hundreds of millions of geo-located 360 degree panoramic images. The ability to automatically transcribe an address number from a geo-located patch of pixels and associate the transcribed number with a known street address helps pinpoint, with a high degree of accuracy, the location of the building it represents.

In this project, we will use a dataset with images centered around a single digit (many of the images do contain some distractors at the sides). Although we are taking a sample of the data which is simpler, it is more complex than MNIST because of the distractors.

_Street View House Numbers (SVHN) Dataset_

http://ufldl.stanford.edu/housenumbers/

SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with the minimal requirement on data formatting but comes from a significantly harder, unsolved, real-world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images.
 
**Project-4: CNN_Project_Dog breed_Identification**

_Objective:_

Given a set of different dog breed images, build an image classifier to determine the breed of a dog in the image.

_Context:_

Image Classification problem, which is the task of assigning an input image one label from a fixed set of categories. This is one of the core problems in Computer Vision that, despite its simplicity, has a large variety of practical applications. Moreover, as we will see later in the course, many other seemingly distinct Computer Vision tasks (such as object detection, segmentation) can be reduced to image classification.

_Data Description:_

https://www.kaggle.com/c/dog-breed-identification/data

Provided with a training set and a test set of images of dogs. Each image has a filename that is its unique id. The dataset comprises 120 breeds of dogs. The goal of the competition is to create a classifier capable of determining a dog's breed from a photo.

**Project-5: Computer_Vision_Project_Face_recognition**

_Face Recognition:_

In this hands-on project, the goal is to build a face identification model to recognize
faces.

_Dataset:_

Aligned Face Dataset from Pinterest. This dataset contains 10,770 images for 100 people. All images are taken from 'Pinterest' and aligned using dlib library. 

In this problem, we use a pre-trained model trained on Face recognition to recognize similar faces. Here, we are particularly interested in recognizing whether two given faces are of the same person or not.

**Project-6: Statistical_NLP_Project**

_Project Description:_

Text in the form of blogs, posts, articles, etc. is written every second. It is a challenge to predict the information about the writer without knowing about him/her.
Let's create a classifier that predicts multiple features of the author of a given text as a Multilabel classification problem.

_Dataset:_

https://www.kaggle.com/rtatman/blog-authorship-corpus

Blog Authorship Corpus --> Over 600,000 posts from more than 19 thousand bloggers.

The Blog Authorship Corpus consists of the collected posts of 19,320 bloggers gathered from blogger.com in August 2004.

All bloggers included in the corpus fall into one of three age groups:

8240 "10s" blogs (ages 13-17),

8086 "20s" blogs(ages 23-27)

2994 "30s" blogs (ages 33-47)

**Project-7: Project_Sarcasm_Detection_Sequential_NLP**

_Project Description:_

In this hands-on project, the goal is to build a model to detect whether a sentence is sarcastic or not, using Bidirectional LSTMs.

Past studies in Sarcasm Detection mostly make use of Twitter datasets collected using hashtag based supervision but such datasets are noisy in terms of labels and language. Furthermore, many tweets are replies to other tweets and detecting sarcasm in these requires the availability of contextual tweets.

To overcome the limitations related to noise in Twitter datasets, this Headlines dataset for Sarcasm Detection is collected from two news website. TheOnion aims at producing sarcastic versions of current events and we collected all the headlines from News in Brief and News in Photos categories (which are sarcastic). We collect real (and non-sarcastic) news headlines from HuffPost.

_Dataset:_

https://github.com/rishabhmisra/News-Headlines-Dataset-For-Sarcasm-Detection

Each record consists of three attributes:

  is_sarcastic: 1 if the record is sarcastic otherwise 0
  
  headline: the headline of the news article
  
  article_link: link to the original news article. Useful in collecting supplementary data



