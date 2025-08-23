# 🍎 FruitFusionNet | Fruit Detection & Classification with YOLOv8 + CNN

## 🔍 Project Overview
FruitFusionNet is a hybrid computer vision pipeline that detects fruits in images using YOLOv8 and classifies them using a custom CNN model. It’s designed as a resume-ready demo for migration, freelancing, and showcasing ML/CV skills.

---

## 🧠 Architecture Summary
Input Image → YOLOv8 Detection → Cropped Fruits → CNN Classification → Final Label

- **YOLOv8**: Detects and crops fruit regions
- **CNN**: Classifies cropped fruit images
- **Keras**: Used for training and saving the classification model
- **OpenCV**: Handles image preprocessing and visualization

---

## 📁 Folder Structure


FruitFusionNet/ ├── data.yaml ├── yolo_crop.py ├── cnn_train.py ├── cnn_inference.py ├── models/ │   └── cnn_model.keras ├── Cropped/ │   ├── apple/ │   ├── banana/ │   └── ... ├── Test File/ │   └── images/ ├── README.md

---

## 🚀 How to Run

### 1. Run YOLOv8 and crop fruit images

python yolo_crop.py


2. Train CNN model and save it
python cnn_train.py


3. Run inference on new images
python cnn_inference.py


## 🎯 Use Cases
- Resume and migration portfolio
- Freelance project demo
- Hands-on deep learning practice

## 📌 Technical Notes
- YOLOv8 model trained with Ultralytics (.pt format)
- CNN built with Keras, saved as .keras
- Cropped images must be organized into class-specific folders
- Number of classes must match CNN output layer

## 🙋‍♂️ Developer
Alireza
Machine Learning & Computer Vision Developer
Based in Iran, preparing for migration to the USA(NYC)
Passionate about real-world ML projects,and freelance growth

## 📫 Contact
## Feel free to reach out via LinkedIn or GitHub for collaboration or freelance opportunities.
## https://www.linkedin.com/in/alireza-sobhani-385134245
---

