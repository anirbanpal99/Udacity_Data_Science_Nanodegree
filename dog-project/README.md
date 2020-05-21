[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

Welcome to the Convolutional Neural Networks (CNN) project. In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, your algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

Along with exploring state-of-the-art CNN models for classification, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience!

## Datasets

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  

2. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  

3. Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  

## Implementation

I have used several technologies here:
<ul>
	<li><b>OpenCV: </b>It is used to read the images.</li>
	<li><b>Haarcascade Classifier: </b>It is used to identify the face of the images.</li>
	<li><b>CNN: </b>It is used to classify the dog breeds.</li>
</ul>

## Conclusion

This project helps to classify the dog breed. The main pros of this project is that it can also identify whether the image is of a dog or of a human. I have written on blog on this project you can have a look on it. To see the bolg click <b><a href="https://medium.com/@anirban345678/best-algorithm-to-classify-dog-breed-8feef13f9753">here</a></b> 
