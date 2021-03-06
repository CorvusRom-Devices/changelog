# OnePlus 6 Enchilada

## Corvus v14.0

- Update to Redfin's Feb 2021 fingerprint
- GoogleCamera: Switch to Urnyx05
- Update default Sounds
- Fixup! Battery Saver Force Close
- Fixup! SELinux Status bug Now its shows Enforcing
- Fixup! Root Youtube Vanced now works fine
- overlay: Enable RGB battery led
- overlay: Use custom vibration configs
- overlay: configure SQLite to operate in MEMORY mode
- overlay: Don't pin camera app in memory
- overlay: Enable SmartCharging
- overlay: Disable LiveDisplay for now
- Switch to SonicKernel
- Kernel Compiled with Proton-clang Version 13.0.0
- bluetooth: Switch to unified bdroid header
- bluetooth: Switch to a map based BT name
- bluetooth: Fix undefined PROPERTY_VALUE_MAX
- bluetooth: Disable clean turn on
- pixelcharger: Optimize Pixel charger animation
- rootdir: Adjust dex2oat thread count after setup wizard
- DeviceSettings: Bump version to 4.0
- DeviceSettings: VibratorStrengthPreference: Set default to 1000
- DeviceSettings: Remove TouchGestures category for now
- DeviceSettings: Add Lottie animation header
- Tress Cleanup!
- Thanks to @Vindipi and @Imscarecrow for testing Enchilada Build

## Corvus v13.0
- Update to Redfin's Jan 2021 fingerprint
- Kernel Upstreamed to 4.9.250
- Ship AndroidAuto stub package
- Set default sounds
- DeviceSettings: Add LogTile
- Add TetheringOverlay
- Add OnePlus ScreenRecorder
- Fix TouchGestures Force Close

## Corvus v12.5

- Remove no longer used Brightness Settings
- Use Bonito Brightness Curve
- DeviceSettings: Display toasts for slider
- Gboard: Remove navbar spacing

## Corvus v12.0 

- Initial Android 11 Release
- Kernel Compiled with proton-clang (12.0.0 V)
- Switch to Redfin's Dec 2020 fingerprint
- Upstream kernel to 4.9.244
- Switch to QTI bt stack
- Switch to DMGC GoogleCamera
- Overlay: Set Default to Full Gesture Navigation
- Add AOSP RCS packages
- SELinux Status: Enforcing
- Add Pixel Charging Animation on Screen off
- Add APN and Battery Stats privapp permissions
- Sepolicy: Address a few more denials
- Update OnePlus Gallery
- Removed CorvusParts
- Removed OnePlusCamera for now
- Removed BatteryHealth Support
- Introducing New Device Extras (OnePlus Settings)
- DeviceSettings: Add Device Extras QS Tile
- DeviceSettings: Update HBM Tile & Switch on Screen off
- DeviceSettings: Vibrator: Set defaults to OOS

## Broken/Bugs:

- WFD doesn't work
- OK Google detection doesn't work, assistant works though
- No Verizon Network Support

## Note:
- No Twrp Inbuilt
