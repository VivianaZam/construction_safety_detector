# Construction Safety Detector

## Project Overview
The Construction Safety Detector is a computer vision application designed to identify important personal protective equipment (PPE) on construction workers.

The system will analyze construction-site images and detect:
- People
- Hard hats / helmets
- Safety vests

## Problem
Construction workers may enter hazardous work areas without required PPE. Manually monitoring workers can be difficult, especially on large job sites.

## Proposed Solution
The application will use object detection to analyze an image and identify workers and visible safety equipment.

Input → Object Detection Model → PPE Detections → Output Image

## Technical Approach
- Computer Vision Technique: Object Detection
- Model: YOLO
- Framework: Ultralytics
- Programming Language: Python
- Compute Environment: Google Colab

## Data Plan
A public construction safety / PPE image dataset will be used. The dataset will contain labeled images of workers, hard hats, and safety vests.

More information about the dataset will be documented in the `data/README.md` file.

## Success Metrics
- Target at least 80% performance using an appropriate object detection metric.
- Target image processing time of approximately one second or less.

## Project Milestones
1. Select and inspect dataset
2. Prepare data
3. Configure object detection model
4. Train model
5. Evaluate detections
6. Build demonstration
7. Test final application
8. Prepare final presentation

## Risks
Possible risks include inconsistent training data and long model training times. Backup plans include using an alternate public PPE dataset and using transfer learning with a pretrained YOLO model.

## Estimated Cost
$0 using free Google Colab resources.
