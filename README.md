# Mnist-handwritten-digit-classification

PROGRAMMING TEST: LEARNING ACTIVATIONS IN NEURAL NETWORKS (MNIST) - MONK AI

I. BACKGROUND
Selection of the best performing AF for classification task is essentially a naive (or brute-force) procedure wherein, a popularly used AF is picked and used in the network for approximating the optimal function. If this function fails, the process is repeated with a different AF, till the network learns to approximate the ideal function. It is interesting to inquire and inspect whether there exists a possibility of building a framework which uses the inherent clues and insights from data and bring about the most suitable AF. The possibilities of such an approach could not only save significant time and effort for tuning the model, but will also open up new ways for discovering essential features of not-so-popular AFs.


II. PROBLEM STATEMENT

Given a specific activation function
        g(x) = k0 + k1x                                                                                                                                                                                                                           
and categorical cross-entropy loss, design a Neural Network on MNIST dataset where the activation function parameters k0, k1 are learned from the data you choose from one of the above-mentioned data sets. My solution was included by the learnable parameter values. I.e. final k0, k1 values at the end of training, A plot depicting changes in k0, k1 at each epoch, Training vs test loss, train vs. Test accuracy and a Loss function plot.


NOTE : 

* This report containing implementation details (al-gorithm, initial settings such as sampling the parameters k0, k1 from some distribution, parameter updates one pochs, final parameter values at the end of training, train vs test loss, train and test accuracy, F1-Score, plot of the loss function vs. epochs.

•	And Focusing on to recognization of hand written digits. The approach that will be implemented to solve this classification problem is by using the method of Artificial Neutral Network(ANN).


MNIST :

* All images are labelled with the respective digit they represent

* There are 70,000 images, and each image has 784 features

* Each image is 28*28 pixels, and each features simply represents one pixel's intensity
from 0 (white) to 255(black)


# Confusion matrix
![alt text](http://url/to/img.png)




 

A plot depicting changes in k0, k1 at each epoch, train vs. Test accuracy :

 

A plot depicting changes in k0, k1 at each epoch, Training vs test loss :
 


