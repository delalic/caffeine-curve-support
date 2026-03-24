# Caffeine Curve - Release Notes

Welcome to the release notes for Caffeine Curve! Here you can find all the details about our updates, new features, and bug fixes.

---

## 🚀 Upcoming Releases (1.0.11 - 1.0.13)
*These features are currently in development or internal testing and will be available in upcoming updates.*

### Version 1.0.13
- **New Feature:** Added a helpful empty state view (an empty cup with tips) when no caffeine data is logged or if HealthKit lacks permission.
- **Improvement:** Enhanced background refresh by registering the background query during app initialization.

### Version 1.0.12
- **New Feature:** Added a brand new widget featuring a trend arrow for quick insights.
- **Enhancement:** Added trend indicators to individual intake items and the main gauge.
- **UI Updates:** 
  - Increased the size of the badge on the main view for better visibility.
  - Adjusted card backgrounds and removed scrollbars for a cleaner, polished look.
  - Refined the widget design with rounded corners and a bold bean icon instead of truncation.

### Version 1.0.11
- **Improvement:** Updated terminology in the app, replacing the word "left" with "active" to better clarify active caffeine levels in the body.

---

## 🎉 Version 1.0.10 (Initial App Store Release)
*Status: Currently in App Store Review*

Our very first official release! We've worked hard to bring you a clean and effective way to monitor your daily caffeine intake.

### Major Changes & Features
- **Rebranding:** The app has officially been renamed to **Caffeine Curve**.
- **Design Overhaul:**
  - Fresh new app icon featuring a bold orange color.
  - Updated the onboarding logo to an elegant coffee bean.
  - Improved layout and responsiveness for iPad users.
- **Graph & Timeline Improvements:**
  - Increased timeline frequency for much higher precision (1-minute intervals for the first 24 hours, 5-minute intervals for hours 24-48).
  - Fixed time formatting on the graph's x-axis to be more concise (e.g., "11a").
- **HealthKit & Privacy:**
  - Added new error messaging to help when HealthKit is not authorized.
  - Updated the HealthKit usage description to clearly state: *"This app reads caffeine intake to calculate active caffeine levels in the body."*
  - Added the required Privacy Manifest for the App Store.
- **General Fixes:**
  - Disabled the iPad and other unnecessary widgets to focus on core performance.
  - Reverted to the classic settings view for better usability.
