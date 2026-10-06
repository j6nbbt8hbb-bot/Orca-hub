# ORCA CLIENT — Fabric 1.21.11

A modular client framework based on the supplied Orca specification.

## Current implementation

- Right Shift GUI toggle
- Configurable GUI keybind
- Futuristic dashboard
- Search screen
- 18 category system
- 100+ registered module placeholders
- HUD framework
- Troll/cosmetic framework
- Local visual Troll effects
- Streamer Mode for privacy information
- Config manager
- Notification manager
- First-launch animation
- Settings model
- Fabric 1.21.11 / official Mojang mappings

## Build

Requirements:
- Java 21
- Gradle 8.x or the included Gradle wrapper if you add one
- Minecraft Java 1.21.11 development environment

Run:

    ./gradlew build

The built JAR is produced under:

    build/libs/

## Notes

The module registry deliberately contains safe framework placeholders rather than implementations for cheating, anti-cheat bypasses, or screen-share concealment.

Streamer Mode is privacy-focused: it masks information such as server names, coordinates and waypoint labels in the client's own UI.
