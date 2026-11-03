# Pixelforge
### Digital Image Processing & Computer Vision Workbench

Pixelforge is a Python-based computer vision project exploring image restoration, segmentation, feature extraction, object detection and video motion analysis.

## Modules

### 1. Image Restoration and Segmentation
- Gaussian and Salt-and-Pepper Noise
- Median and Gaussian Filtering
- PSNR and SSIM Evaluation
- Thresholding and Morphological Operations
- Canny Edge Detection
- Watershed Segmentation

### 2. Feature Extraction and Matching
- Histogram of Oriented Gradients (HOG)
- SIFT Keypoint Detection and Descriptors
- Feature Matching
- Rotation and Resizing Experiments

### 3. Object Detection and Motion Analysis
- Viola-Jones Haar Cascade
- YOLO Object Detection
- Video Frame Extraction
- Frame Differencing
- GMM Background Subtraction (MOG2)
- Lucas-Kanade Optical Flow

## Technology Stack
Python, OpenCV, NumPy, Pandas, Matplotlib, scikit-image, Ultralytics YOLO, PyTorch and Jupyter Notebook.

## Repository Structure
- notebooks/ - Practical implementations
- dataset/ - Local input photographs and videos
- outputs/ - Generated experiment results
- models/ - Model setup information
- documentation/ - Technical documentation
- assets/ - Project visuals

## Installation

Install core dependencies:

pip install -r requirements.txt

For YOLO functionality:

pip install -r requirements-unit5.txt

Launch Jupyter:

jupyter notebook

## Dataset
The experiments use personally captured photographs and a self-recorded video. Original personal media is excluded from the public repository.

## Project Status
The core image-processing, feature-extraction, object-detection and motion-analysis experiments are implemented. An interactive computer-vision interface is a planned extension.

## Author
Shivam
