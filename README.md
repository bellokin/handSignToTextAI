Sign Language Recognition AI
This project is a real-time sign language recognition AI built using Python, TensorFlow, and MediaPipe. The model can recognize hand gestures for American Sign Language (ASL) and display predictions on the screen.

Features
Real-time hand tracking and gesture recognition using MediaPipe.
Predicts ASL gestures (A-Z, 0-9).
Includes the dataset used for training within the repository for easy reproduction.
Designed to work efficiently on most systems.
Easy to set up and use.
Requirements
Python 3.8 or higher
Anaconda (recommended)
TensorFlow
MediaPipe
OpenCV
NumPy
scikit-learn
Setup Instructions
Clone the Repository

bash
Copy code
git clone  the repo
cd sign-language-recognition
Set Up Environment

Open Anaconda Prompt and create a new environment:
bash
Copy code
conda create --name signlang python=3.8
conda activate signlang
Install Dependencies

bash
Copy code
pip install tensorflow mediapipe opencv-python-headless numpy scikit-learn
Run the Application

Start the script using the command:
bash
Copy code
python main.py
Using the Application

Ensure your webcam is connected.
Perform ASL gestures in front of the camera.
The recognized gesture will appear on the screen.
Dataset
The American Sign Language Dataset used for training is included in the asl_dataset folder within the repository.

If you need to retrain the model, simply load the dataset from this folder. The directory structure is already prepared for training:
 
Copy code
archive/asl_dataset/
├── 0/
├── 1/
├── 2/
├── ...
├── a/
├── b/
├── ...
└── z/
License
This project is licensed under the MIT License. See the LICENSE file for details.
 
