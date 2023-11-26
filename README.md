# CIFAR100_ImageRecognition


## Result
The project focuses on building a convolutional neural network to recognize and classify images from the CIFAR-100 dataset, which contains 60,000 colored images categorized into 100 classes and 20 superclasses. It is clear from the graphs that the model is not learning at learning rates 0.01 and 0.001 whereas a lot of learning has been happening at the learning rate of 0.00001. The final optimized model uses the Adam optimizer and learning rate 0.0001, providing better accuracy than the original model with a learning rate of 0.0001.
The model uses multiple layers and filters to improve accuracy. It has a 5-layer neural network with 643,492 parameters and a loss versus number of epochs graph. Early stopping prevents overfitting and the model stops training at the 49th epoch after 20 epochs. The model has an accuracy of 82% on the testing dataset.
