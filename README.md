# 🎫 Dristi Badge

> A PCB hackathon badge featuring a camera, display, NFC, and thermal printer integration. Built on ESP32-S3, designed from scratch for the Outpost/Opensauce competition.

**Key Features:**
- 📷 Camera with live viewfinder
- 🎮 Game mode with sprite support
- 📱 E-ink display
- 🏷️ NFC capability
- 🖨️ Thermal printer sticker output
- 🔋 Rechargeable LiPo battery system
- 💾 SD card storage

---
## Board Images

<div align="center">
  <img src="Assets/frontrender.png" alt="DroydBadge - Front View" width="40%" />
  <img src="Assets/backrender.png" alt="DroydBadge - Back View" width="40%" />
</div>

<div align="center">
  <img src="Assets/frontpcb.png" alt="PCB Layout - Top View" width="40%" />
  <img src="Assets/backpcb.png" alt="PCB Layout - Detailed View" width="40%" />
</div>

<div align="center">
  <img src="Assets/schema.png" alt="Power System Schematic" width="90%" />
</div>

---

## Development Log

### June ≤15th — Power System & Charging

**Goal:** Establish reliable power distribution and charging infrastructure

I identified all required components and sourced them from JLCPCB for easy access and datasheet reference. My primary focus was setting up a charging system for the rechargeable LiPo battery. I designed the complete charging circuit including the charging IC, ESD protection, and USB connector.

**Time Spent:** 3 hrs

---

### June 17th — Voltage Regulation & ESP32 Pinout

**Goal:** Complete power delivery and microcontroller initialization

I finalized the battery voltage regulation section and began mapping the essential ESP32 pins (power, reset, and boot). This established the foundation for the rest of the digital systems on the badge.

**Time Spent:** 2 hrs

---

### June 18th-19th — Sensors & I/O Expansion

**Goal:** Integrate motion sensing and expand GPIO capabilities

With the power system complete, I moved on to the peripheral modules. I wired up the accelerometer (for camera/game mode detection) and configured the primary I/O expander to handle additional I/O requirements.

**Time Spent:** 2.2 hrs

---

### June 22nd

*In Progress...*

---

### June 23rd

*In Progress...*

---

## 📁 Project Structure

- **CAD/** — 3D case design files
- **Gerber_PCB/** — PCB manufacturing files (Gerber format)
- **PCB/** — KiCad project files
- **Assets/** — Documentation and reference materials
