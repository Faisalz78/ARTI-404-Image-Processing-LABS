# ✨ Lab 8 — Edge Detection

## 📌 Overview
In this lab, I applied a set of **edge detection techniques** using **Python, OpenCV, NumPy, and Matplotlib** on four different images.

The goal of the lab is to detect object boundaries and compare how different edge detection methods respond to image details, textures, and intensity changes.

---

## 🖼️ Images Used
The following images were used in this notebook:

- `bird.png`
- `Butterfly.jpg`
- `Coins.png`
- `kid1.jpg`

---

## ✅ What I Did
In this lab, I completed the following tasks:

- Loaded the required Python libraries
- Defined the paths of the given images
- Applied multiple **edge detection methods**
- Displayed the **original image** beside the **result image**
- Compared the output of each method on all given images
- Organized the code into clear notebook cells for easy execution and understanding

---

## 🧪 Edge Detection Methods Implemented
The following techniques were applied:

### 1. Sobel Edge Detector
Used to detect horizontal and vertical edges by computing image gradients.

### 2. Roberts Edge Detector
A simple edge detection method based on diagonal differences.

### 3. Prewitt Edge Detector
Used to estimate edge strength in horizontal and vertical directions.

### 4. Canny Edge Detector
A more advanced method that detects strong and thin edges with better noise handling.

### 5. Multi-Channel Canny Edge Detector
Applied Canny edge detection separately on color channels, then combined the results.

### 6. LoG (Laplacian of Gaussian)
Used Gaussian smoothing first, then detected edges using the Laplacian operator.

### 7. DoG (Difference of Gaussians)
Used two Gaussian-blurred versions of the image and subtracted them to enhance edges.

### 8. Color Gradient Edge Detector
Calculated gradients across RGB channels to detect color-based edges.

---

## 🛠️ Tools & Libraries
This lab was implemented using:

- **Python**
- **OpenCV**
- **NumPy**
- **Matplotlib**

Install them using:

```python
!pip install opencv-python numpy matplotlib