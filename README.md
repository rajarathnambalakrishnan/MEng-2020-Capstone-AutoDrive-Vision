# Image-Recognition-for-Autonomous-Driving
UC Berkeley MEng 2019 -2020 Capstone Project

#### Team Members:
#### Rajarathnam Balakrishnan | UC Berkeley MEng '20(IEOR)|rajarathnam_b@berkeley.edu
#### Tianrui Huang |  UC Berkeley MEng '20(IEOR)
#### Xeuqi Zhao |  UC Berkeley MEng '20(IEOR)
#### Xinyue Liu |  UC Berkeley MEng '20(IEOR)

The main obejctive of this project is to build an image recognition algorithm that detects vehicles and pedestrians for autonomous driving use case with **mAP >= 0.5**.


## STAGE 1 : Image Recognition Algorithm based on Pre-trained Network 
The sole reason to use a pre-trained neural network is to provide a sense of code structure and to understand what the result looks like. This work would help the team to assess the range of changes that are required for **Stage 2**.

### STAGE 1.1 : Vehicle Detection
The image recognition algorithm (pre-trained neural net) would be trained to identify **vehicle or not** classification only.

### STAGE 1.2 : Pedestrian Detection
The image recognition algorithm (pre-trained neural net) would be trained to identify **pedestrian or not** classification only.

## STAGE 2 : Image Recognition Algorithm based on Custom Trained Neural Network 
This stage of the capstone project is about building on Stage-1's results and train the convolutional neural network from the scratch along with the object detection module (YOLO). The results of this stage would be compared and contrasted with the results of Stage-1.

## STAGE 2.1: Vehicle detection
The convolutional neural network responsible for feature extraction and classification would be trained on image datasets of **vehicle classes** only. Then the trained neural network would be connected to the object detection module to further train the model to identify and predict the position of the vehicle class objects in a general image dataset (image datasets for autonomous driving research) to form the complete neural network architecture. 

## STAGE 2.2: Pedestrian detection
The convolutional neural network responsible for feature extraction and classification would be trained on image datasets of **pedestrian classes** only. Then the trained neural network would be connected to the object detection module to further train the model to identify and predict the position of the pedestrain class objects in a general image dataset (image datasets for autonomous driving research) to form the complete neural network architecture. 

## STAGE 3: Combining the two detection models based on the understanding gained from previous stages 1 and 2.
The combined model would then be trained on multiple datasets to tune its performance and compute the final mAP score.
