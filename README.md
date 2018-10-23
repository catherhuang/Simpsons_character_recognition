# Simpsons Character Recognition

# Goal
Identify Simpsons Characters with Artificial Neural Network.

Data resouce: https://www.kaggle.com/alexattia/the-simpsons-characters-dataset

# Setup & Clean up
The dataset contains approximately 20000 images from the Simpsons. Since the number of images for each of the top 20 characters is not evenly distributed, we choose the top 10 characters with the most images. To ensure that our dataset is clean, we manually checked the training set to make sure the images are labeled correctly, and that each image only shows the specific character specified. The remaining characters are identified as others. 

# Convolutional Neural Networks
Created multiple CNN to generate the most efficiently model to identify Bart, Homer, Marge, Lisa, Principal Skinner, Moe, Milhouse, Krusty, Burns, and Others

# Convolutional Neural Networks with Image Augmentation 
To increase the accuracy of the model performance, added image augmentations to increase the variations of the image set for each of the characters. 

# Testing the model performance 
Using a separate set of images to demonstrate the model's performance at recognizing character. 

# Transfer Learning
#### https://www.youtube.com/watch?v=COlbP62-B-U&vl=en
Utalized a pre-trained SSD Mobile Net for object detection. We annotated individual frames of Bart Simpsons in training set, and trained the SSD architecture using these images to recognize Bart in a video. We ran the trained model on each frame of the video clip, and re-complied the video with the object detection model built in.



