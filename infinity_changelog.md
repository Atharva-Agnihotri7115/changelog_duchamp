# Device Changelog

## 13/07/2025
- Switched to OSS (Open Source) Kernel for improved performance and maintainability
- Implemented MIUI-style color profile modes
- Fixed color flickering issues
- Resolved Turbo Charge (18W) not working for some users
- Fixed Wi-Fi wakelock causing idle battery drain
- Removed 30Hz refresh rate mode entirely
- Fixed adaptive refresh rate behavior
- Battery charge ETA now displays correctly
- Reverted back to previous thermal implementation as newer ones were causing heating

## 06/07/2025
- Tweak Thermal a bit
- Import prebuilt kernel 6.1.78
- Import Vendor Blobs from HyperOS EEA
- Fix WPA3/WiFi6

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

