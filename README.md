# nomade-yolo
Nomade Rover - AI Object Detection System


his repository contains an AI-powered object detection module for the Nomade Rover. It leverages a camera and YOLOv8 to detect and classify various objects in real time. The system is designed for tactical defense, surveillance, and autonomous navigation.

Features ✨
✅ Real-time Object Detection – Uses YOLOv8 for fast and accurate recognition.
✅ Camera Integration – Supports RGB & Depth Cameras for better scene understanding.
✅ ROS2 Compatible – Designed to work seamlessly within the Nomade Rover ecosystem.
✅ Customizable Models – Fine-tune YOLOv8 to detect specific objects based on mission needs.
✅ Edge Processing – Optimized for deployment on NVIDIA Jetson hardware.

Installation & Usage 🛠️
1️⃣ Clone the repository


git clone 
cd nomade-rover-ai
2️⃣ Install dependencies


pip install -r requirements.txt
3️⃣ Run the AI Detection Node


ros2 launch nomade_ai object_detection.launch.py
Future Enhancements 🚀
🔹 Multi-camera support for 360° vision
🔹 Integration with Nav2 for autonomous navigation
🔹 Improved AI models for better accuracy

