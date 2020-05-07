# UC Berkeley MEng 2019 -2020 Capstone Project


#### Team Members:
#### Rajarathnam Balakrishnan | UC Berkeley MEng '20(IEOR)|rajarathnam_b@berkeley.edu
#### Tianrui Huang |  UC Berkeley MEng '20(IEOR)
#### Xeuqi Zhao |  UC Berkeley MEng '20(IEOR)
#### Xinyue Liu |  UC Berkeley MEng '20(IEOR)

The main objective of this project is to build an image recognition algorithm that detects vehicles and pedestrians for autonomous driving use case.


### STAGE 1 : Classifiers - ResNet , DenseNet 
Classifiers were trained on multi-class CIFAR 10 datset to enhance the feature extraction.

**Training accuracy and loss graphs for ResNet**

![](https://github.com/rajarathnambalakrishnan/Image-Recognition-for-Autonomous-Driving/blob/master/res_acc.png)

![](https://github.com/rajarathnambalakrishnan/Image-Recognition-for-Autonomous-Driving/blob/master/res_loss.png)

**Training accuracy and loss graphs for DenseNet**

![](https://github.com/rajarathnambalakrishnan/Image-Recognition-for-Autonomous-Driving/blob/master/dens_acc.png)

![DenseNet Training Loss Graph](https://github.com/rajarathnambalakrishnan/Image-Recognition-for-Autonomous-Driving/blob/master/dens_loss.png)


### STAGE 2. Detection - Inspired from YOLOv2
Attach the detection networks to an already trained classifier and then again train for detection.
