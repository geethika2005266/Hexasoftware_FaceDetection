# HexSoftwares_Face-Detection
# Face Detection Using OpenCV in Python
Demo vedio link:https://drive.google.com/file/d/1c45pwuytLz7c-pq9RBgDETEFPCyc5TRP/view?usp=drivesdk

Face Detection using OpenCV

This project implements Face Detection on both images and real-time video streams using OpenCV’s Deep Neural Network (DNN) module and a pre-trained Caffe deep learning model.

✨ Features

🔍 Detects faces in images with bounding boxes and confidence scores

🎥 Real-time face detection via webcam feed

⚙️ Adjustable confidence threshold to filter weak detections

🖼️ Detection results displayed on-screen and in terminal logs

🛠️ Tech Stack

Python 3.7+

OpenCV (cv2) with DNN module

NumPy

Imutils

⚙️ Installation

1.Clone the Repository

cd face-detection-opencv


2.Create a Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3.Install Dependencies

pip install -r requirements.txt


4.Download Pre-trained Model Files

deploy.prototxt → Network architecture definition

res10_300x300_ssd_iter_140000.caffemodel → Pre-trained model weights

You can download them from:

deploy.prototxt

res10_300x300_ssd_iter_140000.caffemodel

Place both files in the project directory.

🚀 Usage
1️⃣ Detect Faces in an Image
  
  python detect_faces.py \
  --image sample1.jpg \
  --prototxt deploy.prototxt \
  --model res10_300x300_ssd_iter_140000.caffemodel

2️⃣ Real-Time Face Detection (Webcam)
 
  python detect_faces_video.py \
  --prototxt deploy.prototxt \
  --model res10_300x300_ssd_iter_140000.caffemodel

📂 Project Structure
face-detection-opencv/

├── detect_faces.py              # Image-based face detection

├── detect_faces_video.py        # Real-time face detection via webcam

├── deploy.prototxt              # Model architecture

├── res10_300x300_ssd_iter_140000.caffemodel  # Pre-trained model

├── requirements.txt                        # Project dependencies

└── sample1.jpg                            # Example input image

💡 Applications

🔐 User Authentication Systems

🎞️ Photo/Video Tagging

🕵️ Surveillance & Security Systems

🤖 Human-Computer Interaction (HCI)

<img width="1330" height="1000" alt="image" src="https://github.com/user-attachments/assets/39d6cdfc-1c75-49e3-bc43-6e3bd5e593b6" />


