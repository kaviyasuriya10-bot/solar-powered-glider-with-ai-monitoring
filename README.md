## Overview

This project presents the design and development of a solar-powered autonomous glider with AI-based monitoring capabilities. The system integrates renewable energy, embedded electronics, and flight control to enable efficient and long-endurance aerial operation.

![Solar Glider](https://github.com/user-attachments/assets/b6b901fc-1503-4f5c-ac58-f5eaf1de84e6)

The glider uses solar panels to supplement battery power, extending flight duration while reducing dependence on ground charging. A flight controller manages stabilization and navigation, while onboard electronics monitor system performance in real time.

---

## Key Features

* Solar-assisted power system for extended endurance
* Autonomous flight using Pixhawk and ArduPlane
* Real-time telemetry and system monitoring
* Lightweight fixed-wing glider design
* Modular architecture for future AI integration

---

## System Components

* **Flight Controller:** Pixhawk
* **Power System:** LiPo battery + solar panels + CN3722 MPPT
* **Sensors:** IMU, GPS, barometer, compass
* **Communication:** Telemetry module
* **Actuators:** Servo motors and brushless motor (ESC controlled)

---

## How It Works

Solar panels generate energy during flight and charge the battery through an MPPT controller. The flight controller processes sensor data to maintain stable flight and execute missions. Control signals are sent to servos and the motor to adjust the aircraft’s movement.

---

## Repository Structure

* `firmware/` → Pixhawk configuration and companion control code
* `hardware/` → Wiring diagrams and system design
* `cad/` → 3D models of the glider
* `docs/` → Documentation and design explanations
* `bom.csv` → Bill of materials

(https://www.eclipson-airplanes.com/_files/ugd/f2f22d_e23a7729de954317890bd4dba99b989c.pdf)

---

## Project Status

This project is currently in the design and prototyping phase. Hardware integration and real-world testing are planned for future stages.

---

## Future Improvements

* AI-based flight optimization
* Solar energy-aware navigation
* Autonomous landing system
* Advanced telemetry and data logging
* Optional upgrades:

  * Caddx Ratel 2 Micro FPV Camera
  * Thermal sensor (for environmental monitoring)
  * External charger (e.g., IMAX B6)

---

## Goal

To develop a low-cost, efficient, and scalable solar-powered UAV platform for research, learning, and real-world applications.

## NOTE:
Some basic components like connectors and wiring are already available and not included in the cost.

other components like GPS,gyro sensor,barometer,altitude sensor and some other

The solar panels are used to supplement battery power and extend flight time, not to fully power the aircraft.

solar panels sourced locally at reduced cost

## Badges Justification

CAD: Airframe designed using CAD modeling for aerodynamic structure.

Motors: Brushless motor and servos are used for propulsion and control surfaces.

I2C: Sensors such as IMU and GPS communicate with the flight controller using I2C protocol.
