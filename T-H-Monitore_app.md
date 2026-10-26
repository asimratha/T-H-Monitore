VERSION: 1.1.0
NOTES:
Per-Sensor Condition Switch (< / >) & Multi-Sensor Matrix Overhaul
- Overhauled Relay Configuration: Removed global relay inversion toggle and moved condition control directly into each individual sensor container.
- Added dedicated per-sensor condition toggle switches: "<" [Toggle Switch] ">" to independently set triggering condition to Less Than (< MIN) or Greater Than (> MAX) per sensor rule.
- Dynamic threshold indicators: dynamically display "Trigger if Temp < 28.0 °C" / "Trigger if Temp > 28.0 °C" and humidity equivalents.
- Extended SensorRule model with per-sensor isLessThan condition flag.
- Upgraded SET_RELAY BLE transmission to transmit 18-parameter payload including per-sensor condition flags.
- Fully compatible with ESP32 Firmware V1.1.0.
