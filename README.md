# NOX Launcher (MVP source project)

Native Android launcher starter using Kotlin + Jetpack Compose. It includes:
- HOME/DEFAULT intent filter so Android can offer it as a Home app
- Vertical clock
- Installed-app list and app launching
- Alphabetical app drawer with search
- 30 dark-fantasy theme palette entries

## Build
1. Open this folder in Android Studio (recent stable version).
2. Let Gradle sync and install the Android SDK Platform 35 if prompted.
3. Build > Build APK(s).
4. Install the generated APK, then select NOX Launcher in Android Settings > Default apps > Home app.

## Current MVP limitations
- Theme entries currently change the accent palette; the 30 unique wallpapers/artwork assets still need to be added.
- The right-side alphabet index currently filters by starting letter rather than scrolling precisely to each section.
- Notification display/listener, wallpaper picker, icon pack support, drag-and-drop dock, widgets, and persistent settings are not implemented yet.
- Device manufacturers may impose their own launcher restrictions.
