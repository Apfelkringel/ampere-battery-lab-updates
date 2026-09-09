# Ampere Battery Lab updates

This repository contains public release binaries and the update manifest for Ampere Battery Lab.
The application source code and user data are not stored here.

The current manifest points to release 0.70.

Release 0.60 separates detailed telemetry from automatic Android backup, validates imported keys before restore, neutralizes spreadsheet formulas in CSV exports, and bounds update metadata/download verification. Release 0.61 completes the manual backup allowlist for sleep-time statistics. Release 0.62 fixes the Light theme selection in Settings. Release 0.63 restores DownloadManager completion delivery using Android's signature-protected sender permission. Release 0.64 opens a selected history session in its matching charging or discharging view. Release 0.65 includes local telemetry in encrypted Android backups so data can survive a reinstall when the device backup transport is enabled. Release 0.66 aligns the in-app privacy and backup explanations with that encrypted-backup behavior. Release 0.67 makes the charger state display read-only and Android-derived. Release 0.68 avoids treating a full but unplugged battery as connected. Release 0.69 labels the design-capacity fallback explicitly when Android does not expose the factory value. Release 0.70 shows the correct sign for charging and discharging current in the overview and overlay. The APK is the only executable artifact; source code, signing keys and user data are not stored in this repository.
