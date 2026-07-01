# Free Armenian iOS Capacitor Project — V16.40

This repository contains the approved Free Armenian V16.40 HTML application prepared as a Capacitor project.

App name: Free Armenian
Bundle ID: org.freearmenian.app
Web app entry: www/index.html

## Codemagic
The repository includes `codemagic.yaml`.
Start with workflow: `Free Armenian iOS - Build Check`.
This first workflow checks that Codemagic can generate and build the iOS project.

After successful build check, configure Apple Developer code signing in Codemagic for TestFlight/App Store upload.
