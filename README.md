# Emotion Detection using Webcam

## Overview
This project is an Emotion Detection system that utilizes a Convolutional Neural Network (CNN) model for real-time analysis of facial expressions. It was developed during a Microsoft Engage mentorship and includes features such as overlaying predicted emotions on the webcam feed and capturing frames with predicted emotions for further analysis.


## Screenshots
DashBoard
![ECOMART SALE DASHBOARD_page-0001](https://github.com/Sameer1232018/powerBI_Dashboard/assets/49482350/563035fb-2adf-4b8e-8c50-2b2f51e31790)

## Key Features
- Real-time Emotion Detection: Utilizes a CNN model to analyze facial expressions in real-time through the webcam.
- Overlay Predicted Emotions: Displays predicted emotions as an overlay on the webcam feed, providing immediate feedback.
- Frame Capture: Allows users to capture frames with predicted emotions for further analysis or storage.

## Technologies Used
- Python: The primary programming language for the project.
- Keras: Used for building and training the CNN model.
- OpenCV: Utilized for accessing and processing webcam video feeds.
- TensorFlow: Backend for Keras model.
- Additional Python libraries: NumPy, Matplotlib, etc.
## Dataset
The project used the (https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset) dataset from Kaggle. This dataset provides a diverse collection of facial images with expressions, which can be used for training and evaluation.

## Project Structure
- README.md               # Project documentation
- emotion-classification-cnn-using-keras.ipynb   # Jupyter Notebook with code and explanations
- haarcascade_frontalface_default.xml   # Haar Cascade XML file for face detection
- main.py                 # Main Python script for running the emotion classification
- model.h5                # Pre-trained CNN model for emotion classification
- tempCodeRunnerFile.py   # Temporary code runner file (can be removed)


## Getting Started
1. Clone the repository to your local machine:
2. Set up the required Python environment and dependencies:

3. Download the pre-trained model (`model.h5`) from [here](provide-download-link) and save it to a local directory of your choice.

4. Open the `main.py` file and update the `load_model` line with the local path to your downloaded `model.h5` file:
   classifier = load_model(r'path_to_your_model.h5')
5. Run the main.py script:
6. Press 'Q' to quit the application
