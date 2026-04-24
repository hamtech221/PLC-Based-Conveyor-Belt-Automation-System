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


## ⚙️ Working:
  The video below will show the demo. Since there are push buttons and LEDs, we make some assumptions. Those assumptions are:
  
  • I0.0 means that sensor detects an object on the belt is placed so Q0.2 indicates the motor is running. 
  • I0.1 indicates that sensor detects no object is on the belt, so the motor stops running.
  • I0.7 is just used as a reset for counters.
  • A safety feature was added that is if the both sensors show incorrect reading, the motor is in the "suspended" state         meaning that it suddenly stops running.
  • Interlocking logic was also added in the program as another safety feature.

  
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
• PLC Program / Logic (.mwp file) 
• System Design Logic
• Demonstration Video  
