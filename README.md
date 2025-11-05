# Zeroforce Antivirus

> "The only antivirus Windows 2000 will ever need."

---

## About Zeroforce

Zeroforce is a custom-built, C++ antivirus engine for legacy Windows systems primarily Windows 2000 (and at some point for XP).  
It started as a personal challenge to see how far a pure Win32/MSVC6 project could go toward building modern protection on old hardware/OS.

This repository serves as the **only official release archive and update log** for Zeroforce.  
No source code is publicly released during the early development phase (at least up to **v1.0.0**).  
Until then, this repo only hosts **compiled releases, changelogs, and update announcements**.

---

## Technical Overview

| Component | Description |
|------------|--------------|
| **Core Engine** | Full system + file scan. Scans all file types with position-independent signature matching. |
| **Heuristics** | Entropy analysis + PE structure logic. Low/Medium/High/Extreme threat scoring. |
| **Self-Protection** | Prevents self-flagging or rename bypass. |
| **Dependencies** | SDK RC2 (None for 0.0.1)
| **Compiler** | Microsoft Visual C++ 6.0 (1998). |
| **Executable Size** | 88–96 KB depending on version. |
| **RAM Usage** | 2–5 MB 

---

## Development Timeline

| Version | Codename | Date | Highlights |
|----------|-----------|------|------------|
| **0.0.1 – Genesis** | 2025-11-04 | First build. Full EICAR detection, quarantine system, self-exclusion, GUI with live log. |
| **0.0.2 – Worm Patch** | 2025-11-05 | Added script-worm detection, Improved Quarantine System, Improved Scanning, Improved UI Stabillity. |

---

## Next Goals

- Real-time protection
- Better quarantine handling
- Improved system protection / self-repair
- Auto-Update
- Cleaner and Better UI Design

---

## Technical Environment

- **Language:** C++ (pure Win32 API)
- **Compiler:** MSVC6 (1998 toolchain)
- **Target OS:** Windows 2000 (NT 4.0)
- **Platform SDK Release Candidate 2**

---

## Repository Policy

> **Important Notice**

- **Zeroforce is not open source (until at least v1.0.0).**  
- Source code is privately maintained to ensure stability and security during early development.
- This repository exists solely for **version releases, changelogs, and technical archives**.
- Once the engine reaches **v1.0.0**, open-source release will be re-evaluated.

## Credits

- **Project Lead:** F1re-ops    
- **Core Engine:** Zeroforce  
- **Written in:** C++ / Win32 API  
- **Build Tool:** MSVC6 (1998)

---

All rights reserved © 2025 F1re-ops.  
Zeroforce binaries and documentation may not be redistributed, modified, or reverse-engineered without explicit permission.  
This repository is for historical preservation, update tracking, and educational documentation only.

---

