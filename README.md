# Face Detection and Recognition System

![Face Detection](https://imgur.com/G56K9Gq.jpg)

## 📝 Project Overview
This project is a **real-time face detection and recognition system** that identifies individuals from a live video stream. Using **Computer Vision and Deep Learning**, it captures and processes facial images to build a recognition model, which can then identify a person from a live feed.

## 🚀 Features
- **Real-time face detection** using OpenCV and Haar Cascade Classifiers.
- **Data collection** module to capture facial images for dataset creation.
- **Deep Learning-based recognition** using a pre-trained model.
- **Live video stream processing** from a mobile camera (IP webcam).
- **Automated image preprocessing** (resizing, grayscale conversion, and normalization).

## 📂 Dataset
The dataset is built by the `collect_data.py` script, which captures **facial images** from a live video feed. The `consolidated_data.py` script then prepares this raw data for model training.

## 🏗️ Tech Stack
- **Python**
- **TensorFlow & Keras** (Deep Learning)
- **OpenCV** (Computer Vision)
- **NumPy & pickle** (Data Processing)

## 📥 Installation
### 1️⃣ Clone the Repository
```sh
git clone [https://github.com/your-username/Face-Detection-System.git](https://github.com/your-username/Face-Detection-System.git)
cd Face-Detection-System
