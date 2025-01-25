# Body Control Module (BCM) for Automotive Applications

## Overview
This repository contains the development of a customized Body Control Module (BCM) for automotive applications. The system is built using the STM32F4 processor and is designed to be modular, configurable, and highly efficient for managing various automotive electrical functionalities.

## Features
- **Electrical Function Management:**
  - Control of lights, wipers, dashboard controls, and other electrical systems.

- **Dual CAN Bus Communication:**
  - Ensures seamless integration with automotive subsystems.

- **Configurable Inputs/Outputs:**
  - Accessible via USB, Bluetooth, or web interface.
  - Settings are securely stored in FRAM for persistent and reliable operation.

- **Advanced Logic Control:**
  - Implements custom automotive functionalities using STM32Duino and FreeRTOS.

## System Architecture
1. **Processor:** STM32F4 microcontroller for robust and real-time processing.
2. **Communication:** Dual CAN bus for interaction with other vehicle modules.
3. **Configuration:**
   - User-friendly interfaces for setup and customization.
   - FRAM storage ensures data retention even during power loss.
4. **Software Frameworks:**
   - STM32Duino for efficient development and Arduino compatibility.
   - FreeRTOS for multitasking and real-time control.

## Applications
- Control of interior and exterior vehicle lighting systems.
- Wiper and washer control.
- Dashboard and infotainment management.
- Integration of custom automotive functions.

## Getting Started
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ishtiiyak/bmc_module.git
   ```
2. **Hardware Setup:**
   - Connect the STM32F4 microcontroller to the required hardware peripherals (lights, wipers, CAN bus, etc.).
3. **Software Installation:**
   - Install the STM32Duino framework and FreeRTOS libraries.
   - Set up the development environment (e.g., Arduino IDE, STM32CubeIDE).
4. **Configuration:**
   - Use the provided interfaces (USB, Bluetooth, or web) to configure the inputs/outputs.
5. **Deployment:**
   - Flash the firmware onto the STM32F4 microcontroller.

## Contributions
Contributions are welcome! Feel free to fork this repository, make improvements, and submit pull requests.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For queries or collaboration, please contact ishtiiyak@gmail.com.

---
**Note:** Ensure proper safety measures are followed during hardware setup and testing, as automotive systems interact with critical components.
