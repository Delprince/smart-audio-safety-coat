## Overview
The Smart Audio Safety Coat is a wearable hardware system designed to provide open-ear audio, hands-free calls, and safe communication for construction workers.This document describes the technical blueprint, including the hardware components, system workflow, communication flow, and feasibility of the architecture.
## Frontend (User Interaction Layer)
No software frontend required. 
# User interaction happens through:
Play/Pause
Answer/End call
Volume up/Down
# Bluetooth pairing interface on the worker's mobile device
# LED indicator light showing charging or pairing status (this can be optional)
## Backend (Core Processing Layer)
# Bluetooth Audio Module
Receives wireless signals from mobile phone for music or call
# Microcontroller/logic 
Manage incoming signals to speakers and button actions
# Power Management Circuit
Control battery usage, charging and power distribution
# Audio output  driver
ensure safe sound levels for open-ear listening
## Database Layer
This device does not require database because; It does not log activity, save audio or call history and does not store user profile.
## Component Communication flow
# how it works
The workers pairs their phone with the coat via bluetooth
The bluetooth module receieves audio signals
![systemarchitecture png](https://github.com/user-attachments/assets/bf2ffa53-7515-4067-ac2e-cf2c7fcbf921)


