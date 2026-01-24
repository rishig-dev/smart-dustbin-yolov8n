# ♻️ Waste Detection and Classification using YOLOv8

An end-to-end **Computer Vision & Deep Learning project** that performs **waste (trash) detection and classification** using **YOLOv8**. This project is trained on the **TrashNet dataset** and demonstrates how AI can be used for **smart waste management and environmental sustainability**.

---

## 📌 Table of Contents

* Overview
* Problem Statement
* Objectives
* Features
* Dataset Description
* Project Structure
* Tech Stack
* Model Used
* Workflow
* Installation & Setup
* How to Run the Project
* Training & Evaluation
* Results
* Applications
* Limitations
* Future Enhancements
* Author

---

## 🔍 Overview

Improper waste segregation is a major environmental challenge. Manual sorting of waste is inefficient, unsafe, and error-prone. This project uses **YOLOv8 (You Only Look Once)**, a state-of-the-art object detection model, to automatically **detect and classify waste items** such as plastic, paper, glass, metal, cardboard, and trash.

The system can be extended to **smart bins, recycling plants, and smart cities**.

---

## ❓ Problem Statement

Manual waste classification:

* Is time-consuming
* Leads to incorrect segregation
* Requires human labor in unsafe environments

The goal of this project is to **automate waste detection and classification** using deep learning and computer vision.

---

## 🎯 Objectives

* To build an automated waste detection system
* To prepare a dataset suitable for object detection
* To train a YOLOv8 model on waste images
* To evaluate model performance
* To demonstrate AI for environmental sustainability

---

## ✨ Features

* Uses YOLOv8 for real-time object detection
* Trained on TrashNet dataset
* Automatic dataset preparation (train/val split)
* Bounding box annotation support
* High-speed and accurate detection
* Google Colab compatible

---

## 🗂 Dataset Description

**Dataset:** TrashNet (resized version)

### Classes

* Trash
* Plastic
* Paper
* Glass
* Metal
* Cardboard

### Dataset Processing

* Images extracted from ZIP file
* Converted into YOLO format
* Split into training and validation sets

---

## 📂 Project Structure

```
Waste-Detection-YOLOv8/
│
├── Untitled5.ipynb          # Main training notebook
├── dataset/
│   ├── images/
│   │   ├── train/
│   │   └── val/
│   └── labels/
│       ├── train/
│       └── val/
├── data.yaml               # YOLO dataset configuration
├── runs/                   # YOLO training outputs
├── README.md               # Project documentation
└── requirements.txt        # Dependencies
```

---

## 🧰 Tech Stack

* **Programming Language:** Python
* **Frameworks & Libraries:**

  * Ultralytics YOLOv8
  * PyTorch
  * NumPy
  * OpenCV
* **Platform:** Google Colab / Jupyter Notebook

---

## 🧠 Model Used

### YOLOv8 (You Only Look Once)

YOLOv8 is a real-time object detection algorithm that:

* Detects objects in a single forward pass
* Provides bounding boxes and class labels
* Is fast and suitable for real-time systems

---

## 🔄 Workflow

1. Install required libraries
2. Upload TrashNet dataset
3. Extract and organize images
4. Convert dataset into YOLO format
5. Split dataset into train and validation sets
6. Configure `data.yaml`
7. Train YOLOv8 model
8. Evaluate performance
9. Test detection on new images

---

## ⚙️ Installation & Setup

Clone the repository:

```
git clone https://github.com/your-username/Waste-Detection-YOLOv8.git
cd Waste-Detection-YOLOv8
```

Install dependencies:

```
pip install ultralytics
```

---

## ▶️ How to Run the Project

1. Open `Untitled5.ipynb` in Google Colab
2. Upload the TrashNet dataset ZIP
3. Run all cells sequentially
4. Train the YOLOv8 model
5. View detection results and metrics

---

## 📊 Training & Evaluation

* Loss functions: Box loss, Class loss, DFL loss
* Metrics:

  * Precision
  * Recall
  * mAP (mean Average Precision)

YOLOv8 provides built-in evaluation after training.

---

## 📈 Results

* Accurate detection of waste categories
* Fast inference suitable for real-time use
* Good generalization on validation data

*(Results depend on training epochs and dataset size)*

---

## 🌍 Applications

* Smart waste segregation bins
* Recycling plants
* Smart city waste management
* Environmental monitoring
* Autonomous robots for waste collection

---

## ⚠️ Limitations

* Requires good lighting conditions
* Performance depends on dataset quality
* Limited classes based on dataset

---

## 🚀 Future Enhancements

* Add more waste categories
* Integrate with IoT-based smart bins
* Deploy on edge devices (Jetson, Raspberry Pi)
* Real-time camera-based detection
* Mobile application integration

---

## 👨‍💻 Author

**Galla Rishi**
MTech – Robotics / AI & Machine Learning

---

## ⭐ Acknowledgment

* TrashNet Dataset
* Ultralytics YOLOv8

---

**End of README.md**
