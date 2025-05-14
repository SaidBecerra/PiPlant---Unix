# PiPlant: Smart Plant Watering System

## Overview
PiPlant is an automated plant watering system built on Raspberry Pi that monitors soil moisture levels and waters plants when needed. The system uses moisture sensors to detect when soil becomes too dry and automatically activates a watering mechanism to maintain optimal plant health.

## Features
- Real-time soil moisture monitoring
- Automated watering based on moisture thresholds
- Logging system for moisture readings and watering events
- Automatic startup on boot

## Technical Implementation
- **Platform**: Raspberry Pi with Debian-based OS
- **Sensors**: Both resistive and capacitive soil moisture sensors
- **Watering Options**: Peristaltic pump or solenoid valve with water reservoir
- **Software**: Python-based control system running as a daemon
- **System Integration**: Uses Unix IPC, cron scheduling, and log rotation

## Project Structure
- Moisture monitoring service
- Watering control system
- Logging and monitoring components

## Timeline
- Week 1: Research and Planning
  - Conducted research to define and scope the PiPlant project
  - Evaluated different Raspberry Pi models for optimal compatibility with our needs
  - Researched and compared various soil moisture sensors (resistive vs. capacitive)
  - Investigated watering mechanism options (pumps, valves, reservoirs)
  - Created initial project plan and requirements documentation
  - Established GitHub repository and project structure
- Week 2: Core functionality and integration
  - Compared different Raspberry Pi models and decided on the most compatible one
  - Ordered the neccessary kits and devices for the project
  - Worked on the hardware and connecting the correct wires to the devices
  - Assambled the Raspberry Pi
- Week 3: Refinement and presentation preparation
  - Connected the Raspberry Pi with VNC Viewer
  - Finalized the code to run the device
  - Uploaded the neccessary documents
  - Prepared the presentation

## License
MIT License

## Team
- Said Becerra (6234475)
- Sona Martirosyan (6224603)

## Course Information
UNIX 420-321-VA, Section 00001
Winter 2025
