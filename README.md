# Object-Recognition-Using-CNN-for-CIFAR-10-Dataset

# About the Dataset
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. 
There are 50000 training images and 10000 test images. The dataset is divided into five training batches and one test batch, 
each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. 
The training batches contain the remaining images in random order, but some training batches may contain more images
from one class than another. Between them, the training batches contain exactly 5000 images from each class. 

#Here are the classes in the dataset:-
airplane										
automobile										
bird										
cat										
deer										
dog										
frog										
horse										
ship										
truck	

# Steps followed 
1.Reshaped image shape, normalized them prior to tackling categorical inputs with one hot encoder to optimize input to neural networks

2.Created Multi layer perceptron CNN layers using Keras(Theano backend) to train the model with 1,369,738 parameters;Relu, Softmax Function, Mean Pooling, Padding were used

3.Implemented model again using defined weights to avoid performance gap of CPU by completing evaluation of 10,000 images with 87% accuracy;Predicted results aligned with models behavior
