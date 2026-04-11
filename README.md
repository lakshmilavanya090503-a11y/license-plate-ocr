🚗 License Plate Detection & Recognition System

📖 Overview

This project is a real-time License Plate Detection and Recognition System built using YOLOv8 and EasyOCR. It detects vehicle license plates from a live video stream and extracts the alphanumeric text using OCR techniques.

Additionally, the system integrates with hardware through serial communication to enable automated access control based on recognized license plate numbers.

---

🎯 Objectives

- Detect vehicle license plates in real-time
- Extract text using OCR
- Automate access control using hardware integration
- Build a practical AI-based surveillance system

---

🧠 Key Features

- 🚀 Real-time object detection using YOLOv8
- 🔍 Accurate text recognition using EasyOCR
- 🔗 Serial communication with external hardware (Arduino)
- ⚡ Automated access control system
- 📹 Live camera feed processing
- 🧾 Bounding box visualization with labels

---

🏗️ System Architecture

1. Capture video stream from webcam
2. Detect license plates using YOLOv8
3. Crop detected region
4. Apply OCR using EasyOCR
5. Validate extracted text
6. Send signal via serial communication
7. Display results with bounding boxes

---

🛠️ Tech Stack

- Programming Language: Python
- Computer Vision: OpenCV
- Object Detection: YOLOv8 (Ultralytics)
- OCR: EasyOCR
- Hardware Communication: PySerial
- Configuration Management: Hydra
- Deep Learning Framework: PyTorch

---

📂 Project Structure

license-plate-ocr/
 ├── server/
 │    └── main.py
 ├── requirements.txt
 ├── README.md
 ├── .gitignore
 └── LICENSE

---

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone (https://github.com/lakshmilavanya090503-a11y/license-plate-ocr.git)
cd license-plate-ocr

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the project

python server/main.py

---

🔌 Hardware Integration

This project uses serial communication to interact with external hardware (e.g., Arduino).

- Port: COM5
- Baud Rate: 9600
- Sends signal when an authorized license plate is detected

---

📸 Output

- Real-time detection with bounding boxes
- Extracted license plate text displayed on screen
- Serial signal sent for authorized access

(Add screenshots or demo video here)

---

🚀 Future Enhancements

- 🌐 Web-based dashboard (React frontend)
- 🗄️ Database integration for storing logs
- 🔐 User authentication system
- 📊 Analytics dashboard
- ☁️ Cloud deployment

---

📚 Learning Outcomes

- Practical implementation of computer vision
- Working with real-time object detection models
- OCR integration in real-world scenarios
- Hardware-software communication
- End-to-end system development

---

⚠️ Limitations

- OCR accuracy depends on image quality
- Performance may vary in low lighting
- Requires proper camera positioning

---

🔄 System Flow

Flow Charts
![Flow 1](assets/flow1.png)
![Flow 2](assets/flow2.png)
![Flow 3](assets/flow3.png)

---

📷 Results

Detection Outputs
![Result 1](assets/result1.png)
![Result 2](assets/result2.png)
![Result 3](assets/result3.png)
![Result 4](assets/result4.png)

---

👩‍💻 Author

Lakshmi Lavanya

---

📜 License

This project is licensed under the MIT License.
