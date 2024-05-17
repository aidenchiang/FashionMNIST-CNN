# FashionMNIST-CNN
A CNN model for the FashionMNIST dataset.

Model Architecture:
|Layer                     | # of Params |
--------------------------|:-----------:|
CNN (+ ReLU + Max Pooling)|     160     |
CNN (+ ReLU + Max Pooling)|    4640     |
CNN (+ ReLU + Max Pooling)|    18496    |
FC (+ ReLU)               |    1.05M    |
FC (+ Softmax)            |    10250    |


Model Accuracy

| Data Subset       | Accuracy|
--------------------|:-------:|
Training Accuracy   | 100.00% |
Validation Accuracy | 92.92%  |
Testing Accuracy    | 92.22%  |

Findings: After < 10 epochs, the validation accuracy plateaued at ~92%, whereas the training accuracy kept climbing to 100%. This would suggest overfitting, which could be resolved for example, by adding/increasing regularization among many other techniques used to address overfitting.



This is part of an assignment for the STAT 453 class Introduction to Deep Learning and Generative Models taught by Professor Yiqiao Zhong during the Spring 2024 semester at UW-Madison
