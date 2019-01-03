# Image-Classification-using-CIFAR-10-dataset
#Dataset

CIFAR-10 python version link: https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz

We'll be using the CIFAR-10 dataset, which is very famous dataset for image recognition!
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

#Understanding the original labels

The label data is just a list of 10000 numbers in the range 0-9, which corresponds to each of the 10 classes in CIFAR-10.

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

#Implement Preprocess Functions

Normalize

Min-Max Normalization
