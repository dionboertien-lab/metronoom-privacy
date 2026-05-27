---
title: Privacy Policy — Metronoom V2
---

# Privacy Policy — Metronoom V2

**Last updated:** 2026-05-27

This metronome application is designed to respect your privacy.
**We do not collect, store, or transmit any personal data.**

---

## What data does the app handle?

**Settings (tempo, time signature, colors, playlists, sound choice)**
Stored locally on your device using Android's encrypted DataStore.
Never leaves the device.

**Microphone audio (only if you turn on Listen Mode)**
Captured in real time, analyzed locally for tempo onset detection, and
immediately discarded. Audio is never recorded to disk and never
transmitted off-device.

**Ableton Link networking (only if you enable Ableton Link)**
When enabled, the app participates in a peer-to-peer session on your
local Wi-Fi network to synchronize tempo with other Link-enabled
applications. The network traffic contains:

- A random session identifier generated per app launch
- The current tempo (BPM)
- Timing data for beat alignment

It does **NOT** contain your name, email, device identifier, location,
microphone audio, or any other personal data. Network traffic stays
inside your local Wi-Fi network — nothing is sent to Ableton's servers
or to ours.

---

## What permissions does the app request?

| Permission | Purpose |
|---|---|
| `SYSTEM_ALERT_WINDOW` | Show the floating metronome dot. No data collection. |
| `POST_NOTIFICATIONS` (Android 13+) | Foreground service notification while the metronome runs. |
| `RECORD_AUDIO` | Optional — Listen Mode tempo detection. Audio processed locally and discarded. |
| `INTERNET` / `ACCESS_NETWORK_STATE` / `CHANGE_WIFI_MULTICAST_STATE` | Ableton Link peer discovery on the local network only. No remote servers contacted. |
| `WAKE_LOCK` | Keeps the audio thread alive during playback to prevent timing drift. |

---

## Third-party services

The app does **NOT** use:

- Analytics (no Google Analytics, no Firebase Analytics, no equivalents)
- Crash reporting (no Crashlytics, no Sentry, no equivalents)
- Advertising (no ad SDKs)
- Cloud storage or backup to external services
- User accounts or authentication

---

## Children

This app does not knowingly collect any data from anyone, including
children. It is safe for general audiences.

---

## Changes to this policy

If this policy changes in future versions, the new version will be
bundled with the corresponding app release and the "Last updated"
date at the top of this page will reflect the change.

---

## Contact

Questions about this policy can be sent to
[dionboertien@gmail.com](mailto:dionboertien@gmail.com).
