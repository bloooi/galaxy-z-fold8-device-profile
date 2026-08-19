# Galaxy Z Fold8 Device Profile

Samsung Galaxy Z Fold8 (SM-F971) Android Emulator hardware profile.

## Basis

This is an Android SDK `devices.xml` hardware definition (`schemas.android.com/sdk/devices/10`).

The internal device id is `pixel_10_pro_fold` on purpose. That is the foldable key the Android Emulator already understands, so Android 36+ can inject its built-in device-state / posture configuration. Open and closed displays stay in one device definition. Do not split them if you need emulator posture controls.

## What it supports

- Foldable postures via a single hinge (`0–180°`)
  - Open inner display: `2448 × 1848`, 403 dpi, 7.6"
  - Closed cover region: `1248 × 1972`
- Landscape (default) and Portrait states
- Play Store enabled
- API 34+
- 12 GB RAM, 256 GB storage
- Wi-Fi, Bluetooth, NFC, UWB
- Accelerometer, gyroscope, compass, GPS, barometer, light, proximity, fingerprint
- Front / rear cameras
- OpenGL ES 3.2

## File

- [`devices.xml`](./devices.xml)
