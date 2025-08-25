# Facial Emotion Recognition using Deep Learning

This project implements a **real-time facial emotion recognition system** using **Deep Learning (TensorFlow/Keras)** and **Computer Vision (OpenCV)**.  
It can detect faces from a webcam or uploaded images and classify them into 7 emotions.

## 🎯 Features
- Real-time face detection using Haar Cascade Classifier.
- Emotion classification into **anger, contempt, disgust, fear, happiness, sadness, surprise**.
- GUI built with **PyQt5** for easy interaction.
- Option to test on images or webcam feed.
- Logs detected emotions with timestamps using **Pandas**.
- Generates emotion trend visualization with **Matplotlib**.

## 🛠️ Technologies Used
- Python 3  
- TensorFlow / Keras  
- OpenCV  
- PyQt5  
- Pandas  
- Matplotlib  

## 🚀 How to Run
1. Clone the repository and navigate to the project folder.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the project:
   ```bash
   python "main code.py"
   ```
4. Use the GUI to start detection via webcam or upload an image.

## 📸 Screenshots
### GUI Interface  
![GUI Interface](output%202.png)

## 📂 Project Structure
```
.
├── main code.py                  # Main application with PyQt5 GUI
├── model.h5                      # Pre-trained CNN model for emotion recognition
├── haarcascade_frontalface_default.xml   # Face detection cascade
├── output 2.png                  # Example screenshot
└── README.md                     # Project documentation
```

## 📖 Use Cases
- Human-computer interaction research  
- Mental health monitoring  
- Security & surveillance systems  
- Educational tools to study emotional response  

---
✨ Developed as a Machine Learning project for real-time **Facial Emotion Recognition**.
