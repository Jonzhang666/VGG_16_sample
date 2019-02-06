#VGG_16_sample
====
Description：
------- 
For this project, I use pretrained vgg-16 model (vgg16_weights.npz) to test the example input image from input_images. 

(1) This project provides an implementation of VGG16 and the weights from the original Caffe model converted to TensorFlow.

(2) Use tensorboard to produce the histogram of feature maps and weights at layers 1-5 of pretrained vgg-16 for an example input image.

![](https://github.com/Jonzhang666/VGG_16_sample/results/conv1_1.png)

Model weights - vgg16_weights.npz (Due to big size, I don't upload it)

TensorFlow model - vgg16.py

Class names - imagenet_classes.py

Example input - input_images/snake.jpg
