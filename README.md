# parikar
<p align="left">
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/sq_home.jpg" width="200"/>
</p>

## Introduction:
The "Parikar" project is a mobile app designed to classify 12 distinct types of Nepali cuisine using transfer learning with YOLOv8, InceptionV3, and VGG16 models. It addresses the gap in existing food classification systems that predominantly focus on global cuisines, lacking the specificity needed to recognize Nepali dishes accurately. It is developed using Flutter and Dart. It allows users to identify Nepali dishes by using their smartphone cameras. The models are converted into TensorFlow Lite format for efficient use on mobile devices.

## Table of Contents
- [Introduction](#introduction)
- [Objectives](#objectives)
- [Features](#features)
- [Background](#background)
- [Methodology](#methodology)
- [Results](#results)
- [Appendix](#appendix)
- [Conclusion](#conclusion)
- [Outcomes](#outcomes)
- [Resources](#resources)

## Objectives:
* To design and implement a Nepali food classification system that can accurately categorize various Nepali dishes.
* To create a strong dataset of Nepali food cuisine.
* To create a user-friendly classification app.

## Features:
* Model Selection Toggle: Allows users to switch between different models for accurate identification.
* User-Friendly Interface: An intuitive interface ensures accessibility for all users.
* Detailed Food Information: Provides additional information about the detected food, including its background, recipe, and ingredients.
* Location-Based Food Suggestions: Suggests nearby locations where the detected food might be available.
* Presence of Null Class: Includes a "null class" for items outside recognized food categories, helping the model discern known foods from unrecognized ones.

## Background:
Existing food classification systems lack the specificity and diversity needed to capture the nuances of Nepali culinary diversity effectively. This project aims to address this gap by creating a system specifically tailored to identify and celebrate the unique flavors and ingredients of Nepali dishes. Recent trends in classification include the use of TensorFlow and Transfer Learning for food classification with Convolutional Neural Networks (CNNs).

## Methodology:
The "Parikar" project uses transfer learning with YOLOv8, InceptionV3, and VGG16 models to classify 12 types of Nepali food. The models are converted to the TensorFlow Lite format for mobile use. An ImageDataGenerator is used for data augmentation and preprocessing, and the data is split into training and validation sets. The goal is to develop a user-friendly mobile app with Flutter and Dart that can accurately identify Nepali dishes using smartphone cameras.

## Results:
We were able to implement the exported model with a Flutter app and achieve over 90% accuracy with all three models.
### InceptionV3
<p align="center">
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/v3_tv_accuracy.png" width="400"/>
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/v3_tv_loss.png" width="400"/>
</p>

### VGG16
<p align="center">
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/vgg_tv_accuracy.png" width="400"/>
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/vgg_tv_loss.png" width="400"/>
</p>
<p align="center">
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/vgg_confusion_matrix.png" width="700"/>
</p>


## Appendix:
<p align="center">
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/start.jpg" width="200"/>
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/classify.jpg" width="200"/>
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/select_model.jpg" width="200"/>
</p>

<p align="center">
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/select_image.jpg" width="200"/>
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/momo_2.jpg" width="200"/>
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/pizza.jpg" width="200"/>
</p>

<p align="center">
  <img src="https://github.com/C-s-on/parikar/blob/main/gfx/info.jpg" width="200"/>
</p>

## Conclusion:
Parika serves as a technological bridge, promoting Nepali culinary heritage through efficient food recognition. The project intends continuous database enrichment for expanded coverage and improved accuracy in identifying Nepali dishes.

## Outcome:
Precise and accessible app that aids in cultural awareness and dietary choices for users.

## Resources
1. Python Documentation - https://docs.python.org/3/tutorial/index.html
2. Ipython Documentation - https://ipython.org/documentation.html
3. Plotly Documentation - https://plotly.com/python/
4. Tensorflow Documentation - https://www.tensorflow.org/api_docs
5. Flutter Documentation - https://api.flutter.dev/
6. Keras Documentationion - https://keras.io/api/
7. MongoDB Documentation - https://www.mongodb.com/docs/
