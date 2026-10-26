VERSION: 1.1.3
NOTES:
Open-Arc Analog Dial, 1:1 Square Cards & Fixed Persistent Footer (1.1.3)
- Open-Arc Dial Aesthetic: Removed outer gray/red circular boundary outline from both the main temperature gauge and humidity sub-gauge; both now render as clean, modern open-arc sweeps.
- Lowered Humidity Sub-Dial: Shifted humidity sub-dial center lower down so the main needle pivot and sweep do not enter into or overlap the humidity center circle.
- 1:1 Square Gauge Cards: Configured analog gauge cards to childAspectRatio 1.0 (perfect square) and added responsive LayoutBuilder to dynamically expand gauge diameter to full card capacity.
- Fixed Persistent Footer: Relocated "Powered by PriME Technology" branding directly above the BottomNavigationBar inside the Scaffold dock; permanently fixed across all 4 tabs (Preview, Relays, Config, Settings), immune to scroll shifts or card clipping.
- ESP32 Firmware Compatibility: Full BLE telemetry & matrix control preserved with firmware V1.1.2.
