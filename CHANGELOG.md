# Changelog

## 1.0.1

- Fixed: after a side ended, the app could think the needle dropped again a few seconds later (from the arm returning and the motor stopping) and start "playing"
- The arm-up level now sits well between silence and groove noise, learns your turntable's groove level, and ignores noise for 10 seconds after a side ends
- Old calibrations are converted automatically; measuring silence while a record plays is refused instead of saving a bad setting
- New: set the arm-up level by hand with -/+ in Settings (with "Back to automatic")
- Fixed overlapping and cut-off text in Settings, and the ListenBrainz box showing a darker background
- Discord always uses the built-in Turntable Listener app (the custom app option is gone)

## 1.0.0 (first release)

- Plays a USB turntable through any output device, with volume and level meter
- First-run setup that finds your turntable and calibrates its silence
- Album search (MusicBrainz) with cover art, tracklists by side, and live song tracking
- Detects the needle drop, the start of the music, gaps between songs and the end of each side
- Flip notifications with an optional chime
- Discord Rich Presence with album art
- Scrobbling to Last.fm and ListenBrainz, with an offline queue
- Records shelf with play counts and listening time
- Stylus-hours counter with replacement reminders
- Album-coloured backdrop and music visuals (bouncing record, floating notes, glow)
- Reconnects automatically if the turntable is unplugged or the PC sleeps
- Sharp on high-DPI displays; system tray support; optional start with Windows
