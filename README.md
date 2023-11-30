# Pose based Form Correction Trainer
- Pose Estimation Module – MediaPipe framework for estimating key points and pose in our video input.
- Form Verification Module
  – Angle Evaluation : We calculate the angle between relevant key points depending on the exercise being performed in this method.
  – Machine Learning Approach : K Means Clustering
- Form Correction Module
  – Incorrect joint detection + Improvements that needs to be made on the user form

![Form Correction Trainer Pipeline](/form2.png)

## Required libraries: 

* numpy
* pandas
* matplotlib
* opencv-python
* mediapipe
* traceback
* math

## Project Structure:

* main.py
* Input_data.csv
* BicepCurl.py
* Lunges.py
* PoseUtils.py
* Model.py
* CollectData.py

## Execution Instructions:

* For Bicep curl exercise execute command “python main.py bicep_curl” on your terminal/powershell.
* For lunges exercise execute command “python main.py lunges” on your terminal/powershell
