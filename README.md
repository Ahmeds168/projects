# projects
This repository contains machine learning projects done in class as well as from datacamp. 


1. Caltech Original Prepared: This is object detection project in which we detect 101 objects such as accordian, aeroplane, pyramid, canon, camera, crab, cup, dragonfly and many more. First of all we divide the dataset into train, test, validation. Then we create a sequential model with 101 dense layers with sigmoid activation function. Then we compile the model with categorical crossentropy and the metric used is accuracy. As we need more images for training so we apply data augmentation. Then we run 100 epochs (15 steps per epoch). Then we run the model. Then we save the model as h5 file. Then we predict the images. Then we visualize the train and validation accuracy as well as train and validation loss.

2. Coil 20 Unprocessed: This is also object detection project except that it detects only 5 kinds of objects and the objects are in black and white rather than colorful. First of all we divide the dataset into train, test, and validation. Then we create the sequential model with 5 dense layers with sigmoid activation function. Then we compile the model with categorical crossentropy and the metric used is accuracy. Here we have few images for each class, therefore, we apply data augmentation to generate more images so that we may have more images for training and so forth increase the accuracy.  Then we run 100 epochs(30 steps per epoch). Then we save the model as h5 file. Then we plot the training and validation accuracy as well as training and validation loss. 

2. Same process is applied for cat and dog recognition model as well Credtit Card approval prediction model from datacamp.
