#SRISHTI-24 ASSIGNMENT
# Semantic Segmentation Challenge: Indian Driving Dataset(IDD)

## Description

This initiative aims to enhance comprehension of road environments in complex settings. The dataset encompasses imagery taken by a forward-facing vehicle camera across urban and suburban landscapes of Hyderabad and Bangalore.

## Task

The Semantic Segmentation Challenge: Indian Driving Dataset (IDD) aims to advance the understanding of road scenes in diverse environments. Leveraging the IDD Lite dataset captured in urban areas like Hyderabad and Bangalore, participants predict pixel-level labels for seven classes: Drivable, Non-Drivable, Living things, Vehicles, Roadside objects, Far objects, and Sky. The Mean Intersection over Union (mIoU) metric evaluates model performance. With 1403 training, 204 validation, and 404 test images, the challenge fosters innovation in semantic segmentation for urban scene understanding, benefiting autonomous driving and urban planning.

## Type of Problem

Semantic Segmentation

## Performance Metric

Mean Intersection over Union (mIoU)

## Dataset Overview

- Input image and segmentation masks dimensions: [227, 320, 3]
- Train: 1403 images
- Validation: 204 images
- Test: 404 images

## Methods and Results

UNet achieved an mIoU of 0.72 on Train and 0.61 on Validation data.

