
# 🚘 Robust License Plate Detection in Low-Light & Blurry Conditions

## 📅 Duration

**December 2024 – January 2025**

## 🛠 Technologies Used

* PyTorch
* CUDA
* YOLOv10
* MIRNet
* DeblurGAN
* ESRGAN

---

## 📖 Overview

This project focuses on building a **GPU-accelerated deep learning pipeline** for **robust license plate detection in low-light and motion-blur scenarios**.
By integrating advanced image enhancement models prior to detection, the system significantly improves object detection accuracy in real-world challenging conditions.

---

## 🧩 Key Features

* **🔧 End-to-End Pipeline:**
  Complete flow from image enhancement to license plate detection.

* **🚀 GPU Acceleration:**
  Optimized for performance using **CUDA with PyTorch**.

* **📈 Improved Detection Accuracy:**
  Applied pre-processing models to enhance YOLOv10 detection outcomes.

* **📸 Real-World Testing:**
  Evaluated on images with poor lighting and motion blur to validate robustness.

---

## 🏗️ Architecture

```
Input Image  
   └──▶ MIRNet (Denoising)  
         └──▶ DeblurGAN (Deblurring)  
               └──▶ ESRGAN (Super-Resolution)  
                     └──▶ YOLOv10 (License Plate Detection)  
```

---

## 🧪 Models Used

* **MIRNet:**
  Denoises low-light images using multi-scale residual learning.

* **DeblurGAN:**
  Removes motion and defocus blur through adversarial training.

* **ESRGAN:**
  Upscales image resolution to improve feature extraction.

* **YOLOv10:**
  State-of-the-art object detection model for accurate license plate localization.

