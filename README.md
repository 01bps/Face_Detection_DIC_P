# Face Detection, Training, and Recognition Project

## Overview:

This project focuses on developing a robust facial recognition system in three main phases: face detection, training, and recognition. Leveraging the power of computer vision, OpenCV, and machine learning, the system employs the Haar cascading method for efficient face detection and recognition. The project utilizes popular Python libraries such as OpenCV, NumPy, PIL, and OS for image processing, numerical operations, and file handling.

## Phases:

### 1. Face Detection:
   - **Method:** The Haar cascading method is employed for real-time face detection.
   - **Libraries:** OpenCV is used to load the pre-trained Haar cascade classifier, while NumPy assists in efficient numerical operations.

### 2. Training:
   - **Algorithm:** The LBPH (Local Binary Pattern Histogram) Face Recognizer is employed for training the system.
   - **Data Handling:** Images are processed using the PIL (Python Imaging Library), and face data is stored with OS library functions.
   - **Storage:** The trained model is saved into a YAML file using OpenCV's LBPHFaceRecognizer.

### 3. Recognition:
   - **Integration:** The trained model is integrated into the recognition phase using Haar cascading for face detection and LBPH Face Recognizer for identification.
   - **Real-time Display:** The recognized faces are annotated in real-time video streams, displaying names and confidence levels.

## Libraries Used:

- **OpenCV:** Utilized for image and video processing, Haar cascading, and LBPH Face Recognizer.
- **NumPy:** Used for efficient numerical operations and array manipulations.
- **PIL (Python Imaging Library):** Employed for image loading, grayscale conversion, and preprocessing.
- **OS:** Facilitates file and directory manipulation, crucial for managing datasets and trained models.

## Sample Usage:

- Execute `face_detection.py` for real-time face detection using the Haar cascade method.
  Note: Create a dataset Subfolder in the parent directory.
- Run `training.py` to train the system on a dataset of faces.
  Note: Create a trainer Subfolder in the parent directory.
- Utilize `recognition.py` for real-time face recognition with annotations.

Feel free to contribute, report issues, or extend the project for personalized use cases!

---
