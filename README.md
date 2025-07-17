Robust License Plate Detection in Low-Light & Blurry Conditions Duration: December 2024 – January 2025 Technologies: PyTorch, CUDA, YOLOv10, MIRNet, DeblurGAN, ESRGAN

Overview This project focuses on developing a GPU-accelerated deep learning pipeline for robust license plate detection under low-light and motion-blur conditions. By integrating a series of enhancement models before detection, we significantly improved object detection accuracy in real-world challenging environments.

Key Features 🔧 End-to-End Pipeline: From image enhancement to license plate detection.

🚀 GPU Acceleration: Leveraged CUDA with PyTorch to optimize performance.

📈 Improved Detection Accuracy: Enhanced YOLOv10 results using pre-processing techniques.

📸 Real-world Scenarios: Tested on images with poor lighting and motion-induced blur.

Architecture scss Copy Edit Raw Image └──▶ MIRNet (Denoising) └──▶ DeblurGAN (Deblurring) └──▶ ESRGAN (Super-Resolution) └──▶ YOLOv10 (License Plate Detection) Models Used MIRNet – Denoises low-light images using multi-scale residual learning.

DeblurGAN – Removes motion and defocus blur through adversarial training.

ESRGAN – Upscales image resolution for enhanced feature extraction.

YOLOv10 – State-of-the-art object detector for license plate localization.
