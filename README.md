# 🧠 AI-Enhanced Image Stitching and Edge Detection

## 📌 Overview
This project is an interactive Python application that enables users to upload and stitch multiple images into a panoramic view and apply various edge detection techniques. The application supports:

- 🔹 **Canny Edge Detection**
- 🔹 **Difference of Gaussians (DoG) + Morphological Operations**
- 🔹 **AI-based Human Figure Detection** (using models like YOLO or SSD)

Users can dynamically adjust parameters and compare the outputs in real-time through an intuitive multi-window GUI.

---

## 🎯 Goal
To develop an intelligent image processing tool that:
- Stitches multiple images into one panoramic image.
- Applies classical and AI-driven edge detection methods.
- Visualizes human figure detection with >50% confidence.
- Provides user interaction via a responsive and adjustable GUI.

---

## 🛠 Features

### 🖼 Image Stitching
- Select multiple local images via GUI.
- Preview both individual and panoramic results.

### 🧪 Edge Detection Techniques
1. **Canny Edge Detection**
2. **DoG + Morphological Operation**
   - Adjustable kernel size via UI slider.
   - Developer-selected kernel shapes (rectangular, elliptical, etc.).

### 🧠 AI-Based Human Detection
- Uses pretrained object detection models (e.g., YOLO, SSD).
- Filters and displays results with >50% confidence.
- Highlights detected human figures on the stitched image.

---

## 🖥 User Interface
- Simple, intuitive UI using `tkinter` or similar library.
- Three main windows:
  1. **Image Selection + Stitching**
  2. **Edge Detection Results (with parameter controls)**
  3. **AI-Based Human Detection Visualization**

---

## 📦 Requirements

### Functional
- Image selection and stitching
- Multiple edge detection algorithms
- AI-based human detection
- Adjustable morphological operation settings
- Real-time UI interaction

### Non-Functional
- Efficient processing and responsiveness
- Scalable design for future features
- Clear, intuitive UX

---

## 🔧 Technologies Used
- `Python 3.x`
- `OpenCV` – for image processing and stitching
- `NumPy` – for array and image manipulation
- `PyTorch` or `TensorFlow` – for AI model inference
- `tkinter` / `PyQt` – for GUI (select one)
- Pretrained models: `YOLOv5`, `YOLOv8`, or `SSD` via `torchvision` or `cvlib`

---

## 🧪 Evaluation Criteria

| Criteria                        | Weight |
|--------------------------------|--------|
| Functionality                  | 40%    |
| User Interface & Experience    | 20%    |
| Code Quality & Documentation   | 20%    |
| Innovation & Creativity        | 20%    |

---

## 📁 Project Structure

