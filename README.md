# Age_Detection
Age detecteion of Indian Actors 
A contest from Analytics Vidhya : https://datahack.analyticsvidhya.com/contest/practice-problem-age-detection/

Problem Statement : Classifying faces of Indian film actors/actresses according to their age. Images are taken from IMFDB (http://cvit.iiit.ac.in/projects/IMFDB/)

Main libraries used: Keras, sklearn, scipy etc

Experimented with,
1)Deep CNN's with Data Augmentation,Dropout,BatchNormalization
  -Used advanced activation layers like LeakyRelu

2)Transfer learning using DenseNet169
  -Removed fully connected layers of DenseNet
  -Added classifier on top of convolution base
