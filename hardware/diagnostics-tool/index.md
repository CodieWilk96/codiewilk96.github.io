# Universal Hardware Diagnostics Tool

The Universal Diagnostics Tool is a modular, multi‑sensor hardware platform designed to identify and diagnose physical faults in smartphones, tablets, and laptops. Unlike traditional repair tools that only test individual components, this system evaluates an entire device at once using a network of interchangeable diagnostic modules.

It can detect issues ranging from simple component failures—like a bad resistor or damaged connector—to complex faults such as shorted power rails, failing sensors, degraded batteries, or unstable voltage regulators. Each module focuses on a specific type of signal or behavior, and together they provide a complete picture of a device’s health.

This tool is built for repair technicians, refurbishers, and hardware developers who need fast, accurate insight into what’s wrong with a device before opening it or replacing parts.

## Device Modules

Each part of the diagnostics tool is built as an independent module, allowing the system to analyze different electrical, thermal, and structural behaviors. Together, these modules form a complete diagnostic platform.

- [Full Cradle Overview](full-cradle-overview.md)  
  The physical frame that positions all sensors around the device under test. It ensures consistent geometry, stable readings, and repeatable diagnostics.

- [NCV Buffer Module](ncv-buffer-module.md)  
  A high‑sensitivity non‑contact voltage detection module used to identify shorts, power‑rail anomalies, and abnormal AC field activity.

- [Thermistor Grid](thermistor-grid.md)  
  A matrix of precision thermistors that maps heat distribution across the device, revealing thermal runaway, cold zones, and component‑level failures.

- [Hall Sensor Array](hall-sensor-array.md)
  An array of analog and digital EM hall sensors strategically positioned throughout the cradles sensor grid. Their purpose is to detect EM signatures and send the data back to the brain to be analyzed.

- [Brain Module](brain-module.md)  
  The central controller that reads sensor data, processes signals, and communicates with the UI. This module synchronizes all other modules.

- [Power Module](power-module.md)  
  Provides clean, isolated power rails for the sensors and supports high‑current testing for devices under load. Includes protection and monitoring circuitry.

- [USB Interface](usb-interface.md)  
  Handles communication with the device being tested, enabling software‑assisted diagnostics, USB descriptor reading, charging behavior analysis, and log extraction.

