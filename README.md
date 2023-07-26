# Image_Recognition
Using the CIFAR10 dataset present inside the tensorflow library. The dataset contains different images which can be classified and predicted using the Convolution Neural Network (CNN). First we used the ANN for image classification but the accuracy of the model is poor less than 50% on the test dataset. 

Then we used CNN by addding covolution layers and Batch Normalization which follows a pattern i.e CONV => RELU => CONV => RELU => POOL => DROPOUT and filter size of 32,64,128. After that we flattened and transformed them into the Dense neural network with different hidden layers. The test accuracy is now 82%.

For further increment in the test accuracy we used a technique called Data Augmentation which helped in increasing our test accuracy upto 87%.
