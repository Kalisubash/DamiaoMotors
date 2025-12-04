# DamiaoMotors
This project demonstrates how to control a Damiao (DM) brushless servo motor—specifically the DM6006 or any supported DM series motor—using Python over a CAN bus interface. The code uses the DM_CAN_Library to communicate with the motor via a USB-to-CAN adapter connected to a Raspberry Pi


DM Motor Test – Python Script Using DM_CAN_Library

This repository contains a simple and reliable Python test script for running a DM6006 brushless motor using the DM_CAN_Library over a USB-to-CAN adapter on a Raspberry Pi or PC.

The script performs:
-Motor enable
-Velocity control mode
-Forward rotation
-Stop
-Reverse rotation
-Safe shutdown

It is intended for beginners and developers working with T-Motor DM series motors and custom CAN-based motor control systems.

📌 Features
Control DM Motor (DM6006 or others supported by library)
-USB-based CAN communication
-Velocity control mode (VEL)
-Forward, stop, reverse test sequence
-Safe disable and serial port closure
-Works on Raspberry Pi 4 and Windows/Linux PC

🛠️ Hardware Requirements
Component	Description
-DM6006 / DM4310 / DM Series Motor	Motor being controlled
-DM_CAN_Library	Python library for motor CAN control
-USB to CAN Adapter	Example: DAMIAO CAN Debugger USB to CAN
-Raspberry Pi 4 / Laptop / PC	Running the Python script
-Power Supply	As required by your motor
-CAN wiring	CANH → CANH, CANL → CANL, (GND → GND optional)

Required Library
pip install pyserial

