# Nuttfy Board – Arduino Core (Customized NodeMCU BSP)

## Overview

Nuttfy Board is a **fully customized Arduino-compatible development board** built on the **NodeMCU platform**, modified to meet **real-life project requirements at an advanced level**.

The main objectives:

* Provide an easy start for beginners
* Offer a stable and flexible environment for real projects
* Remove unnecessary limitations and allow advanced configurations

> ⚠️ Note: This is a **customized and modified board support package** specifically designed for **Nuttfy Board**.

---

## Why Nuttfy Board?

When I started learning microcontroller programming, I realized:

* Each project has unique requirements
* Default settings are not always efficient
* Advanced control requires customization

**Nuttfy Board** was created to:

* Be beginner-friendly
* Be powerful for advanced users
* Be optimized for real-world IoT and automation projects

---

## Key Features

* Arduino-compatible programming
* Built-in WiFi networking support (TCP / UDP)
* HTTP Server & Client capability
* OTA (Over-The-Air) update support
* Flash-based file system support
* mDNS, SSDP, DNS server functionality
* SPI, I2C, UART peripheral support
* Servo & SD card compatibility
* Optimized memory management

> All features are enabled with custom configurations for better performance and stability.

---

## Installation Options

Nuttfy Board can be installed and used in multiple ways:

### 1. Using Arduino Boards Manager (Recommended)

Best method for beginners.

**Steps:**

1. Install Arduino IDE (1.x or 2.x)
2. Open Arduino IDE
3. Go to `File > Preferences`
4. Add the following URL to **Additional Boards Manager URLs**:
   `https://raw.githubusercontent.com/techmcu/nuttyfi/refs/heads/main/package/package_nuttyfi_index.json`
5. Open `Tools > Board > Boards Manager`
6. Install **Nuttfy Board Platform**
7. Select **Nuttfy Board** from the board list

---

### 2. Using Git Version (Advanced Users)

For users who want the latest changes and manual configuration:

* Source-based installation
* Custom experimentation and testing

---

### 3. Using PlatformIO

PlatformIO is a powerful ecosystem for IoT development.

Supported Systems:

* Windows
* Linux (32/64)
* macOS
* ARM-based systems

Features:

* Advanced build system
* Library manager
* OTA upload support
* Cloud & local IDE integration

---

### 4. Building with Makefile

For production and automated builds:

* Custom makefile based build
* CI/CD friendly
* Recommended for large projects

---

## Documentation

* Latest stable documentation: *(internal / project-specific)*
* Development version docs: *(updated with custom changes)*

---

## Issues & Support

When reporting issues, include:

* Board version
* IDE settings
* Flash size
* Serial output

Support and discussions are available for learning and troubleshooting.

---

## Contributing

If you want to improve Nuttfy Board:

* Minor fixes → Direct pull request
* Major changes → Discuss before PR

Guidelines:

* Clean commits
* Single-purpose changes
* Proper testing

---

## License & Credits

* Based on Arduino ecosystem open-source tools
* Toolchains and libraries under respective open-source licenses
* Custom modifications maintained under **Nuttfy Board Project**

---

## Final Note

Nuttfy Board is not just a development board —
It is a **complete solution from learning to production**.

> This board is created keeping my needs, experience, and real-world problems in mind, so beginners like me can avoid struggles in the future. 🚀

---

Happy Coding 💻
Happy Building 🔧
