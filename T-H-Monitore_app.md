VERSION: 1.1.1
NOTES:
Smart Version Comparison & Analog Thermo-Hygrometer Dial Overhaul (1.1.1)
- Added semantic version comparison engine (_isVersionNewer): accurately parses major.minor.patch versions and prevents redundant update dialogs when firmware/app is up-to-date.
- Settings Tab Firmware Update: Checks GitHub release for firmware updates. Only triggers dialog when a strictly newer version is available; otherwise displays feedback toast "Device firmware is up to date (V...)".
- Startup & Lifecycle Auto-Update: WidgetsBindingObserver auto-checks GitHub releases for Mobile APK updates on startup and app resume. Displays [UPDATE NOW] and [CANCEL] dialog on newer release.
- BLE Connection Auto-Firmware Check: Automatically checks for ESP32 firmware updates when BLE device connects and firmware version is verified.
- App Style Selector: Added "App Style" selector under App Theme in Settings Tab offering "Digital Cards" and "Analog Meters".
- 2x2 Analog Thermo-Hygrometer Gauges: In Preview Tab, "Analog Meters" mode replaces sensor cards with a 2x2 grid of round dual-dial analog gauges:
  - Outer dial: Temperature meter (°C) with Cold (-30..15°C, cyan/blue), Comfort (15..25°C, emerald), and Hot (25..60°C, orange/red) zones and animated needle.
  - Sub-dial: Humidity meter (% RH) with Dry (0..30%), Comfort (30..70%), Wet (70..100%) arcs and sub-needle.
  - Live digital readout pill: "--.- °C • --.- %" with animated telemetry updates.
  - Theme-adaptive glassmorphic aesthetics across Obsidian Glass, Light White, Dark Black, and System.
