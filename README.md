# Micromouse Line Follower Robot Simulation

A MATLAB/Simulink-based simulation of a Micromouse line follower robot designed to autonomously follow a predefined track using sensor feedback and PID control.

## Overview

This project simulates a two-wheeled differential drive Micromouse robot in a 3D virtual environment. The robot uses virtual sensors to detect the track and a PID controller to maintain stable line-following performance. The simulation is developed using MATLAB, Simulink, and Simulink 3D Animation.

## Features

- Autonomous line-following robot simulation
- PID-based control system
- Virtual sensor modeling
- Differential drive robot dynamics
- Real-time 3D visualization
- Customizable robot and course CAD models
- Sensor data monitoring and analysis

## Project Structure

```text
Micromouse-Line-Follower/
│
├── LineTrace2025a.slx
├── Tracer.stl
├── Course.stl
├── README.md
```

## System Architecture

### Sensor Model

- Simulates four front-mounted sensors (L2, L1, R1, R2)
- Detects the line using virtual camera-based sensing
- Converts image data into sensor signals

### Control Model

- Processes sensor inputs
- Implements PID control
- Generates motor speed and direction commands
- Maintains stable line-tracking behavior

### Plant Model

- Simulates motor characteristics
- Models differential drive robot kinematics
- Computes robot position and orientation

### Environment Model

- Displays the robot and track in a 3D environment
- Uses STL CAD files for visualization
- Supports custom robot and course designs

## Technologies Used

- MATLAB
- Simulink
- Simulink 3D Animation
- PID Control
- Robotics
- Control Systems
- CAD/STL Modeling

## Files

### Tracer.stl

3D CAD model representing the Micromouse robot.

### Course.stl

3D CAD model representing the line-following track.

### LineTraceSample2025a.slx

Main Simulink model containing the sensor, control, plant, and environment subsystems.

## Requirements

- MATLAB R2025a (or compatible version)
- Simulink
- Simulink 3D Animation

## Running the Simulation

1. Open MATLAB.
2. Navigate to the project folder.
3. Ensure the following files are present:
   - LineTraceSample2025a.slx
   - Tracer.stl
   - Course.stl
4. Open the Simulink model.
5. Click **Run** to start the simulation.
6. Observe the robot's behavior in the 3D animation window.

## Results

The robot successfully follows the predefined path using sensor feedback and PID control. Real-time visualization enables analysis of robot movement, sensor responses, and control performance.

## Future Improvements

- LiDAR-based obstacle detection
- Sensor noise modeling
- Reinforcement learning-based control
- Advanced path planning algorithms
- Real hardware implementation
- Improved motor and friction models

## Applications

- Micromouse Competitions
- Mobile Robotics
- Autonomous Navigation
- Control System Development
- Robotics Research


