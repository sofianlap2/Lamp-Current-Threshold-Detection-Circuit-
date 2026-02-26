# Lamp-Current-Threshold-Detection-Circuit-
Lamp Current Threshold Detection Circuit 

This project is a transistor-based current threshold detection circuit designed to verify whether a 12V lamp is operating within its specified current consumption of 0.11A.
The system monitors the lamp current and provides a clear visual indication using two LEDs:
•	Green LED ON → Lamp current is 0.11A or higher (Normal operation)
•	Red LED ON → Lamp current is below 0.11A (Fault or underperformance)
How It Works
•	A sensing resistor network converts lamp current into a proportional voltage.
•	Q1 (2N2222A) acts as the main current-sensing transistor.
•	When the sensed current reaches the calibrated threshold (~0.11A), Q1 switches state.
•	A transistor switching stage (Q2 and Q3) forms a signal inverter/driver stage.
•	Depending on the detected current level:
•	One transistor path activates the green LED
•	The opposite path activates the red LED
•	A 9V supply powers the control circuit.
Use cases:
Lamp production testing
Load verification systems
Automotive bulb diagnostics

<img width="1090" height="705" alt="image" src="https://github.com/user-attachments/assets/08a83e69-4179-4bce-891b-05ac27f737ff" />

<img width="1090" height="715" alt="image" src="https://github.com/user-attachments/assets/9fb92907-27d2-4623-a4c8-9e71a4cd8ba8" />

<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/e71f6c43-dfb3-4b9f-92ed-648a49d9cccb" />

<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/116b3201-07fa-45b0-8e01-725c9dd6e645" />
