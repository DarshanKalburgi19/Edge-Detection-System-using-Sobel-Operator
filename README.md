# Sobel Edge Detection (JavaScript + Canvas)

A browser-based implementation of edge detection using the Sobel operator.

This project performs real-time image processing using JavaScript and the HTML Canvas API, demonstrating how gradient-based edge detection works at the pixel level.

---

## 🧠 What is Edge Detection?

Edge detection is a technique used to identify boundaries in an image by detecting sharp changes in pixel intensity.

---

## ⚙️ How it Works

This project applies the Sobel operator using two convolution kernels:

- **Gx (Horizontal Gradient)** → detects vertical edges  
- **Gy (Vertical Gradient)** → detects horizontal edges  

The gradients are combined to calculate the final edge intensity.

---

## 📐 Core Formula

Edge magnitude is computed using:

G = √(Gx² + Gy²)

---

## 🚀 Features

- Upload and process images directly in the browser  
- Converts image to grayscale  
- Applies Sobel convolution (Gx & Gy)  
- Displays:
  - Original Image  
  - Gradient X  
  - Gradient Y  
  - Final Edge Output  
- Download processed output as image  
- No external libraries required  

---

## 🛠 Tech Stack

- HTML  
- CSS  
- JavaScript (Canvas API)

---

## 📂 Project Structure

sobel-edge-detection/
└── index.html

---


## ▶️ How to Run

1. Download or clone the repository  
2. Open `index.html` in your browser  
3. Upload an image  
4. View edge detection results instantly  

---

## 📸 Demo

(Add screenshots here)

---

## 🎯 What this Project Demonstrates

- Image processing fundamentals  
- Convolution operations  
- Gradient-based edge detection  
- Pixel-level manipulation using Canvas  

---

## 📈 Project Status

Completed — functional implementation of Sobel edge detection

---

## 🔄 Future Improvements

- Add threshold control for edge sensitivity  
- Implement Canny Edge Detection  
- Support real-time webcam processing  
- Add UI controls for kernel tuning  

---

## 🤝 Contributing

Suggestions and improvements are welcome

---

## 📄 License

Open-source project for educational purposes

