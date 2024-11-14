# **Facial-Emotion-Recognition**

## **Overview**
This project implements a **real-time facial emotion detection system** using **Convolutional Neural Networks (CNNs)**. The system can identify emotions like **happiness**, **sadness**, **anger**, **surprise**, and others based on live video feed from a camera.

### **Key Features:**
- **Real-Time Emotion Classification**: Detects emotions from live video streams.
- **High Accuracy**: Achieves **80% accuracy** in emotion classification.
- **Dynamic Updates**: Provides immediate feedback on emotions as they are detected.
- **Adaptability**: Performs well under varying lighting conditions and different facial angles.
- **Open-Source**: Fully open for modifications and improvements.

## **Technologies Used**
- **Python**: Core programming language for model development.
- **TensorFlow/Keras**: For building and training the Convolutional Neural Network (CNN).
- **OpenCV**: Used for facial detection and handling video input.
- **Pre-trained Datasets**: FER-2013, AffectNet for training the model.

## **Installation**

### **Clone the repository**:
```bash
git clone https://github.com/sujeethsundaram/Facial-Emotion-Recognition.git
```

### **Required Libraries**:
Ensure the following Python libraries are installed:

- **TensorFlow:** For CNN implementation.
- **Keras:** For deep learning layers and model training.
- **OpenCV:** For image and video processing.
- **NumPy, Matplotlib:** For data handling and visualization.

### **Usage**
**Running the Program**
After setting up, run the main application using:


```bash
python main.py
```
The system will start the camera feed and display the predicted emotion in real-time based on the detected facial expression.

## **Model Input**
The model processes grayscale images from the webcam and performs emotion classification based on the detected face.

## **Sample Output**
When a face is detected, the model will output one of the following emotions:

- Happy
- Sad
- Surprised
- Anger
- Neutral
- Fear
- Disgust

These results will appear on the screen in real time as the video feed progresses.

## **Future Improvements**
- Data Augmentation: Enhance the model's ability to generalize better in varying conditions.
- Mobile Optimization: Adapt the system to run efficiently on mobile devices with limited resources.
- Additional Emotion Recognition: Add more nuanced emotion categories.
- Advanced Error Handling: Improve the system's handling of edge cases like occlusions or partially visible faces.

## **Contributing**
We welcome contributions! To contribute:

- Fork the repository.
- Create a new branch.
- Make your changes.
- Submit a pull request.
