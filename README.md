# YoloV4
This repository contains the code for darknet yolov4, ready to be trained on our custom drone detection dataset.  
All the necessary files are in the yolov4 directory and are also copied to the darknet directory.  
Here is info about the files:  
drone_detection_yolov4.ipynb notebook contains code for making the darknet and for initializing training.  
obj.data file contains number of classes and path to train.txt, test.txt, obj.names, and to the backup folder.   
obj.names contains name of all the 12 classes.  
process.py script split the dataset into 70-30 ratio for training and testing. It creates train and test text files that contain path to training and testing images.  
train.txt file contains path to training images.  
test.txt file contains path to testing images.  
yolov4-custom.cfg file contains the yolov4 architecture and hyperparameter values.  
please make changes to obj.data files according to your own system paths.

