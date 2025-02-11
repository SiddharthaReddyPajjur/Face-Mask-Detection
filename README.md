# Face Mask Detector  

## Overview  
The **COVID-19 Mask Detector** is designed to help ensure safety by detecting whether a person is wearing a mask or not.  
This project employs a simplified approach using fundamental **Machine Learning** techniques with **TensorFlow, Keras, and OpenCV**.  
It accurately detects faces in an image and determines whether a mask is present.  

The goal is to build a robust solution that works across varying **distances**, **lighting conditions**, and **color combinations**, ensuring high accuracy in real-world scenarios.  

## Dataset  
A total of **1143 images** were used for training, and **286 images** for validation. These images were categorized into two classes:  
- **With Mask**  
- **Without Mask**  

Dataset link: [FFHQ Dataset](https://github.com/NVlabs/ffhq-dataset)  

## Model Results  
The final trained model achieved:  
✅ **99.36% accuracy** and **0.0285 loss** on the training dataset  
✅ **98.97% accuracy** and **0.0396 loss** on the validation dataset  
The model performs exceptionally well for **live detection via webcam**.  

## Demo  
Below is an example of the mask detection model in action:  

![Mask Detection Demo](https://camo.githubusercontent.com/298fc06975ef30d8972a6fa29a9a771f78db048d325a25897d9fe2af5844bea9/68747470733a2f2f6173736574732e6c6f737370726576656e74696f6e6d656469612e636f6d2f75706c6f6164732f323032302f30372f4d61736b2d446574656374696f6e2d31323830783732302d312e6a7067)  
