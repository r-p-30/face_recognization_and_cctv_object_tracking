# Setup Instructions for Python Environment with Libraries

# Object Tracking and Face Detection
This detects and trackes a moving face in a live frame. it also captures the face for further prcessing.

## Requirements
- Python
- Anaconda
- pip
- Jupyter Notebook

## Steps to Set Up Environment

### 1. Install Anaconda
If you don't have Anaconda installed, download and install it from the official Anaconda website (https://www.anaconda.com/products/distribution).


### 2. Install Required Libraries

#### Install OpenCV
To install the `opencv-python` library, which includes the core OpenCV, use the following pip command:

pip install opencv-python

#### Install OpenCV (with Contrib modules)
To install the `opencv-contrib-python` library, which includes both the core OpenCV and extra modules, use the following pip command:

pip install opencv-contrib-python


#### Install MediaPipe
To install `mediapipe`, run:

pip install mediapipe


### 3. Install Jupyter Notebook
To use Jupyter Notebook, install it with:

pip install notebook


### 4. Launch Jupyter Notebook
Once everything is installed, launch Jupyter Notebook by running:

jupyter notebook

This will open a new tab in your browser where you can start writing your Python code in notebooks.


# Face Recognizer
The model can recognize faces in real-time video feeds or static images using Harcascade or siemese networks to recognize a face. 

## Requirements
- Python
- Anaconda
- pip
- Jupyter Notebook

## Steps to Set Up Environment

### 1. Install Anaconda
If you don't have Anaconda installed, download and install it from the official Anaconda website (https://www.anaconda.com/products/distribution).

### 2. Install required libraries
- pip install opencv-python
- pip install cmake
- pip install face_recognition
- pip install mediapipe
- pip install numpy
- pip install tensorflow
- pip install scikit-learn
- pip install scipy

### 3. Install Jupyter Notebook
To use Jupyter Notebook, install it with:

pip install notebook


### 4. Launch Jupyter Notebook
Once everything is installed, launch Jupyter Notebook by running:

jupyter notebook

This will open a new tab in your browser where you can start writing your Python code in notebooks.

## Dataset Requirements
To ensure accurate face recognition, the model should be trained on a dataset that includes **at least 10 images per individual**. These images should capture a variety of conditions, including:

- Different **angles** (front, left, right, slightly up/down)
- Varying **lighting conditions**
- **Accessory changes**:
  - Hair up/down
  - With/without glasses
  - With/without beard

This diversity helps the model generalize better and recognize faces even under real-world variability.


***P.S. Restart kernel in case of 'module not found' or 'no attribute' errors if all libraries are installed properly. Create necessary folders per your structure.***
