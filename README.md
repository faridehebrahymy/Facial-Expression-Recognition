# Facial Emotion Recognition using CNN :

This is a completely deep learning project that is completely based on neural networks, and it can be said that the Facial Emotion Recognition (FER) project is one of the classic projects in deep learning.
<br/>
<br/>
During this project, we implement a human emotion recognition system from facial images using Convolutional Neural Networks (CNN). The main goal of this project is to identify 7 categories of different emotions, including anger, disgust, fear, happiness, sadness, surprise, and neutral.
<br/>
Here I trained the convolution neural network with kaggle facial emotion dataset. so that it learns patterns for each facial expression and able to detect facial emotions
<br/> <br/>



The picture below shows the distribution of labels for each emotion for the real test labels and the labels predicted by the model.
<br/>
<br/>
![Label_Comparision](content/images/Label_Comparision.png) --
<br/>


-------




## Installation of python libraries:
  * keras with tensorflow as backend
  * OpenCV
  * numpy
  * pandas
  * matplotlib


## DataSet:
In this project I used kaggle dataset i.e  <br/>
  https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/overview
  <br/>
    we can use a kaggle API to access and download that dataset.

## Instructions:
<br/>
<br/>
In this notebook, I have tried to separate the parts from each other and explain what is happening for each part by title.<br/>
I document almost everything  that is used in the  program.<br/>
This notebook file is a complete wrapout  of practical exposure.
<br/>
<br/>

  * facial_Emotion_Recognition_using_cnn.ipnb -->  main file
  * images folder --> consists of images to be tested and also contains screenshots of results of that images.
  * model.h5 --> saved weights of the model which is trained with 200 epochs
  * model_architecture.json --> saved architecture of the neural network.
  * haarcascade classifiers --> higly pretrained classifiers to detect faces.

  --------
## Result:
<br/>
The following is the results of the images. I also add the number of persons in the image and the relevant emojis to their emotions of the persons to create sense of feel.
<br/><br/>

In the image provided below, you can see the distribution of different emotions predicted by the model for a random image
![prediction_test_labels](content/images/prediction_test_labels.png)
 <br/>
 <br/>
And below are some images and model predictions
 <br/> <br/>
![gol_p](content/images/gol_p.jpg) --

![gol2_p.jpg](content/images/gol2_p.jpg)



![friends](content/images/friends.jpg)

  <br/>
  <br/>
  Thanks, Hope you enjoy the project! :)
  <br/>
  <br/>
  <br/>
  
  ## Contributing:
 all pull requests are welcome. I felt glad if you give me any suggestions. :))) [![GitHub issues](https://img.shields.io/github/issues/faridehebrahymy/Facial-Expression-Recognition%2Fissues
)](https://github.com/faridehebrahymy/Facial-Expression-Recognition/issues)
  <br/>
    <br/>

Feel free to download, clone , fork the project.

  <br/>



## Licence & copyright: 
  © farideh ebrahimi, _Computer Science<br/>
Licensed under the [MIT License](LICENSE)
  [![GitHub license](https://img.shields.io/github/license/faridehebrahymy/Facial-Expression-Recognition)](https://github.com/faridehebrahymy/Facial-Expression-Recognition/blob/main/LICENSE)



  --------
## Contact:
<a href="https://www.linkedin.com/in/farideh-ebrahimi-275195197/"><img src="https://github.com/PrudhviGNV/PrudhviGNV/blob/master/logos/linkedin.png" width="40" /> </a>  <a href="https://github.com/faridehebrahymy"><img src="https://github.com/PrudhviGNV/PrudhviGNV/blob/master/logos/github-logo.png" width="40" 
/> </a> <a href="mailto:‫farideh.ebrahymy@gmail.com‬"><img src="https://github.com/faridehebrahymy/faridehebrahymy/blob/main/logos/Gmail_Logo_512px.png" width="40" /> </a>



