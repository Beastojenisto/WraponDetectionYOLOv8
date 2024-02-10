# Weapon Detection using YOLOv8

This repository contains code for training a YOLOv8 (You Only Look Once) model for object detection, a pre-trained YOLOv8 model, code for a web application utilizing the trained model, and the dataset used for training.

## Overview

- `weapondetection.ipynb`: Contains scripts and configuration files for training a YOLOv8 model.
- `GunDetector.pt`: Is a pre-trained YOLO model for object detection.
- `kaggle/working/Weapon-Detection-2`: Contains the dataset used for training the YOLO model.

## Dataset

The dataset used for training the YOLO model is available in the `kaggle/working/Weapon-Detection-2` directory. It consists of images annotated with bounding boxes for various objects. The dataset is structured in a format suitable for training YOLO models. The dataset is not mine. You can find the dataset [here](https://universe.roboflow.com/fypit2/weapon-detection-mhdza)

## YOLO Training

The `weapondetection.ipynb` contains scripts and configuration files for training a YOLO model. Follow the instructions in the `README.md` file to train the model using your dataset.

## Trained Model

The `GunDetector.pt` contains a pre-trained YOLO model for object detection. This model can be used directly for inference or fine-tuned on a custom dataset if needed.

## Usage

1. Train a YOLO model using your dataset by running the code in the `americansignlanguagedetector.ipynb` file.
2. Alternatively, you can use the pre-trained YOLO model provided in the `HandSignDetector.pt` file.
