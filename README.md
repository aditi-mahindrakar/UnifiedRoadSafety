# Unified Road Safety: Animal-Vehicle Collision Prevention

This system uses an **ESP32 Cam** and **YOLO** object detection to prevent animal-vehicle collisions on highways.

## 🚀 How it Works
1. **Detection:** The ESP32 Cam captures live video.
2. **AI Processing:** A YOLO model identifies animals (cattle, dogs, etc.) in real-time.
3. **Alert:** A buzzer and LED alert the driver when a collision risk is detected.

## 📸 System in Action
![Live Testing](live%20testing.jpg)

## ⚙️ Software Setup
To run the YOLO server, you need to install the required Python libraries. Run the following command in your terminal:

```bash
pip install -r requirements.txt
```

## 🛠️ Hardware Used
- ESP32 Cam Module
- ESP32 Devkit
- LED & Buzzer for alerts

---
*Note: This project includes code optimized with the assistance of AI for real-time detection logic.*
