# Smart Parking System 🚗📊

This project is an **IoT-based Smart Parking System** that helps manage vehicle parking efficiently using **Arduino Uno, IR sensors, an LCD display, and a servo motor**. It automatically detects vehicles entering and exiting and updates the number of available parking slots in real-time.

## 🛠 Features

- Detects vehicle entry and exit using **IR sensors**
- Automatically opens/closes gate using a **servo motor**
- Displays available parking slots on an **LCD screen**
- Powered by **Arduino Uno** and programmed using **Arduino IDE**

## ⚙️ Hardware Components

- Arduino Uno  
- 2x IR Sensors (for entrance and exit)  
- Servo Motor (for gate control)  
- 16x2 LCD Display (with I2C module)  
- Breadboard and jumper wires  
- 5V Power supply  

## 💻 Software Requirements

- Arduino IDE  
- Wire.h (for I2C communication)  
- LiquidCrystal_I2C.h (for LCD display)  
- C++ (Arduino programming language)

## 📈 Working Principle

1. **IR sensor at entrance** detects a car and checks if parking space is available.
2. If space is available, **servo motor** opens the gate and the **LCD** updates the available slot count.
3. **IR sensor at exit** detects a leaving car and the gate opens again, updating the slot count.
4. The system runs in a loop and always shows current availability.

## 📸 Circuit Diagram

![iot  circuit](https://github.com/user-attachments/assets/0a0ce092-b179-4009-879b-fa35bd9e076d)


## 📦 Future Enhancements

- Add mobile app integration  
- Cloud-based slot monitoring  
- Voice assistant support

## 📃 License

This project is open-source and free to use for educational purposes.

---
