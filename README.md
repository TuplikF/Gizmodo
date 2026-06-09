# Gizmodo

# Gizmondo Neo (Work in Progress)

Gizmondo Neo is an open‑source hardware and firmware project inspired by the original Gizmondo handheld.  
This repository currently contains the first iteration of the design, and the project will continue to evolve as new hardware revisions, firmware modules, and documentation are completed.

If you have suggestions, improvements, or technical feedback, feel free to open an Issue or leave a comment. Community input is highly appreciated.

---

## 🚧 Project Status
This is an early‑stage project.  
Both hardware and firmware are under active development, and many features are experimental or not yet implemented.

Expect frequent changes, incomplete modules, and ongoing refactoring.

---

## 🛠 Technical Overview

### Hardware
- **MCU:** ESP32‑S3 (dual‑core, Wi‑Fi, Bluetooth LE)
- **Display:** SPI‑based TFT/IPS panel
- **Input System:** Custom button matrix connected via GPIO
- **Audio:** Planned I2S/DAC output
- **Power & Connectivity:** USB‑C for power, flashing, and serial output
- **Expansion Interfaces:** I²C, SPI, GPIO for additional modules or sensors

All schematics, PCB layouts, and 3D models will be available in the `/hardware` directory as the design progresses.

### Firmware
- Based on **ESP‑IDF** (Arduino layer optional)
- Modular architecture:
  - display driver abstraction
  - input handling
  - basic UI framework
  - audio subsystem (planned)
  - example applications and test utilities

Firmware sources will be located in `/firmware`.

---

## 📁 Repository Structure (planned)



🤝Contributing

This project is open to contributions of all kinds - hardware, firmware, documentation, or testing.

If you notice something missing, unclear, or technically incorrect, please:

open an Issue

submit a Pull Request

start a Discussion

Every contribution helps move the project forward.

📃License

This project is licensed under the Apache License 2.0.

See the LICENSE