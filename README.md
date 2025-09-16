# Joystick & Rudder Pedals with Realistic Trim System

Welcome to the repository for my custom-designed **joystick and rudder pedal system**, built with 3D-printed components and a **realistic trim system** aimed at student pilots, flight sim enthusiasts, and hobbyists.

## Project Overview

This project is focused on delivering a more immersive and mechanically faithful flight control experience. The key features include:

- **Acceptable Trim System** – Allows pilots to "trim off control pressures" as they would in a real aircraft.
- **Hall Effect Sensor Input** – Uses hall effect sensors for smooth, precise control with minimal wear.
- **3D-Printable** – All mechanical components are either 3D printable on most standard FDM printers or available at hardware stores or amazon.
- **Arduino-Based Electronics** – Design goals include easy setup and future implementation of portable version with 2.4GHz transmitter for use with quadcopter and R/C airplanes.

## Repository Contents

- `Console/` – 3D printable parts for throttle, flap, gear, and additional, configurable switches.
- `MKII_Joystick/` – 3D printable parts for the joystick mechanism.
- `Rudder Pedals/` – STL files for the rudder pedal system.
- Root level stl files are used throughout
- Code, assembly instructions, photos to follow

## Technologies Used

- **Arduino Micro** for reading sensor input.
- **Linear Hall Effect Sensors (SS49E)** for detecting axis movement.
- **3D CAD** for component design (Fusion 360).
- **FDM 3D Printer** this project was developed with an FDM 3D printer in mind for making physical components. All necessary parts fit on a 200mm x 200mm print bed.
- **Joystick Library** This project uses MHeironimus' joystick library which you'll need to download from here: https://github.com/MHeironimus/ArduinoJoystickLibrary

## Customization

This design is open for experimentation:
- Adjust control forces with different springs or electromagnets in the future.
- Adapt to different form factors or simulators eg. implement a collective for rotary wing simulations
- Expand with scale to a permanent-installation cockpit,

## Goals

- Deliver an **affordable** (approximately $250 CA in parts) but **high-fidelity** home cockpit experience.
- Provide a **satisfactory trim system** that allows pilots to practice proper trimming techniques in a flight simulator.
- Keep everything **open-source** and easy to replicate.

## Build and Setup

*Details, photos, and instructions to follow*
