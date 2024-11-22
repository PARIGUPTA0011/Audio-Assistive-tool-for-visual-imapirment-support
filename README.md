# Object-Detection-for-Visual-Impairment-Support

This repository contains the implementation of an object detection system aimed at aiding visually impaired individuals. The project utilizes YOLOv8 and Detectron2 models to detect objects, with a specific focus on Indian currency notes. The models were trained using a custom dataset sourced from Roboflow.

The findings from this research conclude that the YOLOv8 model outperforms the Detectron2 model in terms of both accuracy and efficiency.

Contributors : Pari Gupta and Prachi Jindal

# Project Overview
Visual impairment limits access to vital information in the surrounding environment. This project addresses this challenge by providing a system that identifies objects (Indian currency notes) and communicates their identity to the user.

Key Features:
Object Detection Models: YOLOv8 and Detectron2.
Dataset: Custom Indian currency dataset from Roboflow.
Performance Comparison: Evaluated model performance using metrics like training losses i.e, class loss, box loss.

# Results and Findings
Model Performance:
YOLOv8 performed better in detecting currency notes and took less time for training.
Detectron2, while robust and was more effective in object segmentation , required longer training time and performed comparatively lower in specific applications.
Training and Validation:

Training parameters like loss, learning rate, and precision were monitored to ensure optimal performance.
The dataset included multiple annotations for accurate detection.

# Training Details
Training Parameters:
Epochs: 10
Optimizer: SGD (Detectron2), AdamW (YOLOv8)
Hardware Used: NVIDIA GPU (Google colab)
Training Metrics Graph: 

YOLOv8 :  

![Screenshot 2024-11-22 133021](https://github.com/user-attachments/assets/dcbf770b-77f9-4341-98cf-46211094f8b0)


Detectron2 model : 

![image](https://github.com/user-attachments/assets/2a768ef5-8408-4b92-b96b-f9465702c053)
![image](https://github.com/user-attachments/assets/cf174540-7a63-4d93-a457-b299f673fb0e)


# Sample Detections

Below are sample outputs showcasing the detection capabilities of the models:

YOLOv8 Detection:

![image](https://github.com/user-attachments/assets/d6dd31c6-f874-4188-a267-d3cdef66e08a)

Detectron2 Detection:

![image](https://github.com/user-attachments/assets/3ea12f3a-ff98-426b-820d-cb3890c25554)

