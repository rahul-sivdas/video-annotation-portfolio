# Video Annotation Dataset Overview

This repository contains sample datasets demonstrating video and image annotation for computer vision model training.

## Categories

### Traffic Video Annotation
Urban traffic scenes with vehicles and pedestrians.

Tasks:
- Object detection (car, truck, motorcycle, person)
- Traffic monitoring
- Pedestrian detection

### Human Activity Recognition
Office and street scenes with people performing activities.

Tasks:
- Activity recognition
- Object labeling (laptop, monitor, person)
- Scene understanding

## Annotation Format

Annotations are stored in JSON and include:
- image: filename
- annotations: list of objects with
  - label
  - bounding_box [x1, y1, x2, y2]

## Purpose

Demonstrates preparation of structured training data for AI and machine learning models using frame images and bounding-box annotations.
