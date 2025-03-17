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
- **Tools**: OpenCV, YOLOv8n (Ultralytics), Albumentations, Labelme.


SOME OUTPUT IMAGES:

![image](https://github.com/user-attachments/assets/81cf0b8d-36f9-492a-ac4c-572f7a90b16a)
![image](https://github.com/user-attachments/assets/2a3f0d07-1265-44a7-9a38-f827f23c5216)
![image](https://github.com/user-attachments/assets/749f76fc-417e-42b6-9339-d62c4f03fde0)
![image](https://github.com/user-attachments/assets/8e4204e7-e74d-4e68-8a85-c3acfce54b1c)


