# VR_MiniProject1: Multi-Object Apparel Detection and Instance Segmentation

## Objective
Detect, classify, and segment multiple clothing items in a single image using deep learning, based on visual attributes such as garment type, shape, texture, and spatial location.

---

## Overview
This project focuses on a multi-task visual recognition pipeline built on the DeepFashion2 dataset. It includes:

- **Multi-Label Classification**
- **Object Detection + Instance Segmentation**

The models are trained on the most frequently occurring apparel categories.

---

## Models Used

### 🔹 Classification

#### ResNet-50
- Notebook: `Classification/resnet-final.ipynb`
- Includes:
  - Training from scratch  
  - Transfer Learning  

#### MobileNetV3 & EfficientNet
- Notebook: `Classification/vr-classification.ipynb`
- Includes:
  - Training from scratch  
  - Transfer Learning  

---

### 🔹 Detection & Segmentation

#### YOLO
- Notebook: `Segmentation/yolo_final.ipynb`
- Includes:
  - Training from scratch  
  - Transfer Learning  

#### Mask R-CNN
- Notebooks:
  - `Segmentation/vr-mask-rcnn-transfer_learning.ipynb`
  - `Segmentation/vr_mask_rcnn_scratch.ipynb`

#### U-Net
- Notebooks:
  - `Segmentation/unet-scratch.ipynb`
  - `Segmentation/unet-transfer-learning.ipynb`

---

## Project Structure
VR_MiniProject1/
│
├── Classification/
│ ├── resnet-final.ipynb
│ ├── vr-classification.ipynb
│
├── Segmentation/
│ ├── unet-scratch.ipynb
│ ├── unet-transfer-learning.ipynb
│ ├── vr-mask-rcnn-transfer_learning.ipynb
│ ├── vr_mask_rcnn_scratch.ipynb
│ ├── yolo_final.ipynb
│
├── preprocessing/
│ └── (data preprocessing scripts / notebooks)
│
├── VR_Report.pdf
├── README.md


---

## Report
Read the full report here: **[Report Link]**

---

## Inference Code
Hugging Face deployment code: **[Code Link]**

---

## Notes
- `resnet-final.ipynb` contains both **scratch training** and **transfer learning** implementations.
- `vr-classification.ipynb` includes **MobileNetV3** and **EfficientNet**, both with **scratch** and **transfer learning**.
- `yolo_final.ipynb` includes both **scratch training** and **transfer learning**.
- Each notebook is self-contained with training, evaluation, and results.
