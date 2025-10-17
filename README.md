# Implementing Artificial Neural Network (ANN) for Camera-Based Object Detection

![Kotlin](https://img.shields.io/badge/Kotlin-1.9-blue?logo=kotlin)
![Android](https://img.shields.io/badge/Android%20Studio-IDE-green?logo=android)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow%20Lite-ML-orange?logo=tensorflow)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

This project demonstrates the implementation of an **Artificial Neural Network (ANN)** — specifically a **Convolutional Neural Network (CNN)** — to perform **real-time object detection** using a device camera.  
Developed with **Android Studio**, **TensorFlow Lite**, and **CameraX**.

---

## 🚀 Key Features
- Real-time **object detection** using the device camera.  
- Efficient **ANN/CNN-based image classification**.  
- Smooth **CameraX integration**.  
- Fast inference powered by **TensorFlow Lite**.  
- Displays **detection labels and confidence scores** instantly.  

---

## 🧩 Technologies Used

| Component | Description |
|------------|-------------|
| **Language** | Kotlin |
| **IDE** | Android Studio |
| **Machine Learning Framework** | TensorFlow Lite |
| **Camera Library** | CameraX |
| **Model** | `mobilenet_v1.tflite` |
| **Minimum SDK** | 21 (Lollipop) |

---

## 📁 Project Structure
```
app/
 ┣ 📁 src/
 ┃ ┣ 📁 main/
 ┃ ┃ ┣ 📁 java/com/indandy/mycamera/
 ┃ ┃ ┃ ┣ CameraActivity.kt
 ┃ ┃ ┃ ┣ ImageClassifierHelper.kt
 ┃ ┃ ┣ 📁 res/
 ┃ ┃ ┃ ┣ activity_camera.xml
 ┃ ┃ ┃ ┣ strings.xml
 ┣ build.gradle
 ┣ AndroidManifest.xml
```

---

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/INDandy/Implementasi-Artificial-Neural-Network-ANN-pada-Aplikasi-Deteksi-Objek-Berbasis-Kamera.git
   ```
2. Open the project in **Android Studio**.  
3. Make sure you have added the TensorFlow Lite model file under the `assets/` directory.  
4. Run the application on a physical device or emulator.  
5. Point the camera at an object to see the detection results in real time.  

---

## 🧠 About ANN and CNN
- **Artificial Neural Network (ANN)** is a machine learning model inspired by the human brain, capable of recognizing patterns and learning from data.  
- **Convolutional Neural Network (CNN)** is a specialized type of ANN designed for processing visual data such as images, making it ideal for image classification and object detection tasks.  

---

## 📷 Application Preview
*(Add screenshots here if available)*  

Example:
```
Camera active → Displays detected object  
Result: "Cat — 92%"
```

---

## 👨‍💻 Developer
**Dandy Royan Firdaus**  
Engineer & Game Developer  
Cirebon, Indonesia  
[GitHub Profile](https://github.com/INDandy)

---

## 📜 License
This project is intended for educational and research purposes.  
You are free to use or modify it with proper attribution to the developer.

---

*"Bringing neural intelligence to your camera — powered by ANN and CNN."*
