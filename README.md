# 🚨 Accident Alert System (Arduino + GSM + Ultrasonic Sensor)

This project is an **Accident Alert System** built using **Arduino UNO**, **Ultrasonic Sensor (HC-SR04)**, and a **GSM Module (SIM800/900)**.  
It continuously monitors distance using the ultrasonic sensor, and if an object/impact is detected within a short range, it **sends an SMS alert** to a predefined mobile number.

---

## 📂 Project Files
- `accident_alert.ino` → Arduino source code  
- `diagram.jpg` → Block diagram of the system  
- `output.jpg` → Example output photo / working prototype  

---

## ⚙️ Hardware Components
- Arduino UNO  
- Ultrasonic Sensor (HC-SR04)  
- GSM Module (SIM800L / SIM900)  
- Breadboard & Jumper Wires  
- Power Supply  

---

## 🛠️ Working Principle
1. Ultrasonic sensor measures distance continuously.  
2. If distance ≤ 10 cm, the system detects a possible accident.  
3. GSM module sends an SMS alert:  
   > *"Alert: Possible accident detected! Immediate attention needed."*  

---

## 🔧 How to Run
1. Connect all hardware components properly.  
2. Open **Arduino IDE**.  
3. Load the file `accident_alert.ino`.  
4. Select correct **Board: Arduino UNO** & **Port**.  
5. Upload the code.  
6. Open **Serial Monitor** (9600 baud rate) to see sensor values.  

---

## 🖼️ Images
Block Diagram:  
![Block Diagram](diagram.jpg)

Output Screenshot:  
![Output](output.jpg)

---

## 📞 Alert SMS Example
When accident is detected, GSM module sends SMS:  
