VERSION: 1.0.6
NOTES:
Resilient BLE sync, 60s radar scanner animation, and instant telemetry.
- Fixed BLE synchronization: eliminated redundant GET_CONFIG requests and resolved JSON Parse errors.
- 60-second continuous green neon radar pulse animation on scanning screen.
- Auto-stops scanning immediately upon device selection (zero background scan overhead).
- Full-width stylish disconnected sensor alert UI: [ ⚠️ NO SENSOR CHANNEL <X> DISCONNECTED ].
- Dynamic AppBar subtitle reliably rendering full MAC address and device firmware version.
