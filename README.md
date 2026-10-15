# Bacheror's thesis
 
In this repository is shown a CNN created by Aleksandr Pavlenko during bachelor's thesis work.

To work with this repository, you need to install libraries

* skbuild (pip install scikit-build)
* cv2 (pip install opencv-python)
* torch (pip install torch)


To test the model in real time, you need to run the webcam_fer.py file in the Application_for_real_time_testing folder

## Brief description of all folders:
* Application_for_real_time_testing - folder for testing the model in real time. The webcam_fer.py file accepts a video stream from a webcam as input and draws a rectangle with the name of an emotion in the area of all faces in the image in real time.

* Best_model - the folder contains the EmotionClassifier_v16_nc16_ep50.pth file, which is the model. Moreover, the folder contains training logs and visualization of the training process. From the name of the model, we can get the information that the model is the 16th version model of the EmotionClassifier class, it takes 16 neurons for input, 50 epochs were allocated for training.

* CNN_training - folder with training notebook and dataset.

* haarcascades - folder containing haar cascades for face detection in video.
