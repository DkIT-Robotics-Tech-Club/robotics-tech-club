# Project Lattice - System Requirements

## 1. Purpose

This document defines the initial requirements for Project Lattice.

The requirements provide a basis for selecting hardware, developing software and evaluating the final demonstrator.

They may be updated as the project develops and new information is obtained through testing.

## 2. Functional Requirements

### Acoustic Sensing

The system should:

* Use multiple microphones to capture acoustic signals.
* Acquire signals from the microphones for processing.
* Allow recorded signals to be stored for testing and analysis.
* Process microphone signals to identify relevant acoustic activity.
* Investigate TDOA-based methods for estimating sound direction.

### Computer Vision

The system should:

* Use a camera to capture visual data.
* Process camera frames using suitable computer vision methods.
* Detect objects within the camera's field of view.
* Track detected objects over time.
* Provide positional information that can be used by the wider system.

### Sensor Fusion

The system should:

* Allow acoustic and visual information to be processed together.
* Compare information from the two sensing systems.
* Investigate methods of combining acoustic direction estimates with visual information.
* Provide a combined output that can be used for target tracking.

## 3. Performance Requirements

The system should be evaluated using measurable tests.

Initial performance areas include:

* Microphone signal quality
* Reliability of signal acquisition
* Accuracy of direction estimation
* Detection reliability
* Visual tracking performance
* Sensor-fusion performance
* System response time
* Stability during continuous operation

Specific numerical targets will be established after initial hardware and software testing.

## 4. Hardware Requirements

The project will require hardware capable of supporting the two sensing systems.

Potential hardware includes:

* Multiple microphones
* Camera
* Signal-conditioning circuitry
* Microcontroller or acquisition hardware
* Processing computer or single-board computer
* Power supply
* Storage for recorded data
* Mechanical mounting hardware
* Wiring and connectors

Final component selections will be documented as development progresses.

## 5. Software Requirements

The software system should support:

* Sensor data acquisition
* Acoustic signal processing
* TDOA analysis
* Direction estimation
* Image processing
* Object detection
* Object tracking
* Sensor fusion
* Data recording
* Data visualisation
* Testing and evaluation

Software tools and frameworks will be selected based on project requirements and available hardware.

## 6. Physical Requirements

The final system should:

* Be suitable for a desktop-scale demonstrator.
* Provide stable mounting for the sensors.
* Allow access to components for testing and modification.
* Keep wiring organised and accessible.
* Allow individual subsystems to be replaced or upgraded.
* Provide sufficient space for future development.

## 7. Testing Requirements

Testing should be carried out under controlled conditions wherever possible.

Testing should include:

* Individual microphone testing
* Microphone-array testing
* Acoustic signal tests
* TDOA experiments
* Known-position direction tests
* Camera tests
* Object-detection tests
* Object-tracking tests
* Sensor-fusion tests
* Full-system tests

Test conditions and results should be recorded in the project repository.

## 8. Documentation Requirements

The project should maintain documentation covering:

* System requirements
* Architecture
* Hardware decisions
* Software decisions
* Experiments
* Test procedures
* Test results
* Design changes
* Problems encountered
* Solutions and improvements

Documentation should be updated throughout the project rather than being written only at the end.

## 9. Project Constraints

The project is being developed as a student engineering project during the academic year.

Important constraints include:

* Limited development time
* Student budget
* Availability of hardware
* Student experience levels
* Processing limitations
* Access to laboratory equipment
* Physical size of the demonstrator

The system should therefore prioritise a working and testable demonstrator over unnecessary complexity.

## 10. Requirement Priorities

Requirements will be prioritised during development.

### Essential

* Acoustic data acquisition
* Camera data acquisition
* Acoustic signal processing
* Basic direction estimation
* Basic object detection
* Basic visual tracking
* Physical demonstrator
* Experimental testing

### Target

* Reliable TDOA direction estimation
* Reliable object tracking
* Acoustic classification
* Acoustic and visual sensor fusion
* Combined target tracking

### Stretch

* Real-time sensor fusion
* Improved robustness in different environments
* More advanced classification
* Extended tracking capabilities
* Further hardware optimisation

These priorities may change as the project develops.

