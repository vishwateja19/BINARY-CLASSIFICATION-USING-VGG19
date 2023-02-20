# BINARY-CLASSIFICATION-USING-VGG19:









![App Screenshot](https://conservationaction.co.za/wp-content/uploads/2018/09/WP.jpg)



Since we are using vgg199 for this model development instead of our own custom model 
so a brief introduction about vgg19:


VGG-19 is a convolutional neural network that is 19 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database . The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals.

for more information:
https://keras.io/api/applications/vgg/




In this is a  CNN model to classify images whether they african or asian elephants . While the output is the accuracy, the main objective of this project is not to get a high accuracy but rather to learn how to use convolution neural network (CNN) for classification using tensorflow and instead of our own architecture which include kernel layers,
maxpooling layers of cnn and hidden layers of ann we use vgg19 architecture.











## DESCRIPTION





Since we use tensorflow framework so brief introduction about tensorflow.

TENSORFLOW:

TensorFlow is an open-source software library for deep learning and machine learning developed by Google Brain Team. It is used for a wide range of applications, including image and speech recognition, natural language processing, and computer vision. It is also used to create and train neural networks, which are the backbone of deep learning.

![App Screenshot](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhTtFXWao9sbX4P__SCJhLChXRdTkVur0sJTnQp5K0MtVR7U0-l3j5Yrpx41U2YSh4N671c-Wn7dJ68xim8cGAiexDI3IOdEV_vHpMsWdsZxSYU3TUpAzNEIVOOOV3O-wxa4caTUT2VwVTTy-R6GlGji1H4lhewb9WC5nmRCzN8Ofe7yF1NW6ArPI7Q/s1600/Tensorflow-septmber-update-social%20%281%29.png)



After collecting the data , i gave training and test data paths for image preprocessing using tensorflow framework ImageDataGenerator and then training the model withb vgg19 architecture instead of using our own architecture.Finally predicting the image whether it is African and Asian elephants.

 I trained the data with 50 epochs and the accuracy i got from the model is 0.8464.




 

 





## SKILLS

1.Python

2.Numpy

3.Pandas

4.Matplotlib

5.Seaborn

6.feature-engine

7.Sckit-learn

8.Statistics

9.Probability

10.Deep learning

11.Machine learning
## DATASET

follow this link:
https://www.kaggle.com/datasets/vivmankar/asian-vs-african-elephant-image-classification
