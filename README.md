Artificial Neural Network
This is a Python code for building an Artificial Neural Network (ANN) using TensorFlow library. The code is divided into three parts:

Part 1 - Data Preprocessing
In this part, the necessary libraries are imported, and the dataset is loaded and preprocessed. The dataset used is the Churn_Modelling.csv, which contains information about bank customers. The preprocessing steps involve encoding categorical data, such as the "Gender" and "Geography" columns, splitting the dataset into training and testing sets, and feature scaling.

Part 2 - Building the ANN
In this part, the ANN is initialized and built using the Keras Sequential model. Three layers are added: two hidden layers with ReLU activation function, and one output layer with sigmoid activation function.

Part 3 - Training the ANN
In this part, the ANN is compiled and trained on the training set. The compilation involves defining the optimizer, loss function, and evaluation metric. The ANN is then trained using the fit() method, and the training results are displayed.

Note: This code uses TensorFlow 2.x, and it may not be compatible with other versions.
