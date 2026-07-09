<div align="center">

# VortexDelta

### Sim-racing telemetry, analysis & coaching for Windows

Drive, and VortexDelta records every lap, breaks it down corner by corner, tells you exactly where you're losing time, and ranks your best laps on a live leaderboard.

![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-8b5cf6?style=flat-square)
![Assetto Corsa Competizione](https://img.shields.io/badge/ACC-supported-a855f7?style=flat-square)
![Le Mans Ultimate](https://img.shields.io/badge/Le%20Mans%20Ultimate-supported-a855f7?style=flat-square)
![Free](https://img.shields.io/badge/price-free-22c55e?style=flat-square)

<br/>

<img src="assets/laps-analysis.png" alt="VortexDelta lap analysis — track map, distance-synced telemetry and the AI coach" width="900"/>

</div>

---

## What is VortexDelta?

VortexDelta is a desktop app that plugs into your sim and turns raw driving into something you can actually learn from. It combines the tools you'd normally scatter across MoTeC, a coaching service, a setup manager and a leaderboard site into one dark, fast, purpose-built app.

**Local analysis — the track map, traces, sector breakdown and coach — works with no account and no internet.** Only the leaderboard and setup-sharing go online, and only once you sign in.

> Formerly known as RaceIQ — same app, new name. Existing installs update in place and keep your account, settings and laps.

---

## Features

### Deep lap analysis

Every lap is sliced into micro-sectors and drawn on a distance-synced view: speed, **raw** throttle and brake (your exact inputs, no smoothing), **gear changes**, steering and the delta to your reference, all lined up against a track map with the racing line. Scrub anywhere to see exactly what your hands and feet were doing at that point on track.

Sector times match the in-game ones — VortexDelta learns each track's real sector lines as you drive.

<div align="center">
<img src="assets/laps-analysis.png" alt="Lap analysis view" width="850"/>
</div>

### Real track maps

The map draws the actual track surface. On **8 circuits** — Barcelona, Brands Hatch, Hungaroring, Imola, Misano, Monza, Nürburgring and Valencia — that's the *true measured track boundary*, so you can see precisely how much of the road you're using. Everywhere else, a clean to-scale ribbon. More tracks are added regularly.

### AI driver coach

Fully offline, deterministic corner-by-corner feedback that tells you where the lap time actually went — and how much each fix is worth.

> **Turn 8** — Carry +10 km/h through the apex; you're scrubbing too much speed. *(+0.146s)*

### Online leaderboards

Valid laps upload automatically and rank per **track**, per **car**, and per **track-temperature** band — so you're compared against laps run in the same conditions, not someone's perfect-weather hotlap. All your comparable bests show at once (different cars, different conditions), and you can toggle between the **global** board and a **friends-only** board.

Click **Compare** on any lap to pull it straight into the analysis screen against a lap of yours — a browser lets you pick from *any* of your sessions on that track, filtered by car and temperature.

<div align="center">
<img src="assets/leaderboard.png" alt="Online leaderboard with global/friends toggle and filters" width="850"/>
</div>

### Setups — share, browse & compare

Browse the setups on your PC, then share any of them at the visibility you choose — **Everyone**, **Friends only**, or **Just me**. Pull down setups other drivers have shared for the same car and track straight from the cloud, or compare them without downloading at all — including right from the leaderboard.

<div align="center">
<img src="assets/setups.png" alt="Setups screen — local setups and cloud setups" width="850"/>
</div>

Pick any two setups as **A** and **B** and VortexDelta diffs them field by field — tyres, electronics, mechanical grip, dampers and aero — highlighting every changed value so you can see at a glance what actually differs.

<div align="center">
<img src="assets/setup-compare.png" alt="Setup A/B comparison with changed values highlighted" width="850"/>
</div>

### Session history

Every stint is saved and browsable — best lap, optimal lap, average, valid-lap count, duration, the setup you ran and the air/track temps. Jump back into any session to compare laps on the map or grab the setup you drove. After each session, VortexDelta can offer to remember which setup you used (entirely optional).

<div align="center">
<img src="assets/sessions.png" alt="Session history" width="850"/>
</div>

<div align="center">
<img src="assets/session-detail.png" alt="Session lap table with sector times and summary" width="850"/>
</div>

### Friends

Share your code and send friend requests — nobody is added without accepting. Import friends' laps to put head-to-head against your own on the track map and traces, and see their friends-only setups.

<div align="center">
<img src="assets/friends.png" alt="Friends panel with codes" width="850"/>
</div>

### Config

Set your default setup-sharing visibility and decide whether VortexDelta offers to upload your setup at the end of each driving session.

<div align="center">
<img src="assets/config.png" alt="Config screen" width="850"/>
</div>

### Live telemetry & dashboard

Real-time speed, throttle/brake, gear and inputs the moment you go on track — laps and live data appear automatically, no clicking required. Le Mans Ultimate needs zero setup: VortexDelta installs the required telemetry plugin for you.

### Auto-updating

Updates download in the background and install silently — the app restarts itself in seconds, no installer wizard, no clicking through steps.

---

## Install

1. Download the latest **`VortexDelta-Setup-x.y.z.exe`** from the [Releases](../../releases) section and run it. It installs per-user — **no admin needed**.
2. Windows SmartScreen will warn because the app isn't code-signed — click **More info → Run anyway**. It's safe; signing is on the roadmap.
3. Launch **VortexDelta** from the Start menu.

Already installed (including as RaceIQ)? Do nothing — the app updates itself to the newest build automatically.

---

## Getting started

1. Open the **RANKS** tab and create an account (email + password).
2. Hop into **Assetto Corsa Competizione** or **Le Mans Ultimate** and drive a clean lap — it uploads automatically and appears on the board.
3. Open the **FRIENDS** panel, share your code, and send a request to a friend to compare laps and setups head-to-head.

<div align="center">
<img src="assets/dashboard.png" alt="VortexDelta dashboard" width="850"/>
</div>

---

## Requirements

- **Windows 10 / 11** (64-bit)
- For live capture: **Assetto Corsa Competizione** or **Le Mans Ultimate**

Local analysis needs nothing else. The leaderboard and setup-sharing need a free account.

---

## Roadmap

- Code-signing the installer (no more SmartScreen warning)
- Password reset
- True track edges for every circuit
- More sims

---

*Found a bug or have feedback? [Open an issue](../../issues) — or use the Feedback button right inside the app.*
