# Project Lattice - System Requirements

## 1. Purpose

This document defines the initial system requirements for Project Lattice.

The requirements provide a basis for researching hardware, developing software, planning experiments and evaluating the final demonstrator.

The requirements are expected to develop throughout the project as the team gains practical experience through research, prototyping and testing.

Specific technical targets should only be introduced when they can be supported by research or experimental results.

## 2. Functional Requirements

### Acoustic Sensing

The system should:

- Use multiple microphones to capture acoustic signals.
- Acquire microphone signals for processing and analysis.
- Allow recorded signals to be stored for testing and development.
- Process acoustic signals to identify relevant acoustic activity.
- Investigate TDOA-based methods for estimating the direction of detected sounds.
- Provide acoustic information that can be used by the wider tracking system.

### Computer Vision

The system should:

- Use a camera to capture visual data.
- Process camera frames using suitable computer vision methods.
- Detect relevant objects within the camera's field of view.
- Track detected objects over time.
- Provide visual information that can be used by the wider tracking system.

### Sensor Fusion

The system should:

- Allow acoustic and visual information to be processed together.
- Compare information from the acoustic and visual sensing systems.
- Investigate methods of combining acoustic direction estimates with visual information.
- Produce a combined output that can support target tracking.

Sensor fusion will be developed progressively as the individual sensing systems become operational.

## 3. Performance Requirements

The system should be evaluated using measurable tests.

Initial performance areas include:

- Microphone signal quality
- Reliability of signal acquisition
- Accuracy of direction estimation
- Object-detection reliability
- Visual tracking performance
- Sensor-fusion performance
- System response time
- Stability during continuous operation

Specific numerical targets will be established after initial hardware selection, software development and experimental testing.

Performance targets may be revised as the capabilities and limitations of the system become clearer.

## 4. Hardware Requirements

The project will require hardware capable of supporting acoustic sensing, computer vision, processing and supporting electronics.

Potential hardware includes:

- Multiple microphones
- Camera
- Signal-conditioning circuitry
- Microcontroller or acquisition hardware
- Processing computer or single-board computer
- Power supply
- Storage for recorded data
- Mechanical mounting hardware
- Wiring and connectors

Final component selections will be based on research, testing, availability and project constraints.

Hardware decisions should be documented in the project repository.

## 5. Software Requirements

The software system should support, where required:

- Sensor data acquisition
- Acoustic signal processing
- TDOA analysis
- Direction estimation
- Image processing
- Object detection
- Object tracking
- Sensor fusion
- Data recording
- Data visualisation
- Testing and evaluation

Software tools, libraries and frameworks will be selected based on project requirements, available hardware and student experience.

## 6. Physical Requirements

The final system should:

- Be suitable for a desktop-scale demonstrator.
- Provide stable mounting for the sensors.
- Maintain suitable positioning and alignment of the sensing hardware.
- Allow access to components for testing and modification.
- Keep wiring organised and accessible.
- Allow individual subsystems to be replaced or upgraded.
- Provide sufficient space for future development.

The mechanical design should support experimentation and allow the system to be modified as development progresses.

## 7. Testing Requirements

Testing should be carried out throughout development under controlled conditions where practical.

Testing should include:

- Individual microphone testing
- Microphone-array testing
- Acoustic signal tests
- TDOA experiments
- Known-position direction tests
- Camera tests
- Object-detection tests
- Object-tracking tests
- Sensor-fusion tests
- Full-system tests

Tests should be used to identify limitations, compare different approaches and measure system performance.

Test conditions, measurements and results should be recorded in the project repository.

## 8. Documentation Requirements

The project should maintain documentation covering:

- System requirements
- System architecture
- Hardware research
- Hardware decisions
- Software decisions
- Experiments
- Test procedures
- Test results
- Design changes
- Problems encountered
- Solutions and improvements

Important technical decisions should be documented so that other students can understand the reasoning behind them.

Documentation should be updated throughout development rather than being written only at the end of the project.

## 9. Project Constraints

Project Lattice is being developed as a student engineering project during the academic year.

Important constraints include:

- Limited development time
- Student budget
- Availability of hardware
- Student experience levels
- Processing limitations
- Access to laboratory equipment
- Physical size of the demonstrator
- Availability of team members throughout the academic year

Some senior students may have reduced availability during placement periods. Project work should therefore be documented clearly enough that another student can continue a task when required.

The project should prioritise a working and testable demonstrator over unnecessary complexity.

## 10. Requirement Priorities

Requirements will be prioritised during development.

### Essential

- Acoustic data acquisition
- Camera data acquisition
- Basic acoustic signal processing
- Basic computer vision processing
- Physical demonstrator
- Experimental testing
- Documented evaluation of the sensing systems

### Target

- TDOA-based direction estimation
- Reliable object detection
- Reliable visual tracking
- Acoustic classification
- Acoustic and visual sensor fusion
- Combined target tracking

### Stretch

- Real-time sensor fusion
- Improved robustness in different environments
- More advanced classification
- Extended tracking capabilities
- Further hardware optimisation

These priorities may change as the project develops and the capabilities and limitations of the selected hardware and software become clearer.

## 11. Development Approach

Project Lattice will be developed incrementally.

Individual sensing and processing components should be tested before being integrated into larger subsystems.

The development process will generally follow:

1. Research
2. Hardware and software selection
3. Prototype development
4. Component testing
5. Subsystem testing
6. Integration
7. System testing
8. Improvement

The acoustic sensing and computer vision systems will be developed as parallel parts of the project rather than treating computer vision as a later addition.

Sensor fusion and combined tracking will be developed as the individual sensing systems become sufficiently mature.

## 12. Requirement Review

The requirements should be reviewed throughout the project.

Changes may be made when:

- Research identifies better approaches.
- Hardware limitations are discovered.
- Experiments produce new information.
- System integration creates new requirements.
- Project constraints change.

Significant requirement changes should be documented along with the reason for the change.

