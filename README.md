# How Different Types of Deep Learning Models Performs on Face Mask Detection
#### CS7643 Final Project 
#### Group members: Tianxue Hu, Chenjun Tang, Danrong Zhang 
With the spreading of COVID-19, face mask has becomea  regular  item  for  our  daily  life.   With  the  reopening  ofrestaurants and business, face mask is essential to stop the spread of COVID-19 and protect people’s health. Everyone should wear face mask in public places in order to protect both ourselves and  others under this special situation. However, how to detect whether people are wearingface mask or not? In this paper, we are going to detectface mask with the help of deep learning method. We first gathered the pictures with different people with and without mask. Then, we explored different different models including VGG, ResNet, GoogleNet and DenseNet. With the con-volutional neural network built by ourselves, we reached theaccuracy of 0.84. We show that with our final model with VGG16 reached the accuracy of 0.98. In this regard we can generate a reliable face mask detector which can be used in public places to help remind people wearing masks.<br>

## Tools 
    * torch
    * torchvision
    * sklearn

## Folder Structure
**dataset** contains the data we use for our model. The first source is Real-world Masked Face Dataset(RMFD). 5000 masked faces and 90,000 unmasked faces are consisted in the RMFD dataset. The second source is from Kaggle. We downloaded the picture of people wear face mask to increase the percentage of masked faces. We can get the dataset from https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset and https://www.kaggle.com/andrewmvd/face-mask-detection<br>
<br>
**mask_detect_exp.ipynb** is the source code for processing data and train the model. The notebook was originally built in Google Colab, to run the notebook, please change file paths to the corresponding directory/folder. <br>
<br>
**Report.pdf** is the report of this project.<br>
