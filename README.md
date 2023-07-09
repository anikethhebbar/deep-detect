# Deepfake Detection System

This repository contains a deepfake detection system that utilizes a deep learning model to identify and classify deepfake videos. The system extracts frames from videos, detects faces, and analyzes the probability of fakeness for each detected face using the InceptionResNetV2 architecture.

## Features

- Capturing images from videos and preprocessing them for model training
- Training a deep learning model using the InceptionResNetV2 architecture
- Evaluating the model's performance through accuracy and loss metrics
- Applying the trained model to detect deepfakes in videos
- Classifying videos as REAL, FAKE, or POSSIBLY FAKE based on the detection results.
