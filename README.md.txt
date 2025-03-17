# Camouflaged Weapon Detection with YOLOv8n

This project implements a camouflaged weapon detection system using the YOLOv8n model, achieving **92% mAP@50** and **60% mAP@50:95** on an augmented dataset. Developed as a computer vision learning project, it showcases effective detection of camouflaged weapons starting from limited initial data.

## Project Overview
- **Objective**: Detect camouflaged weapons in images using YOLOv8n, a lightweight object detection model.
- **Dataset**: 
  - Original: 35 images per class (weapon/no-weapon), totaling 70 images.
  - Augmented: Expanded to 500 images per class (1000 total) using Albumentations.
- **Results**:
  - mAP@50: 92% - Near-perfect detection accuracy at IoU=0.5.
  - mAP@50:95: 60% - Robust localization across IoU 0.5 to 0.95.
- **Tools**: OpenCV, YOLOv8 (Ultralytics), Albumentations, Labelme.


*Note*: Raw and augmented data are included to imporvise the project and facilitate involvement of ideas of other people.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/thetruth65/CAMOUFLAGED_WEAPON_DETECTION-USING-YOLOv8n-LABELME-ALBUMENTATIONS-OPENCV.git
   cd CAMOUFLAGED_WEAPON_DETECTION-USING-YOLOv8n-LABELME-ALBUMENTATIONS-OPENCV
