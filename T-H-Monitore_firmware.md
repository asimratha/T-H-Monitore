VERSION: V1.1.3
NOTES:
Firmware V1.1.3 release with Quad LDR Analog Monitoring & Settings Control
- FIRMWARE_VER bumped to "V1.1.3" with Quad LDR telemetry engine.
- Configured LDR analog input pins on ADC1 channels: LDR1 (GPIO 36), LDR2 (GPIO 39), LDR3 (GPIO 34), LDR4 (GPIO 35).
- Persistent SPIFFS storage (/ldr_config.json) for 4 LDR switch states.
- 1-second non-blocking timer reads and prints active LDR channels to Serial Monitor ("LDR <X> Value <VALUE>").
- BLE command handlers for "SET_LDR_SW" and "GET_LDR_SW" with instant notifications.
- PartitionScheme=min_spiffs compilation with full wireless BLE OTA update support.
- Fully synchronized with Mobile App 1.1.7.
