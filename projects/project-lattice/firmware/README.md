# Project Lattice - Firmware

This folder contains firmware developed for the embedded hardware used in Project Lattice.

Firmware will handle low-level hardware functions such as sensor interfacing, data acquisition, communication and control.

## Main Areas

### Sensor Interface

Firmware may be used to interface with:

- Microphones
- Analogue-to-digital converters
- Cameras or camera interfaces where applicable
- Other sensors used during development

### Data Acquisition

Firmware may handle:

- Sensor sampling
- Timing
- Data buffering
- Data transmission
- Basic preprocessing where appropriate

### Communication

Firmware may provide communication between embedded hardware and the main processing system.

Possible interfaces include:

- USB
- UART
- I2C
- SPI
- Other suitable interfaces

The final communication methods will depend on the hardware selected.

### Hardware Control

Firmware may also be responsible for:

- Initialising hardware
- Monitoring system status
- Controlling peripherals
- Managing timing
- Handling errors

## Development Approach

Firmware should be developed in small, testable components.

Where practical:

- Keep hardware drivers separate from application logic.
- Document hardware interfaces.
- Record pin assignments.
- Document communication protocols.
- Test hardware interfaces individually.
- Keep experimental firmware separate from stable versions.

## Hardware Documentation

Firmware should correspond to the hardware documented in:

`../hardware/`

Important information such as:

- Pin assignments
- Sensor connections
- Communication interfaces
- Power requirements
- Hardware revisions

should be documented alongside the relevant hardware.

## Current Status

**Status:** Initial setup

Firmware requirements and hardware interfaces will be defined after the hardware research and selection process.

No final microcontroller or firmware platform has been selected yet.
