VERSION: V1.0.5
NOTES:
Real-time sensor disconnect detection, relay safety shutdown, and auto-recovery.
- Instant sensor connectivity tracking with automatic disconnect detection (isnan read failure/timeout).
- Safety relay safeguard: automatically deactivates relay output if sensor disconnects.
- Real-time BLE disconnect telemetry streaming T<ch>=ERR,H<ch>=ERR to alert connected app.
- Continuous background polling with seamless recovery the moment sensor is plugged back in.
- Strict on-change BLE notifications and clean serial output.
