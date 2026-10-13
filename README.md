# ESP32-Based Remote-Controlled RC Vehicle

This project explores the design of custom electronics for a compact, remotely controlled RC vehicle. It brings together power distribution, motor control, and wireless control in a dedicated hardware platform.

Where practical, custom PCBs are used instead of off-the-shelf development boards, providing hands-on experience with electronics development and embedded-system integration.

## Project Overview

The vehicle's electronic platform is built around modular blocks for microcontroller control, motor driving, power management, communication, and external connections.

The goal is to create more than a moving vehicle: the project follows a practical engineering approach to building hardware that is functional, organized, and suitable for manufacturing.

## Project Goals

- Develop an ESP32-based embedded system
- Design custom PCBs
- Integrate a motor-driver circuit
- Plan power distribution for a battery-powered system
- Build wireless vehicle-control capability
- Combine hardware blocks into one integrated system

## System Architecture

The RC vehicle consists of the following main hardware blocks:

### Microcontroller

An ESP32-based controller handles wireless communication, generates control signals, and exchanges data with peripheral devices.

### Motor Driver

A motor-driver stage controls the DC motors in forward and reverse directions and provides the signals needed to steer the vehicle.

### Power

The board is designed for battery operation, with power inputs, regulation, filtering, and distribution connections planned to provide suitable supplies for both the control and driver stages.

### Connections and Interfaces

Connectors and pin assignments are planned for the motors, power rails, control signals, and auxiliary connections. This approach is intended to make assembly, testing, and maintenance easier.

## PCB Design Approach

The boards are planned to be both functional and orderly, with manufacturing and serviceability in mind. The design process focuses on:

- Keeping the schematic and PCB layout consistent
- Separating power and signal paths by function
- Keeping motor-current paths apart from control signals
- Using short, practical connections in component placement
- Planning suitable layouts around the regulator, driver, and microcontroller
- Positioning connectors for convenient assembly and access
- Keeping the board compact while allowing service access

## Work Completed

- Identified the hardware blocks required for the RC vehicle
- Planned the ESP32-based control system
- Planned motor-driver integration
- Designed the power input and regulation approach
- Created a custom PCB layout
- Arranged connectors and interfaces
- Considered system wiring, control logic, and assembly together

## Technologies and Components

- ESP32
- DC motor-driver stage
- Li-Po battery system
- Voltage-regulation circuits
- PCB design software
- Schematic and PCB layout tools

## Skills Applied

- Embedded hardware architecture
- PCB design and layout planning
- Power-management design
- Motor-driver integration
- Wireless-control system design
- System-level electronics integration

## Project Photos

![Schematic view](images/sematik.png)

![PCB top view](images/pcb-ust.png)

![3D PCB view](images/pcb-3d.png)

![Prototype system](images/prototip.png)

## Possible Extensions

- Design a more compact multilayer PCB
- Add current measurement and battery monitoring
- Implement more advanced motor-control algorithms
- Integrate sensors
- Add a camera or video-transmission module
- Develop a mobile application interface
- Strengthen EMI and ESD protection

## Summary

This project develops the electronics for a remote-controlled vehicle using a custom-board design approach. It brings together microcontroller control, motor driving, power distribution, and PCB design in one practical hardware project.
