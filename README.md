# Hand Gesture Detection


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/145GC1wY9dAeOz6zBKy4sh7AU0_gu7Ypj?usp=sharing)
<![![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)](https://aman-095.github.io/Hand_Gesture_Detection/)

## Overview:
The project presents a website for hand gesture detection using deep learning models. The system can be used
to recognize and classify hand gestures captured through a camera on various platforms such as desktop, and
mobile. The application uses convolutional neural network (CNN) models trained
on large datasets of hand gesture images to detect and recognize a variety of gestures. The system is
designed to be fast and efficient, allowing real-time recognition of hand gestures with high accuracy.

## Dataset Description
We are using Hand Gesture Recognition Database
for efficient training of various Deep learning models. It contains a total of 20,000 images and 10 labels named as palm, L, fist, moved, thumb, index,
ok, palm moved, C, down, each containing 2000
images. Hand gesture recognition database is composed by a set of near-infrared images acquired by
the Leap Motion sensor.
## Source of Dataset
[Hand Gesture Recognition Database](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
## Built using:
- [Scikit Learn: ](https://scikit-learn.org/stable/) ML Library used
- [TensorFlow Keras: ](https://www.tensorflow.org/api_docs/python/tf/keras) ML Libraries used
- [HTML: ](https://developer.mozilla.org/en-US/docs/Web/HTML) HTML documentation used
- [Javscript: ](https://developer.mozilla.org/en-US/docs/Web/JavaScript) Javscript framework used
- [Pandas: ](https://pandas.pydata.org/) Python data manipulation libraries
- [Seaborn: ](https://seaborn.pydata.org/) Data visualisation library
- [OpenCV2: ](https://pypi.org/project/opencv-python/) Image Preprocessing library
## Pipeline:
### [1. Gesture_Detection.ipynb](https://github.com/aman-095/Hand_Gesture_Detection/blob/main/Gesture_Detection.ipynb)
This is the main file containing EDA, preprocessing, application of various deep learning models.
- Installing libraries and dependencies
- Importing the dataset
- Exploratory Data Analysis and Visualisation
- Data Preprocessing
  - Normalisation
  - Resizing image
  - Segmentation
- Deep learning Models (CNN)
  - AutoEncoder
  - VGG 19
  - CNN Based on Research paper
  - Deployment
## How to run:
- Run the cells in main file according to above mentioned pipeline


