<p align="center">
  <img src="custom/res/QGCLogoFull.svg" alt="OrbexaGCS Logo" width="400">
</p>

<h1 align="center">OrbexaGCS</h1>

<p align="center">
  <b>A High-Performance, Custom Ground Control Station for Autonomous Systems</b>
</p>

<p align="center">
  <a href="https://github.com/mavlink/qgroundcontrol/releases">
    <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-blue" alt="Supported Platforms">
  </a>
  <a href="https://github.com/mavlink/qgroundcontrol/blob/master/.github/COPYING.md">
    <img src="https://img.shields.io/badge/License-Apache%202.0%20%2F%20GPL%20v3-green" alt="License">
  </a>
</p>

---

*OrbexaGCS* is a customized, streamlined Ground Control Station engineered specifically for precision flight operations, mission planning, and real-time telemetry management. Built on top of the robust QGroundControl engine, OrbexaGCS offers an enhanced, bespoke user interface tailored for modern UAV operations.

---

### 🌟 Key Enhancements in OrbexaGCS

* 🎨 **Customized User Interface**: Re-branded header, navigation bars, and custom color palette tuned for high readability in outdoor and indoor field conditions.
* 🎯 **Optimized Workflow**: Streamlined single-vehicle focus with simplified dashboard metrics to reduce pilot cognitive load.
* 🛰️ **Comprehensive Mission Planning**: Drag-and-drop waypoint generation, survey grid planning, and real-time waypoint synchronization over MAVLink.
* ⚡ **PX4 & ArduPilot Integration**: Full native support for advanced parameter configuration, sensor calibration, and vehicle setup across PX4 Pro and ArduPilot systems.

---

### 🚁 Core Features

* **Full Flight Control & Telemetry:** Real-time HUD, PFD instruments, live map tile caching, and dynamic flight mode status.
* **Custom Toolbar Actions:** Dedicated action lists customized for custom vehicle routines and mission commands.
* **Open Source Base:** Maintained and customized through strict C++ plugin overrides (`CustomPlugin`) and isolated CMake modular builds.

---

### 🛠️ Developer & Build Guide

#### System Requirements
* **Qt Framework:** Qt 6.8.3 (MSVC 2022 64-bit)
* **Build System:** CMake 3.22+ & Ninja
* **Compiler:** MSVC 2022 (Windows) / GCC / Clang

#### Build Steps
1. Clone the repository with submodules:
   ```bash
   git clone --recursive [https://github.com/your-org/groundcontroller.git](https://github.com/your-org/groundcontroller.git)
   cd groundcontroller