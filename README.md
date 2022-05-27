# Clothing-type-Classifier
This clothing type classifier was implemented with different approaches to reach optimal results.
# Dataset
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

* Download CSV files from 
[Here](https://pjreddie.com/projects/mnist-in-csv/)

![embedding](https://user-images.githubusercontent.com/105811813/170795613-4a816f11-3760-47a5-9139-35722456ade4.gif)

# Labels

Each training and test example is assigned to one of the following labels:

* 0 T-shirt/top 
* 1 Trouser
*  2 Pullover 
*  3 Dress 
*  4 Coat 
*  5 Sandal 
*  6 Shirt 
*  7 Sneaker 
*  8 Bag 
*  9 Ankle boot

# Methodology

In this project I used multiple approaches:

As the problem is a classification one, so my first approach was to implement  Classification Algorithms in ML.

- The first algorithm was: "K nearest neighbours (KNN)"

The KNN algorithm aims to locate all of the closest neighbors around a new unknown input in order to figure out what class it belongs to.
I implemented it using sklearn.

- The second algorithm was: "Logistic Regression"

Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable. 

- The third algorithm was: "Decision Tree Classifier"

A decision tree is a supervised learning technique. It works like a flow chart, sorting data points into two comparable categories at a time, starting with the "tree trunk" and on to "branches" and "leaves," where the categories become increasingly finitely similar. This develops sub-categories, allowing for organic classification with minimal human intervention.

- The fourth algorithm was: "Random Forest Classifier"

 It builds decision trees on different samples and takes their majority vote for classification.
 
 --> Random Forest Classifier was the best algorithm/technique in this data as it gives an 88.48% accuracy in test data.
 
I also implemented the Artificial Neural Network(ANN),
that was my first time dealing with Neural networks.

At first, the accuracy of the model was 87.5%, but after implementing more than one hidden layer the accuracy stay as it was, but after the tunning, the accuracy increased to 88.1%.

and finally, my last approach was "Convolutional neural network (CNN)" and it was the best approach for this data as it gives a 90.5% accuracy.

# Handling Data
