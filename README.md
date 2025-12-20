# Smart Dustbin using YOLOv8n

## Abstract
This project presents a Smart Dustbin system powered by the YOLOv8n object detection
model to automatically identify and classify waste. The system uses computer vision
and deep learning to detect trash in real time, enabling intelligent waste management
and supporting smart city applications.

The complete model training, validation, and testing were performed using Google Colab.

---

## Problem Statement
Traditional waste segregation is manual, inefficient, and error-prone. Improper waste
classification leads to environmental pollution and reduced recycling efficiency.
An automated and intelligent waste detection system is required to improve accuracy
and reduce human intervention.

---

## Proposed Solution
The proposed Smart Dustbin uses the YOLOv8n deep learning model to detect and classify
waste objects from images. The lightweight nature of YOLOv8n makes it suitable for
real-time applications and embedded system integration.

---

## System Workflow
1. A camera captures an image of the waste.
2. The image is passed to the YOLOv8n model.
3. The model detects waste objects using bounding boxes.
4. The detected class is used to trigger further actions such as lid control or sorting
   (hardware integration can be added).

---

## Machine Learning Model
- Model Used: YOLOv8n (You Only Look Once – Nano)
- Learning Type: Supervised Learning
- Task: Object Detection
- Outputs: Bounding boxes, class labels, confidence scores
- Training Platform: Google Colab

---

## Dataset Description
- The dataset consists of labeled waste images.
- Each image is annotated with bounding boxes in YOLO format.
- The dataset is split into training and validation sets.
- Dataset is not uploaded to GitHub due to size limitations.

---

## Technologies Used
- Python
- YOLOv8n
- OpenCV
- NumPy
- PyTorch
- Ultralytics
- Google Colab

---

## Files in This Repository
- `Untitled5.ipynb` : YOLOv8n training and testing notebook
- `requirements.txt` : Required Python dependencies
- `best.pt` : Trained YOLOv8n model weights (if included)

---

## How to Run the Project
1. Clone the repository:

