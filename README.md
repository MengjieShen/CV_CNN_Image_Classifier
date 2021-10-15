# Image classifier using CNN
This is the implementation of deep neural network classifiers to classify input images to respective labels.

The project consists four parts: 

• Lenet Structure with SGD as optimizer 

• Lenet Structure with ADAM as optimizer

• Modified Lenet structure

• VGGnet-19 Structure

## Dataset
The CIFAR-10 dataset consists of 60000 32x32 color images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.


## Accuracy
Lenet with SGD: 60.25%

Lenet with ADAM: 57.5%

Modified Lenet: 70.96%

VGG-19: 80.62%
