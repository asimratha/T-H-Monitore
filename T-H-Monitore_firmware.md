VERSION: V1.0.7
NOTES:
Firmware V1.0.7 maintenance release with high-reliability live sensor streaming and safety shutdown.
- FIRMWARE_VER bumped to V1.0.7 aligning with mobile app Obsidian Glass theme update.
- Instant live sensor data dispatch on subscription (DEV_INFO and LIVE: stream).
- Sensor disconnect detection with automatic background recovery.
- Safety relay safeguard: automatically forces relay deactive on sensor timeout/error.
- PartitionScheme=min_spiffs compilation with full OTA flash support.
