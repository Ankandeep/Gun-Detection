🚀 Project Overview

This project implements a Gun Detection System using Python and OpenCV. It captures video from a webcam (or video file) and applies computer vision techniques to detect guns in real time.

The system uses Haar Cascade / custom-trained classifier to detect guns in frames and highlights them with bounding boxes. Such systems can be applied in security monitoring, surveillance, and safety applications.

📂 Features

✅ Real-time gun detection using webcam

✅ Detection from pre-recorded video files

✅ Bounding boxes drawn around detected guns

✅ Easy to run on any machine with Python & OpenCV

🛠️ Technologies Used

Python 3.x

OpenCV (cv2)

NumPy

Haar Cascade / Custom Classifier (XML file)

📥 Installation
1️⃣ Clone the Repository
git clone https://github.com/Ankandeep/gun-detection-opencv.git cd gun-detection-opencv

2️⃣ Install Dependencies

Make sure Python is installed, then install the required packages:

pip install opencv-python numpy

3️⃣ Download Haar Cascade / Classifier

Place your cascade.xml (gun detection classifier) file in the project directory.

▶️ Usage
Run with Webcam:
python gun_detection.py

Run with Video File:
python gun_detection.py --video sample.mp4


Detected guns will be highlighted with red bounding boxes in the output window.

Press q to exit.
