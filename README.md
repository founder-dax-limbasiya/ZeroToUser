# ZeroToUsers — Android growth workspace

Android-first, free-first workspace for managing multiple small businesses independently.

## Current repository build status

The APK artifact previously built from this repository was a very small prototype, not a complete customer-growth app. Do not treat that artifact as a finished release. A larger local-first rebuild is being prepared and must be committed, compiled and tested before a replacement APK is shared.

## Intended product scope

- Separate workspaces for each business
- Customer research and insight notebook
- Content planner and share-sheet handoff
- Lead pipeline and manual conversation follow-up
- Reusable reply templates and a growth checklist
- CSV export
- No AI service or paid backend

## Platform integration limits

This app must not claim live social integrations until official platform APIs, permissions and account authorisation are implemented and tested. No private endpoints or platform-rule bypasses will be used.

## Build

GitHub Actions builds a debug APK from the source archive on pushes to `main`. JDK 17, Android Gradle Plugin 8.10.1, Gradle 8.13 and Android SDK 36 are used.
