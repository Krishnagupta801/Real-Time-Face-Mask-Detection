## Key Features
* Real-time detection from webcam or CCTV
* High accuracy using deep learning (CNN)
* Visual alerts with colored boxes and labels
* Works with multiple faces at the same time
* Easy to customize / retrain with new datasets

## Technologies Used
Python

OpenCV (for image processing & face detection)

Keras / TensorFlow (for mask classification model)

NumPy & pandas (data handling)

(Optional) Streamlit / Flask (for web dashboard)

## How it works (Workflow)
Capture video frames from webcam.

Detect faces using OpenCV or a DNN-based detector.

Pass detected face ROIs to the trained CNN model.

Predict mask / no-mask.

Draw bounding boxes and display labels on the frame.

Repeat continuously in real time.

## Applications
Offices & public places for mask compliance

Hospitals & clinics

Educational institutions

Malls, airports, and stations

##Future Improvements
Add social distancing detection

Detect incorrect mask usage (e.g., below the nose)

Deploy as a web app or mobile app

Integrate with alert systems (buzzer or email notifications)
