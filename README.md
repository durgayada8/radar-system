# 🚀 Radar System Using Ultrasonic Sensor

## 📖 Overview
This project is a radar system built using an Arduino Uno, ultrasonic sensor, servo motor, and buzzer. It scans the environment in a 180° arc and detects objects using the ultrasonic sensor. The detected data is sent to the Processing IDE, where a real-time radar-like graphical interface visualizes the results.

## 🧰 Components Used
- Arduino Uno  
- Ultrasonic Sensor (HC-SR04)  
- Servo Motor (SG90 or MG995)  
- Buzzer  
- Jumper Wires  
- Arduino IDE  
- Processing IDE (`.pde` file)

## ⚙️ How It Works
1. The servo motor rotates the ultrasonic sensor from 0° to 180° and back.
2. The ultrasonic sensor measures distances at each step.
3. If an object is detected within a specified range, the buzzer is activated.
4. The measured data (angle and distance) is transmitted to the Processing IDE through the serial port.
5. The Processing sketch displays this data in a real-time radar-style visualization.

## 🛠️ Setup Instructions

### Arduino IDE
1. Download and install the Arduino IDE from [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software).
2. Open the Arduino sketch (`.ino` file).
3. Connect your Arduino Uno and upload the code.
4. Ensure the correct board and port are selected.

### Processing IDE
1. Download and install Processing IDE from [https://processing.org/download](https://processing.org/download).
2. Open the Processing sketch (`.pde` file).
3. Set the correct serial port in the sketch (adjust `Serial.list()` index).
4. Run the sketch to view real-time radar visualization.

## ✅ Features
- Real-time object detection
- Audible alert using buzzer
- 180° environmental scanning
- Graphical radar interface using Processing IDE

## 🔧 Future Enhancements
- Add logging for detected object positions
- Integrate IoT to monitor remotely
- Improve visualization with color-coded distance markers

## 📞 Contact
Created by **Durga Dilip Yadav**  
GitHub: [https://github.com/](https://github.com/)  
LinkedIn: [https://www.linkedin.com/in/durga-yadav-913780308](https://www.linkedin.com/in/durga-yadav-913780308)
