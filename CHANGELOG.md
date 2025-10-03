# 📋 Change Log

All notable changes to this project will be documented in this file.

## [0.3.1-beta] - 2025-10-03

### 🐞 Fixes
- Fixed issue with meter graduations running together when downsizing the window.
- Fixed issue of blank form when Always on Top enabled.

---

## [0.3.0-beta] - 2025-09-10

### ✨ Features
- Added **meter modes**: Live, Peak, Hold, None — freeze or follow peaks just like a true peak meter.
- **CW-friendly polling** with tunable intervals, reducing PTT delay in CW operation.
- **Automatic serial reconnect** when the Mercury LUX amplifier is powered back on (no user interaction required).
- Improved **On-Air notification styling** (bold white on red, fixed size).
- **Hide/show meter ticks and tick labels** for a cleaner or more detailed display.
- **Alarm codes mapped to friendly names** from the user manual for easier troubleshooting.
- Added **EMA smoothing option** for meter updates, improving readability of fast-changing signals.

### 🛠 Improvements
- **Cadence-based updates** to PowerBar text and bar values, making SSB and CW signals easier to follow.
- Tick labels now **color-coded** (green/yellow/red) according to thresholds.
- Peak marker **decay scales with meter range** for consistent responsiveness across meters.
- **App Scale Factor** now properly persists after Save and restart.
- **Light theme readability improvements** (green/yellow text fixed).
- **TLS certificate generation** handling improved — clearer errors if OpenSSL or config missing.

### 🐞 Fixes
- Fixed **black window issue** when restoring from “Show Desktop” on Windows.
- Fixed TLS errors when **OpenSSL was not found or config file missing**.
- Fixed **tick label overlap/cutoff** (e.g., at 1800 W).
- Fixed **bar/value disappearing** in None meter mode.
- Fixed **App Scale Factor reset** bug after Save.
- Fixed client app showing stale meter values when server was closed — meters now clear and state updates immediately.

⚠️ **Notes for power users:**
Advanced meter and comm parameters (e.g., hold/decay rates, polling intervals) are not exposed in the GUI, but can be tuned via the settings file (or Registry on Windows).

---

## [v0.2.0-beta] – 2025-08-xx

### Added
- Initial implementation of peak hold with cadence smoothing on power meters.
- Dynamic tick label placement and spacing improvements.
- Enhanced TLS certificate generator handling for Windows and Linux.
- User theme options: Light/Dark modes with font scaling support.

### Fixed
- Light theme readability issues for yellow/green colors.
- Taskbar submenu behavior when restoring from “Show Desktop”.


---

## [v0.1.0-beta] – 2025-07-17

### Added
- Initial beta release for Windows, macOS, and Linux (`x86_64`, `aarch64`)
- Real-time amplifier telemetry & visualization
- TLS Certificate Generator under **Tools → Generate TLS Certificate**
- See [README](https://github.com/RayJr2/MercuryXPc/) for more details

### Known Issues
- macOS Gatekeeper warning (requires manual override in **System Settings → Security & Privacy**)
- No automatic update mechanism yet

### Download Links
Go to [Releases](https://github.com/RayJr2/MercuryXPc/releases) to download the latest builds.

---

## 🛠️ Submitting Feedback

We welcome bug reports and feature suggestions from beta testers.

- 🐞 [Submit a Bug Report](https://github.com/RayJr2/MercuryXPc/issues/new?template=bug_report.md)
- 💡 [Request a Feature](https://github.com/RayJr2/MercuryXPc/issues/new?template=feature_request.md)

You can also view and track open issues here:  
👉 [https://github.com/RayJr2/MercuryXPc/issues](https://github.com/RayJr2/MercuryXPc/issues)

