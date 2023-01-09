# Sign-Language-Interpreter
Indian Sign Language Interpreter using CNN and Google Speech API.

Project Details:

The basic purpose of the project is to recognize all the alphabets (A-Z) and digits (0-9) of Indian
Sign Language and convert them to text/speech. 
The system is tested using various machine learning classifiers like KNN, SVM, Logistic Regression and 
a Convolutional Neural Network (CNN) is also implemented for the same. 
Inversely, the spoken word is taken as input and the corresponding sign images are shown
to achieve dual communication using Google speech API. 
The dataset for this system is created manually in different hand orientations and 
a train-test ratio of 80:20 is used.

Tech Stack:
Python3, Opencv, Tensorflow, Keras, Bag of Visual
Words, Google speech API

Primary Algorithm:
Bag of Visual Words, CNN

Features Implemented:

1. Sign Interpretation:
Detecting and recognising Indian Sign Language Signs and corresponding sequence of alphabets/digits
are shown in the form of text as well as speech .
2. Speech Interpretation:
The spoken word is taken as input and the corresponding sign images are shown.
3. Incorporating custom signs:
Users can add custom signs to the system easily
