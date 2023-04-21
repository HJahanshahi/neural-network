# Convolutional Neural Network
This is an implementation of a Convolutional Neural Network (CNN) using TensorFlow and Keras for image classification.

Libraries Used
TensorFlow
Keras
numpy
Data Preprocessing
The code reads the training and test data from the dataset folder. The ImageDataGenerator from Keras is used to augment the images in the training set. The images are resized to 64x64 pixels and then scaled down to values between 0 and 1. The test set is also scaled down to values between 0 and 1.

Building the CNN
The CNN consists of three convolutional layers, each followed by a pooling layer, and one fully connected layer with a sigmoid activation function. The Sequential model from Keras is used to add the layers to the network.

Compiling and Training the CNN
The CNN is compiled with the binary crossentropy loss function, the Adam optimizer, and the accuracy metric. The fit function is used to train the model on the training set for 25 epochs, with the test set being used for validation.

Making a Prediction
Finally, the code loads a single image and scales it down to 64x64 pixels. It then uses the predict function to determine whether the image is a cat or a dog, and prints the result.

Note: The code is written in Google Colab, but it can be run in Jupyter Notebook by changing the file paths to the dataset folder.
