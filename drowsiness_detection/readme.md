# The approach used for this Python project is as follows :

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy.


# Dataset
Download the dataset: Driver Drowsiness Dataset

# The Model Architecture
The CNN model architecture consists of the following layers:

Convolutional layer; 32 nodes, kernel size 3

Convolutional layer; 32 nodes, kernel size 3

Convolutional layer; 64 nodes, kernel size 3

Fully connected layer; 128 nodes

# Project Prerequisites
The requirement for this Python project is a webcam through which we will capture images. You need to have Python (3.6 version recommended) installed on your system, then using pip, you can install the necessary packages.

OpenCV – pip install opencv-python (face and eye detection).

TensorFlow – pip install tensorflow (keras uses TensorFlow as backend).

Keras – pip install keras (to build our classification model).

Pygame – pip install pygame (to play alarm sound).

# Input/Output

![WhatsApp Image 2023-01-21 at 4 33 42 PM](https://user-images.githubusercontent.com/73791285/213864181-51632847-e33c-4d2d-9f9b-1f8c6f9c9a6d.jpeg)
![WhatsApp Image 2023-01-21 at 4 34 52 PM](https://user-images.githubusercontent.com/73791285/213864187-3324c1f2-0342-4947-98d0-c30c1ae750fc.jpeg)
![WhatsApp Image 2023-01-21 at 4 35 58 PM](https://user-images.githubusercontent.com/73791285/213864173-21209897-03d9-48af-86ca-38efca485996.jpeg)
