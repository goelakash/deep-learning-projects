## Dog breed classifier

This project uses a Convolution Neural-net to differentiate b/w different breeds of dogs. 

Features:  
1. Detecting human and dog faces using OpenCV  
2. Using a pre-trained VGG-16 model from `torchvision` to classify the dog-breeds that achieves
Accuracy - 91%
3. A simple conv-net built using Torch for the classification task as an exercise.
Accuracy - 17%

#### Dataset:
Download links:  
1. [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)  
2. [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

Unzip the files in the same folder as `dog_app.ipynb`.

#### Dependencies:
Latest versions of these packages (or the version numbers I've built with):
```
torch (1.1.0)
torchvision (0.3.0)
numpy (1.16.3)
```

#### Future scope:
There are several ways in which the accuracy of the neural nets can be increased  
1. Hyper-parameter tuning (batch-size, optimization function, learning-rate, etc)  
2. Different pre-processing techniques for training  
and much more!