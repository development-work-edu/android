# Android

A collection of Android applications and projects developed using Android Studio.

---

## Installation

- Version: Ladybug release 2024.2.1 Patch 2
- Storage Required: ~12 GB File Space
- Ram Required: 16 GB Minimum

---

## Project Configuration

- Project Type: Empty Views Activity
- Language: Java
- Minimum SDK (minSDK): API 34 ("UpsideDownCake"; Android 14.0)
- Compile SDK: 35
- File System: Internal Drive, NOT portable drives

---

## Virtual Device Configuration

- Hardware: Pixel 8
- System Image: Android 14.0 (API Level 34, "UpsideDownCake")
- Delete: Any old devices that aren't Android 14 or aren't Pixel 8 devices
- Graphics: Set to "Automatic" (may need "Software" if issues occur)
- Boot: Quick boot by default, use cold boot if needed

---

## Settings to Verify

- compileSdk: 35 (File → Project Structure or Ctrl+Alt+Shift+S)
- System API level: 34 (matches the virtual device)
- Virtualization: Enabled in BIOS if using AMD/Intel processors
- Hyper-V: Properly disabled if using AMD processors to avoid conflicts with Android Emulator

---

## Common Issues

- **Slow builds (>3 minutes)**: Check free memory, disable virus scanner temporarily
- **VM won't start**: Try cold boot, check virtualization settings in BIOS
- **Build errors**: Verify SDK versions match, check dependency versions in `libs.versions.toml`
- **Emulator graphics issues**: Change graphics setting to "Software" in AVD Manager
- **Project sync issues**: Ensure all required SDK components are installed via SDK Manager
- **Gradle sync problems**: Invalidate caches and restart Android Studio (File → Invalidate Caches / Restart)

---
