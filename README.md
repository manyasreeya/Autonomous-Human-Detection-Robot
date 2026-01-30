Autonomous Human Detection Robot
About the Project

The Autonomous Human Detection Robot is a computer vision–based project built to detect the presence of humans in real time. The idea behind this project is to assist in situations where human detection is critical, such as disaster rescue operations, surveillance systems, and autonomous robots navigating unknown environments.

The system uses OpenCV’s Haar Cascade classifier to identify full human bodies from a live video feed and marks them clearly for easy recognition.

Why This Project?

In disaster-prone or restricted areas, manually searching for humans can be risky and time-consuming. This project explores how computer vision can help automate human detection, making it useful for:

Search and rescue missions

Security and surveillance

Autonomous robotic applications

Key Features

Detects humans in real time using a webcam

Uses Haar Cascade full-body classifier

Draws bounding boxes around detected humans

Simple, lightweight, and easy to execute

Beginner-friendly OpenCV implementation

Tech Stack

Python

OpenCV

Computer Vision

How It Works

The program captures live video frames from a webcam, converts them into grayscale images, and applies a Haar Cascade classifier trained to recognize human body patterns. When a human is detected, the system highlights the region with a bounding box.

Getting Started
1. Clone the Repository
git clone https://github.com/your-username/Autonomous-Human-Detection-Robot.git

2. Install Dependencies
pip install opencv-python

3. Run the Application
python human_detection.py

4. Exit

Press Q on the keyboard to stop the program.

Output

The system continuously scans the video feed and displays bounding boxes around detected humans in real time.

Future Enhancements

Replace Haar Cascades with deep learning models (YOLO / SSD)

Improve accuracy in low-light conditions

Integrate with robotic hardware

Send alerts when humans are detected

Author

Manya Sreeya
Computer Science Engineering Student
