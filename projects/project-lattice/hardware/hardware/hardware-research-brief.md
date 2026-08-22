# Project Lattice - Hardware Research Brief

## 1. Purpose

The purpose of this research task is to identify suitable hardware for Project Lattice.

The team will research different hardware options, compare them against the project requirements and make recommendations to the wider project team.

The goal is not simply to find the cheapest components. The selected hardware needs to be suitable for the system, available to the team and realistic to build and test within the project timeframe.

## 2. Research Areas

The research will cover the following areas:

* Acoustic sensing
* Computer vision
* Embedded systems
* Processing
* Power
* Mechanical construction
* Supporting electronics

Members may work individually or in small groups depending on the number of people involved.

## 3. Acoustic Sensing Research

Investigate suitable approaches for the microphone system.

Consider:

* Microphone type
* Number of microphones
* Microphone-array layout
* Analogue vs digital microphones
* Sampling rate
* Synchronisation
* Signal quality
* Acquisition hardware
* ADC requirements
* Signal conditioning
* Expected acoustic environment

### Questions to Answer

1. What type of microphone would be suitable?
2. How many microphones should the initial system use?
3. How should they be positioned?
4. How will the microphone signals be acquired?
5. How will the microphones remain synchronised?
6. What additional electronics are required?
7. What are the main limitations of the proposed approach?
8. What is the estimated cost?

## 4. Computer Vision Research

Investigate suitable camera and computer vision hardware.

Consider:

* Camera resolution
* Frame rate
* Field of view
* Image quality
* Low-light performance
* Connection/interface
* Processing requirements
* Mounting
* Compatibility with the proposed processing hardware

### Questions to Answer

1. What camera would be suitable?
2. What resolution and frame rate are required?
3. What processing hardware is required?
4. What connection/interface should be used?
5. What limitations does the camera have?
6. What is the estimated cost?

## 5. Embedded Systems Research

Investigate hardware that could be used for sensor interfacing and data acquisition.

Consider:

* Microcontrollers
* ADCs
* GPIO
* Communication interfaces
* Processing capability
* Memory
* Development environment
* Power consumption
* Compatibility with the selected sensors

### Questions to Answer

1. Is a microcontroller required?
2. Which microcontroller platforms are suitable?
3. Can the selected platform handle the required data acquisition?
4. What communication interfaces are available?
5. Can it communicate with the main processing system?
6. What is the estimated cost?

## 6. Processing Hardware Research

Investigate what hardware should handle higher-level processing.

This may include:

* Existing DkIT computers
* Student laptops
* Desktop computers
* Single-board computers
* Other suitable computing platforms

Consider the processing requirements of:

* Acoustic signal processing
* TDOA
* Computer vision
* Object detection
* Object tracking
* Sensor fusion
* Data recording

### Questions to Answer

1. What processing power is required?
2. Can existing DkIT hardware be used?
3. Is dedicated processing hardware necessary?
4. What operating systems and software environments are supported?
5. What is the estimated cost if new hardware is required?

## 7. Power Research

Determine the power requirements of the proposed system.

Consider:

* Required voltages
* Current consumption
* Power supplies
* Voltage regulators
* USB power
* Battery operation if required
* Connectors
* Safety

### Questions to Answer

1. What voltage does each major component require?
2. How much current does each component require?
3. Can a common power supply be used?
4. Are voltage regulators required?
5. What is the estimated cost?

## 8. Mechanical Research

Investigate how the sensors and electronics could be physically mounted.

Consider:

* Microphone spacing
* Camera position
* Sensor alignment
* Adjustable mounting
* Frame design
* Enclosure
* 3D printing
* Workshop facilities
* Fasteners

### Questions to Answer

1. How should the microphones be mounted?
2. Where should the camera be positioned?
3. Does the design need adjustable sensor positions?
4. Can DkIT facilities be used to manufacture the structure?
5. What materials are required?
6. What is the estimated cost?

## 9. Existing DkIT Resources

Before recommending any purchase, investigate what is already available through DkIT.

Look for:

* Microphones
* Cameras
* Microcontrollers
* Development boards
* Oscilloscopes
* Signal generators
* Power supplies
* Computers
* 3D printers
* Workshop equipment
* Electronic components

Record anything useful in `hardware-research.md`.

**Do not assume equipment is available. Confirm it with the relevant staff or laboratory.**

## 10. Comparing Options

Each researcher should investigate more than one option where practical.

For each option, record:

* Product/model
* Supplier
* Cost
* Technical specifications
* Advantages
* Disadvantages
* Compatibility
* Availability
* Documentation
* Recommendation

Avoid choosing a component simply because it has the highest specifications.

The objective is to find the most appropriate option for the project.

## 11. Research Sources

Use reliable sources wherever possible.

Preferred sources include:

* Manufacturer datasheets
* Manufacturer websites
* Technical documentation
* Academic papers
* Reputable electronics suppliers
* Engineering documentation

Avoid relying on a single online review or retailer description for important technical specifications.

Record the sources used so that other team members can verify the research.

## 12. Final Recommendation

Each research area should finish with a clear recommendation.

The recommendation should state:

> **Recommended option:**
>
> **Estimated cost:**
>
> **Why:**
>
> **Main advantages:**
>
> **Main limitations:**
>
> **Alternative considered:**

The recommendation is not automatically the final project decision.

Final hardware selections will be reviewed by the Project Lattice team before being added to the official BOM.

## 13. Deliverable

Each researcher or research group should provide:

* A comparison of suitable options.
* Technical specifications.
* Estimated costs.
* Sources.
* Advantages and disadvantages.
* A final recommendation.

The results should be added to:

`docs/hardware-research.md`

The selected components will later be transferred into:

`hardware/BOM.md`

## 14. Research Deadline

**Deadline:** To be agreed by the Project Lattice team.

Research should be completed early enough to allow the team to review the results, select hardware and identify funding requirements before major purchases are made.

## 15. Important Rule

**Do not purchase hardware based solely on individual research.**

Research first.

Compare options.

Discuss the results with the team.

Then agree on the hardware.

This keeps the project within budget and ensures that major technical decisions are made collectively.
