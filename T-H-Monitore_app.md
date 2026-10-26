VERSION: 1.1.5
NOTES:
Persistent Preferences, 30s Auto-Reconnect, System Dark Refinement & Background Download Notifications (1.1.5)
- Persistent User Preferences: Saved app theme (system, glass, dark, light) and app style (digital, analog) via SharedPreferences; automatically restored on app startup.
- 30-Second Auto-Reconnect Engine: Automatically attempts to reconnect to the last connected device for 30 seconds upon startup, seamlessly restoring dashboard without manual scanning if device is in range.
- System Default Dark Overhaul: Refined pure dark background (#0A0D14), clean dark slate gray surface cards (#141923), subtle slate borders (#21262D), and crisp white typography (#F0F6FC) with dedicated indicator accents.
- Android Notification Permission & Download Progress: Full POST_NOTIFICATIONS support on Android 13+; live updating percentage & downloaded bytes progress bar in Android notification drawer during update downloads that continues in background if app is minimized.
