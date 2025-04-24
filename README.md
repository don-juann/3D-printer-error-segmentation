# Training a YOLOv11 Segmentation Model for Detecting Errors in the 3D Printing Process
## Overview
This notebook demonstrates the use of YOLOv11, a computer vision model architecture developed by Ultralytics, the creators of YOLOv5 and YOLOv8. 
YOLOv11 supports a variety of tasks, including object detection, segmentation, classification, keypoint detection, and oriented bounding box (OBB) detection.

## Training Attempts

### Attempt #1
- Model: YOLOv11l-seg
- Epochs: 300
- Result: Failed at epoch 238 due to insufficient GPU resources
- Metrics: None

### Attempt #2
- Model: YOLOv11l-seg
- Epochs: 120
- Result: No metrics obtained (Model too large, decided to test the s-version of YOLOv11-seg)
- Metrics: None
  
### Attempt #3
- Model: YOLOv11s-seg
- Epochs: 250
- Result: Failed at epoch 244 due to insufficient GPU resources
- Metrics: None

### Attempt #4 (Successful attempt)
- Model: YOLOv11s-seg
- Epochs: 240


Metrics:
- Dice Coefficient: 0.4264
- Precision: 0.5064
- Recall: 0.4762
- F1-score: 0.4264
