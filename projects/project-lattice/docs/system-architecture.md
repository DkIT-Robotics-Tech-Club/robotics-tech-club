# Project Lattice - System Architecture

## 1. Overview

Project Lattice is built around two main sensing systems:

* **Acoustic sensing** using a microphone array
* **Computer vision** using a camera

Both systems will collect information about the environment and process it independently before the results are combined.

The system is designed to be developed in separate subsystems so that each part can be tested before full integration.

## 2. High-Level Architecture

```text id="b3xq4f"
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

This represents the intended flow of information through the system rather than a final implementation.

The exact hardware and software architecture may change during development as testing is carried out.

## 3. Acoustic Sensing

The acoustic subsystem will use multiple microphones positioned relative to one another.

The microphones will capture sound simultaneously, allowing the system to compare the signals received at different locations.

### Main stages

```text id="i3j5r5"
Microphone Array
      ↓
Signal Acquisition
      ↓
Signal Conditioning
      ↓
Digital Signal Processing
      ↓
TDOA
      ↓
Direction Estimation
```

### Purpose

The acoustic subsystem is intended to determine whether a relevant sound is present and estimate the direction from which it originated.

TDOA will be investigated as one method of obtaining directional information.

## 4. Computer Vision

The computer vision subsystem will use a camera to provide visual information.

### Main stages

```text id="q6h5c5"
Camera
  ↓
Image Capture
  ↓
Image Processing
  ↓
Object Detection
  ↓
Object Tracking
```

### Purpose

The visual subsystem is intended to identify and track objects within the camera's field of view.

The exact computer vision approach will be determined through testing during development.

## 5. Sensor Fusion

Once the acoustic and visual systems have been developed, information from both systems can be combined.

The purpose of sensor fusion is to investigate whether combining the two sensing methods provides more useful information than either system operating independently.

For example:

* The acoustic system may provide an estimated direction.
* The camera may provide a detected object and its position in the image.
* The combined system can compare these measurements.
* The system can then use both sources when tracking the target.

The specific fusion method will be determined during development and experimentation.

## 6. Processing and Control

The project will require processing hardware and software to connect the different subsystems.

The final implementation may include:

* Microcontrollers for sensor acquisition
* A computer or single-board computer for higher-level processing
* Software for signal processing
* Computer vision software
* Communication between hardware and software
* Visualisation and monitoring tools

Hardware and software choices will be documented as the project progresses.

## 7. Physical System

The final demonstrator will contain the main sensing components in a suitable physical arrangement.

The physical design will consider:

* Microphone positioning
* Camera positioning
* Sensor spacing
* Wiring
* Power
* Mechanical stability
* Ease of testing
* Future expansion

The physical arrangement may be modified based on experimental results.

## 8. Development Strategy

The system will be developed as separate subsystems before integration.

### Stage 1 - Acoustic subsystem

Build and test the microphone array, signal acquisition and initial processing.

### Stage 2 - Computer vision subsystem

Integrate the camera and develop the initial detection and tracking system.

### Stage 3 - Direction and tracking

Develop acoustic direction estimation and visual tracking.

### Stage 4 - Sensor fusion

Investigate methods for combining acoustic and visual measurements.

### Stage 5 - Full integration

Combine the subsystems into the physical demonstrator and evaluate the complete system.

## 9. Design Considerations

Several factors will influence the final architecture:

* Sensor performance
* Processing requirements
* Available hardware
* Cost
* Power consumption
* Physical size
* Data transfer requirements
* Environmental conditions
* Development time
* Reliability

The architecture is therefore considered a working design rather than a fixed final specification.

## 10. Current Architecture Status

**Status:** Initial system architecture

This document describes the intended architecture at the beginning of development.

Hardware selections, software frameworks, processing methods and communication methods will be updated as the project moves from planning into prototyping and testing.

