# YoloV4

## Note: The darknet directory is too big to be uploaded so please download it from the below link and extract it into the yolov4 directory like in the repository.
https://drive.google.com/file/d/1CfC1RizWKzspagXzKitfo1wMQFoqTlgw/view?usp=sharing

This repository contains the code for darknet yolov4, ready to be trained on our custom drone detection dataset.  
All the necessary files are in the yolov4 directory and are also copied to the darknet directory.  
Here is info about the files:  
1) drone_detection_yolov4.ipynb notebook contains code for making the darknet and for initializing training.  
2) obj.data file contains number of classes and path to train.txt, test.txt, obj.names, and to the backup folder.   
3) obj.names contains name of all the 12 classes.  
4) process.py script split the dataset into 70-30 ratio for training and testing. It creates train and test text files that contain path to training and testing images.  
5) train.txt file contains path to training images.  
6) test.txt file contains path to testing images.  
7) yolov4-custom.cfg file contains the yolov4 architecture and hyperparameter values.   
     
Please make changes to obj.data files according to your own system paths.  
In case of any missing files in darket directory or updating any above files, please uncomment that particular code cell in jupyter notebook to update the respective file.
