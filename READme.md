# CIFAR
## CIFAR-10 
The CIFAR-10 is a  dataset consists of several images divided into the following 10 classes:
Airplanes, Cars, Birds, Cats, Deer, Dogs, Frogs, Horses, Ships, Trucks.

The dataset stands for the Canadian Institute For Advanced Research (CIFAR)
CIFAR-10 is widely used for machine learning and computer vision applications.The dataset consists of 60,000 32x32 color images, 6,000 images of each class.Images have low resolution (32x32). 

Data Source: https://www.cs.toronto.edu/~kriz/cifar.html

 There are 50000 training images and 10000 test images.Images are 32x32 pixels(colored)

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 

Here are the classes in the dataset, as well as 10 random images from each:

<img width="481" alt="Screen Shot 2019-03-29 at 12 24 08 AM" src="https://user-images.githubusercontent.com/31596604/55184817-1daa2400-51b9-11e9-93dc-89c659e3f6fe.png">
The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks

## Classification using CNN
Train Accuracy : 94.12%<br/>
Test Accuracy : 77.49%
