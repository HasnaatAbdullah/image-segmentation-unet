# image-segmentation-unet
Implementation of U-Net for semantic image segmentation on the CARLA self-driving car dataset. The project demonstrates pixel-wise classification to accurately detect roads, cars, pedestrians, and more.
# 🧠 Image Segmentation with U-Net | CARLA Self-Driving Car Dataset

This repository contains my implementation of **U-Net** for **semantic image segmentation**.  
The model predicts a **label for every pixel** in an image from the **CARLA self-driving car dataset**, enabling precise detection of roads, cars, pedestrians, and other objects.

---

## 🚀 Project Overview
Semantic image segmentation is an advanced **computer vision** technique where every pixel in an image is classified into a predefined category.  
Unlike **object detection** (which draws bounding boxes), semantic segmentation produces a **mask** for each object, giving pixel-perfect results.

This project focuses on:
- Building a **U-Net** architecture from scratch.
- Training the model on the **CARLA self-driving car dataset**.
- Predicting segmentation masks for real-world driving images.
- Using **sparse categorical crossentropy** for pixel-wise classification.

---

## 📌 Key Features
- 🔹 Implementation of **U-Net** architecture.
- 🔹 End-to-end **semantic segmentation** for self-driving cars.
- 🔹 Pixel-wise prediction for multiple classes.
- 🔹 Model evaluation using training accuracy and mask visualization.
- 🔹 Clean, well-documented code following best practices.

---

## 📂 Project Structure

```bash
image-segmentation-unet/
│── data/                      # Dataset (CARLA self-driving car images & masks)
│── notebooks/                # Jupyter notebooks for training & testing
│── models/                   # Trained U-Net models
│── utils/                    # Helper functions for preprocessing & visualization
│── results/                  # Predicted segmentation masks
│── requirements.txt          # Required dependencies
│── README.md                 # Project documentation
└── unet_model.py             # U-Net implementation
