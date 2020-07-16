# cifar_10
The goal is to build a Neural Network which is able to classify 10 classes of images using Python.
This is done using the following libraries-Keras (TensorFlow in the backend ), matplotlib ( for plotting and analysing the data ), NumPy ( for mathematical calculations and normalising data ).
The data has been taken from Keras CIFAR-10 dataset. Explanation:

1. Loading the Libraries.

2. Loading the data and splitting it into Train and Test Data.

3. Analysing the Data

![EDA](https://github.com/prabhdeepsingh3499/cifar_10/blob/master/img/EDA.png?raw=True)

4. Normalizing the Data

5. Importing the Sequential Model and using Sequential Layers

6. Compiling the Model and Evaluating the Data

7. The Accuracy Score of Model is 81.66 %

![Accuracy](https://github.com/prabhdeepsingh3499/cifar_10/blob/master/img/Accuracy.png?raw=True)

8. The Neural Network looks like-

![Summary](https://github.com/prabhdeepsingh3499/cifar_10/blob/master/img/Summary.png?raw=True)

9. The graphs of accuracy and loss of training set and test set with increasing epochs is as shown - 

![Graph](https://github.com/prabhdeepsingh3499/cifar_10/blob/master/img/Graphs.png?raw=True)

The activation function used in the last layer is Softmax, as it gives the probability of the prediction, the label that gives maximum probability is selected as the label.

In order to get better accuracy, you can tweak the neural network and accordingly change the number of layers or change the activation functions.
