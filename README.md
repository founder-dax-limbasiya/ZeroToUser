# ZeroToUsers — Android growth workspace

A free-first Android app for managing multiple businesses independently. Every workspace keeps its own social profile directory, content drafts, engagement notes, reply-rule drafts and leads on the device.

## Current MVP

- Multiple business workspaces with a saved active workspace
- Separate social profile lists per business
- Local content planner and Android share-sheet handoff
- Per-business lead tracker
- Manual DM/comment inbox log with handled status
- Keyword reply-rule drafts
- Local SQLite storage; no paid backend, subscription or AI integration

## Honest feature status

This initial APK does **not** connect social accounts or perform background auto-posting, automatic DMs, comment syncing or moderation. Those capabilities require supported official platform APIs, developer app registration, user authorization and, for some capabilities, platform review. This app does not use private endpoints or attempt to bypass platform rules.

## Build

GitHub Actions builds a debug APK on each push to `main` and stores it as the `ZeroToUsers-debug-apk` workflow artifact. Build requirements: JDK 17, Android SDK platform 36 and Android Gradle Plugin 8.10.1.
