VERSION: V1.0.9
NOTES:
Firmware V1.0.9 release with Multi-Sensor Relay Matrix evaluation & persistent SPIFFS storage.
- Full multi-sensor matrix evaluation in relay_manager: each relay R1..R4 independently checks all assigned sensors.
- Normal logic: triggers when any enabled sensor matches or rises above threshold (>=).
- Inverted logic: triggers when any enabled sensor falls below threshold (<).
- Non-blocking SPIFFS serialization/deserialization for r1..r4 and s1..s4 matrix JSON schema.
- Automatic migration from legacy 1-to-1 config format to multi-sensor matrix format.
- Added SET_RELAY protocol command handler with SET_RELAY_OK confirmation.
- PartitionScheme=min_spiffs compilation with full OTA wireless update support.
- Fully synchronized with Mobile App V1.0.9 and 3D Obsidian Glass telemetry display.
