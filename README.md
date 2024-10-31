# Comparative Analysis of YOLO Models for Military Aircraft Detection

## Overview
This repository contains a comparative analysis of different versions of the YOLO (You Only Look Once) model, specifically YOLOv8, YOLOv9, YOLOv10, and YOLOv11. The objective of this analysis is to evaluate the performance of these models on a military aircraft detection dataset.

## Dataset
The dataset used for this project is sourced from Kaggle. You can access and download it using the following link: [Military Aircraft Detection Dataset](https://www.kaggle.com/datasets/a2015003713/militaryaircraftdetectiondataset).

## Model Performance(epochs = 30, batch_size = 16)
In our comparative analysis, YOLOv11 consistently demonstrated the best performance across key metrics:

- **Precision**: 0.781
- **Recall**: 0.617
- **mAP@50**: 0.727
- **mAP@50-95**: 0.653

These results indicate that YOLOv11 is the most effective model for accurately detecting objects and offers the best overall balance between precision and recall. Therefore, it is deemed the most suitable model for military aircraft detection in our experiments.

## Contact

For any questions or inquiries, please contact(mail to : karbiswajit396@gmail.com)

## Installation and Usage
1. Clone this repository:
   ```bash
   git clone <repository-url>
