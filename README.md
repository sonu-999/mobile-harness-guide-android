# Sonu Mobile Harness Guide

A personalized Android application built around the concept of the provided `MH.html` guide: a dark, glassmorphism-inspired onboarding and reference experience for Android reverse-engineering, app inspection, and safe local testing workflows.

This project is designed as an Android WebView app that loads a local HTML guide, styled to match the original cinematic UI: green glow accents, floating glass cards, stage-based navigation, and terminal copy blocks.

## Purpose

- Present the Mobile Harness learning flow in a polished mobile-first experience
- Use a modern dark UI inspired by the original HTML design
- Package the guide as an Android app shell so it can run as an APK
- Keep the project aligned with the HTML's educational and ethical focus

## Project structure

- `app/src/main/assets/index.html` — the guide UI and content
- `app/src/main/java/com/sonu/mobileharnessguide/MainActivity.kt` — WebView host
- `app/src/main/AndroidManifest.xml` — app launch configuration
- `.github/workflows/android.yml` — CI build for generated APK

## Build

```bash
./gradlew assembleDebug
```

This produces a debug APK under:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Notes

The content is intended for educational use and responsible, authorized testing of apps you own or are explicitly allowed to assess.
