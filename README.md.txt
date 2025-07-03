# 🚗 Autonomous Vehicle Guidance using Color Signals

This project demonstrates a simple autonomous vehicle system that detects color signals through a webcam and sends movement commands to a car powered by an Arduino and motors.

## 🔍 Objective

Guide an autonomous vehicle using predefined color cues such as red, green, blue, etc. to perform actions like move forward, stop, turn left/right, or reverse.

---

## 🎯 Color to Action Mapping

| Color         | Action           |
|---------------|------------------|
| Green         | Move Forward     |
| Red / Apple   | Stop             |
| Yellow/Orange | Turn Right       |
| Blue/Violet   | Turn Left        |
| Black/White   | Move Backward    |

---

## 🛠️ Tech Stack

- **Python**
  - OpenCV
  - PySerial
  - KNN Classifier
- **Arduino**
  - NodeMCU ESP8266
  - L298N Motor Driver
  - DC Motors

---

## 📁 Project Structure


---

## 🔄 How It Works

1. `main.py` uses OpenCV to detect color in webcam.
2. KNN classifier maps color to label (e.g., green, red).
3. Serial command is sent to Arduino (e.g., `F` for forward).
4. Arduino runs `vehicle_movement.ino` and moves the car accordingly.

---

## 📚 Credits

Developed by:
- Sowmya Namburi
- Team Members: K. Priyanka, N. Rushika, T. Thriveni, N. Pavani  
Under the guidance of Dr. Peda Gopi Arepalli & K. Jyosthna

---

## 🌐 License

Open for educational use. Contact for collaboration.

## 📺 Full Demo Video

[▶️ Watch Full Demo on Google Drive]

https://drive.google.com/file/d/1fsjYgX5msgtyckHfGpDSuvrwwEaVTpyQ/view?usp=sharing
