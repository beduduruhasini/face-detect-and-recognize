Face and Object Detection using OpenCV
📌 Project Overview

This project demonstrates Face Detection and Object Detection using Python and OpenCV. It uses pre-trained Haar Cascade classifiers to detect faces and common objects in real-time through a webcam or from images/videos.

The project is suitable for beginners in Computer Vision and helps understand how real-time detection systems work.

🎯 Features

Real-time Face Detection using webcam

Object Detection using Haar Cascade classifiers

Works on images, videos, and live camera feed

Simple and beginner-friendly implementation

Fast and lightweight using OpenCV

🛠️ Technologies Used

Python 3

OpenCV (cv2)

Haar Cascade Classifiers

NumPy

📂 Project Structure
face-object-detection/
│
├── src/
│   ├── face_detection.py
│   ├── object_detection.py
│   └── main.py
│
├── cascades/
│   ├── haarcascade_frontalface_default.xml
│   └── haarcascade_eye.xml
│
├── requirements.txt
├── README.md
└── LICENSE

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/face-object-detection.git
cd face-object-detection

2️⃣ Install Required Libraries
pip install -r requirements.txt


Or manually:

pip install opencv-python numpy

▶️ How to Run the Project
Run Face Detection
python src/face_detection.py

Run Object Detection
python src/object_detection.py

Run Main Program
python src/main.py


📷 Press q to exit the camera window

🧠 How It Works

The program captures frames from a webcam.

Each frame is converted to grayscale.

Haar Cascade classifiers scan the image for features.

Detected faces/objects are highlighted using bounding boxes.

📸 Sample Output

Detects faces with a rectangular bounding box

Supports multiple face detection

Real-time video processing

🚀 Applications

Surveillance systems

Attendance systems

Security applications

Face recognition projects

Human-computer interaction

🔮 Future Enhancements

Add face recognition

Improve accuracy using Deep Learning (DNN, CNN)

Support multiple object detection models

Add GUI interface

👩‍💻 Author

BEDURU HASINI
B.Tech – Computer Science Engineering

📜 License

This project is licensed under the MIT License – feel free to use and modify.
