# Smart-Switch-DIY
Ever wished to turn your regular light switches into smart switches without the hassle of modifying your AC switchboards? This DIY project utilizes ESP8266-01, a solid-state relay, and a Hi-Link power supply to create a cost-effective smart switch solution.

## Project Overview

- *Features:*
  - Converts conventional switches into smart switches without modifying AC switchboards.
  - Uses ESP8266-01 for the project's core.
  - Incorporates a solid-state relay for secure AC switching.
  - Powered by a Hi-Link supply.
  - Includes a custom-designed 3D-printed enclosure for safety and aesthetics.

- *Project Components:*
  - ESP8266-01
  - Solid-state relay
  - Hi-Link power supply
  - 3D-printed enclosure

## Project Structure

1. */Documentation:*
   - README.md: Project overview, setup instructions, and documentation.
   - Project_Schematic.png: Schematic diagram of the project.
   - Project_Design.jpg: Images of the physical switch design.
   - ...

2. */Code:*
   - smart_switch.ino: Arduino code for the project.
   - ...

3. */Designs:*
   - 3D_Print_Enclosure.stl: 3D printable enclosure file.
   - ...

## Circuit Diagram

![Circuit Diagram](Documentation/Project_Schematic.png)

## Getting Started

Follow these steps to set up the smart switch:

1. *Materials Required:*
   - ESP-01
   - Hi-Link Power Supply (5V 0.6A)
   - Solid State Relay
   - Terminal Block
   - Capacitor (100uF, 2.2uF)
   - Resistor (100KΩ, 10KΩ, 1KΩ)
   - BC557 Transistor
   - AMS1117 3.3V Voltage Regulator
   - Soldering Kit
   - Connecting Wires
   - Perf Board
   - Wi-Fi Smart Switch Circuit Diagram (see /Documentation)

2. *Circuit Connections:*
   - Refer to the circuit diagram in /Documentation for detailed connections.

3. *Arduino Setup:*
   - Open smart_switch.ino in the Arduino IDE.
   - Upload the code to your ESP8266-01.

4. *Usage:*
   - Power up the circuit and connect to the Wi-Fi network.
   - Access the smart switch interface through a web browser.
