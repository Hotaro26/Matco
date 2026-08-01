# Mascot / StrictClock v1.4 Release

## What's New 🚀
- **Stopwatch Service**: Introduced a new foreground service for the Stopwatch to keep it running smoothly in the background, complete with a persistent notification.
- **Material 3 Expressive UI Redesign**: 
  - Upgraded settings toggles and components to use a new `ExpressiveSwitch`.
  - Upgraded the Flashbang settings to use a custom animated `ExpressiveSlider`, featuring shape morphing, bold primary colors, and spring physics conforming to the latest Android 14+ / Material You Expressive guidelines.
- **Tablet UI Improvements**: Refined the layout and split-screen behavior for the WakeUpScreen on tablet devices in landscape mode.
- **Timer Persistence**: Enhanced the Timer component with `SharedPreferences` to ensure timer settings persist across app restarts.
- **Notification Improvements**: Switched app icons and notifications to use the updated `v2` channel IDs.
- **Cleanup**: Removed legacy demo alarms and optimized the `AlarmViewModel.kt`.

## Under the Hood 🛠️
- Updated `versionCode` to 5.
- Target API remains 34 (Android 14).
