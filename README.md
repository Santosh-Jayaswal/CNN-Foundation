# Handwritten Classification using CNN

CNN stands for Convolutional Neural Network which is mainely used for image classification task. In this project we are using MNIST dataset that is available in Keras library which contains 70000 handwritten images of 0-9 numbers. These images are in 28 x 28 dimensions and segreegated in train and test dataset that are 60000 and 10000 images respectively. 

At first, we started with preprocessing where we splited the dataset into train and test, so that later they can be used for training and evaluating the model. Then we scaled these X_train and X_test in order to bring them at same scale, follwed by reshaping them which helps the model to understand the structure of the data correctly and enable it to learn features effectively during training. When we feed the data into CNN, it requires a 3D array: width, height and channels. 
