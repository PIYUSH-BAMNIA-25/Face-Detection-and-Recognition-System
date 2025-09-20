# Face Detection and Recognition System

![Face Detection]


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
git clone https://github.com/PIYUSH-BAMNIA-25/Face-Detection-and-Recognition-System.git
cd Face-Detection-and-Recognition-System
```

## 📥 Installation
### 2️⃣ Install Dependencies
Install the required Python libraries:

```sh
pip install opencv-python tensorflow numpy
```

### 3️⃣ Setup
Ensure the following files are in the same directory:
- `haarcascade_frontalface_default.xml` (for face detection)
- `my_model_file.h5` (the trained recognition model)

---

## 🎯 Usage
This project has two main phases: **data collection** and **recognition**.

### 1️⃣ Collect Data
Run the `collect_data.py` script to capture facial images for your dataset. This script is configured to capture 100 images and saves them in an `Images` directory.
```sh
python collect_data.py
```
**Note:** Before running, ensure your mobile IP webcam is running and the URL in the script `http://192.168.73.223:8080/shot.jpg` is correct.

### 2️⃣ Recognize Faces
Once you have trained your model and have the `my_model_file.h5` file, you can run the recognition script.
```sh
python recognize.py
```

## 📊 Model Architecture
The deep learning model for facial recognition is built using **TensorFlow & Keras**. The model (`my_model_file.h5`) is loaded for inference. The input to the model consists of preprocessed grayscale images of faces, and the output is a prediction of the person's identity.

---

## 🔥 Future Enhancements
- ✅ **Train the model** using the `consolidated_data.py` script and a separate training script.
- ✅ **Expand the dataset** to include more individuals for more robust recognition.
- ✅ **Improve UI/UX** with a graphical interface.
- ✅ **Support multi-face detection** for group recognition.
- ✅ **Integrate with a live webcam** instead of a mobile camera.

---

## 🤝 Contributing
Contributions are welcome! Feel free to submit **pull requests** or open an **issue** for bug reports and feature requests.

---

## 📜 License
This project is licensed under the **GNU GENERAL PUBLIC LICENSE**.

---

## 👨‍💻 Team Name
**Team Name:** Team Sigmoid

### 👥 Contributors
- **Piyush Bamnia**
  📧 Email: piyushbamnia25@gmail.com
  🔗 [GitHub](https://github.com/PIYUSH-BAMNIA-25) | [LinkedIn](https://www.linkedin.com/in/piyush-bamnia-ab09ab255/)

- **Tansukh Suthar**
  📧 Email: jatsourabhsinghgovindsingh@gmail.com
  🔗 [GitHub](https://github.com/contributor2) | [LinkedIn](https://www.linkedin.com/in/tansukhsuthar18/)

---

_If you like this project, don't forget to ⭐ the repository!_ 🌟
