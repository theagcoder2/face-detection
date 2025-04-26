# face-detection
  This project demonstrates real-time face detection using the Haar Cascade Classifier technique implemented through the OpenCV library in Python.  
  By leveraging a pre-trained model (`haarcascade_frontalface_default.xml`), the application identifies human faces from a live webcam feed and highlights them with bounding boxes.

# Technologies and Libraries
  Python 3.x
  OpenCV (cv2)

# Install Python Libraries**
   Open your terminal or command prompt and run the following command to install OpenCV:
 
# pip install opencv-python

git clone 

Face-Detection/
├── face_detection.py                
├── haarcascade_frontalface_default.xml  
├── README.md    

# Steps to Use This

1. Open a terminal in the project directory.
2.Execute the Python script:
3.A window will appear showing your webcam feed.
Faces detected within the video stream will be enclosed within a rectangular box.

# Press the 'q' key to exit the application.  

# How it Works 

1. Capture Frames: OpenCV captures continuous frames from the webcam.
2.Preprocessing: Each frame is converted to grayscale to simplify computations.
3.Detection: The Haar Cascade Classifier slides a small window over the image and applies trained features to detect facial patterns.
4.Result: If a face is detected, OpenCV draws a rectangle around it on the live video stream.

![image](https://github.com/user-attachments/assets/5b979849-e7b5-4fa8-af75-83cdda9a2286)

![image](https://github.com/user-attachments/assets/13f5f4ea-bd38-4f91-b52c-f737a4bf34f3)






