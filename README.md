🚦 Traffic Management Using AI (YOLOv8)

An AI-powered Smart Traffic Management System that detects vehicles in real-time using YOLOv8 and optimizes traffic signal timings based on traffic density. This project demonstrates the use of Computer Vision, Machine Learning, and Real-Time Analysis to reduce congestion and support intelligent transportation systems.

📌 Features

Real-time vehicle detection using YOLOv8

Detects: Car, Bus, Bike, Truck, Rickshaw

Dynamic traffic signal control based on lane density

Static & Dynamic traffic simulation

Charts and graphs for comparison

Lane-wise direction support: Up, Down, Left, Right

🎯 Objective

To automate and optimize traffic signal timing using AI by analyzing road traffic density and vehicle movement, reducing congestion and improving traffic flow efficiency.

🧠 Technologies Used

Python

YOLOv8 (Ultralytics)

OpenCV

NumPy

Matplotlib

📂 Project Structure
Traffic-Management-Using-AI/
│
├── images/
│   ├── signals/
│   ├── up/
│   ├── down/
│   ├── left/
│   ├── right/
│   └── intersection.jpg
│
├── Video/
│   ├── Static.mp4
│   └── Dynamic.mp4
│
├── Charts/
│   ├── chart.py
│   ├── chart.csv
│   ├── Comparison.png
│   └── graph.png
│
├── simulationDy.py
├── simulationstate.py
├── README.md
└── requirements.txt

▶️ How to Run
1️⃣ Install dependencies
pip install -r requirements.txt

2️⃣ Run Dynamic Traffic Simulation
python simulationDy.py

3️⃣ Run Static Traffic Simulation
python simulationstate.py

📺 Demo Videos

Add your video demo links here:

Dynamic Simulation → link here

Static Simulation → link here

📊 Charts & Analysis

Charts inside the Charts/ folder show:

Traffic density comparison

Static vs Dynamic performance

Lane-wise vehicle counts

🌟 Future Improvements

Live CCTV camera integration

Predictive traffic forecasting (LSTM)

Multi-intersection coordination

Deployment on edge devices (Raspberry Pi / Jetson Nano)

👩‍💻 Author

Bhavya Sri
GitHub: @bhavyasri0331

📜 License

This project is open-source under the MIT License.
