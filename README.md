# Deepfake Detection System

This repository contains a deepfake detection system that utilizes a deep learning model to identify and classify deepfake videos. The system extracts frames from videos, detects faces, and analyzes the probability of fakeness for each detected face using the InceptionResNetV2 architecture.

## Features

- Capturing images from videos and preprocessing them for model training
- Training a deep learning model using the InceptionResNetV2 architecture
- Evaluating the model's performance through accuracy and loss metrics
- Applying the trained model to detect deepfakes in videos
- Classifying videos as REAL, FAKE, or POSSIBLY FAKE based on the detection results.
## Dataset
https://www.kaggle.com/competitions/deepfake-detection-challenge/data
## Folder Structure

The file structure for this project is as follows:
``` bash
├── dataset/
│ ├── fake/
│ │ ├── fake_image_1.png
│ │ ├── fake_image_2.png
│ │ └── ...
│ └── real/
│ ├── real_image_1.png
│ ├── real_image_2.png
│ └── ...
├── model/
│ └── deepfake-detection-model.h5
├── deepfake_detection.ipynb
├── train_sample_videos/
│ ├── metadata.json
│ ├── video1.mp4
│ ├── video2.mp4
│ └── ...
├── test_sample_videos/
│ ├── video1.mp4
│ ├── video2.mp4
│ └── ...
└── requirements(installed alongside ipynb)
```
