# Privacy Policy — Metronoom

_Last updated: 2026-05-30_

Metronoom ("the app") is designed to respect your privacy. This policy explains what data the app handles and how.

## Short version

**The app does not collect, store, or transmit any personal data.** No accounts, no analytics, no ads, no tracking, no cloud, no microphone, no camera — nothing leaves your device.

## Ableton Link (local network)

If you enable **Ableton Link**, the app uses your local network (Wi-Fi)
to discover and sync tempo with other Link-enabled apps/devices on the
same network. This is a peer-to-peer feature.

- The traffic contains only a random per-launch session id, the current
  tempo (BPM), and beat-timing data.
- No data is sent to us or any third party, and nothing reaches the internet.
- Used only for tempo synchronisation on your local network.
- Can be turned off at any time in the app.

## Bluetooth band sync (local, peer-to-peer)

If you enable **Bluetooth Sync** (band mode), the app uses Bluetooth Low
Energy to discover and connect to other nearby devices running this app,
so a band can share one tempo and meter.

- The exchanged data contains only a random per-launch session id, tempo,
  time signature, accents, and the current song title.
- It contains no name, email, contacts, or location.
- Bluetooth scanning is declared with the **`neverForLocation`** flag — the
  app does not and cannot use Bluetooth to derive your location.
- Nothing is sent to the internet. Can be turned off at any time.

## Data storage

All your settings (tempo, time signatures, sounds, playlists, audio offset,
footswitch mappings) are stored **locally on your device**. The app itself
uploads nothing. If you have Android's system backup enabled, Android may
include these local settings in your device backup — this is handled by the
operating system, not by the app, and involves no personal data.

## Permissions summary

| Permission | Why | Optional? |
|------------|-----|-----------|
| `SYSTEM_ALERT_WINDOW` | Floating overlay dot | Yes — optional overlay |
| `INTERNET` / network state / Wi-Fi multicast | Ableton Link sync | Yes — only with Link on |
| `BLUETOOTH_*` (+ legacy location on Android ≤ 11) | Bluetooth band sync | Yes — only with Bluetooth Sync on |
| `WAKE_LOCK` | Keep audio alive while screen off | Automatic |
| `FOREGROUND_SERVICE` / media playback | Keep the metronome running in the background | Automatic |
| Notifications | Foreground-service status | Automatic |
| Ignore battery optimisation | One-time prompt for reliable long live sessions | Yes — you can decline |

The app does **not** request the microphone or camera.

## Contact

Questions? Contact the developer via the Play Store listing or the
email associated with the app (dionboertien@gmail.com).
