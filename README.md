🪪 ID Card Detection using YOLOv8

This project uses YOLOv8 (You Only Look Once) object detection to detect ID cards and persons in images.
The model is trained using a custom dataset and can identify ID cards in real-world images.

🚀 Project Overview

The goal of this project is to build a computer vision system that can automatically detect ID cards in images.
This can be useful for:

College entry verification

Workplace security

Event access control

Attendance systems

The model is trained using YOLOv8 and performs real-time object detection.

🧠 Model Used

YOLOv8 (Ultralytics)

Python

OpenCV

The model detects the following classes:

Class ID	Object
0	ID Card
1	Person
📂 Project Structure
id-card-detection-yolov8
│
├── src/
│   └── index.py
│
├── config/
│   └── data.yaml
│
├── test_images/
│
├── results/
│
├── requirements.txt
└── README.md
⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/yourusername/id-card-detection-yolov8.git
cd id-card-detection-yolov8
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Install YOLOv8
pip install ultralytics
▶️ Run Detection

Run the detection script:

python src/index.py

The model will detect ID cards and persons in the image and display bounding boxes.

📊 Example Output

The model detects objects and shows bounding boxes with confidence scores.

Example:

person 0.95

person 0.91

idcard 0.55

Detection results are saved in the results/ folder.

📦 Dataset

The dataset used for training is not included in this repository because of GitHub size limits.

Dataset structure used for training:

dataset
│
├── train
├── valid
└── test

Each folder contains:

images/
labels/
📈 Future Improvements

Improve ID card detection accuracy

Real-time webcam detection

OCR to extract ID card information

Deploy as a web application

👨‍💻 Author

Developed by Sivamurugan Balasekar
