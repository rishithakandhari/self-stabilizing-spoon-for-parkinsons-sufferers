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
![image](https://github.com/user-attachments/assets/b0e4fe88-573c-4da6-940f-6a9491fed6ee)


## How to Run the Project
1. **Hardware Setup:**
   - Connect the MPU6050 and servomotors to the Arduino.
   - Upload the code to the Arduino using the Arduino IDE.
2. **Simulation:**
   - Open the simulation on Wokwi
3. **Testing:**
   - Power the setup and test the spoon’s stability by simulating tremors.

## Working
# Motion Detection:
- The MPU6050 gyroscope and accelerometer continuously monitor the spoon’s orientation and movement.
- When a tremor is detected (via changes in pitch, roll, or yaw), the sensor data is sent to the Arduino.

# Data Processing:
- The Arduino receives the sensor data and processes it in real-time to detect hand tremors.
- It uses algorithms to determine the magnitude and frequency of the tremor.

# Tremor Analysis:
- Based on the processed data, the system calculates whether the tremor is significant enough to require correction.
- The system uses a predefined threshold to decide when to activate the stabilizing motors.

# Stabilization:
- Servomotors (SG90) connected to the spoon react by moving in the opposite direction of the detected tremor.
- The motors make small, precise adjustments to counteract the tremor and keep the spoon stable.

# Adjustable Sensitivity:
- The sensitivity of tremor correction can be adjusted by fine-tuning the PID (Proportional-Integral-Derivative) values in the Arduino code.
- This adjustment allows users to control how aggressively the spoon responds to minor or major tremors.

# Real-Time Operation:
- The system operates with minimal delay, providing constant feedback and adjustments to keep the spoon stable during tremors, ensuring a smooth experience for the user.

## Future Scope
- Improve the stabilization accuracy by fine-tuning PID values.  
- Reduce power consumption.  
- Implement Bluetooth control for remote adjustments.

##  License
This project is licensed under the MIT License.  

