# EV Tracker â€” College-Friendly IoT Initiative

An IoT-based Electric Vehicle (EV) tracking and monitoring system developed as a college internship project. The system is designed to be an affordable, accessible solution for tracking EV usage on college campuses.

> **Note:** The original repo name uses triple dashes (`EV-Tracker---College-friendly-Initiative`). Consider renaming it to `EV-Tracker-College-Initiative` for cleaner formatting.

---

## Overview

This project aims to build a low-cost EV tracking solution tailored for college environments â€” tracking vehicle location, monitoring battery state, and logging trip data. The system bridges embedded hardware (sensors + microcontroller) with a data backend for real-time monitoring.

---

## Project Context

| Detail | Info |
|--------|------|
| Type | Industry Internship Project |
| Domain | IoT / Embedded Systems / Electric Vehicles |
| Institution | Anna University |
| Documents | Project Report, NDA, Internship Letters |

---

## System Architecture (Proposed)

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”        â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”        â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚   EV Hardware    â”‚â”€â”€GPSâ”€â”€â–¶â”‚  MCU / Pico â”‚â”€â”€WiFiâ”€â–¶â”‚  Cloud / DB  â”‚
â”‚  (Battery, Motor)â”‚        â”‚  (RP2040)   â”‚        â”‚  Dashboard   â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜        â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜        â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                                  â”‚
                             SD Card Log
```

---

## Features (Planned / Implemented)

- Real-time GPS tracking of EV location
- Battery voltage and State-of-Charge (SoC) monitoring
- Trip data logging to SD card (CSV format)
- Dashboard for live tracking
- Geofencing alerts for campus boundary violations

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Microcontroller | Raspberry Pi Pico / ESP32 |
| Communication | WiFi / GSM (SIM800L) |
| Location | NEO-6M GPS Module |
| Storage | MicroSD Card |
| Frontend | Web Dashboard (planned) |
| Protocol | MQTT / HTTP REST |

---

## Repository Contents

| File | Description |
|------|-------------|
| `EV TRACKER_P&R_2025.pdf` | Project proposal and requirements document |
| `Acceptance & Joining form.pdf` | Internship acceptance documentation |
| `Internship Permission Letter - Anna University.pdf` | University permission for internship |
| `NON DISCLOSURE AGREEMENT.pdf` | NDA with the host organization |
| `Terms and Conditions.pdf` | Internship terms |

> **Important:** The resume PDF (`umeshkannakb_amwayresume_2025.pdf`) should be removed from this public repo and stored privately. Resumes should not be in public project repositories.

---

## File Structure (To Be Built)

```
EV-Tracker-College-Initiative/
â”œâ”€â”€ README.md
â”œâ”€â”€ .gitignore
â”œâ”€â”€ docs/
â”‚   â”œâ”€â”€ EV_TRACKER_Project_Report.pdf   â† Move existing PDF here
â”‚   â”œâ”€â”€ system_architecture.png         â† Block diagram
â”‚   â””â”€â”€ circuit_diagram.png             â† Hardware wiring
â”œâ”€â”€ firmware/
â”‚   â””â”€â”€ main.py                         â† MicroPython firmware
â”œâ”€â”€ hardware/
â”‚   â””â”€â”€ bom.md                          â† Bill of materials
â””â”€â”€ dashboard/                          â† Web frontend (if applicable)
```

---

## What to Add Next

- [ ] Remove `umeshkannakb_amwayresume_2025.pdf` from this public repo
- [ ] Add firmware source code to `firmware/`
- [ ] Add circuit schematic / wiring diagram to `docs/`
- [ ] Add system architecture block diagram
- [ ] Set GitHub topics: `iot` `electric-vehicle` `ev-tracker` `raspberry-pi-pico` `embedded-systems` `college-project` `gps`

---

## License

MIT License
