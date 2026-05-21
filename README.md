# Low-Light Image Enhancement using U-Net

This project presents a deep learning-based low-light image enhancement system developed using U-Net architecture in PyTorch. The model enhances dark images by improving brightness, preserving structural details, and generating visually clearer outputs.

## Project Overview

Low-light images often suffer from poor visibility, noise, and loss of details. This project uses a convolutional neural network (U-Net) to learn the mapping between low-light and normal-light image pairs from the LOL dataset.

The model performs image enhancement while maintaining important visual structures and textures.

---

## Technologies Used

* Python
* PyTorch
* Deep Learning
* Computer Vision
* Image Processing
* U-Net Architecture
* NumPy
* Matplotlib
* TorchMetrics
* Google Colab

---

## Features

* Low-light image enhancement
* U-Net based encoder-decoder architecture
* Image preprocessing and transformation
* PSNR evaluation metric
* SSIM evaluation metric
* Brightness comparison analysis
* Model checkpoint saving
* Visualization of enhanced outputs

---

## Workflow

1. Dataset Loading
2. Image Preprocessing
3. U-Net Model Building
4. Model Training
5. Image Enhancement
6. Performance Evaluation
7. Visualization of Results

---

## Evaluation Metrics

### PSNR (Peak Signal-to-Noise Ratio)

Measures image reconstruction quality.

### SSIM (Structural Similarity Index)

Measures similarity between enhanced image and ground truth image.

### Brightness Analysis

Compares brightness before and after enhancement.

---

## Model Architecture

The project uses a U-Net convolutional neural network consisting of:

* Encoder (Downsampling)
* Bottleneck Layer
* Decoder (Upsampling)
* Skip Connections

The architecture helps preserve image details while enhancing brightness.

---

## Sample Results

The model successfully enhances low-light images and improves visual quality significantly.

Screenshots and output results are included in the repository.

---

## Future Improvements

* Real-time enhancement system
* Streamlit or Flask deployment
* Higher resolution training
* Advanced attention mechanisms

---

## Author

Harshal Kolekar
