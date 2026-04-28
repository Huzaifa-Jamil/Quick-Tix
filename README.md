# Quick Tix

A Java-based ticketing system for event browsing, seat reservation, payment processing, and ticket generation.

---

## Versions

### v1.0.0 — Initial Release
Core ticketing application with:
- Event browsing
- Seat reservation
- Payment processing (Card / JazzCash / EasyPaisa)
- Ticket generation
- User account creation

Files stored relative to project directory.

---

### v2.0.0 — UI & Input Refinement
- UI layout improvements (menu spacing, borders)
- No functional changes from v1.0.0

---

### v3.0.0 — Stability & Path Overhaul
- Rewrote input handling using try-catch validation
- Migrated file storage to AppData/Local/QuickTix/
- Added Desktop.open() for OTP and ticket auto-opening
- Introduced global Scanner and BASE_PATH constant
- Improved empty input handling across application

---

## Requirements
- A Laptop/PC
- Windows operating system recommended
- Java 14 or higher installed (required only for JAR in version 3.0.0)

---

## Usage

### 1. Run EXE version
- Download the latest `.exe` from Releases
- Double-click to run

The application will automatically use:
`C:\Users\<UserName>\AppData\Local\QuickTix\` for storing files.

---

### 2. Run JAR version
- Download and extract `QuickTix-v3.0.0.zip`

Open terminal in extracted folder:

```bash
cd path/to/jar
java -jar Quick_Tix.jar