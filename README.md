# Face Recognition & Automated Attendance System

## Overview
A real-time face recognition system that identifies registered individuals using OpenCV and a Convolutional Neural Network (CNN). It also tracks attendance by recording entry time, exit time, and total stay duration in an Excel sheet.

## Technologies Used
- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- OpenPyXL
- Jupyter Notebook

## Features
- Real-time face detection using Haar Cascade
- Face dataset collection and preprocessing
- CNN-based face recognition
- Automated entry and exit tracking
- Attendance records exported to Excel

## Project Files
- `data_collect.ipynb` – Collects facial images.
- `consolidate_data.ipynb` – Prepares the dataset.
- `Face_Detection.ipynb` – Trains the CNN model.
- `recognize.ipynb` – Performs face recognition.
- `attendance.ipynb` – Tracks attendance.
- `haarcascade_frontalface_default.xml` – Face detection model.

## How to Run
1. Install the required Python libraries.
2. Collect images of registered individuals.
3. Preprocess the dataset and train the CNN model.
4. Run the recognition and attendance notebooks.

Install dependencies:
```bash
pip install opencv-python tensorflow numpy openpyxl matplotlib scikit-learn
```

## Note
The project requires a camera/image stream and a trained model. Update any local file paths and camera-stream URLs before running the notebooks.
