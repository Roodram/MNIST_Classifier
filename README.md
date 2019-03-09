# MNIST_Classifier
Keras based CNN model for MNIST dataset classification

Since, generally the number of elements in a image array are very large. This increases the number of parameters to be trained if we directly flatten the image and use dense layers in the model. This results in a higher computational cost. To solve this problem, we use convlutional layers, which decreases the number of parameters to be trained in the image. 
  
But, the dimensions of mnist dataset image are very less, so it is possible to flatten the image and pass it directly through fully connected dense layers.
  
Here, I have implemented the classifier model in both ways.
