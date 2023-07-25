# CodeClause_Age_and_Gender_Detection
Age and Gender Detection with Machine Learning by using the Python programming language. Age and Gender Detection is the task of Computer vision so I will be using the OpenCV library in Python.
The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, I made this a classification problem instead of making it one of regression.

# The contents of this Project :
opencv_face_detector.pbtxt
opencv_face_detector_uint8.pb
age_deploy.prototxt
age_net.caffemodel
gender_deploy.prototxt
gender_net.caffemodel

For face detection, we have a .pb file- this is a protobuf file (protocol buffer); it holds the graph definition and the trained weights of the model. We can use this to run the trained model. And while a .pb file holds the protobuf in binary format, one with the .pbtxt extension holds it in text format. These are TensorFlow files. For age and gender, the .prototxt files describe the network configuration and the .caffemodel file defines the internal states of the parameters of the layers.

# Usage :
Download my Repository
Open your Command Prompt or Terminal and change directory to the folder where all the files are present.
Detecting Gender and Age of face through webcam Use Command :
  python main.py
Press 'q' to stop the program execution.

# Examples :
![Screenshot 2023-07-25 121713](https://github.com/Nidhi2003/CodeClause_Age_and_Gender_Detection/assets/91655994/bdb0447a-7a1a-4c55-91e3-c84c17a3c0eb)

![image](https://github.com/Nidhi2003/CodeClause_Age_and_Gender_Detection/assets/91655994/a71d8bec-d199-42d2-bbad-03fb77d4b724)


