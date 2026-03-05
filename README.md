# 👁️ Vision-Core: Morphological & Structural Analysis Toolkit

[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org/)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Vision](https://img.shields.io/badge/Domain-Machine%20Vision-success?style=for-the-badge)](https://github.com/alhoulsy0/vision-core-morphology-toolkit)

## 📌 Project Overview
This repository serves as a foundational toolkit for **Low-Level Computer Vision** tasks. It implements essential algorithms for extracting structural information from images, reducing noise, and isolating features using **Morphological Transformations** and **Edge Detection**.

## 🛠️ Key Vision Capabilities
* **Edge Detection:** Comparative analysis using **Sobel Operators** (directional gradients) and the **Canny Algorithm** (multi-stage detection).
* **Morphological Operations:** Implementation of Dilation, Erosion, Opening (noise removal), and Closing (hole filling).
* **Thresholding:** Binary segmentation for object isolation and background subtraction.
* **Color Space Analysis:** Grayscale and HSV transformations for robust feature detection.

## 📂 Structure
* `notebooks/`: `01_morphology_and_structural_analysis.ipynb` — Interactive vision pipeline.
* `samples/`: Test images used for benchmarking algorithms.
* `assets/`: Resulting visual comparisons (Edge maps, morphological masks).

## 🚀 Quick Start
```bash
git clone [https://github.com/alhoulsy0/vision-core-morphology-toolkit.git](https://github.com/alhoulsy0/vision-core-morphology-toolkit.git)
pip install opencv-python matplotlib numpy
