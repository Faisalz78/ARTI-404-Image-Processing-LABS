# 🧪 Lab 5 – Spatial Filtering (Smoothing and Sharpening)

## 📚 Course
ARTI 404 – Image Processing  
Imam Abdulrahman Bin Faisal University  

---

## 🎯 Objective
The objective of this lab is to implement fundamental image processing techniques using spatial filtering, including smoothing and sharpening.

---

## 🛠️ Tools & Libraries
- Python 3  
- OpenCV (cv2)  
- NumPy  
- Matplotlib  

---

## 📂 Project Structure
Lab5/
│
├── images/
│   └── Parrot.png
│
├── lab5.ipynb
├── report.pdf
└── README.md

---

## 🔹 Task 1 – 7x7 Box Filter
A 7x7 box filter is applied to smooth the image by averaging neighboring pixels.

---

## 🔹 Task 2 – Gaussian Filters
Gaussian filters are applied using:
- 5x5 (light smoothing)
- 21x21 (strong smoothing)

---

## 🔹 Task 3 – Laplacian Sharpening
The Laplacian filter is used to detect edges and sharpen the image using:
np.clip(image_float - laplacian, 0, 1)

---

## 📊 Conclusion
- Box and Gaussian filters are used for smoothing.
- Larger kernels produce stronger blur.
- Laplacian enhances edges and sharpens images.

---

## 📌 Submission Requirements
- Jupyter Notebook  
- Images used  
- PDF Report  
- GitHub repository link  

---

## 👨‍💻 Author
Faisal Alzahrani  
Artificial Intelligence Student  
IAU – CCSIT  
