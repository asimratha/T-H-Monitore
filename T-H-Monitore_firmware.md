VERSION: V1.0.6
NOTES:
Immediate live telemetry on subscription, reliable sync, and sensor health monitoring.
- Immediate dispatch of current live readings (LIVE:T1=...,H1=...,R1=...) on subscription and GET_CONFIG.
- Eliminates sensor waiting state by instantly transmitting live temperature, humidity, and ERR states.
- Real-time sensor disconnect detection with automatic background recovery.
- Safety relay safeguard: automatically deactivates relay output if sensor disconnects.
- Strict on-change BLE notifications and clean serial output.
