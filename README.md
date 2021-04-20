# Context 
Convolutional Neural Network (CNN) being computationally strong has the ability to automatically detect the important features without the governance of humans. Also compared to normal neural networks accuracy of CNN models are always high and is considered to be one of the strong architectures when it comes to image classification. CNN models are now capable of doing classification better than humans; it has surpassed human ability for classifying an image.

# Implementing a CNN for finger counting 
Build a Convolutional Neural Network (CNN) model to classify the finger counting. 



## The dataset
The chosen dataset is composed of pictures of hands describing a number. The goal of this CNN is to count the number of fingers that we can count thanks to image recognition. All the images are 64 by 64 pixels.
![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5299578%2F7b415cbfd942b3feb3d8b7e16d96d11f%2FSIGNS.png?generation=1602653063304686&alt=media)

## Requirements
In order to run this CNN you will require : 
<li> Files [train_signs.h5](https://github.com/thomastrg/ConvolutionalNN_Finger_count/blob/main/train_signs.h5) and [test_signs.h5](https://github.com/thomastrg/ConvolutionalNN_Finger_count/blob/main/test_signs.h5) in order to train and test your convolutional neural network
<li> Libraries : h5py, tensorflow and matplotlib
<li> Activate GPU as harware accelerator in order to facilitate epochs during the training
