# ZeroToUsers — Android growth workspace

A free-first, local-first Android app for founders and small businesses. One installation can hold multiple business workspaces, with each workspace's records kept separate on the device.

## v0.3.0 scope

- Multiple business workspaces
- Customer discovery shortcuts for Google, Reddit, YouTube, Quora, LinkedIn and Product Hunt
- Customer-problem / insight notebook
- Content planner with share-sheet handoff
- Lead pipeline with search, stages and phone/email/browser handoff
- Manual DM/comment follow-up tracker
- Reusable reply templates
- Weekly growth checklist
- Social profile directory (labels only)
- CSV export for one active workspace
- SQLite persistence; no paid backend, AI API, sign-in or remote analytics

## Honest platform status

This release does **not** connect social accounts, auto-publish posts, sync DMs/comments, scrape communities or send automatic replies. Those features need official platform APIs, developer app registration, user permission and sometimes platform review. This app does not use private endpoints or bypass platform rules.

Data stays on the phone. Export a workspace before uninstalling or clearing app data. CSV files are plain text and should be stored carefully.

## Build and smoke test

GitHub Actions compiles the APK, checks the Android package contents and debug signature, then installs and launches the app in an Android emulator. The APK is uploaded only after those checks pass.

Toolchain: JDK 17, Android Gradle Plugin 8.10.1, Gradle 8.13, Android SDK 36.
