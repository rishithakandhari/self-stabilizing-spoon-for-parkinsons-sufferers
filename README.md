# Self-Stabilizing Spoon for Parkinson's Sufferers

## Project Overview
This project is a self-stabilizing spoon designed to help individuals with Parkinson's disease by minimizing hand tremors. It uses an Arduino Uno, MPU6050 gyroscope, and servomotors to stabilize the spoon.

## Features
- Real-time tremor detection and stabilization.
- Uses MPU6050 for motion sensing.
- Adjustable sensitivity for tremor correction.

## Components Used
- Arduino Uno  
- MPU6050 Gyroscope and Accelerometer  
- Servomotors (SG90)  
- Power supply (9V battery or adapter)  
- Connecting wires and breadboard  

## Circuit Diagram
![Circuit](images/circuit-diagram.png)

## How to Run the Project
1. **Hardware Setup:**
   - Connect the MPU6050 and servomotors to the Arduino.
   - Upload the code to the Arduino using the Arduino IDE.
2. **Simulation:**
   - Open the simulation on Wokwi:  
   [Wokwi Simulation Link](https://wokwi.com/)  
3. **Testing:**
   - Power the setup and test the spoon’s stability by simulating tremors.

## Simulation Demo
![Demo](images/demo.gif)

## Future Scope
- Improve the stabilization accuracy by fine-tuning PID values.  
- Reduce power consumption.  
- Implement Bluetooth control for remote adjustments.

##  License
This project is licensed under the MIT License.  

