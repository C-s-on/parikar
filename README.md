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
- [Results and appendix](#results)
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

## Results and appendix:
We were able to implement the exported model with a Flutter app and achieve over 90% accuracy with all three models.
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
2. Seaborn Documentation - https://seaborn.pydata.org/tutorial.html
3. Pandas Documentation - https://pandas.pydata.org/docs
4. Numpy Documentation - https://numpy.org/doc/stable
5. Matplotlib Documentation - https://matplotlib.org/stable/tutorials/index
6. Ipython Documentation - https://ipython.org/documentation.html
7. Plotly Documentation - https://plotly.com/python/
