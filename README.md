# 🚀 PLC-Based Conveyor Belt Automation System

This project demonstrates the design and implementation of an automated conveyor belt system using PLC-based control logic. The system simulates an industrial setup where materials are transported, detected, and processed efficiently using sensors and actuators.

## 🧠 Working Principle:
The system uses sensor inputs to detect objects on the conveyor belt. Based on predefined logic, the PLC controls the motor to start, stop, or perform actions such as sorting or counting. The entire process is automated, reducing manual intervention and improving efficiency.

## 🔧 Key Features:
• Automated conveyor movement using PLC logic  
• Object detection using sensors (e.g., IR/Proximity)  
• Start/Stop and safety control mechanisms  
• Sequential operation and timing control  
• Modular and scalable design for industrial applications  


## ⚙️ Working

The video below demonstrates the system operation. Since the setup uses push buttons and LEDs, the following assumptions are made:

- **I0.0** → Sensor detects an object on the belt → **Q0.2 (motor ON)**
- **I0.1** → Sensor detects no object → **Motor OFF**
- **I0.7** → Reset signal for counters
- **Safety Feature:** If both sensors give an invalid/contradictory reading, the motor enters a *suspended state* (immediate stop)
- **Interlocking Logic:** Implemented to prevent unsafe or conflicting operations

  
## ⚙️ Technologies Used:
PLC: Siemens S7-200 / S7-1200
Software: STEP 7 MicroWIN
Programming Language: Ladder Logic (LAD)


## 🎥 Demonstration

[▶ Watch Demo](https://github.com/user-attachments/assets/fba61171-8dea-4398-af4e-5652abb1afe7)

## 🎯 Applications:
• Manufacturing Industries  
• Packaging Systems  
• Material Handling  
• Sorting & Counting Systems  

## 📂 Repository Contents
- PLC Program / Logic (.mwp file) 
- System Design Logic
- Demonstration Video  
