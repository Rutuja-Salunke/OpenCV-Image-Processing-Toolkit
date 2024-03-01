
---

# Image Processing with OpenCV in Python

## Overview
This repository contains Python code snippets for performing fundamental image processing tasks using the OpenCV library. The provided scripts cover a range of techniques, including image blurring, resizing, grayscale conversion, and the creation of image pyramids.

## Table of Contents

1. **Image Blurring**
2. **Image Resizing**
3. **Grayscaling of Image**
4. **Image Pyramid**

---

## 1. Image Blurring

### Description
The script `image_blurring.py` demonstrates various image blurring techniques using OpenCV. It includes Gaussian blur, median blur, and bilateral blur. Image blurring is often used to reduce noise or emphasize certain features in an image.

### How to Run

```bash
python image_blurring.py
```

---

## 2. Image Resizing

### Description
The script `image_resizing.py` showcases image resizing methods using OpenCV. It covers resizing to half the original size, resizing to a custom size, and using different interpolation methods to maintain image quality during resizing.

### How to Run

```bash
python image_resizing.py
```

---

## 3. Grayscaling of Image

### Description
The script `grayscale_conversion.py` converts a color image to grayscale using OpenCV's `cvtColor` function. Grayscale conversion is a common preprocessing step in computer vision and image analysis applications.

### How to Run

```bash
python grayscale_conversion.py
```

---

## 4. Image Pyramid

### Description
The script `image_pyramid.py` generates an image pyramid using the pyrDown function in OpenCV. An image pyramid is a multi-scale representation of an image, where each level represents a scaled-down version of the original image. This can be useful in various computer vision applications.

### How to Run

```bash
python image_pyramid.py
```

---

## Dependencies

- **Python 3.x**
- **OpenCV**
- **NumPy**
- **Matplotlib**

### How to Install Dependencies

```bash
pip install opencv-python numpy matplotlib
```

---

