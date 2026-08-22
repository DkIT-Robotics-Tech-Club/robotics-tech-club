# Project Lattice - Data

This folder contains datasets and supporting data generated during the development and testing of Project Lattice.

Data should be organised clearly so that experiments can be reproduced and results can be understood by other team members.

## Types of Data

### Acoustic Data

May include:

- Raw microphone recordings
- Processed audio signals
- Multi-channel recordings
- TDOA test data
- Direction-estimation measurements

### Computer Vision Data

May include:

- Test images
- Video recordings
- Object-detection datasets
- Tracking data
- Camera calibration data

### Sensor Fusion Data

May include:

- Acoustic measurements
- Visual measurements
- Combined sensor measurements
- Target-position data
- Tracking results

### Experimental Data

May include:

- Test measurements
- Calibration results
- Performance measurements
- Environmental conditions
- Comparison results

## Data Organisation

Data should be organised by experiment or purpose rather than being stored as a single collection of files.

Example:

```text
data/
├── acoustic/
├── vision/
├── calibration/
├── sensor-fusion/
└── experiments/
