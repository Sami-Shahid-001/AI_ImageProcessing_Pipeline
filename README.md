# AI_ImageProcessing_Pipeline

A Python-based image processing and analysis pipeline that transforms raw image data into AI/ML-ready datasets. This project demonstrates the complete data science workflow: data preprocessing, transformation, statistical analysis, and feature engineering, making it suitable for machine learning and computer vision applications.

---

## Features

### Data Loading & Handling
- Load and save images as NumPy arrays for efficient processing.
- Supports multiple image formats such as JPG and PNG.

### Preprocessing & Transformation
- Grayscale conversion for simplified image data.
- Normalization and standardization to scale pixel intensities.
- Resize, flatten, and channel separation (R, G, B) for feature extraction.
- Missing pixel handling with statistical imputation (mean, median, zero).

### Statistical Analysis & Visualization
- Compute mean, variance, standard deviation, min/max pixel values.
- RGB channel correlation analysis.
- Generate histograms to visualize pixel intensity distributions.

### Image Transformations for AI/ML
- Adjust brightness and contrast.
- Rotation, flipping, cropping, and inversion.
- Sharpening, smoothing, and blurring for data augmentation.

### Exception Handling
- File existence validation.
- Input validation for robust execution.

---

## Tools & Libraries
- Python – core programming language.
- NumPy – numerical operations and array manipulation.
- Pillow (PIL) – image processing and transformations.
- Matplotlib – visualization and statistical insights.

---
