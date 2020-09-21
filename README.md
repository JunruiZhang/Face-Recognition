# Face Recognition Based on Deep Learning
## Introduction
Face recognition is a method that uses digital images or video frames of human faces to identify or verify the identity of a person. It has been a critical human computer interaction technique and has been widely applied in plenty of areas, such as video surveillance, identity verification, access control, public security system and even daily life.

Traditional methods are based on shallow learning. This kind of methods only use basic features of images, which have been facing many challenges, such as lighting, shadow, complexity of background, facial expression and pose variation. However, Deep learning has changed this situation. Deep learning-based methods can extract more complicated features and it is more accurate and stable.
## Problem description
Convolutional Neural Network is the most commonly used algorithm in face recognition. CNN is an artificial neural network that uses a convolution method to extract features from input data to increase the number of features. They learn multiple representations corresponding to different levels of abstraction. These levels form a hierarchical structure of concepts, showing the strong invariance of facial posture, lighting, shadow and expression changes.

The general structure of face recognition process should have three stage. The first stage is pre-processing. In this stage, we will localize faces in images, resize images, and do color space conversion. The second stage is to identify and extract face features. The last stage is to classify these feature set from previous stage. 
