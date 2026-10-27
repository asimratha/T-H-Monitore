VERSION: 1.1.7
NOTES:
Quad LDR Analog Monitoring & Settings Control (1.1.7)
- LDR Sensor Monitor in Settings: Added dedicated "LDR Sensor Monitor" card with 4 independent toggle switches for LDR 1 (GPIO 36 VP), LDR 2 (GPIO 39 VN), LDR 3 (GPIO 34), and LDR 4 (GPIO 35).
- Hardware ADC1 Channel Integration: Engineered for ESP32 ADC1 channels, ensuring zero interference with BLE connectivity.
- Real-Time Command & Sync: Toggling any LDR switch immediately dispatches "SET_LDR_SW" BLE command to ESP32, saved persistently to SPIFFS (/ldr_config.json) across reboots.
- Automatic State Sync: Switch states automatically restore and synchronize with the mobile app upon connection via GET_CONFIG and DEV_INFO telemetry.
- Telemetry Streaming: When enabled, ESP32 samples and streams analog readings to Serial Monitor every 1 second ("LDR <X> Value <VALUE>").
- Bumped app version to 1.1.7 (Build: 1.1.7+18) with clean analyzer verification.
