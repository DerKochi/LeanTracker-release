# Lean Tracker

An Android app that measures how far you lean your motorbike in corners, records your rides and lets you replay them.

Mount your phone on the bike (e.g. a Quad Lock), calibrate once, and ride.

## Features

- **Live lean angle**: big gauge with current lean, max left and max right, plus speed
- **Floating window**: press Home and the gauge stays on top of your navigation app
- **Ride recording**: works with the screen off; pause/resume, or auto start above 20 km/h and auto stop when you park
- **Ride map**: your route on a map, coloured by lean angle, speed or braking/acceleration
- **Graphs**: lean, speed and g-force over time; pinch to zoom, tap to see any moment on the map
- **Replay**: play the ride back fast or in real time
- **Corner list**: every corner with max lean, entry/exit speed and braking force; tap to jump to it
- **Records**: total km, top speed and max lean across all rides; tap to jump to the moment it happened
- **Share card**: image of your ride with map and key numbers
- **Export & backup**: CSV, GPX (Strava, Google Earth) and full backup/restore

## How it measures lean

The phone's gyroscope tracks fast changes in lean. GPS speed and turn rate keep it accurate over time (`lean = atan(speed × turn rate / g)`). The app also learns if the phone is slightly twisted in its mount.

## Install

1. Open the [latest release](../../releases/latest) on your phone and download `LeanTracker.apk`
2. Open it and allow installing from your browser when Android asks
3. Google Play Protect may warn about an unknown app. Tap **More details → Install anyway**

After that, the app updates itself: **Settings → Updates → Check for updates**.

Requires Android 10 or newer, with a gyroscope and GPS.

## Privacy

Rides are stored only on your phone. Nothing is uploaded. The app only goes online for map tiles and update checks.

---

Made by Simon and his very talented friend Claude.
