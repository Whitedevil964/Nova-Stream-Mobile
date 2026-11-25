<div align="center">

<img src="assets/hero-banner.svg" width="100%" alt="NovaStream Mobile — Dark Cinema Anime Streaming Client" />

<br/><br/>

<img src="assets/logo.png" width="84" height="84" alt="NovaStream Mobile Icon" />

<h3>Streamlined. Standalone. Built for Night-Mode Cinema.</h3>

<p>
  <strong>NovaStream Mobile</strong> is a 100% standalone native Android anime streaming client built in Kotlin and Jetpack Compose.<br/>
  No companion desktop server, no external proxy required — just crisp 1080p HLS playback, tri-audio discovery, and an offline MP4 vault in your pocket.
</p>

<p>
  <img src="https://img.shields.io/badge/Edition-v1.0.0%20Standalone-5E6AD2?style=for-the-badge&labelColor=0A0A0C" alt="Version v1.0.0 Standalone" />
  <img src="https://img.shields.io/badge/Android-7.0%2B%20(API%2024%E2%86%9236)-22D3EE?style=for-the-badge&labelColor=0A0A0C" alt="Android 7.0+" />
  <img src="https://img.shields.io/badge/UI-Jetpack%20Compose-7C3AED?style=for-the-badge&labelColor=0A0A0C" alt="Jetpack Compose" />
  <img src="https://img.shields.io/badge/Distribution-Closed%20Source-F59E0B?style=for-the-badge&labelColor=0A0A0C" alt="Closed Source" />
</p>

</div>

<br/>

<img src="assets/cinema-divider.svg" width="100%" alt="" />

<br/>

## The Experience

<img src="assets/experience-pillars.svg" width="100%" alt="NovaStream Mobile Core Capabilities" />

<br/>

<img src="assets/nav-dock-preview.svg" width="100%" alt="Five Dedicated Destinations in NovaStream Mobile" />

<br/>

<img src="assets/cinema-divider.svg" width="100%" alt="" />

<br/>

## Feature Deep-Dive

<details open>
<summary><strong>Cinema Player Engine — Built Around Uninterrupted Viewing</strong></summary>

<br/>

- **1080p Native HLS Streaming**: Powered by AndroidX Media3 ExoPlayer with selectable resolution caps (`1080p`, `720p`, `480p`) to match your bandwidth.
- **Sub & English Dub Switching**: Switch audio preferences cleanly between Japanese Sub and English Dub with default audio preference memory.
- **Auto-Skip Opening (`+85s`) & Auto-Play Next**: Floating quick-skip action during openings plus a sleek countdown overlay near episode completion.
- **Custom Subtitle Studio**: Live-preview subtitle customization controls for comfortable late-night readability.
- **Full Mobile Ergonomics**: Picture-in-Picture (`PiP`) mode, `0.5x`–`2.0x` playback speed selector sheet, customizable seek intervals (`5s`–`30s`), screen touch lock, and landscape fullscreen toggle.

</details>

<details open>
<summary><strong>Isolated Hindi Dub Zone — Zero Interference With Main Feed</strong></summary>

<br/>

- **Dedicated Navigation Tab**: Lives cleanly alongside the main Discover experience so Hindi Dub browsing stays uncluttered and separate.
- **Multi-Season Support**: Built to handle both compact seasonal series and massive multi-season epics with season pills and full episode lists.
- **Isolated Search & Playback**: Dedicated catalog search and server switching without polluting Sub/Dub history or stream defaults.

</details>

<details>
<summary><strong>Offline Vault & Background Sync — Ready Without Signal</strong></summary>

<br/>

- **Foreground Download Service**: Persistent notification progress while downloading episodes in the background.
- **Pause & Resume Reliability**: Byte-range resumable downloads preserve partial progress cleanly so interrupted downloads pick up right where they left off.
- **Scoped Storage Folder Picker**: Choose between App Sandbox, `Movies`, `Downloads`, or External SD Card with a live free-space storage meter and Wi-Fi-only download guard.
- **Offline Network Banner**: Automatically detects offline state and surfaces a one-tap shortcut straight to your downloaded episodes.
- **Background Episode Alerts & Deep Links**: Periodic 6-hour WorkManager sync checks active watchlist series for new releases and opens titles directly via `novastream://anime/{id}`.

</details>

<details>
<summary><strong>Discovery, Library Vault & Watch Analytics</strong></summary>

<br/>

- **3D Carousel & Dual-Source Search**: Interactive parallax hero carousel paired with instant debounced search, recent search pill chips, genre/status filters, and `"More Like This"` recommendations.
- **Continue Watching & Episode Completion**: Automatic resume timestamps, range pagination chips (`1–100`, `101–200`, ...) for 1,000+ episode series, and one-tap watched markers.
- **Unified Library**: Clean tabs for **Watchlist** (`Watching`, `Plan to Watch`, `Completed`), **Downloads**, and **Watch History**.
- **Personal Stats**: Daily watch streaks, total time watched, episode counters, and achievement milestones.

</details>

<br/>

<img src="assets/cinema-divider.svg" width="100%" alt="" />

<br/>

## Visual Language & Architecture

<img src="assets/design-system.svg" width="100%" alt="Modern Dark Cinema Color Tokens" />

<br/>

| Layer | Technology | Role in NovaStream Mobile |
| :--- | :--- | :--- |
| **UI & Motion** | Kotlin · Jetpack Compose · Material 3 | Declarative Dark Cinema layouts, tactile haptics, spring transitions, and shimmer states |
| **Media Engine** | AndroidX Media3 ExoPlayer & HLS | Smooth adaptive HLS streaming, offline MP4 playback, speed control, and Picture-in-Picture |
| **Local Storage** | Room SQLite · KSP · DataStore | Instant offline watchlist, episode completion tracking, watch history, and user preferences |
| **Background & Media** | WorkManager · Coil · Android Palette | 6-hour new-episode alerts, foreground downloads, image caching, and adaptive color extraction |
| **Compatibility** | Min SDK 24 · Target SDK 36 | Runs on Android 7.0 Nougat through modern Android releases with Scoped Storage compliance |

<br/>

<img src="assets/cinema-divider.svg" width="100%" alt="" />

<br/>

## Availability & Proprietary Notice

> **Closed-Source Software — All Rights Reserved**
>
> **NovaStream Mobile** is private, proprietary software created by [**Whitedevil964**](https://github.com/Whitedevil964).  
> This repository serves strictly as the **public showcase, feature overview, and release announcement hub** for the application. Source code, scraping internals, and build pipelines are intentionally not open-sourced or distributed here.
>
> - **Current Release Milestone**: `v1.0.0 (Standalone Edition)`
> - **Bug Reports & Feedback**: Use [GitHub Issues](https://github.com/Whitedevil964/Nova-Stream-Mobile/issues) for feature requests or UI feedback.

<br/>

<div align="center">
  <sub>Crafted with a Dark Cinema obsession for Android · Copyright © Whitedevil964</sub>
</div>
