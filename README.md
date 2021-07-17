# EMOJIFY - Detecting facial emotions 

This is a project where Convolutional Neural Networks for image classification are used.

The FER2013 dataset consists of **48x48** pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). [link to the dataset](https://data-flair.training/blogs/create-emoji-with-deep-learning/)

After the model has been trained, for testing it on real world examples, we add the functionality to capture images from the computer's webcam. We have used OpenCV and face_recognition for this. The library would automatically detect the user's face, and then we preprocess the captured image into the required format. 
