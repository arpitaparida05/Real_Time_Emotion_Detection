# Real-Time Emotion Detection using CNN and OpenCV

A comprehensive deep learning project that captures live video from a webcam, detects human faces, and predicts facial emotions in real-time. 

## 📂 Repository Structure
* **`Detection.ipynb`**: The core real-time deployment script utilizing OpenCV for face tracking and Keras for emotion inference.
* **`Model_Training.ipynb`**: The Convolutional Neural Network (CNN) training notebook detailing model architecture, layer configurations, and optimization.
* **`Emotion Zip.ipynb`**: Data preprocessing notebook handling dataset extraction, balancing, and preparation stages.
* **`Emotion_detection_model_new.h5`**: The pre-trained, optimized CNN model weights (3.82 MB).

## 🚀 Features & Technical Stack
* **Deep Learning Framework**: Keras & TensorFlow Sequential CNN model.
* **Computer Vision**: OpenCV Haar Cascade (`haarcascade_frontalface_default.xml`) for high-speed face detection.
* **Classification**: 5-class emotion mapping (**Angry, Happy, Neutral, Sad, Surprised**).
* **Optimization**: Multi-layered Convolutional (`Conv2D`) and Pooling (`MaxPooling2D`) structure with Dropout/Dense layers for optimal accuracy.

## 🛠️ How to Run
1. Clone this repository to your local machine.
2. Ensure you have the dependencies installed: `pip install opencv-python numpy tensorflow keras`
3. Place your webcam in a well-lit area.
4. Run `Detection.ipynb` and press **'q'** on your keyboard to safely terminate the video stream window.
