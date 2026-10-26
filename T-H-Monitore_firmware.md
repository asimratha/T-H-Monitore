VERSION: V1.1.0
NOTES:
Firmware V1.1.0 release with Per-Sensor Condition Switch (< / >) & Matrix Evaluation
- Upgraded SensorRule struct to include per-sensor isLessThan condition boolean.
- Matrix evaluation loop in relay_manager independently checks each assigned sensor's condition (< MIN vs >= MAX) against live readings.
- Persistent SPIFFS storage updated: serializes and deserializes the per-sensor "lt" flag in /th_config.json.
- SET_RELAY BLE protocol handler upgraded to parse 18-parameter payloads with per-sensor condition flags while preserving backwards compatibility.
- PartitionScheme=min_spiffs compilation with full wireless BLE OTA update support.
- Fully synchronized with Mobile App V1.1.0.
