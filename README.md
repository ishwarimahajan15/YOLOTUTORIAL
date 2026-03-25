# 🚀 YOLOv8 Object Detection, Segmentation & Classification Project

## 📌 Overview

This project demonstrates the implementation of **YOLOv8** for three major computer vision tasks:

- **Object Detection**
- **Instance Segmentation**
- **Image Classification**

It covers dataset preparation, model training, validation, testing, visualization, fine-tuning, and model export. The entire workflow was implemented in **Google Colab with GPU acceleration**.

---

## 🎯 Project Objectives

- Set up a deep learning environment in Google Colab
- Train YOLOv8 models on standard datasets
- Perform detection, segmentation, and classification tasks
- Evaluate performance using **Precision, Recall, and mAP**
- Visualize training results and predictions
- Export trained models for deployment
- Compare performance across YOLOv8 variants

---

## 📂 Dataset

The project uses subsets of the **COCO 2017 Dataset** and MNIST:

| Task                  | Dataset  | Config File        |
| --------------------- | -------- | ------------------ |
| Object Detection      | COCO128  | `coco128.yaml`     |
| Instance Segmentation | COCO128  | `coco128-seg.yaml` |
| Image Classification  | MNIST160 | -                  |

---

## 🧠 Models Used

YOLOv8 variants applied for different tasks:

| Task             | Model       |
| ---------------- | ----------- |
| Object Detection | YOLOv8n     |
| Segmentation     | YOLOv8n-seg |
| Classification   | YOLOv8n-cls |

All models share the same backbone but differ in task-specific heads.

---

## 🔄 Project Workflow

Environment Setup → Dataset Preparation → Detection Training → Segmentation Training → Classification Training → Validation → Prediction → Visualization → Fine-Tuning → Model Export

---

## ⚙️ Environment Setup

Executed in **Google Colab** with GPU support.  
Required libraries:

- `torch`, `torchvision`
- `ultralytics`
- `opencv-python`
- `matplotlib`, `pandas`, `seaborn`

---

## 🏋️ Model Training

Training configuration:

| Parameter     | Value      |
| ------------- | ---------- |
| Image Size    | 640        |
| Batch Size    | 16         |
| Epochs        | 10–20      |
| Optimizer     | Adam / SGD |
| Learning Rate | 0.001      |

Generated outputs:

- Loss curves
- Precision-Recall curves
- Confusion matrix
- mAP scores

---

## 📊 Evaluation Metrics

- **Precision**
- **Recall**
- **Mean Average Precision (mAP)**
- **Confusion Matrix**
- **Loss Curves**

These metrics provide a comprehensive view of model accuracy and robustness.

---

## 🎨 Visualization

- Detection outputs with bounding boxes
- Segmentation masks
- Training loss graphs
- Confusion matrices
- Precision-Recall curves

---

## 💾 Model Saving & Export

Models saved automatically after training:

- `runs/detect/.../best.pt`
- `runs/segment/.../best.pt`
- `runs/classify/.../best.pt`

Export formats:

- **ONNX**
- **TorchScript**

---

## 📈 Results Summary

| Task           | Model       | Dataset | Performance        |
| -------------- | ----------- | ------- | ------------------ |
| Detection      | YOLOv8n     | COCO128 | Good               |
| Segmentation   | YOLOv8n-seg | COCO128 | Good               |
| Classification | YOLOv8n-cls | MNIST   | Very High Accuracy |

- Detection & segmentation required more computation
- Classification trained faster and achieved higher accuracy

---

## 🌍 Applications

Potential real-world use cases:

- Smart surveillance systems
- Traffic monitoring
- Autonomous vehicles
- Retail analytics
- Medical image analysis
- Industrial automation
- Object tracking systems

---

## ✅ Conclusion

This project successfully demonstrates YOLOv8’s flexibility across **object detection, segmentation, and classification**.  
The results confirm YOLOv8 as an efficient framework for multi-task computer vision applications.

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Install required libraries
3. Download datasets
4. Train detection model
5. Train segmentation model
6. Train classification model
7. Run validation
8. Run predictions
9. Visualize results
10. Export models

---

## 👨‍🎓 Author

**Student Name:** Ishwari Mohan Mahajan  
**PRN:** 202301040173
**Course:** Deep Learning  
**Instructor:** Dr. Diptee Ghusse
[README.md](https://github.com/user-attachments/files/26252506/README.md)
