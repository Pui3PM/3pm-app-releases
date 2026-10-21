# 3PM Archery Android test builds

## 0.4-test (21 October 2026)

[Download the verified test APK](https://github.com/Pui3PM/3pm-app-releases/blob/0e0d3d2a9b153dc1ad59496ff10d380992a73814/apks/v0.4-test/3PM_Scanner_Android_0.4_TEST_20261021.apk). On the GitHub file page, use the download control, then open the APK on your Android phone.

This is a **debuggable TEST build**, not a production or hardware-certified release. Android 8.0/API 26 or newer is required. Android and manufacturer installation policies still apply.

Export important local records before updating. Install over the existing com.threepm.scanner app with the same signing identity. Do not uninstall, clear storage, or disable Android security protections to force an update.

### Changes
- BLE raw-axis graphs, real dashboard/audio metrics and controls with compatible UX02.4 sensor firmware; durable history and capability-gated replay STOP.
- Colored score entry, manual drag/loupe, per-spot photo review, and saved scoring statistics grouped by target type/size and distance.
- Truthful stationary/gap display and read-only graph diagnostics.
- Optional Internet update checks. Downloads and Android installation require user action; there is no silent installation.

### Limits
- Scores and photo positions need user review. Six current recurve face presets; no full MyTargets parity claim.
- Analyzer score transfer in this version is explicit JSON export/import, not automatic wireless synchronization.
- The 60-second orientation recording/CSV functions still require Wi-Fi.
- Physical radio, phone, audio, battery and camera acceptance remain pending. Sensor firmware updates are separate and still use USB.
- Version 0.3 has no configured update endpoint: install this configured version once manually on the phone. Future checks are optional, Android-scheduled, and require Internet; they are not immediate push notifications.

APK SHA-256: `567ab7bbe9b886055520a5935a9c193676f7eee651b8259cf7d644b5f45b9fa0`

Signing certificate SHA-256: `b8e41751dafc00855aaf26d32b7c8f457fc99755ce012287671fc9f1b1bca556`

This repository contains test APKs and version information only. No source code, signing private keys, user scores or photos are published here.
