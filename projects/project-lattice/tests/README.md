# Project Lattice - Tests

This folder contains formal tests used to evaluate Project Lattice against its requirements.

Testing will take place throughout development, with more complete system testing carried out as the individual subsystems become operational.

## Purpose

Testing is used to determine whether the system and its individual components perform as expected.

Tests may cover:

- Acoustic sensing
- Signal processing
- TDOA
- Direction estimation
- Computer vision
- Object detection
- Visual tracking
- Sensor fusion
- Target tracking
- Hardware reliability
- Software reliability
- System performance

## Testing Approach

Testing should be carried out in stages.

### Component Testing

Individual components are tested before being integrated.

Examples:

- Microphone testing
- Camera testing
- Sensor-interface testing
- Microcontroller testing
- Software-module testing

### Subsystem Testing

Complete subsystems are tested independently.

Examples:

- Acoustic sensing system
- Computer vision system
- Embedded system
- Processing pipeline

### Integration Testing

Multiple subsystems are tested together.

Examples:

- Microphone system with processing hardware
- Camera with computer vision software
- Acoustic and visual systems together
- Sensor fusion

### System Testing

The complete demonstrator is tested as a system.

## Test Structure

Each formal test should record:

```text
 Test Title

 Requirement

What requirement is this test evaluating?

 Objective

What should the test determine?

 Test Setup

Describe the hardware and software configuration.

 Procedure

1.
2.
3.

 Expected Result

What should happen if the system is operating correctly?

 Actual Result

What actually happened?

 Measurements

Record relevant measurements.

Pass / Fail

**Result:** Not tested

Problems

Record any issues encountered.

 Conclusion

Summarise the result.

 Follow-up

Record any required changes or additional testing.
