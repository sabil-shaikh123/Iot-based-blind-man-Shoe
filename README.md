# Obstacle Detection with Ultrasonic Sensor and Buzzer 🚨

This project demonstrates a simple **obstacle detection system** using an **ultrasonic sensor (HC-SR04)** and a buzzer. The buzzer's volume varies based on the distance of the detected object, providing real-time audio feedback.

---

## 🔧 Features

- **Distance Measurement**: Calculates distance using an ultrasonic sensor (HC-SR04).
- **Dynamic Audio Alerts**: Produces variable buzzer sounds based on object proximity.
- **Real-Time Feedback**: Outputs distance measurements to the Serial Monitor for debugging.

---

## 📂 Components Used

- **Arduino Board** (e.g., Uno, Mega, Nano)
- **Ultrasonic Sensor** (HC-SR04)
- **Buzzer**
- **Jumper Wires and Breadboard**

---

## 📜 How It Works

1. The **trig pin** sends ultrasonic pulses.
2. The **echo pin** listens for the reflected signal.
3. The distance is calculated using the time it takes for the pulse to return.
4. If an object is detected within the specified range, the buzzer sound varies with the object's distance.

---
