# 🚗 Intelligent Parking Solution 

An IoT-based Smart Parking System that monitors and manages parking space availability in real time using sensors, LCD display, and wireless communication. The system helps reduce traffic congestion, improve user experience, and provide real-time updates through Blynk or Firebase.

## 📌 Project Description

The **Intelligent Parking Solution** is designed to automate the detection of available parking slots and control the entry/exit of vehicles using IR sensors, servo motors, and a central Arduino controller. The system includes real-time updates to a cloud platform (Firebase or Blynk) for monitoring slot status remotely.

## 🔧 Features

- Real-time detection of available and occupied parking slots
- Automated gate control using servo motors
- LCD display showing available slots and slot assignment
- Buzzer alert for gas or fire detection (via MQ2 and DHT11 sensors)
- Temperature and gas data monitoring
- Firebase/Blynk integration for real-time remote access
- LED indicators for slot availability
- Scalable for multi-slot configurations

## 🔩 Components Used

- Arduino Uno
- NodeMCU (for Wi-Fi connectivity and Firebase/Blynk communication)
- IR Sensors (for slot, entry, and exit detection)
- Servo Motors (Entry & Exit gate control)
- 16x2 I2C LCD Display
- Green/Red LEDs (Slot status)
- Buzzer (Alert system)
- MQ2 Gas Sensor
- DHT11 Temperature Sensor
- Jumper wires, breadboard, and power supply

## 🛠️ Circuit Configuration (Arduino)

| Component            | Pin (Arduino) |
|----------------------|----------------|
| IR1                  | D2             |
| IR2                  | D3             |
| IR3                  | D4             |
| Entry IR             | D5             |
| Exit IR              | D6             |
| Green LED            | D7             |
| Red LED              | D8             |
| Entry Gate Servo     | D9             |
| Exit Gate Servo      | D10            |
| Buzzer               | D11            |
| MQ2 (Analog Out)     | A0             |
| LCD I2C (SDA)        | A4             |
| LCD I2C (SCL)        | A5             |

## 🌐 Firebase/Blynk

- Firebase: Stores real-time status of each parking slot and environmental data
- Blynk: Displays parking data and environmental alerts in a user-friendly mobile app

## ⚙️ Installation & Setup

1. Connect components as per the pin configuration
2. Upload Arduino code using the Arduino IDE
3. Connect NodeMCU with Wi-Fi credentials and Firebase/Blynk credentials
4. Monitor LCD for slot availability and gate assignment
5. Use Blynk app or Firebase dashboard for remote monitoring

## 📊 Use Cases

- Shopping mall parking systems
- Office complexes
- Smart city applications
- University campus parking

## 📸 Screenshots

![parking-system](https://github.com/user-attachments/assets/2a85011a-217a-45b9-ba6b-d0ba9d9521eb)


## 🙋‍♂️ Author

**Aman Manderna**  
*Master of Computer Applications (MCA)*  
