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

### v2.0.0 — Minor Changes
- Fixed input mismatch bugs, file/folder checks
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

- Download the `Source code (zip)` from the **Latest Releases** which will be named as `QuickTix-v3.0.0.zip`
- Extract the zip file
- Note: Java 14 or higher installed 

Open terminal in the extracted folder and run:

```bash
java -jar Quick_Tix.jar

```