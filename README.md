# Awesome Even Realities G2 with stars

> A curated list of SDKs, tools, apps, and resources for developing on the Even Realities G2 smart glasses.

The [Even Realities G2](https://www.evenrealities.com) are everyday display smart glasses with dual micro-LED displays, no camera, and no speaker, paired with the R1 control ring. G2 apps are web apps: your code runs on a server, the iPhone Even App loads it in a WebView, and display and input are relayed over BLE to the glasses. This list collects the best community and official resources for building them.

**Scope:** This is a resource for *building* on the G2 — every entry is open source or an official resource you can read, clone, and learn from. Closed-source apps aren't listed in these sections; if you've built one, open an issue and we can look at adding a separate app directory for owners down the line.

## Contents

* [Official](#official)
* [Documentation and Guides](#documentation-and-guides)
* [SDK, Tooling, and Simulators](#sdk-tooling-and-simulators)
* [Protocol and Reverse Engineering](#protocol-and-reverse-engineering)
* [Apps - Productivity and Utilities](#apps---productivity-and-utilities)
* [Apps - Navigation and Transit](#apps---navigation-and-transit)
* [Apps - Smart Home and Car](#apps---smart-home-and-car)
* [Apps - Fitness and Health](#apps---fitness-and-health)
* [Apps - Finance and Markets](#apps---finance-and-markets)
* [Apps - Voice and Speech-to-Text](#apps---voice-and-speech-to-text)
* [Apps - Games and Learning](#apps---games-and-learning)
* [Apps - Media and Music](#apps---media-and-music)
* [Apps - Streaming](#apps---streaming)
* [AI and Agent Integrations](#ai-and-agent-integrations)
* [Related and Legacy (G1)](#related-and-legacy-g1)
* [Community](#community)

## Official

* [EvenDemoApp](https://github.com/even-realities/EvenDemoApp) ⭐ 473 | 🐛 28 | 🌐 C | 📅 2026-06-09 - Official demo app from Even Realities.
* [everything-evenhub](https://github.com/even-realities/everything-evenhub) ⭐ 69 | 🐛 15 | 📅 2026-08-20 - Official developer kit bundling the Even Hub SDK, CLI, simulator, and documentation for building G2 apps.
* [Even Hub Starter Templates](https://github.com/even-realities/evenhub-templates) ⭐ 47 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-07 - Four official scaffolds to clone and run: minimal, ASR, image, and text-heavy.
* [EH-InNovel](https://github.com/even-realities/EH-InNovel) ⭐ 14 | 🐛 1 | 🌐 Kotlin | 📅 2026-03-25 - Official Even Hub web demo: a simple novel reader for the G2.
* [lvgl-sys-v9](https://github.com/even-realities/lvgl-sys-v9) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-31 - Official LVGL v9 system library for the G2 display stack.
* [Even Hub Developer Portal](https://hub.evenrealities.com) - Official portal to build, test, and publish apps directly to the G2.
* [Even Realities Developer Docs](https://hub.evenrealities.com/docs) - Official SDK documentation for plugins, widgets, and AI integrations.

## Documentation and Guides

* [even-g2-notes](https://github.com/nickustinov/even-g2-notes) ⭐ 114 | 🐛 1 | 📅 2026-07-31 - Community-maintained SDK reference covering architecture, the display and container model, input events, page lifecycle, device APIs, and packaging. The de facto documentation hub for G2 development.
* [even-hub-devguide](https://github.com/aleapc/even-hub-devguide) ⭐ 1 | 🐛 0 | 📅 2026-04-21 - Community-maintained, battle-tested guide to building apps on Even Hub for the G2.

## SDK, Tooling, and Simulators

* [MentraOS](https://github.com/Mentra-Community/MentraOS) ⭐ 2,332 | 🐛 793 | 📅 2026-08-31 - Open-source smart-glasses OS and app SDK that drives the G2, among other glasses, over BLE.
* [even-toolkit](https://github.com/fabioglimb/even-toolkit) ⭐ 93 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Shared SDK utilities: design system, web components, pixel-art icons, an STT module, and pixel-accurate G2 text measurement.
* [even-dev](https://github.com/BxNxM/even-dev) ⭐ 85 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-23 - Even Hub simulator and multi-app test environment for building and testing G2 apps locally.
* [xg-glass-sdk](https://github.com/hkust-spark/xg-glass-sdk) ⭐ 38 | 🐛 21 | 🌐 Kotlin | 📅 2026-08-31 - One API for camera, mic, display, and audio across the G2, Rokid, Meta Ray-Ban, Brilliant Labs Frame, RayNeo, and INMO, with a simulator.
* [faceclaw](https://github.com/jimrandomh/faceclaw) ⭐ 22 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-31 - Native desktop dashboard for driving the G2 display outside the WebView.
* [OpenEvenSdk](https://github.com/Thepizzapie/OpenEvenSdk) ⭐ 10 | 🐛 0 | 🌐 Swift | 📅 2026-06-15 - Local-first G2 toolkit with Python, Swift, and Kotlin BLE bridges and protocol documentation.
* [even-realities-g2-glasses](https://github.com/brianmatzelle/even-realities-g2-glasses) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-03 - Starter template for building G2 plugins with TypeScript and Vite.
* [g2mirror](https://github.com/jimrandomh/g2mirror) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-31 - Rust utility for mirroring a terminal session to the G2 display.
* [droidbridge](https://github.com/Commute773/droidbridge) ⭐ 3 | 🐛 1 | 🌐 Kotlin | 📅 2026-04-16 - Bridges the G2 BLE connection over the network so a desktop can talk to the glasses.
* [evenhub-app-ui](https://github.com/JustinasLa/evenhub-app-ui) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-04 - Even Hub design system packaged as a Claude Code skill, with color tokens, typography, layout rules, and 193 SVG icons.
* [g2-icon-studio](https://github.com/naotake/g2-icon-studio) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-06-08 - Browser tool for creating the 24x24 monochrome app icons Even Hub requires, with a 1-bit image converter and pixel editor.
* [evenhub-playground](https://github.com/shimopino/evenhub-playground) ⭐ 2 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-15 - Development playground for experimenting with Even Hub G2 apps.
* [even (CLI)](https://github.com/aluminumio/even) ⭐ 2 | 🐛 0 | 🌐 Swift | 📅 2026-07-01 - Swift command-line tool for sending text to the G2 over Bluetooth.
* [even-ui-builder](https://github.com/langerhans/even-ui-builder) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-02-15 - Simple UI builder and code generator for the Even Hub SDK.
* [takemotions-media-bridge](https://github.com/r-tkbyc/takemotions-media-bridge) ⭐ 2 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-16 - Android helper exposing now-playing media and R1 ring playback controls to glasses apps over localhost.
* [even-realities-ui](https://github.com/jappyjan/even-realities) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2026-03-25 - Foundation UI package (components, icons, and design tokens) for building G2 apps aligned to Even Realities' design guidelines.
* [even-voice-shim](https://github.com/tntpsu/even-voice-shim) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-07 - Push-to-talk speech-to-text shim with a Cloudflare Worker template, working around the missing on-device STT API.
* [Even Terminal Launcher](https://github.com/3mintimer/even-terminal-launcher) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-05 - macOS and Windows tray app for managing Even Terminal connection profiles and supervising agent sessions.
* [even-card-platform](https://github.com/tntpsu/even-card-platform) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-23 - Reusable framework for G2 card-game packs with card primitives, deck and hand rendering, a gesture model, and a shared style guide.
* [even-demo](https://github.com/fabioglimb/even-demo) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Interactive showcase of the even-toolkit design system with 55+ components, 191 icons, and light and dark themes.
* [even-notifications](https://github.com/ryanadiaz/even-notifications) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-13 - Draws simulated notification popup overlays so you can design around them without a live phone notification.
* [even\_g2\_picoruby](https://github.com/kishima/even_g2_picoruby) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-14 - Runnable example of writing a G2 app in Ruby via PicoRuby compiled to WebAssembly.
* [eveng2-demo](https://github.com/bigdra50/eveng2-demo) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-08 - Feature demo app exercising the display, input, audio, IMU, and storage APIs.
* [even-publisher](https://github.com/ivlaevski/even-publisher) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-12 - Tool for packaging and publishing G2 apps to Even Hub.
* [Hermes Glass](https://github.com/chanakyav/hermes-glass) ⭐ 0 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-02 - Vite and TypeScript starter for G2 apps with R1 ring input and a debug panel.
* [even-development](https://github.com/oggunderscore/even-development) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-08 - Reference monorepo of G2 apps and utilities, including a HUD with gesture routing, weather, clock, and reminders.
* [create-even-app](https://github.com/fabioglimb/create-even-app) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Scaffolder for G2 apps with six starter templates built on even-toolkit.
* [takemotions-gps-bridge](https://github.com/r-tkbyc/takemotions-gps-bridge) ⭐ 0 | 🐛 0 | 📅 2026-06-07 - Android helper supplying phone GPS to Even Hub apps, working around the in-app browser's lack of location access.
* [Glance-Companion](https://github.com/Munkhu1/Glance-Companion) ⭐ 0 | 🐛 0 | 📅 2026-06-15 - Android media control companion for the G2.
* [even-img-benchmark](https://github.com/opinsky/even-img-benchmark) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-24 - Benchmark harness for the G2 image pipeline, useful for tuning against the SDK 0.0.12 compressed image path.
* [appsbridge](https://gitlab.com/homeauto.cc/appsbridge) - Off-SDK companion bridge that exposes the phone's magnetometer, step count, and GPS to the WebView over a local WebSocket, enabling compass and navigation apps.

## Protocol and Reverse Engineering

* [even-g2-protocol](https://github.com/i-soxi/even-g2-protocol) ⭐ 181 | 🐛 7 | 📅 2026-01-20 - Community effort to reverse-engineer the G2 BLE protocol, with characteristic mapping and Python examples.
* [g2-kit-unofficial](https://github.com/Commute773/g2-kit-unofficial) ⭐ 35 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-17 - Unofficial reverse-engineering kit including R1 ring authentication and 27 decoded protobuf definitions.
* [g2flash](https://github.com/jimrandomh/g2flash) ⭐ 24 | 🐛 0 | 🌐 C | 📅 2026-08-31 - Custom firmware for the G2 that adds compressed image transfer, full-screen 576x288 single-image support, per-lens stereo output, and beeper tones, paired with matching custom send-side software.
* [evenRealities-openCFW](https://github.com/kalanihelekunihi/evenRealities-openCFW) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2026-08-31 - Reverse-engineering documentation of the G2 firmware and BLE protocol, paired with a custom-firmware effort.
* [even-g2-patched](https://github.com/cokeeffekt/even-g2-patched) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-03 - Patched Even app build that bypasses voice-intent interception so every G2 voice command routes to a custom AI agent.
* [Even-G2-RE](https://github.com/lonelyobserver0/Even-G2-RE) ⭐ 3 | 🐛 1 | 🌐 Java | 📅 2026-03-13 - Reverse-engineering effort covering the Even G2 app and its BLE system.
* [men-g2-ble-gateway](https://github.com/gpsnmeajp/men-g2-ble-gateway) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-06-13 - Python gateway exposing the G2 over HTTP, WebSocket, and MCP, with a local browser UI.
* [ffs-os](https://github.com/yonif8/ffs-os) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-23 - Clean-room Swift BLE driver and glasses OS for the G2, independent of the official stack.
* [g2\_helloworld](https://github.com/gpsnmeajp/g2_helloworld) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-05-10 - Minimal sideload app and WebSocket demo for the G2, useful as a bare-metal starting point.
* [men-g2-atoms3-hello](https://github.com/gpsnmeajp/men-g2-atoms3-hello) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2026-05-25 - Arduino sketch for the M5AtomS3 that connects to the G2 over BLE, authenticates, and boots an Even Hub page.

## Apps - Productivity and Utilities

* [weather-even-g2](https://github.com/nickustinov/weather-even-g2) ⭐ 23 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-31 - Five-screen weather forecast driven by the free Open-Meteo API, with no backend server required.
* [even-messages](https://github.com/thibautrey/even-messages) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-15 - Unified inbox client bringing messages from multiple services to the glasses.
* [epub-reader-g2](https://github.com/chortya/epub-reader-g2) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-12 - Read EPUB ebooks on the G2 display.
* [powerslides](https://github.com/jappyjan/powerslides) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-14 - Control presentation slides and read speaker notes from the G2.
* [rdt-even-g2](https://github.com/fuutott/rdt-even-g2-rddit-client) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-13 - Reddit client for the G2.
* [even-stars](https://github.com/thibautrey/even-stars) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-01 - Star and sky viewer for the G2.
* [even-browser](https://github.com/fabioglimb/even-browser) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-14 - Web browser for the G2: enter a URL on your phone and read pages hands-free with scroll, link navigation, history, and bookmarks.
* [tmux-on-g2](https://github.com/Tohoso/tmux-on-g2) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-19 - Streams a tmux pane to the glasses with double-tap voice input.
* [even-kitchen](https://github.com/fabioglimb/even-kitchen) ⭐ 4 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-06 - Cooking assistant with recipes, step-by-step guidance, and timers on the lens.
* [even-g2-calendar-companion](https://github.com/harikapadia999/even-g2-calendar-companion) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2026-02-22 - Next-event calendar notifications on the G2 over an optimized BLE path.
* [wordpeek-g2](https://github.com/Alireza29675/wordpeek-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Reading companion that shows the meaning or translation of a spoken or typed word.
* [even-aozora-reader](https://github.com/howyi/even-aozora-reader) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-16 - Reader for Japanese public-domain literature from Aozora Bunko on the G2.
* [EvenAware](https://github.com/Xuefeng-Zhu/EvenAware) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-18 - Real-time notification hub aggregating alerts from multiple sources onto the G2.
* [Glance G2](https://github.com/aleapc/glance-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-21 - Personal dashboard aggregator with an Expo mobile companion feeding calendar, health, weather, and finance data.
* [G2-Gmail](https://github.com/r-castelo/G2-Gmail) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-14 - Gmail reader for the G2.
* [Even-R-Clock](https://github.com/Morfeussession2/Even-R-Clock) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-02 - Unified clock app combining stopwatch, countdown timer, and alarm.
* [reddit-feed-even](https://github.com/plungarini/reddit-feed-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Full-featured Reddit client rendering feeds, posts, and comments through a Cloudflare Worker proxy.
* [Birdie](https://github.com/plungarini/birdie-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-14 - Real-time ambient bird identification that listens and names the species in your view.
* [Smokeless](https://github.com/plungarini/smokeless-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Cigarette tracker and quit companion logging each smoke with a tap on the frame.
* [even-g2-aviation-weather](https://github.com/MrMartellato/even-g2-aviation-weather) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-28 - Live METAR and TAF aviation weather on the G2.
* [bible-memory-g2](https://github.com/gn2b5gvcq5-tech/bible-memory-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - Scripture memory app with AI verse suggestions and fill-in-the-blank practice.
* [SalesEye](https://github.com/cphizz/SalesEye) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-03-03 - Real-time sales coach that detects objections and buying signals on live calls and surfaces cues on the lens.
* [Glance](https://github.com/tntpsu/Glance) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-06 - Glasses web reader that renders clean article text from any URL across a three-layer source, article, and reader view.
* [Pulse](https://github.com/tntpsu/Pulse) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - Multi-card personal dashboard with calendar, tasks, weather, and GitHub activity.
* [g2sidian](https://github.com/liyiyuian/g2sidian) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-06-30 - View and voice-capture Obsidian notes on the G2 through a self-hosted Tailscale backend.
* [Nutshell](https://github.com/refact0r/nutshell) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-19 - Reads PDFs, articles, and links on the G2 with AI-generated summaries and question answering.
* [Simple HUD](https://github.com/ryanadiaz/simple-hud) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-12 - Minimalist heads-up display showing clock, weather, and microphone level on the G2.
* [Daily App](https://github.com/marcometz/daily-app-even-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Multi-screen G2 app with a dashboard, RSS reader, and shopping list, with persisted state and navigation.
* [even-g2-obsidian](https://github.com/hiraghi/even-g2-obsidian) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-04 - Browse and edit an Obsidian vault on the G2 with live editor mirroring and IME composition support.
* [SolarWorldClock](https://github.com/KamalQ/SolarWorldClock) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-08 - World clock for the G2 for tracking time across multiple zones.
* [flipctl](https://github.com/KuriGohan-Kamehameha/flipctl) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-07-19 - Mirrors a Flipper Zero on the G2 HUD with R1 ring control and a one-tap launcher.
* [Even-G2-Sentinel-Ops](https://github.com/btstevens1984az/Even-G2-Sentinel-Ops) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-09 - Fully offline IT security toolkit for the G2 and R1 ring with eight operator tools.
* [G2-md-browser](https://github.com/r-castelo/G2-md-browser) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - Markdown file reader with folder browsing, search, and phone-managed favourites.
* [2FA-for-G2](https://github.com/a-bissell/2FA-for-G2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - TOTP authenticator that runs on your face.
* [Sun-Scout-Pro](https://github.com/quemorez/Sun-Scout-Pro) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-08 - Cinematography sun-tracking HUD with solar position, golden-hour timing, and a rotating sun-path map.
* [PRLens](https://github.com/VTorres09/PRLens) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-22 - Reads your open GitHub pull requests on the G2.
* [even\_score](https://github.com/opinsky/even_score) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Live score tracker for the G2.
* [ER Markdown Notes](https://github.com/Katazui/ER-Markdown-Notes) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-09 - Markdown notes browsed on the G2 HUD and edited on the phone, stored in IndexedDB.
* [My Pomodoro](https://github.com/tarumzu/my-pomodoro-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-31 - Pomodoro timer for the G2 with adjustable work and break cycles and session persistence.
* [even-matrix](https://github.com/narfman0/even-matrix) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-19 - Matrix messaging on the G2 with voice input and message-history browsing.
* [even-menu](https://github.com/ivlaevski/even-menu) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-23 - App launcher that manages and displays Even Hub apps by priority, configured from the phone.
* [NBA Pulse](https://github.com/Minna-Cross/even-nba-pulse) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-25 - Live NBA game tracker for the G2 with a play-by-play timeline and multi-game navigation.
* [even-prayer](https://github.com/ivlaevski/even-prayer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-20 - Prayer journal and daily-needs reflection app for the G2.
* [even-docs](https://github.com/Darielquinta/even-docs) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-30 - Local document editor for the G2 with multiple documents, version-history snapshots, and bridge-backed storage.
* [even-g2-apps](https://github.com/mfethe1/even-g2-apps) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-15 - Collection of custom Even Hub SDK apps for the G2, including a Telegram HUD, calendar events, and dashboard notifications.
* [x-for-even-g2](https://github.com/sommohapatra/x-for-even-g2) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-13 - Browse your X (Twitter) home timeline on the G2 with ring or touchpad navigation.
* [matrix-g2](https://github.com/logicalpeyote777/matrix-g2) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-19 - Matrix client that reads chats on the HUD and dictates replies by voice through a Python bridge.
* [even-scribe](https://github.com/hiraghi/even-scribe) ⭐ 0 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-04 - Japanese note-taking app for the G2 with a kana-kanji IME.
* [Bring-Lens](https://github.com/jappyjan/Bring-Lens) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-27 - Displays Bring! shopping lists on the glasses.
* [NOSnieuws\_G2](https://github.com/SachaEpskamp/NOSnieuws_G2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-03 - Unofficial NOS (Dutch public broadcaster) news reader for the G2.
* [BreakMate](https://github.com/aleapc/breakmate-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-21 - Lifecycle-aware health and break reminders fronted by an animated pixel-art character.
* [even-simple-calendar](https://github.com/r-tkbyc/even-simple-calendar) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-07-18 - Hands-free month-view calendar navigated entirely with the R1 ring.
* [even-simple-timer](https://github.com/r-tkbyc/even-simple-timer) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-07-18 - Hands-free countdown and count-up timer for the G2.
* [whisprompt](https://github.com/ewfefrs/whisprompt) ⭐ 0 | 🐛 0 | 📅 2026-07-24 - Offline Android teleprompter that drives scripted text onto the G2.
* [notion-ultimate-brain-even-g2](https://github.com/hofstede-matheus/notion-ultimate-brain-even-g2) ⭐ 0 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-30 - Ultimate Brain Notion template surfaced as a G2 interface.
* [even-todoist](https://github.com/howyi/even-todoist) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-11 - Todoist tasks on the G2, with a phone WebView for settings and a HUD focus display.
* [EvenG2\_GoogleKeep](https://github.com/TakaakiIchijo/EvenG2_GoogleKeep) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-24 - Projects Google Keep notes and checklists onto the G2 via a Flask and gkeepapi backend.
* [level-even-g2](https://github.com/nickustinov/level-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Spirit level for the G2.
* [even-traeger](https://github.com/tgarrell/even-traeger) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-11 - Monitor and control a Traeger pellet smoker from the G2.
* [fronius-even-g2](https://github.com/manuelwilhelmer/fronius-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-26 - Real-time Fronius Solar.web PV system data as a hands-free HUD.
* [evenG2](https://github.com/zijiebuzhuang/evenG2) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-24 - Collection of G2 apps including MoonWalker, a minimalist AR navigation app with dual map services.
* [even-my-news-hub](https://github.com/r-tkbyc/even-my-news-hub) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-06-15 - Personal news hub for the G2, built as a dependency-free HTML, CSS, and JavaScript app.
* [Visionote](https://github.com/takashicompany/visionote) - Displays photos and illustrations on the G2 with real-time greyscale conversion and brightness and contrast controls.
* [G2Terminal](https://github.com/tazzatdotnet/G2Terminal) - Terminal emulator for the Even Realities G2.

## Apps - Navigation and Transit

* [even-transit](https://github.com/langerhans/even-transit) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-21 - Public transit information on your glasses.
* [RoadView-G2](https://github.com/double-r-squared/RoadView-G2) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-14 - Live WSDOT highway camera feeds on the G2, browsable by highway.
* [EvenGo-Paris](https://github.com/Arkinos1/EvenGo-Paris) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Paris public transport, all modes in one app.
* [G2 Drive Nav](https://github.com/matthewmiglio/g2-drive-nav) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-07 - Turn-by-turn driving navigation for the G2 using Mapbox directions and live GPS.
* [HUD-Navigation-Integration-Even-Hub](https://github.com/ArmasF31/HUD-Navigation-Integration-Even-Hub) ⭐ 2 | 🐛 0 | 🌐 Swift | 📅 2026-07-01 - Live turn-by-turn navigation and OBD-II vehicle metrics on the G2 via a Swift bridge.
* [Wondereye](https://github.com/cmdlabtech/Wondereye) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-17 - Landmark exploration app surfacing context about places around you.
* [StoryWalk](https://github.com/aleapc/storywalk-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-21 - GPS-tracked point-of-interest storytelling for tourism and running, with an Expo companion.
* [wander](https://github.com/laolao91/wander) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-30 - Surfaces nearby points of interest on the G2.
* [MetroTracker](https://github.com/ltrademark/EvenG2-Metro-Tracker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - Real-time DC Metro arrivals board on the G2 lens with a phone map companion.
* [even-simple-compass](https://github.com/r-tkbyc/even-simple-compass) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2026-07-18 - Minimal compass HUD for the G2.
* [apexline-g2](https://github.com/Apolly009/apexline-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-31 - Motorcycle-first navigation app for the G2.
* [World-Monitor](https://github.com/Danikrlop47/World-Monitor-EvenRealities-G2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-25 - 3D globe world-monitor demo for the G2.
* [Perron-NS](https://github.com/JustinasLa/perron-ns-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Dutch Railways (NS) journey planner for the G2 with live departure boards and station search.
* [JapanTrainTransit](https://github.com/TakaakiIchijo/JapanTrainTransit-EvenG2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-27 - Voice-activated Japan train routing for the G2, backed by the Transit API.
* [even-g2-geocache](https://github.com/marcometz/even-g2-geocache) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-26 - Geocaching on the G2 showing nearby caches, direction, and distance from the OpenCaching OKAPI.
* [Checkin](https://github.com/typester/even-swarm) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-09 - Foursquare Swarm check-in app that surfaces nearby venues on the G2.
* [EUC-G2-Hud](https://github.com/Jessica-Hunt/EUC-G2-Hud) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Electric-unicycle telemetry HUD showing real-time speed, battery, and ride metrics on the G2.
* [even-adventure-hud](https://github.com/myclark/even-adventure-hud) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-17 - Heads-up display for hiking and biking on the G2 with live GPS speed and distance.
* [G2BusTracker](https://github.com/jamie950315/G2BusTracker) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-23 - Real-time Taiwan bus arrivals on the G2 with location-based stop finding.
* [Hunter](https://github.com/aleapc/hunter-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-21 - Place discovery with pixel-art icons, an offline cache, and OSRM walking routes.
* [HUD-KVV-Depatures-G2](https://github.com/ArmasF31/HUD-KVV-Depatures-G2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-03 - Next Karlsruhe (KVV) tram departures from your nearest stop, located by GPS.
* [glass-transit-511](https://github.com/contextablemark/glass-transit-511) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-16 - SF Bay Area BART and Muni arrivals via the 511.org feed.
* [subwaylens](https://github.com/laolao91/subwaylens) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-20 - Real-time NYC subway arrivals on the G2.
* [moto-hud](https://gitlab.com/homeauto.cc/moto-hud) - Motorcycle heads-up display that scrapes turn-by-turn directions and media from the Android notification tray.

## Apps - Smart Home and Car

* [tesla-even-g2](https://github.com/nickustinov/tesla-even-g2) ⭐ 29 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-14 - Tesla vehicle status and controls.
* [even-home-assistant](https://github.com/maik353-debug/even-home-assistant) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-13 - Home Assistant dashboard and control from the glasses.
* [g2\_macrodroid](https://github.com/gpsnmeajp/g2_macrodroid) ⭐ 3 | 🐛 0 | 🌐 HTML | 📅 2026-05-11 - Trigger MacroDroid automations from the G2.
* [connect-remote](https://github.com/Jack-Berry/connect-remote) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 - Remote companion for Genesis, Kia, and Hyundai vehicles showing battery, range, and climate on the G2.
* [Homekit-Integration-Even-Hub](https://github.com/ArmasF31/Homekit-Integration-Even-Hub) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-01 - Apple HomeKit control via a local Mac bridge.
* [car-hud](https://github.com/waliulawaltaha/car-hud) ⚠️ Archived - Distraction-free vehicle telemetry HUD for the G2.
* [glass-car-dash](https://github.com/drrobotk/glass-car-dash) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Driving dashboard and media remote for the G2.

## Apps - Fitness and Health

* [G2 Gym App](https://github.com/r-castelo/G2_Gym_App) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-22 - Workout tracking app for the G2 via Even Hub.
* [evenhub-running-tracker](https://github.com/kissyjpf/evenhub-running-tracker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28 - GPS and accelerometer running pace tracker for the G2.
* [golf-caddie-glasses](https://github.com/moisesvargasjr/golf-caddie-glasses) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-11 - Live round data and shot logging on the G2, paired with an iOS and watchOS tracker.
* [hevy-g2](https://github.com/Alireza29675/hevy-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Drives Hevy gym workouts from the glasses: pick a routine on your phone and see sets and reps on the display.
* [even-workout](https://github.com/fabioglimb/even-workout) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Guided workout tracking on the G2.
* [EyeFit](https://github.com/aleapc/eyefit-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-21 - Eye-exercise app driven by IMU head tracking, with a scheduling companion app.

## Apps - Finance and Markets

* [even-market](https://github.com/fabioglimb/even-market) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-06 - Stock market quotes and watchlists on the glasses.
* [evenhub-news-ticker](https://github.com/valve4/evenhub-news-ticker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-11 - Live financial news ticker for the G2.
* [Even Balance](https://github.com/Morfeussession2/EVEN-G2-Balance) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-17 - Personal finance HUD tracking balances and spending categories on the G2.
* [even-g2-crypto-ticker](https://github.com/ARNLTony/even-g2-crypto-ticker) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-30 - Live cryptocurrency price ticker for the G2.
* [g2-currency-hub](https://github.com/evde-ga4/g2-currency-hub) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-04 - Currency converter for the G2.

## Apps - Voice and Speech-to-Text

* [stt-even-g2](https://github.com/nickustinov/stt-even-g2) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-20 - Real-time on-glasses speech-to-text via Soniox.
* [even-bridge](https://github.com/invendor/even-bridge) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-05 - Transcribes G2 speech and sends it on to Telegram, Slack, or Gmail.
* [soniox-translate](https://github.com/intelc/soniox-translate) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-14 - Real-time speech translation with live captions, powered by Soniox.
* [ERGram](https://github.com/tiagodeoliveira/ERGram) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-10 - Server-free push-to-talk voice messaging to a Telegram group from the G2.
* [G2 Captions](https://github.com/iamantonio/g2-captions) ⭐ 1 | 🐛 7 | 🌐 TypeScript | 📅 2026-07-20 - Accessibility-first real-time captioning prototype for the G2 using AssemblyAI and OpenAI Realtime.
* [Convo Exchange](https://github.com/XXXStars0/STT_G2_Demo) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-15 - Real-time transcription and keyword detection on the G2 via Deepgram.
* [speechcoach-g2](https://github.com/aleapc/speechcoach-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-21 - Real-time speech-pacing coach for the G2 with an STT backend, a VU meter, and an animated pixel mascot.
* [Lingua Franca](https://github.com/d3hospitality/lingua-franca) ⭐ 0 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-26 - Live language conversation coach for the G2 that suggests next phrases in a target language during face-to-face dialogue.
* [even-app-one](https://github.com/cscartjp/even-app-one) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-08-06 - Interactive Q\&A assistant for the G2 with audio capture, live transcription, and preset questions.

## Apps - Games and Learning

* [EvenChess](https://github.com/dmyster145/EvenChess) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-21 - Chess for the G2.
* [pong-even-g2](https://github.com/nickustinov/pong-even-g2) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Pong, player versus AI, controlled by swipes.
* [snake-even-g2](https://github.com/nickustinov/snake-even-g2) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Classic Snake game.
* [tetris-even-g2](https://github.com/nickustinov/tetris-even-g2) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Tetris for the G2.
* [gloss](https://github.com/dxiv/gloss) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-13 - Type or dictate text and view it as a stack of American Sign Language slides.
* [EVEN-G2-Tamagotchi](https://github.com/Morfeussession2/EVEN-G2-Tamagotchi) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-11 - Tamagotchi-style virtual pet for the G2.
* [arkanoid-even-g2](https://github.com/nickustinov/arkanoid-even-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Arkanoid brick-breaker for the G2.
* [G2 Flashcards](https://github.com/tomtau/g2-flashcards) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-28 - Flashcard app for the G2 with FSRS scheduling.
* [EvenSolitaire](https://github.com/dmyster145/EvenSolitaire) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-21 - Solitaire card game for the G2.
* [SMRTi](https://github.com/prasants/smrti) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-21 - Spaced-repetition flashcards for the G2 with FSRS v6, an ambient mode, and pre-meeting prep.
* [Lenski](https://github.com/Xuefeng-Zhu/Lenski) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-18 - Spaced-repetition flashcards for the G2 with Anki import, phone deck management, and AI deck generation.
* [Card Pack](https://github.com/tntpsu/CardPack) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-23 - Seven classic card games, including Hearts, Spades, and Cribbage, for the G2.
* [flappy-g2](https://github.com/200even/flappy-g2) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-03-13 - Flappy Bird clone for the G2.
* [Heads or Tails](https://github.com/dmyster145/EvenHeadsOrTails) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-23 - Animated coin-flip game for the G2 with a running tally counter.
* [HoppyRoads](https://github.com/dmyster145/EvenRoads) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-14 - Crossy Road-style crossing game for the G2 with deterministic text-first gameplay.
* [Vault Zero](https://github.com/fraugho/dungeon) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-18 - First-person dungeon crawler with textured raycast 3D rendering on the G2.
* [House Games](https://github.com/tntpsu/HouseGames) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-12 - Four casino games for the G2: Blackjack, Video Poker, Three Card Poker, and Roulette.
* [even-doom](https://github.com/narfman0/even-doom) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-04 - Doom E1M1 raycaster rendered as ASCII art on the G2.
* [EvenFoundryVTT](https://github.com/Aiacos/EvenFoundryVTT) ⭐ 0 | 🐛 6 | 🌐 TypeScript | 📅 2026-07-07 - D\&D 5e on the G2 and R1 ring, synced with FoundryVTT via a phosphor-green tactical HUD.
* [darts-even-g2](https://github.com/JustinasLa/darts-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Darts checkout counter for the G2.
* [Quiz Flashcards](https://github.com/KamalQ/g2-flashcards) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-16 - Multiple-choice quiz flashcards with JSON, CSV, and plain-text deck import.
* [lingua-lens](https://github.com/kolife01/lingua-lens) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-20 - Ambient English coach that offers full phrases when you stall and stays silent when you don't.
* [even-sliding-puzzle](https://github.com/r-tkbyc/even-sliding-puzzle) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-06-22 - Sliding puzzle in 3x3 and 4x4 for the G2.
* [even-japanese-map-quiz](https://github.com/r-tkbyc/even-japanese-map-quiz) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-08-04 - Silhouette quiz covering all 47 Japanese prefectures, played entirely with the R1 ring.
* [evenTaipan](https://github.com/opinsky/evenTaipan) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-12 - Taipan-style trading game for the G2.

## Apps - Media and Music

* [DisplayPlusMusic](https://github.com/Oliemanq/DisplayPlusMusic) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 - Spotify now-playing viewer for the G2.
* [even-g2-matrix](https://github.com/wmoto-ai/even-g2-matrix) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-01 - Matrix-style digital rain animation for the G2 display.
* [MuSe](https://github.com/ltrademark/EvenG2-Music-Search) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-07 - Ambient music identification on the G2 showing song, artist, and cover art with searchable history.
* [even-now-playing](https://github.com/r-tkbyc/even-now-playing) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-08-21 - Now-playing media display and ring control, paired with an Android media bridge.
* [even-g2-media-remote](https://github.com/aramood/even-g2-media-remote) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-11 - Media remote driven by the G2 and R1 ring, with an Android helper.
* [Even-G2-Guitar-Tuner](https://github.com/Comm4nd0/Even-G2-Guitar-Tuner) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-19 - Guitar tuner that shows detected pitch on the glasses.
* [orpheus-g2](https://github.com/L3G/orpheus-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Synced lyrics and now-playing for both Apple Music and Spotify.
* [lyrics-glow](https://github.com/tntpsu/lyrics-glow) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-06 - Time-synced karaoke lyrics on the G2 display, backed by LRCLIB.
* [HUD-Music-Integration-Even-Hub](https://github.com/ArmasF31/HUD-Music-Integration-Even-Hub) ⭐ 0 | 🐛 0 | 🌐 Swift | 📅 2026-07-01 - Apple Music now-playing display via a local Mac bridge.
* [Sudden Karaoke](https://github.com/inutano/sudden-karaoke) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-30 - Song recognition and time-synced karaoke lyrics on the G2 via the AudD and LRCLIB APIs.
* [spotify-g2](https://github.com/yannrapaport/spotify-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-14 - Spotify playback control plugin driven by the R1 ring.
* [g2-multi-instrument-tuner](https://github.com/r-castelo/g2-multi-instrument-tuner) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-22 - Cross-platform tuner for guitar, bass, and ukulele with alternate tunings.

## Apps - Streaming

* [EvenTwitchChat](https://github.com/kevin-huff/EvenTwitchChat) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - Twitch chat client for the G2 with configurable display and username filtering.
* [g2-twitch-hud](https://github.com/tomsamwel/g2-twitch-hud) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-07 - Twitch chat HUD for outdoor IRL streaming with priority and alert filter modes.

## AI and Agent Integrations

* [cc-g2](https://github.com/wmoto-ai/cc-g2) ⭐ 33 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-28 - Control a Claude Code session from the G2: approve or deny prompts and enter voice commands.
* [OpenVide](https://github.com/open-vide/openvide) ⭐ 33 | 🐛 6 | 🌐 TypeScript | 📅 2026-07-06 - Remote control for Claude Code and Codex sessions with a G2 WebView client over an SSH and HTTPS bridge.
* [claude-code-g2](https://github.com/sam-siavoshian/claude-code-g2) ⭐ 28 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-11 - Run Claude Code hands-free from the G2 via voice and temple taps, billed against a Claude subscription.
* [G2CC](https://github.com/expectbugs/G2CC) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-14 - Direct-BLE Claude Code dispatch for the G2 with DJI two-mic noise cancellation and Parakeet ASR.
* [Even Reality Memory System](https://github.com/Tej-Sharma/even-reality-memory-system) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-07-26 - Ambient AI memory for the G2 that captures thoughts, answers queries, and transcribes meetings with on-lens cues.
* [EvenHub-LocalLLM](https://github.com/axchristie/EvenHub-LocalLLM) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-05 - Voice-controlled local LLM interface for the G2, backed by open-webui over Tailscale.
* [Even-Voice-AI](https://github.com/MrScautHD/Even-Voice-AI) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-01 - Wake-word voice assistant using the browser's speech recognition, GPT-4o-mini, and streaming text-to-speech routed to the phone.
* [Unofficial Even G2 Local Assistant](https://github.com/marienbaptiste/unofficial-even-g2-local-assistant) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-04-19 - Local-first voice assistant for the G2 with Whisper STT and dual-model routing between local Qwen and a cloud fallback.
* [even-g2-agentic-app](https://github.com/brianmatzelle/even-g2-agentic-app) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-05 - Agentic framework for the G2 with voice input, MCP tools, and interactive widgets on the display.
* [g2-claude-remote](https://github.com/ThatCrispyToast/g2-claude-remote) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-20 - Controls Claude remote-control sessions from the G2 with a HUD app, companion panel, and uvx-runnable bridge.
* [HeadLenss](https://github.com/takashicompany/headlenss) ⭐ 5 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-31 - Drive Claude Code on your PC by voice from the G2, plus tmux control from a phone browser.
* [evenai-gemini-bridge](https://github.com/langerhans/evenai-gemini-bridge) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-03-04 - Rewrites the built-in Even-AI voice intents to Google Gemini, with request deduplication.
* [hermes-even-hub-app](https://github.com/huntsyea/hermes-even-hub-app) ⭐ 3 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-29 - G2 WebView client that drives locally running Hermes agents hands-free with voice and streaming responses.
* [even-g2-hermes](https://github.com/wingk1314/even-g2-hermes) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-09 - Connects the G2 to Hermes agents through AI-proxy, Terminal Mode, and Even Hub plugin integrations.
* [cos-glasses-server](https://github.com/ukaoma/cos-glasses-server) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-27 - Self-hosted heads-up-display server that drives the G2 from a local Claude Code CLI.
* [claude-hud](https://github.com/m4rpqfbbc2-debug/claude-hud) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-15 - Voice-driven Claude Code terminal HUD for the G2.
* [even-jarvis](https://github.com/iDigz/even-jarvis) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-07 - OpenClaw-powered assistant with glasses-mic voice input, streamed responses, and image generation.
* [Cue](https://github.com/tntpsu/Cue) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-24 - Real-time conversation coach suggesting responses live, powered by Deepgram speech-to-text and Claude.
* [openclaw-g2-hud](https://github.com/kqb/openclaw-g2-hud) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-08 - Heads-up display for monitoring OpenClaw agents, with voice capture and tap and scroll navigation.
* [even-better](https://github.com/pawaca/even-better) ⭐ 2 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-15 - Mirrors live Claude Code and Codex terminal sessions to the G2 over the Even Terminal protocol.
* [EvenCode](https://github.com/TheOmran/EvenCode) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-27 - Voice-driven Claude Code conversations on the G2, including scrolling results and answering interactive prompts.
* [evenai-anthropic-bridge](https://github.com/jase-perf/evenai-anthropic-bridge) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-03-08 - Replaces the built-in Even AI assistant with Claude via a small local server.
* [g2-channels](https://github.com/Alireza29675/g2-channels) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-31 - Two-way terminal for Claude Code sessions: talk to a session and read its replies on the glasses.
* [hermes-evenhub-bridge](https://github.com/huntsyea/hermes-evenhub-bridge) ⭐ 1 | 🐛 14 | 🌐 Python | 📅 2026-08-29 - Python adapter exposing the G2 as a Hermes agent platform.
* [even-terminal-pi](https://github.com/lallenlowe/even-terminal-pi) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-16 - Runs the pi coding agent on the G2 as an Even Terminal provider.
* [evenglass](https://github.com/xntj-ai/evenglass) ⚠️ Archived - Real-time relay between the G2, an Android hub, a Phoenix and Elixir server, and a Windows client.
* [Cue (ambient memory)](https://github.com/abhishekj720/Cue-evenRealitiesG2) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-04-20 - Ambient social-memory app for the G2 that captures voiceprints and speaker context locally with Resemblyzer and Whisper.
* [GlassAI](https://github.com/BondIT-ApS/glass-ai) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-15 - Voice-first assistant for the G2 bridging to a Hermes agent over an OpenAI-compatible API, with a companion phone app.
* [G2 OpenClaw](https://github.com/kyle-deprow/g2_openclaw) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-22 - Bridges the G2 to a local OpenClaw agent via a PC gateway with Whisper STT and streaming responses.
* [eveng2-terminal-textinput](https://github.com/soualid/eveng2-terminal-textinput) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-08-15 - Phone companion that adds typed text input to Claude Code sessions while keeping the G2 HUD in sync.
* [completion-telegram-bridge](https://github.com/matsei-ruka/completion-telegram-bridge) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-14 - OpenAI-compatible completion API bridging the G2 to a personal Telegram agent.
* [even-deimos](https://github.com/dxiv/even-deimos) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-17 - Pick your AI provider, chat from your phone, and stream replies to a minimal lens HUD, with keys stored on-device.
* [g2-caduceus](https://gitlab.com/Qu4ndo/g2-caduceus) - FastAPI bridge connecting G2 voice input to any OpenAI-compatible chat endpoint (bring your own model).
* [even-g2-local-agent](https://github.com/GumbiiDigital/even-g2-local-agent) - Local-first voice agent using Even Terminal Mode, Android, and Ollama.

## Related and Legacy (G1)

* [awesome-even-realities-g1](https://github.com/galfaroth/awesome-even-realities-g1) ⭐ 34 | 🐛 0 | 📅 2024-12-07 - Companion list for the first-generation G1 glasses.
* [even\_realities\_decomp](https://github.com/JohnRThomas/even_realities_decomp) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2026-08-03 - Reverse-engineering and decompilation of the first-generation G1 firmware.
* [Even Realities G1 Examples and Posts](https://github.com/hpssjellis/my-examples-and-posts-of-g1-even-realities-smart-glasses) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2025-09-18 - Field notes, hacks, and examples for the G1.
* [even-utils](https://github.com/radioegor146/even-utils) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2025-11-28 - Reverse-engineering utilities and protocol experiments for the first-generation G1, including custom dashboard content.

## Community

* [Even Realities Discord](https://discord.com/invite/AZc3by2v9J) - Official community where pilot developers share demos, feedback, and tips.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first, then open a pull request.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-31._
