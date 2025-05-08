# Device Changelog

## 08/05/2025
- Dropped Per-App Thermal Profile (was causing inconsistency and conflicts with Thermal Profile QS Tile)
- Added UDFPS Customisation Back
- Added Display Saturation Manager

## 04/05/2025
- Nuked Display Engine
- Added Dirty GPU fix and new thermal profiles (@luxured)
- Implemented new AIDL fingerprint solution (@rio113)
- Disabled "Lift to Check" by default
- Relaxed Auto-Brightness adjustment (@rio113)

## 21/04/2025
- Fixed High Touch Sampling Rate
- Reverted to usual implementation of refresh rate settings (allows switching between 60/90/120 Hz directly from Display Settings)
- Added Turbo Charging Wattage Limiter in XiaomiParts
- Switched to AIDL fingerprint instead of prebuilt  
  → Fixed Screen-off FOD for Goodix users; FPC users will retain the same experience as earlier builds.
