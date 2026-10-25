VERSION: V1.0.1
NOTES:
SPIFFS persistent file storage (/th_config.json), on-change BLE notifications stream (zero lag), and instant DEV_INFO handshake.
- Refactored persistent storage to genuine SPIFFS file system via SPIFFS.h and SPIFFS.cpp.
- Real-time on-change BLE notifications (notifies only when delta >= 0.2°C, delta >= 0.5% RH, or relay flips) + 10s heartbeat.
- Instant DEV_INFO transmission returning MAC address and firmware version upon connection.
- Compiled targeting Minimal SPIFFS (1.9MB app space with wireless OTA support).
