🔦 GAN-Based Low-Light Image Enhancement for Surveillance Applications

Low-light conditions significantly degrade the quality of images captured by surveillance cameras, leading to poor visibility, noise, and loss of critical details. This project focuses on enhancing low-light surveillance images using deep learning-based image enhancement models, enabling improved visual quality and better scene understanding.

📌 Project Overview

This project implements and compares state-of-the-art low-light image enhancement models to improve image visibility in challenging illumination conditions. We utilize GAN-based and curve estimation-based models to enhance brightness, contrast, and perceptual quality while preserving structural details.

The enhanced results are evaluated using both quantitative metrics and visual comparisons.

🚀 Models Used

-EnlightenGAN
     Unsupervised GAN-based model
     Learns illumination correction without paired ground-truth images
     Produces natural and balanced enhancement
-Zero-DCE++
     Lightweight deep curve estimation model
     Does not require reference images
     Suitable for real-time and low-compute environments
-CLAHE (Baseline)
     Traditional image enhancement technique
     Used for comparison with deep learning models
📂 Dataset
     LOL (Low-Light) Dataset
     Contains real-world low-light images
     Widely used benchmark for low-light image enhancement


