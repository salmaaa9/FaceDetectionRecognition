# FaceDetectionRecognition
Objective: 
The objective is to develop a face recognition system using deep learning and transfer learning techniques on a Pins Face detection on Kaggle. This system will involve face detection and face recognition capabilities that operate in real-time.

Dataset
Available on Kaggle: 
https://www.kaggle.com/datasets/hereisburak/pins-face-recognition
This project is divided into two phases face detection and then face recognition.
Steps
1) Implement face detection using OpenCV's deep learning-based detector.
Use the UINT8 model for transfer learning.
Utilize the weights and architecture files from the previous lab session.
2) Crop faces from the dataset using the OpenCV DNN module.
Create a modified dataset comprised only of the cropped faces
Execute face recognition using Aby pretrained model.
3) Apply Transfer Learning using the TensorFlow library for transfer learning any pre-trained model using VGG, Inception, or ResNets
Update the model weights using the wights file coule be found in github.
 4) Improve model accuracy with additional dense and softmax layers after transfer learning. Apply regularisation techniques.
Attain over 85% accuracy on the validation dataset.
5) Enable the model to identify faces not previously classified.
Option 1: iImplement cosine similarity for recognizing unclassified faces as per a class named "not identified" 
Option 2: utilize a dataset of 10,000 to 70,000 non-defined photos for this task.
You can use any other options.
6) Ensure the model functions with a live camera feed, rather than just static photos. (Bonus)
7) Bonus: Develop a model that simultaneously performs face detection and recognition in a live stream at the same time with the same Neural Network (MIMO). 
