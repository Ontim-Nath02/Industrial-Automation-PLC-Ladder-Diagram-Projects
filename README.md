# Projects Overview
# 1.  Sorting Object Based On Height
Automates the process of detecting and sorting objects by their height using sensors and actuators. The ladder logic reads sensor inputs to classify objects and routes them to the appropriate output lane via conveyor control logic.
Key Concepts:

1. Sensor-based detection (proximity/limit switches)
2. Conditional branching in Ladder Logic
3. Output coil control for sorting actuators
4. Sequential process flow


# 2. 💧 Water Filling Automation
Simulates an automated water filling station that controls the filling of containers to a desired level. The program manages pump activation, valve control, and level sensing to automate the fill cycle.
Key Concepts:

1. Level sensor integration (Float/Ultrasonic)
2. Timer (TON/TOF) usage for fill cycle control
3. Pump and solenoid valve output control
4. Auto/Manual mode logic

# Tools & Environment
1. PLC Software -----> Siemens TIA Portal (v16)
2. Programming Language------> Ladder Diagram (LAD)
3. Simulation --------> TIA Portal PLCSIM
4. PLC Series ------> Siemens S7-1200(simulated)

# How to Open a Project
1. Clone this repository:
2. Open TIA Portal.
3. Click "Open existing project" and browse to the desired project folder (.ap16).
4. Once opened, go to Online → Simulation to launch PLCSIM.
5. Download the program to the simulated PLC and switch it to RUN mode.
6. Use the Watch Table or Force Table to monitor and test I/O signals.
