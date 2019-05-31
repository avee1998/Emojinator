# Emojinator
#Taught very well at Eckovation Machine Learning Course
(https://www.eckovation.com/course/machine-learning-value-package ), 
this code helps you detect and predict emojis from gestures you make in webcam using Convnets.
The techniques used are Deep Neural networks for prediction and OpenCV for pre-processing of images.
For pre-processing we read the images in grayscale format for 2-D images rather than 3-D (if we read in RGB).
We trained the model on images after resizing it to 50x50x1.
The Basic Architecture of Project:
 	Conv -> MaxPool -> Conv -> MaxPool -> Flatten -> Dense -> Dense ->O/P
Due to some problems with my system i have used Theano Backend and Keras for the implementation.
Division of generated dataset:
Train(12000 images) 
Test  (1199 images)  
Some add-ons:
One can add more layers.
More epochs(4 used) can be used.
Regularisation param(Dropout) can be tweaked to avoid overfitting.
	More images can be generated for enhancement of accuracy.
Procedure :
1. First, you have to create a gesture database. For that, run generate_dataset.py. Enter the gesture name and gesture for that emoji.
2. Repeat this for all the features you want. 
3. Run gesture_to_csv.py for converting the images to a CSV file. 
4. If you want to train the model, run train_model_emoji.py 
5. Finally, run Predict_emoj.py for testing your model via webcam. 
Case:
1. This project can be useful for getting insight to CNN based Deep Neural networks, also for a decent intuition to Opencv for image processing and optimise the task of training and generating the dataset.
2. Given the rise of digital communication via text, emoji have become key to communicate emotions. In digital communication, emoji serve the purpose of translating emotions to express facial expressions.  
