# Project Lattice - Project Overview

## 1. Project Summary

Project Lattice is a student-led engineering project focused on developing a multimodal sensing system for detecting, locating and tracking drone-like targets.

The project brings together acoustic sensing, computer vision, electronics, embedded systems, signal processing and software.

The project will be developed throughout the academic year, from September through April, with the different parts of the system being built, tested and integrated during this period.

## 2. Core Concept

Project Lattice uses two main sensing methods.

The first is an acoustic sensing system based around multiple microphones. The microphones will capture sound from the surrounding environment, allowing differences in arrival time to be analysed.

These differences can be used with **Time Difference of Arrival (TDOA)** techniques to estimate the direction of a sound source.

The second sensing method is a camera-based computer vision system. The camera will provide visual information that can be processed to detect and track objects.

The project will investigate how these two sources of information can be used together to improve detection and tracking.

## 3. System Overview

The overall system can be viewed as a series of processing stages:

```text
Project Lattice
      ↓
Acoustic Sensing + Computer Vision
      ↓
Signal Processing + Object Detection
      ↓
Direction Estimation + Visual Tracking
      ↓
Sensor Fusion
      ↓
Target Tracking
```

The acoustic and visual systems will be developed and tested individually before being brought together.

## 4. Project Objectives

The main objectives of Project Lattice are to:

* Build and test a multi-microphone acoustic sensing system.
* Capture and process acoustic signals.
* Investigate TDOA for estimating sound direction.
* Develop methods for identifying relevant acoustic signatures.
* Integrate a camera into the sensing platform.
* Investigate computer vision for object detection.
* Develop visual tracking capabilities.
* Combine acoustic and visual information.
* Investigate sensor-fusion approaches.
* Develop a working physical demonstrator.
* Test the system under controlled conditions.
* Document the development and results.

## 5. Technical Areas

### Electronics

The electronics side of the project will cover the hardware used to collect and support sensor data.

This includes:

* Microphones
* Camera interfaces
* Signal conditioning
* Sensor interfaces
* Power
* Hardware prototyping
* PCB development where appropriate

### Embedded Systems

Embedded systems will provide the connection between the physical hardware and the software.

Areas may include:

* Microcontrollers
* Firmware
* Sensor interfacing
* Data acquisition
* Communication
* Real-time processing

### Signal Processing

Signal processing will be used to extract useful information from the acoustic data.

Areas of investigation include:

* Filtering
* Signal analysis
* TDOA
* Direction estimation
* Acoustic classification

### Computer Vision

Computer vision will provide the visual sensing side of the project.

Areas of investigation include:

* Camera integration
* Image processing
* Object detection
* Object tracking
* Visual data analysis

### Software

Software will support data processing, testing and visualisation across the different parts of the system.

This may include:

* Signal-processing software
* Computer vision software
* Data analysis
* Visualisation
* Testing tools
* System integration

### Mechatronics

The physical construction of the demonstrator will involve mechanical and electrical integration.

This includes:

* Sensor positioning
* Microphone and camera mounting
* Prototype structures
* Enclosures
* Mechanical integration

## 6. Development Approach

Project Lattice will be developed incrementally throughout the September–April project period.

The acoustic sensing and computer vision systems are both part of the core project. They will be developed alongside the other technical areas, with individual components tested before being integrated into the complete system.

The development process will involve:

1. Defining system requirements.
2. Selecting and testing suitable hardware.
3. Developing the acoustic sensing system.
4. Developing the camera and computer vision system.
5. Building the required signal-processing and detection software.
6. Testing direction estimation and visual tracking.
7. Investigating sensor fusion.
8. Integrating the complete system.
9. Testing and evaluating the final demonstrator.

The exact order of work may change as the project develops and testing provides new information.

## 7. Engineering Approach

The project will follow a practical engineering approach based on building, testing and improving the system.

### Measure and test

Design decisions should be supported by measurements and experiments where possible.

### Build in stages

Individual components should be tested before being integrated into larger subsystems.

### Document decisions

Important design decisions, experiments, problems and results should be recorded throughout development.

### Keep testing reproducible

Experiments should be documented clearly enough for other team members to repeat them.

### Learn from results

Unexpected results and failed approaches are part of the engineering process. Testing should be used to identify problems and improve the design.

## 8. Project Timeline

Project Lattice is planned as an academic-year project running from **September through April**.

The project will cover the development and integration of:

* System requirements
* Acoustic sensing
* Camera integration
* Signal acquisition
* Signal processing
* TDOA and direction estimation
* Computer vision
* Object detection
* Visual tracking
* Sensor fusion
* System integration
* Testing and evaluation
* Final demonstrator

The specific implementation and schedule may change as the team gains practical experience with the hardware and software.

## 9. Current Status

**Project phase:** Initial development

The current stage is focused on defining the project and preparing for implementation.

Current priorities include:

* Finalising the system requirements.
* Defining the acoustic sensing approach.
* Defining the computer vision approach.
* Selecting suitable hardware.
* Planning initial experiments.
* Setting up the development environment.
* Establishing testing methods.

Both acoustic sensing and computer vision are part of the planned Project Lattice system.

## 10. Long-Term Goal

The goal of Project Lattice is to produce a working multimodal sensing demonstrator capable of using acoustic and visual information to detect, locate and track drone-like targets.

The project will focus on practical engineering, measurable results and proper documentation throughout development.

The final system will be evaluated based on how well the individual sensing systems work and how effectively they can be combined into a single tracking system.

