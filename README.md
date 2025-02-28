# parikar
![Analysis-of-Meteorites](https://github.com/C-s-on/parikar/blob/main/gfx/home.jpg)

## Introduction:
The "Parikar" project is a mobile app designed to classify 12 distinct types of Nepali cuisine using transfer learning with YOLOv8, InceptionV3, and VGG16 models. It addresses the gap in existing food classification systems that predominantly focus on global cuisines, lacking the specificity needed to recognize Nepali dishes accurately. It is developed using Flutter and Dart. It allows users to identify Nepali dishes by using their smartphone cameras. The models are converted into TensorFlow Lite format for efficient use on mobile devices.

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

## Problems Solved:
The project addresses the limitations of existing systems in accurately recognizing and categorizing Nepali dishes. It provides an easy-to-use phone app that can identify Nepali food.

## Results:
The team was able to implement the exported model with a Flutter app and achieve over 90% accuracy with all three models.

## Limitation:
It was challenging to find all the data sets because they were not commercially available on the Internet. We had to manually click the photo and scrape the dataset online. The model could detect only one type of food within a frame, limiting its capacity to accurately identify multiple foods simultaneously.

## Conclusion:
Parika serves as a technological bridge, promoting Nepali culinary heritage through efficient food recognition. The project intends continuous database enrichment for expanded coverage and improved accuracy in identifying Nepali dishes.

## Outcome:
The expected outcome is a precise and accessible app that aids in cultural awareness and dietary choices for users.
