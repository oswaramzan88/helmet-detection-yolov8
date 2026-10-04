# Helmet Detection using YOLOv8

## Project Overview
This project detects whether a bike rider is wearing a helmet or not, using a custom-trained YOLOv8 object detection model.

## Tools & Technologies
- Roboflow (dataset annotation)
- YOLOv8 (object detection model)
- Google Colab (model training)
- Python

## Workflow
1. Collected images of bike riders (with and without helmets)
2. Annotated images using Roboflow
3. Exported dataset in YOLOv8 format
4. Trained model on Google Colab
5. Tested model on new images

## Classes
- Helmet
- No Helmet

## Result
The model successfully detects helmet-wearing riders with bounding boxes and confidence scores.
