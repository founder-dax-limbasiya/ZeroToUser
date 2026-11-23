# ZeroToUsers — Android growth workspace

ZeroToUsers is a local-first Android tool for small-business founders. It keeps several business workspaces separate and gives each one a practical place to research customer problems, plan content, track leads, organise manual conversation follow-ups and run a weekly growth checklist.

## Features in this build

- Multiple business workspaces, with records scoped by `business_id`
- Customer discovery launcher for Google, Reddit, YouTube, Quora, LinkedIn and Product Hunt searches
- Customer insight notebook for recurring problems, quotes and unmet needs
- Content drafts with target platform/date and Android share-sheet handoff
- Lead pipeline with stages, search/filter and contact handoff to phone/email/browser apps
- Manual DM/comment follow-up log and reusable reply templates
- Per-business growth checklist with completion state
- Social profile directory (labels only)
- CSV export for the active workspace
- SQLite persistence, foreign keys and an upgrade path for existing local databases
- No AI APIs, paid backend, analytics SDK, account sign-up or subscription

## Important boundaries

This build does not connect social accounts, auto-publish in the background, sync comments/DMs, scrape communities or send automatic replies. Live social actions require official platform APIs, app registration, user authorisation and sometimes review. This app does not use private endpoints or bypass platform rules.

The app currently stores data only on the device. Export a CSV before uninstalling or clearing app data. CSV exports are plain text and should be stored securely.

## Build

GitHub Actions builds a debug APK on pushes to `main`. The project uses JDK 17, Android Gradle Plugin 8.10.1, Gradle 8.13 and Android SDK 36.
