# 3PM Archery Android test builds

## 0.5-test (21 October 2026)

[Download the verified test APK](https://github.com/Pui3PM/3pm-app-releases/blob/6bf816b7bb8d892422d667da53a93af9d164ad0e/apks/v0.5-test/3PM_Scanner_Android_0.5_TEST_20261021.apk). On the GitHub file page, use the download control, then open the APK on your Android phone.

This is a **debuggable TEST build**, not a production, Play-ready, or hardware-certified release. Android 8.0/API 26 or newer is required. Android and manufacturer installation policies still apply.

Export important local records before updating. Install over the existing com.threepm.scanner app with the same signing identity. Do not uninstall, clear storage, or disable Android security protections to force an update.

### Changes since 0.4
- Manual X entry on all six supported face presets, worth 10 with a separate X count. This manual training-log option does not change automatic target geometry or claim that every competition counts X.
- BLE audio/control freshness and connection-state handling improvements with compatible firmware; actual physical-device acceptance remains pending.
- In-app verified APK downloading and an explicit Android installer handoff. The user must choose Download and Install; Android may require app-specific installation permission. There is no silent installation or security bypass.
- Optional paired local-network score transfer to compatible Analyzer LINK10: explicit enrollment and laptop approval, reviewed shot mappings, staged conflicts, and confirmed offline backlog. This is a constrained, single-writer test workflow, not unrestricted two-way synchronization.

### Existing features
Colored score entry, manual target drag with a local magnifier, per-spot photo review, saved scoring statistics grouped by face and distance, BLE raw-axis graphs, real sensor dashboard/audio data with compatible UX02.4 firmware, durable history, and capability-gated replay STOP.

### Installation and update limits
- Version 0.3 has no configured update endpoint. Version 0.4 checks metadata and opens a download page. Initial installation of 0.5 therefore still needs an allowed installation route, potentially USB if required by the phone.
- Once 0.5 is installed, future compatible higher versions can use its in-app download/installer flow. OEM restrictions can still reject installation; a successful installer launch is not proof of installation.
- Optional checks require Internet and Android scheduling; they are not immediate push notifications.
- The direct-distribution updater is not a Play Store update implementation. A future Play variant needs appropriate update and permission handling.

### Other limits
- Scores and photo positions need user review. Six current recurve face presets; no full MyTargets parity claim. The magnifier is not whole-target pinch zoom.
- Analyzer direct linking requires compatible LINK10 and session pairing; sessions expire and require re-pairing. No guaranteed arbitrary concurrent-writer merge or zero-touch production enrollment.
- The 60-second orientation recording/CSV functions still require Wi-Fi.
- Physical phone/radio/audio/battery/camera and upgrade-retention acceptance remain pending. Sensor firmware updates are separate and still use USB.
- Software checks do not establish on-target measurement accuracy.

APK SHA-256: `b5903dfcef7ec853b3b72ec497eabd636981f76189791a3ff5fe47b4b69b63d0`

Signing certificate SHA-256: `b8e41751dafc00855aaf26d32b7c8f457fc99755ce012287671fc9f1b1bca556`

[Previous 0.4 test APK](https://github.com/Pui3PM/3pm-app-releases/blob/0e0d3d2a9b153dc1ad59496ff10d380992a73814/apks/v0.4-test/3PM_Scanner_Android_0.4_TEST_20261021.apk) remains unchanged.

This repository contains test APKs and version information only. No source code, signing private keys, user scores or photos are published here.
