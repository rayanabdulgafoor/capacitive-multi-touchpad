# Multi-Touch Capacitive Sensing Pad

Embedded multi-touch capacitive sensing system with real-time GUI visualization using custom electronics and serial communication.

![Hero Image](/assets/capacitive_multi-touchpad_hero_shot.png)

---
## Full Project Documentation

Detailed project documentation, PCB design workflow, firmware, and GUI implementation are available here:

[Portfolio Documentation](https://www.rayanabdulgafoor.in/projects/embedded-systems/capacitive-multi-touch-pad/index.html)

---
## Overview

This project focuses on the development of a multi-touch capacitive sensing pad capable of detecting touch presence, position, and proximity using capacitive sensing principles. The system was designed to detect multiple touch regions simultaneously and visualize touch intensity in real time through a custom graphical user interface (GUI).

The project combines embedded systems, custom electronics, sensor interfacing, and software visualization workflows using a custom ATtiny1614-based controller and a Python Tkinter GUI.

---

## Key Features

* Multi-touch capacitive sensing system
* Real-time touch intensity visualization
* Custom ATtiny1614-based sensing controller
* Conductive copper tape sensor grid
* Serial communication between embedded system and GUI
* Dynamic color-based touch intensity mapping
* Multi-region touch detection and visualization
* Real-time sensor data processing

---

## Tech Stack / Hardware

ATtiny1614 | Capacitive Sensing | Copper Tape Sensor Grid | Embedded Systems | Serial Communication | Python | Tkinter GUI | PCB Design | PCB Fabrication | Roland Modela MDX-20 Milling Machine

---

## System Architecture

The system consists of:

* Capacitive sensing touch grid
* Custom ATtiny1614 sensing controller
* Serial communication interface
* Real-time Python GUI visualization system

Touch intensity values are continuously processed by the embedded controller and transmitted to the GUI for live visualization and interaction analysis.

---

## Capacitive Sensing System

* Multi-region conductive touch grid using copper tape
* Capacitive sensing-based proximity and touch detection
* Simultaneous multi-touch input processing
* Dynamic touch intensity measurement
* Real-time signal acquisition and analysis

---

## Embedded Electronics

![schematic](/assets/schematic.png)

* Custom PCB designed around the ATtiny1614 microcontroller in KiCad
* Embedded sensing firmware for capacitive input acquisition
* Real-time serial communication implementation
* Sensor region scanning and signal processing workflows

![pcb fabrication](/assets/gerber2png.png)

---
## Fabrication & Assembly

The sensing system was developed using:

* Custom PCB fabrication
* Copper tape sensor grid assembly
* Embedded electronics integration
* Rapid prototyping workflows
* Iterative testing and calibration

![pcb fabrication](/assets/pcb_milling_step_response_pic01.jpg)

---



## GUI & Visualization

A custom Tkinter-based GUI was developed to visualize touch interaction in real time.

![gui](/assets/gui_and_visualization.jpg)

Features include:

* Live touch intensity visualization
* Dynamic region updates
* Real-time serial data parsing
* Color-coded touch mapping
* Interactive sensor response monitoring

Touch regions dynamically transition:

* Green for high-intensity touch
* Red for low or inactive regions

---

## Testing & Validation

The system was tested and validated to evaluate:

* Multi-touch detection accuracy
* Sensor response consistency
* Signal stability
* Real-time GUI responsiveness
* Serial communication reliability
* Touch intensity visualization performance

---



## Media & Demonstration

### Capacitive Sensing Demo

[Watch Demo](https://youtu.be/qT3hmeK4nvs)

Click the link above to watch the full project demonstration.

---



## License

This project is licensed under the MIT License.
