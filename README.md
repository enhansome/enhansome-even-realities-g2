# Awesome Even Realities G2 with stars

> A curated list of SDKs, tools, apps, and resources for developing on the Even Realities G2 smart glasses.

The [Even Realities G2](https://www.evenrealities.com) are everyday display smart glasses with dual micro-LED displays, no camera, and no speaker, paired with the R1 control ring. G2 apps are web apps: your code runs on a server, the iPhone Even App loads it in a WebView, and display and input are relayed over BLE to the glasses. This list collects the best community and official resources for building them.

**Scope:** This is a resource for *building* on the G2 — every entry is open source or an official resource you can read, clone, and learn from. Closed-source apps aren't listed in these sections; if you've built one, open an issue and we can look at adding a separate app directory for owners down the line.

## Contents

* [Official](#official)
* [Documentation and Guides](#documentation-and-guides)
* [SDK, Tooling, and Simulators](#sdk-tooling-and-simulators)
* [Protocol and Reverse Engineering](#protocol-and-reverse-engineering)
* [Firmware and Emulation](#firmware-and-emulation)
* [Apps - Productivity and Utilities](#apps---productivity-and-utilities)
* [Apps - Reading and Reference](#apps---reading-and-reference)
* [Apps - Messaging and News](#apps---messaging-and-news)
* [Apps - Navigation and Transit](#apps---navigation-and-transit)
* [Apps - Smart Home and Car](#apps---smart-home-and-car)
* [Apps - Fitness and Health](#apps---fitness-and-health)
* [Apps - Finance and Markets](#apps---finance-and-markets)
* [Apps - Voice and Speech-to-Text](#apps---voice-and-speech-to-text)
* [Apps - Games and Learning](#apps---games-and-learning)
* [Apps - Media and Music](#apps---media-and-music)
* [Apps - Streaming](#apps---streaming)
* [Apps - Coding Agents and Terminals](#apps---coding-agents-and-terminals)
* [AI and Agent Integrations](#ai-and-agent-integrations)
* [Related and Legacy (G1)](#related-and-legacy-g1)
* [Community](#community)

## Official

* [EvenDemoApp](https://github.com/even-realities/EvenDemoApp) ⭐ 474 | 🐛 28 | 🌐 C | 📅 2026-06-09 - Official demo app from Even Realities.
* [everything-evenhub](https://github.com/even-realities/everything-evenhub) ⭐ 82 | 🐛 33 | 📅 2026-10-21 - Official developer kit bundling the Even Hub SDK, CLI, simulator, and documentation for building G2 apps.
* [Even Hub Starter Templates](https://github.com/even-realities/evenhub-templates) ⭐ 57 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-07 - Four official scaffolds to clone and run: minimal, ASR, image, and text-heavy.
* [EH-InNovel](https://github.com/even-realities/EH-InNovel) ⭐ 15 | 🐛 1 | 🌐 Kotlin | 📅 2026-03-25 - Official Even Hub web demo: a simple novel reader for the G2.
* [Even Enterprise SDK (Flutter)](https://github.com/even-realities/flutter_enterprise_sdk) ⭐ 9 | 🐛 0 | 🌐 Dart | 📅 2026-11-11 - Flutter plugin to connect enterprise-designated G2 glasses on Android and iOS.
* [lvgl-sys-v9](https://github.com/even-realities/lvgl-sys-v9) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-31 - Official LVGL v9 system library for the G2 display stack.
* [Even Enterprise SDK](https://github.com/even-realities/enterprise_sdk) ⭐ 2 | 🐛 0 | 🌐 Kotlin | 📅 2026-11-11 - Provides native Android and iOS SDKs for enterprise-authorized G2 glasses.
* [Even Realities Feedback](https://github.com/even-realities/feedback) ⭐ 0 | 🐛 0 | 📅 2026-11-11 - Collects feature requests for the G2, R1, Even Hub and the SDK.
* [Even Hub Developer Portal](https://hub.evenrealities.com) - Official portal to build, test, and publish apps directly to the G2.
* [Even Realities Developer Docs](https://hub.evenrealities.com/docs) - Official SDK documentation for plugins, widgets, and AI integrations.
* [Introducing the Even G2 Enterprise SDK](https://www.evenrealities.com/blogs/news/introducing-the-even-g2-enterprise-sdk) - Announces the Enterprise SDK that lets companies build their own G2 apps without the Even App.

## Documentation and Guides

* [even-g2-notes](https://github.com/nickustinov/even-g2-notes) ⭐ 121 | 🐛 3 | 📅 2026-07-31 - Community-maintained SDK reference covering architecture, the display and container model, input events, page lifecycle, device APIs, and packaging. The de facto documentation hub for G2 development.
* [even\_g2\_simple\_code](https://github.com/flushpot1125/even_g2_simple_code) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-01 - Provides simple sample code for G2 app development, in Japanese.
* [even-hub-devguide](https://github.com/aleapc/even-hub-devguide) ⭐ 1 | 🐛 0 | 📅 2026-04-21 - Community-maintained, battle-tested guide to building apps on Even Hub for the G2.
* [evenhub-g2-skill](https://github.com/goodrahstar/evenhub-g2-skill) ⭐ 1 | 🐛 0 | 📅 2026-08-27 - Agent skill with hard-won rules for building G2 and Even Hub apps.
* [G2 Two-Column List](https://github.com/fuschini/g2-two-column-list) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-30 - Runnable demo showing how to build a scrollable two-column checklist on the G2 display with two text containers.
* [Even G2 Plugin Guide](https://github.com/kkitase/even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-04 - Teaches G2 plugin building in Japanese and ships an AI prompter and a live translation app.
* [Even G2 field notes](https://github.com/nr666-dev/even-g2-field-notes) ⭐ 0 | 🐛 0 | 📅 2026-09-12 - Collects real-hardware findings from building four apps on the G2.
* [even-g2-design-system](https://github.com/wetty-serial/even-g2-design-system) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-03 - Collects UI rules, shared parts, and code examples for designing G2 screens.
* [Even Hub Video Series](https://hub.evenrealities.com/docs/learn/videos) - Gives 14 video lessons from machine setup to app submission on Even Hub.
* [Even Hub docs: Changelog](https://hub.evenrealities.com/docs/reference/changelog) - Lists SDK, CLI, and simulator releases with the Even App version each needs.
* [Even Hub docs: Networking](https://hub.evenrealities.com/docs/build/networking) - Explains the app.json network whitelist and the CORS checks that every request must pass.
* [Even Hub docs: UI/UX Design Guidelines](https://hub.evenrealities.com/docs/build/design-guidelines) - Describes the greyscale canvas, container limits, 24x24 icons, and Unicode characters that render.
* [The unfinished glasses](https://www.evenrealities.com/blogs/even-insider/the-unfinished-glasses) - Explains the Even Hub model: the phone runs apps, the glasses show them, the ring decides.
* [Got an Even G2? Build Your Own Apps!](https://dev.to/yokomachi/got-an-even-g2-build-your-own-apps-hands-on-impressions-and-dev-tips-1glp) - Shares hands-on impressions and limits found while building three G2 apps.

## SDK, Tooling, and Simulators

* [MentraOS](https://github.com/Mentra-Community/MentraOS) ⭐ 2,464 | 🐛 111 | 🌐 TypeScript | 📅 2026-11-26 - Open-source smart-glasses OS and app SDK that drives the G2, among other glasses, over BLE.
* [faceclaw](https://github.com/jimrandomh/faceclaw) ⭐ 130 | 🐛 20 | 🌐 TypeScript | 📅 2026-11-25 - Native desktop dashboard for driving the G2 display outside the WebView.
* [even-toolkit](https://github.com/fabioglimb/even-toolkit) ⭐ 102 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Shared SDK utilities: design system, web components, pixel-art icons, an STT module, and pixel-accurate G2 text measurement.
* [even-dev](https://github.com/BxNxM/even-dev) ⭐ 88 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-23 - Even Hub simulator and multi-app test environment for building and testing G2 apps locally.
* [xg-glass-sdk](https://github.com/hkust-spark/xg-glass-sdk) ⭐ 54 | 🐛 21 | 🌐 Kotlin | 📅 2026-11-23 - One API for camera, mic, display, and audio across the G2, Rokid, Meta Ray-Ban, Brilliant Labs Frame, RayNeo, and INMO, with a simulator.
* [Glyph](https://github.com/gabrielevierti/glyph) ⭐ 26 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-18 - Graphics and UI framework for G2 apps that renders a full framebuffer and sends only the changed tiles.
* [Mentra-Bluetooth-SDK-Starter-Kit](https://github.com/Mentra-Community/Mentra-Bluetooth-SDK-Starter-Kit) ⭐ 19 | 🐛 6 | 📅 2026-11-26 - Apache-2.0 native BLE SDK starter kit for connecting an Android, iOS, or React Native app to smart glasses, including the G2, powered by MentraOS.
* [OpenEvenSdk](https://github.com/Thepizzapie/OpenEvenSdk) ⭐ 12 | 🐛 0 | 🌐 Swift | 📅 2026-06-15 - Local-first G2 toolkit with Python, Swift, and Kotlin BLE bridges and protocol documentation.
* [g2-kit](https://github.com/RAZKOM/g2-kit) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-02 - Provides drawn UI components for G2 apps: charts, controls and HUD pieces as image tiles.
* [even-realities-g2-glasses](https://github.com/brianmatzelle/even-realities-g2-glasses) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-03 - Starter template for building G2 plugins with TypeScript and Vite.
* [takemotions-media-bridge](https://github.com/r-tkbyc/takemotions-media-bridge) ⭐ 5 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-16 - Android helper exposing now-playing media and R1 ring playback controls to glasses apps over localhost.
* [droidbridge](https://github.com/Commute773/droidbridge) ⭐ 4 | 🐛 1 | 🌐 Kotlin | 📅 2026-04-16 - Bridges the G2 BLE connection over the network so a desktop can talk to the glasses.
* [even (CLI)](https://github.com/aluminumio/even) ⭐ 3 | 🐛 0 | 🌐 Swift | 📅 2026-07-01 - Swift command-line tool for sending text to the G2 over Bluetooth.
* [ER Studio](https://github.com/gabrielevierti/er-studio) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-18 - VS Code extension that runs the G2 simulator, dev server, and SDK reference next to your code.
* [ehup](https://github.com/takashicompany/even-hub-uploader) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-08-25 - Command-line tool that drives the Even Hub developer portal to upload builds, manage beta testers, and change release state.
* [EvenHub Grok Bot](https://github.com/zichenzhang04/even-grokbot-avatars) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-08-12 - Animation demo running three synchronized line-art avatars on the G2, showing the bitmap-transfer and luminance-0 transparency pattern.
* [mentra-bluetooth-sdk-ios](https://github.com/Mentra-Community/mentra-bluetooth-sdk-ios) ⭐ 3 | 🐛 1 | 🌐 Swift | 📅 2026-11-26 - Swift Package Manager distribution of the Mentra Bluetooth SDK for iOS.
* [matic even](https://github.com/maticsh/matic-even) ⭐ 3 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-22 - Collects measured G2 hardware findings and TypeScript packages for glasses, phone and tests.
* [g2-icon-studio](https://github.com/naotake/g2-icon-studio) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-06-08 - Browser tool for creating the 24x24 monochrome app icons Even Hub requires, with a 1-bit image converter and pixel editor.
* [Hermes Glass](https://github.com/chanakyav/hermes-glass) ⭐ 2 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-02 - Vite and TypeScript starter for G2 apps with R1 ring input and a debug panel.
* [evenhub-playground](https://github.com/shimopino/evenhub-playground) ⭐ 2 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-15 - Development playground for experimenting with Even Hub G2 apps.
* [even-notifications](https://github.com/ryanadiaz/even-notifications) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-13 - Draws simulated notification popup overlays so you can design around them without a live phone notification.
* [even-ui-builder](https://github.com/langerhans/even-ui-builder) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-02-15 - Simple UI builder and code generator for the Even Hub SDK.
* [evenhub-dev-harness](https://github.com/oneticket99/even_hub_dev_simulator) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-13 - Browser development harness for Even Hub widgets with mocked GPS, IMU, camera, and album inputs the official simulator lacks.
* [even-realities-app-template](https://github.com/r4stl1n/even-realities-app-template) ⭐ 2 | 🐛 0 | 🌐 Swift | 📅 2026-07-24 - MIT-licensed native SwiftUI baseline app for the G2 and R1 ring, with direct BLE, LC3 audio, microphone capture, and on-device speech-to-text.
* [faceclaw-ios-build](https://github.com/doombadroid/faceclaw-ios-build) ⭐ 2 | 🐛 0 | 📅 2026-10-24 - GitHub Actions recipe that builds an unsigned Faceclaw iOS IPA without a Mac.
* [evenhub-deploy](https://github.com/fidelio-wilson-2501/evenhub-deploy) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-25 - Uploads private .ehpk builds to Even Hub from a GitHub Actions workflow.
* [even-apps](https://github.com/plungarini/even-apps) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-19 - Monorepo of Even Hub apps with SDK research notes and an app scaffold script.
* [Hub Preview Studio](https://github.com/zijiebuzhuang/hub-preview-studio) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-30 - Previews an Even Hub phone UI and the 576x288 glasses layout side by side.
* [even\_hub\_emu](https://github.com/aegray/even_hub_emu) ⭐ 2 | 🐛 0 | 🌐 Dart | 📅 2026-02-16 - Emulates the Even Hub SDK in a Flutter app for G2 development.
* [demo-app-g2](https://github.com/nickustinov/demo-app-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-12 - Shows every Even G2 SDK feature in one reference app.
* [even-realities-ui](https://github.com/jappyjan/even-realities) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2026-03-25 - Foundation UI package (components, icons, and design tokens) for building G2 apps aligned to Even Realities' design guidelines.
* [even-voice-shim](https://github.com/tntpsu/even-voice-shim) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-09 - Push-to-talk speech-to-text shim with a Cloudflare Worker template, working around the missing on-device STT API.
* [even-card-platform](https://github.com/tntpsu/even-card-platform) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-23 - Reusable framework for G2 card-game packs with card primitives, deck and hand rendering, a gesture model, and a shared style guide.
* [even-demo](https://github.com/fabioglimb/even-demo) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Interactive showcase of the even-toolkit design system with 55+ components, 191 icons, and light and dark themes.
* [even\_g2\_picoruby](https://github.com/kishima/even_g2_picoruby) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-14 - Runnable example of writing a G2 app in Ruby via PicoRuby compiled to WebAssembly.
* [eveng2-demo](https://github.com/bigdra50/eveng2-demo) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-08 - Feature demo app exercising the display, input, audio, IMU, and storage APIs.
* [even-demo-kit](https://github.com/fuschini/even-demo-kit) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-01 - Turns G2 simulator recordings into demo videos with a transparent background, so the UI looks like it runs on real glasses.
* [G2 Ring Remote](https://github.com/Om-Alve/g2-ring-remote) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-11-14 - Turns a cheap K02 Bluetooth ring into a remote for the glasses through Faceclaw, without root.
* [Omni](https://github.com/lettucegoblin/omnieven) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-16 - Runs a server-driven G2 dashboard whose screens are hot-reloaded scripts, with an HTTP push API.
* [even-g2-hello-world-spatial](https://github.com/tleppane/even-g2-hello-world-spatial) ⭐ 1 | 🐛 3 | 🌐 HTML | 📅 2025-12-31 - Demonstrates a small spatial hello-world for the Even Hub pilot program.
* [g2-launcher](https://github.com/genomiskdiagnostik/g2-launcher) ⭐ 1 | 🐛 1 | 📅 2026-10-25 - Provides a local app library, catalog client, and compatibility runtime for the G2.
* [even-publisher](https://github.com/ivlaevski/even-publisher) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-12 - Tool for packaging and publishing G2 apps to Even Hub.
* [even-development](https://github.com/oggunderscore/even-development) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-21 - Reference monorepo of G2 apps and utilities, including a HUD with gesture routing, weather, clock, and reminders.
* [create-even-app](https://github.com/fabioglimb/create-even-app) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Scaffolder for G2 apps with six starter templates built on even-toolkit.
* [takemotions-gps-bridge](https://github.com/r-tkbyc/takemotions-gps-bridge) ⭐ 0 | 🐛 0 | 📅 2026-06-07 - Android helper supplying phone GPS to Even Hub apps, working around the in-app browser's lack of location access.
* [Glance-Companion](https://github.com/Munkhu1/Glance-Companion) ⭐ 0 | 🐛 0 | 📅 2026-06-15 - Android media control companion for the G2.
* [even-img-benchmark](https://github.com/opinsky/even-img-benchmark) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-24 - Benchmark harness for the G2 image pipeline, useful for tuning against the SDK 0.0.12 compressed image path.
* [EvenG2 Game Engine Debug Bridge](https://github.com/TakaakiIchijo/EvenG2_GameEngineDebugBridge) ⭐ 0 | 🐛 0 | 🌐 GDScript | 📅 2026-08-26 - Sends Unity and Godot debug logs over the local network to the G2 for on-device viewing while you develop.
* [EvenReal Cam](https://github.com/Hyunki6040/evenreal-cam) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-08 - Overlays the G2 HUD on a phone camera feed to shoot demo photos and videos.
* [g2-engine](https://github.com/Jadoking/g2-engine) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-09 - Draws 16-level graphics in a software framebuffer and sends only changed tiles to the glasses.
* [GlassPort](https://github.com/MrDorachan/GlassPort) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2026-11-07 - Android app that gives Even Hub plugins phone data over localhost, with an add-on system.
* [even\_native\_bridge](https://github.com/aegray/even_native_bridge) ⭐ 0 | 🐛 0 | 🌐 Dart | 📅 2026-02-02 - Runs an Android web server that gives Even Hub apps access to native phone features.
* [g2-relay](https://github.com/carlmasters02/g2-relay) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-12 - Cloudflare Worker that relays WebSocket audio to the OpenAI realtime translation API and hides the key.
* [Isometric SF G2 Fitting Lab](https://github.com/d3hospitality/isometric-sf-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-07 - Shows an isometric San Francisco map and tunes display contrast and dithering on the G2.
* [even-dev-hud](https://github.com/ed1868/even-dev-hud) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-11 - Provides a G2 developer HUD with shared core, plugins and setup guides.
* [Earshot](https://github.com/jarekbird/earshot) ⭐ 0 | 🐛 6 | 🌐 TypeScript | 📅 2026-11-26 - Voice-first app framework where apps declare actions that the menu, touchpad, and voice all run.
* [g2-tap-guard](https://github.com/jarekbird/g2-tap-guard) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-16 - Ignores the stray tap that G2 glasses can report during a scroll.
* [Script2G](https://github.com/liyiyuian/Script2G) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Runs your own JavaScript scripts on the G2, many Scriptable scripts included.
* [even-g2-js](https://github.com/mrahtz/even-g2-js) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-03 - Drives the G2 directly from a web page over Web Bluetooth with text, lists, and gestures.
* [Even Hub Starter Kit (Probe)](https://github.com/theJoshLucas/evenhub-starter) ⭐ 0 | 🐛 7 | 🌐 JavaScript | 📅 2026-02-15 - Zero-build probe harness that tests Even Hub SDK behavior on real hardware.
* [TailSight Device Preview](https://github.com/toriumib/tailsight-device-preview) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-29 - Browser simulator that previews HUD layouts for Rokid Glasses and Even G2.
* [g2-ui-builder](https://github.com/y-migita/g2-ui-builder) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-29 - Browser layout builder that places glasses containers and pushes them live to the simulator.
* [evenhub-simulator-nix](https://github.com/yvt/evenhub-simulator-nix) ⭐ 0 | 🐛 0 | 🌐 Nix | 📅 2026-08-11 - Runs the Even Hub simulator on NixOS.
* [even-deskless](https://github.com/penta2himajin/even-deskless) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2026-09-01 - Checks Even Hub plugins without glasses, to cover as much as possible in tests.
* [even-head-tilt-control](https://github.com/penta2himajin/even-head-tilt-control) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-01 - Tests head gestures such as nod, shake, and tilt as G2 input.
* [appsbridge](https://gitlab.com/homeauto.cc/appsbridge) - Off-SDK companion bridge that exposes the phone's magnetometer, step count, and GPS to the WebView over a local WebSocket, enabling compass and navigation apps.
* EvenMic - macOS tool that decodes the G2 microphone stream into a system-wide virtual microphone.
* [Even Hub docs: CLI](https://hub.evenrealities.com/docs/cli/index) - Documents the evenhub CLI for creating apps, packing builds, managing testers, and checking review status.
* [Even Hub docs: Enterprise SDK](https://hub.evenrealities.com/docs/enterprise/index) - Describes the Enterprise SDK for native Android, iOS, and Flutter apps that control G2 glasses.

## Protocol and Reverse Engineering

* [even-g2-protocol](https://github.com/i-soxi/even-g2-protocol) ⭐ 202 | 🐛 7 | 📅 2026-01-20 - Community effort to reverse-engineer the G2 BLE protocol, with characteristic mapping and Python examples.
* [g2-kit-unofficial](https://github.com/Commute773/g2-kit-unofficial) ⭐ 43 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-17 - Unofficial reverse-engineering kit including R1 ring authentication and 27 decoded protobuf definitions.
* [even-g2-protocol (ithinkthisiscool)](https://github.com/ithinkthisiscool/even-g2-protocol) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-10-13 - Implements the G2 BLE protocol in Python, with dashboard control and LC3 audio streaming.
* [even-g2-patched](https://github.com/cokeeffekt/even-g2-patched) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-03 - Patched Even app build that bypasses voice-intent interception so every G2 voice command routes to a custom AI agent.
* [open-g2-hub](https://github.com/ithinkthisiscool/open-g2-hub) ⭐ 8 | 🐛 0 | 🌐 Dart | 📅 2026-10-23 - Replaces the Even companion app offline and controls G2 widgets and the microphone stream.
* [men-g2-ble-gateway](https://github.com/gpsnmeajp/men-g2-ble-gateway) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-13 - Python gateway exposing the G2 over HTTP, WebSocket, and MCP, with a local browser UI.
* [Even-G2-RE](https://github.com/lonelyobserver0/Even-G2-RE) ⭐ 3 | 🐛 1 | 🌐 Java | 📅 2026-03-13 - Reverse-engineering effort covering the Even G2 app and its BLE system.
* [G2/R1 RE Tools and Guide](https://github.com/Commute773/g2-r1-re-tools-and-guide) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-15 - Collects guides, scripts, and protobuf schemas for reverse engineering BLE devices such as the G2 and R1.
* [Even G2 Controller App](https://github.com/fumicado/even-g2-flutter-app) ⭐ 2 | 🐛 0 | 🌐 Dart | 📅 2026-10-08 - Flutter app that scans for the G2 over BLE, runs the handshake and shows a teleprompter.
* [sybilsight-webflasher](https://github.com/AM-Guru/sybilsight-webflasher) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-11-23 - Analyzes G2 glasses and cases in a browser and offers a guarded case recovery console.
* [even-r1-m5stopwatch](https://github.com/timit3-github/even-r1-m5stopwatch) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2026-10-14 - Registers an M5Stack StopWatch in the Even app to send input events to the G2.
* [men-g2-atoms3-hello](https://github.com/gpsnmeajp/men-g2-atoms3-hello) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-05-25 - Arduino sketch for the M5AtomS3 that connects to the G2 over BLE, authenticates, and boots an Even Hub page.
* [OpenG2 Companion](https://github.com/mmirman/open-g2-companion) ⭐ 1 | 🐛 0 | 🌐 Swift | 📅 2026-07-28 - Local-first iOS companion app with a clean-room Bluetooth control layer for the G2.
* [eveng2-agent-poc](https://github.com/fuschini/eveng2-agent-poc) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-16 - Logs the G2 Add Agent requests and replies as an OpenAI-compatible server.
* [ffs-os](https://github.com/yonif8/ffs-os) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-16 - Clean-room Swift BLE driver and glasses OS for the G2, independent of the official stack.
* [g2\_helloworld](https://github.com/gpsnmeajp/g2_helloworld) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-05-10 - Minimal sideload app and WebSocket demo for the G2, useful as a bare-metal starting point.
* [narrowband](https://github.com/RaymonDev/narrowband) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-02 - Documents two simulator bugs in G2 raw image handling, with a one-command reproduction harness.
* [mentra\_g2\_helloworld](https://github.com/gpsnmeajp/mentra_g2_helloworld) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-24 - Shows a Python BLE sample app for the G2, based on the MentraOS implementation.

## Firmware and Emulation

* [g2flash](https://github.com/jimrandomh/g2flash) ⭐ 57 | 🐛 7 | 🌐 C | 📅 2026-11-23 - Custom firmware for the G2 that adds compressed image transfer, full-screen 576x288 single-image support, per-lens stereo output, and beeper tones, paired with matching custom send-side software.
* [evenRealities-openCFW](https://github.com/kalanihelekunihi/evenRealities-openCFW) ⭐ 35 | 🐛 0 | 🌐 C | 📅 2026-11-23 - Reverse-engineering documentation of the G2 firmware and BLE protocol, paired with a custom-firmware effort.
* [Blackwall](https://github.com/hmmhmmhm/blackwall) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-11-20 - Emulates the G2 firmware in Renode to inspect boot, events and display output.
* [even\_realities\_decomp](https://github.com/JohnRThomas/even_realities_decomp) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2026-11-06 - Reverse-engineering and decompilation of the first-generation G1 firmware.
* [Even Realities WebFlasher](https://github.com/AM-Guru/evenRealities-webflasher) ⭐ 16 | 🐛 1 | 🌐 JavaScript | 📅 2026-10-09 - Browser tool that analyses, backs up, and recovers the G2 case and glasses, and flashes signed firmware to the R1 ring over Web Serial and WebUSB.
* [Even G1 Firmware](https://github.com/JohnRThomas/Even-G1-Firmware) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2026-11-23 - Open-source replacement firmware for the G1 glasses that stays compatible with the official app.
* [G2 bootloader patch](https://github.com/drdaeman/g2-bootloader-patch) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2026-11-15 - Patches the G2 bootloader to run RAM programs over UART through the case pogo pins.
* [g2emu](https://github.com/ithinkthisiscool/g2emu) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-10-23 - Runs genuine G2 firmware in Renode and shows the display in a GTK app.
* [damage-wm](https://github.com/expectbugs/damage-wm) ⭐ 2 | 🐛 0 | 🌐 Kotlin | 📅 2026-11-26 - From-scratch window manager and compositor for the G2 on custom firmware, batching per-frame screen damage into a single BLE message, with a measured latency curve replacing the modeled numbers.
* [hardwareone](https://github.com/cadengithubb/hardwareone) ⭐ 2 | 🐛 2 | 🌐 C++ | 📅 2026-11-26 - Runs ESP32 firmware that drives the G2 lens as a full UI, with an optional R1 ring.
* [g2-thai](https://github.com/rayriffy/even-g2-thai) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-11-18 - Patches G2 firmware with a Thai bitmap font so the glasses render Thai text, with documented checksum verification and a rebase playbook.
* [b-d](https://github.com/b-d-io/b-d) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-14 - Provides firmware-exact G2 text layout tools, a lens simulator and an MCP server.
* [even-g2-rs](https://github.com/kenh0u/even-g2-rs) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-11-22 - Rust protocol stack, SDK, CLI, and HUD emulator for the G2 over BLE.
* [g2fast](https://github.com/jimrandomh/g2fast) ⭐ 0 | 🐛 0 | 📅 2026-06-29 - Unofficial firmware mod for the G2 that fixes its slow image handling.

## Apps - Productivity and Utilities

* [weather-even-g2](https://github.com/nickustinov/weather-even-g2) ⭐ 27 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-31 - Five-screen weather forecast driven by the free Open-Meteo API, with no backend server required.
* [even-stars](https://github.com/thibautrey/even-stars) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-01 - Star and sky viewer for the G2.
* [g2sidian](https://github.com/liyiyuian/g2sidian) ⭐ 5 | 🐛 4 | 🌐 Python | 📅 2026-10-14 - View and voice-capture Obsidian notes on the G2 through a self-hosted Tailscale backend.
* [even-kitchen](https://github.com/fabioglimb/even-kitchen) ⭐ 5 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-06 - Cooking assistant with recipes, step-by-step guidance, and timers on the lens.
* [Pulse](https://github.com/tntpsu/Pulse) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-09 - Multi-card personal dashboard with calendar, tasks, weather, and GitHub activity.
* [even-g2-calendar-companion](https://github.com/harikapadia999/even-g2-calendar-companion) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2026-02-22 - Next-event calendar notifications on the G2 over an optimized BLE path.
* [SalesEye](https://github.com/cphizz/SalesEye) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-03-03 - Real-time sales coach that detects objections and buying signals on live calls and surfaces cues on the lens.
* [wordpeek-g2](https://github.com/Alireza29675/wordpeek-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Reading companion that shows the meaning or translation of a spoken or typed word.
* [even-g2-obsidian](https://github.com/hiraghi/even-g2-obsidian) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-04 - Browse and edit an Obsidian vault on the G2 with live editor mirroring and IME composition support.
* [EvenAware](https://github.com/Xuefeng-Zhu/EvenAware) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-18 - Real-time notification hub aggregating alerts from multiple sources onto the G2.
* [flipctl](https://github.com/KuriGohan-Kamehameha/flipctl) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2026-10-10 - Mirrors a Flipper Zero on the G2 HUD with R1 ring control and a one-tap launcher.
* [Even-G2-Sentinel-Ops](https://github.com/btstevens1984az/Even-G2-Sentinel-Ops) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-09 - Fully offline IT security toolkit for the G2 and R1 ring with eight operator tools.
* [Even-R-Clock](https://github.com/Morfeussession2/Even-R-Clock) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-02 - Unified clock app combining stopwatch, countdown timer, and alarm.
* [Birdie](https://github.com/plungarini/birdie-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-14 - Real-time ambient bird identification that listens and names the species in your view.
* [Smokeless](https://github.com/plungarini/smokeless-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Cigarette tracker and quit companion logging each smoke with a tap on the frame.
* [even-g2-aviation-weather](https://github.com/MrMartellato/even-g2-aviation-weather) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-28 - Live METAR and TAF aviation weather on the G2.
* [bible-memory-g2](https://github.com/gn2b5gvcq5-tech/bible-memory-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - Scripture memory app with AI verse suggestions and fill-in-the-blank practice.
* [G2 Network Scanner](https://github.com/btstevens1984az/Even-G2-Network-Scanner) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-09 - Shows local network status on the G2 and alerts you when a new device joins the LAN.
* [Mudra Bridge](https://github.com/Martensiter/even-mudra-bridge) ⭐ 2 | 🐛 6 | 🌐 Python | 📅 2026-09-06 - Forwards Mudra Link wristband gestures to the G2 as navigation input.
* [Flipctl](https://github.com/P1R4N351/flipctl) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2026-10-10 - Mirrors a Flipper Zero on the G2 and launches saved signals with the R1 ring.
* [nutshell-browser](https://github.com/double-r-squared/nutshell-browser) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-04 - Browser extension that sends the current tab to the G2 for hands-free reading.
* [Nutshell for VS Code](https://github.com/double-r-squared/nutshell-vscode) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-03 - Serves your project docs to the G2 from a VS Code extension.
* [The Void](https://github.com/plungarini/the-void-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Shows a live global death counter from World Bank data, reset by tap.
* [Quietglass](https://github.com/samuelvoltarius/quietglass-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-02 - Collects 24 G2 apps that run on your own hardware without cloud or API keys.
* [Simple HUD](https://github.com/ryanadiaz/simple-hud) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-12 - Minimalist heads-up display showing clock, weather, and microphone level on the G2.
* [even-menu](https://github.com/ivlaevski/even-menu) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-23 - App launcher that manages and displays Even Hub apps by priority, configured from the phone.
* [x-for-even-g2](https://github.com/sommohapatra/x-for-even-g2) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-13 - Browse your X (Twitter) home timeline on the G2 with ring or touchpad navigation.
* [even-scribe](https://github.com/hiraghi/even-scribe) ⭐ 1 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-04 - Japanese note-taking app for the G2 with a kana-kanji IME.
* [SolarWorldClock](https://github.com/KamalQ/SolarWorldClock) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-08 - World clock for the G2 for tracking time across multiple zones.
* [notion-ultimate-brain-even-g2](https://github.com/hofstede-matheus/notion-ultimate-brain-even-g2) ⭐ 1 | 🐛 5 | 🌐 TypeScript | 📅 2026-11-24 - Ultimate Brain Notion template surfaced as a G2 interface.
* [2FA-for-G2](https://github.com/a-bissell/2FA-for-G2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - TOTP authenticator that runs on your face.
* [Sun-Scout-Pro](https://github.com/quemorez/Sun-Scout-Pro) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-08 - Cinematography sun-tracking HUD with solar position, golden-hour timing, and a rotating sun-path map.
* [Status Deck](https://github.com/bigdra50/even-status-deck) ⭐ 1 | 🐛 22 | 🌐 TypeScript | 📅 2026-07-02 - HUD showing time, battery, and optional PC or AI-tool status from a local server.
* [Applied Resonance](https://github.com/cwklurks/applied-resonance) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-10-04 - Learns how a healthy machine sounds through the G2 microphone and warns you when the sound changes.
* [Quick Tip](https://github.com/btstevens1984az/Even-G2-Quick-Tip-Calculator) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-09 - Calculates a tip and splits the bill by party size, with the result on the G2.
* [G2 Auth](https://github.com/ARCANGEL0/even-auth) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-13 - Shows TOTP codes on the glasses and imports accounts from Google, Proton, and other authenticators.
* [R1 Remote](https://github.com/AllCrumb/R1-Remote) ⭐ 1 | 🐛 0 | 📅 2026-11-03 - Controls a Windows 11 PC with swipe gestures from the Even R1 ring.
* [EMI Detector](https://github.com/RazBalin/Acoustic_EMI_Detector) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-16 - Uses the four-microphone array to show mains-frequency harmonics on the G2 display.
* [Scoreboard](https://github.com/Tylerthecreator32/scoreboard) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-22 - High-contrast game scoreboard with timer and period tracking for the G2.
* [StageCue](https://github.com/Xuefeng-Zhu/StageCue) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-18 - Imports PPTX files and shows speaker notes on the G2, controlled with the R1 ring.
* [even-playground](https://github.com/eretica/even-playground) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-16 - Shows a conversation partner's mood as a scouter-style gauge display on the G2.
* [Catch](https://github.com/linusho123/catch) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Holds names and promises from a conversation and shows them on the G2.
* [Pomodoro G2](https://github.com/marceloleda/pomodoro-even-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-12 - Runs a Pomodoro timer on the G2 with a compact corner view.
* [G2 Launcher](https://github.com/rjmacalino/g2-launcher) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-20 - Launcher app for the G2 built on the Even Hub SDK, with a developer guide in the README.
* [StepWise](https://github.com/robsartin/stepwise) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-18 - Guides cooking steps by voice with live timers on the glasses.
* [obsidian-atoms](https://github.com/taihartman/obsidian-atoms) ⭐ 1 | 🐛 64 | 🌐 TypeScript | 📅 2026-10-20 - Captures thoughts into Obsidian and files them as linked notes, with a G2 companion app.
* [glint-g2](https://github.com/EmCousin/glint-g2) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-10 - Holds the source code of the Glint plugin published on Even Hub.
* [even-pomodoro](https://github.com/shibomb/even-pomodoro) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-11 - Runs hands-free Pomodoro focus sessions on the G2.
* [even\_score](https://github.com/opinsky/even_score) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Live score tracker for the G2.
* [ER Markdown Notes](https://github.com/Katazui/ER-Markdown-Notes) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-09 - Markdown notes browsed on the G2 HUD and edited on the phone, stored in IndexedDB.
* [My Pomodoro](https://github.com/tarumzu/my-pomodoro-even-g2) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-31 - Pomodoro timer for the G2 with adjustable work and break cycles and session persistence.
* [NBA Pulse](https://github.com/Minna-Cross/even-nba-pulse) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-25 - Live NBA game tracker for the G2 with a play-by-play timeline and multi-game navigation.
* [even-prayer](https://github.com/ivlaevski/even-prayer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-20 - Prayer journal and daily-needs reflection app for the G2.
* [even-docs](https://github.com/Darielquinta/even-docs) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-30 - Local document editor for the G2 with multiple documents, version-history snapshots, and bridge-backed storage.
* [Bring-Lens](https://github.com/jappyjan/Bring-Lens) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-27 - Displays Bring! shopping lists on the glasses.
* [even-simple-calendar](https://github.com/r-tkbyc/even-simple-calendar) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-07-18 - Hands-free month-view calendar navigated entirely with the R1 ring.
* [even-simple-timer](https://github.com/r-tkbyc/even-simple-timer) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-07-18 - Hands-free countdown and count-up timer for the G2.
* [EvenG2\_GoogleKeep](https://github.com/TakaakiIchijo/EvenG2_GoogleKeep) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-24 - Projects Google Keep notes and checklists onto the G2 via a Flask and gkeepapi backend.
* [level-even-g2](https://github.com/nickustinov/level-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Spirit level for the G2.
* [even-traeger](https://github.com/tgarrell/even-traeger) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-11 - Monitor and control a Traeger pellet smoker from the G2.
* [fronius-even-g2](https://github.com/manuelwilhelmer/fronius-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-26 - Real-time Fronius Solar.web PV system data as a hands-free HUD.
* [evenG2](https://github.com/zijiebuzhuang/evenG2) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-24 - Collection of G2 apps including MoonWalker, a minimalist AR navigation app with dual map services.
* [Ethan HUD](https://github.com/EthanChouTW/ethan-hud) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-25 - Glance dashboard showing tasks, calendar, and exchange rates from an aggregator service, with notes on undocumented SDK behaviour.
* [Meater Cooks](https://github.com/trentfoley/even-g2-meater) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-07 - Live MEATER probe temperatures and cook progress on the G2 through a Cloudflare Worker relay.
* [Footy Live](https://github.com/johannboehme/footy-live) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-06 - Live AFL scores, fixtures, and the ladder on the G2.
* [Salah Companion](https://github.com/rmazumder/even-g2-salah-companion) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-23 - Five daily prayer times and the Hijri date on the HUD, computed on device.
* [Moon Phase](https://github.com/chrissantorelli/moonphase-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-28 - Current moon phase, illumination, and days to the next full or new moon.
* [LINE MTC](https://github.com/9vibes/LINE-MTC) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-04 - Keeps a shared aircraft running log with G2 phone companions.
* [Who's Who for Even G2](https://github.com/Bhanu047/whos-who-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Shows one card per person, with role and notes, so you can recall names at events.
* [Net Tools](https://github.com/BrokenFish/even-g2-nettools) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-11 - Network cheat sheets and a subnet calculator on the glasses.
* [Even Hub Pomodoro Timer](https://github.com/BugeshiC/evenhub-pomodoro-timer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-11 - Runs a Pomodoro focus timer on the glasses with adjustable length and tap controls.
* [Even Phone Companion](https://github.com/DeeJanuz/even-t3-android) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2026-09-06 - Android app that forwards selected notifications to the G2 for dictated replies.
* [EvenBetter Weather Test](https://github.com/JulianBeaulieu/evenbetter-weather-test) ⭐ 0 | 🐛 0 | 📅 2026-04-06 - Text-only weather forecast on the G2 using Open-Meteo, built to test the EvenBetter plugin system.
* [G2 CAD Viewer](https://github.com/M4k10HREM/g2-cad-viewer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-23 - Shows 3D CAD files as hidden-line drawings on the G2 and designs parts by voice with Claude and OpenSCAD.
* [Wingman](https://github.com/MickyG03/wingman) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-09 - Shows Google Calendar and Gmail on the G2 and drafts replies and invites with Gemini.
* [Rete](https://github.com/MysteryCoder456/rete) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-18 - Shows a person card and saved facts on the G2 during conversations.
* [HQ for Even G2](https://github.com/N1colov/hq) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-22 - Shows a Spotify bar and a daily task list with reminders, planned from Notion by an AI.
* [OurGroceries for Even G2](https://github.com/Thetechguru-net/g2groceries) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-04 - Shows OurGroceries shopping lists on the G2 and lets you check off items.
* [VisTwin G2 Plugins](https://github.com/VistwinDev/vistwin-g2-plugins) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-23 - Provides a Pomodoro timer and a voice mind-map app for the G2, built as a monorepo.
* [SlideCue](https://github.com/agoodbear/slidecue) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-04 - Shows Keynote speaker notes on the glasses and turns the page when slides change.
* [Noor Prayer](https://github.com/alhusariuk-cell/noor-prayer) ⭐ 0 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-02 - Shows prayer times, a next-prayer countdown, and the Hijri calendar on the glasses.
* [Noor Quran](https://github.com/alhusariuk-cell/noor-quran) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-01 - Shows the Quran in Madani Mushaf layout on the G2 using Arabic text rendered as image tiles.
* [Cue (alphagengar1)](https://github.com/alphagengar1/cue) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Shows three short networking cards on the G2 after you say a name, organisation, and role.
* [Haven](https://github.com/ayaanma/haven) ⭐ 0 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-18 - Texts your emergency contacts with your location after a countdown on the G2.
* [trellis-evenhub](https://github.com/benkolera/trellis-evenhub) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-31 - Shows your Trellis planner entry, focus timer and habit nudges on the G2.
* [evenlink](https://github.com/bropple/evenlink) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-25 - Streams a Flipper Zero screen to the G2 and maps R1 ring gestures to Flipper buttons.
* [us-clocks](https://github.com/cwkaatz/us-clocks) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-23 - Shows the time in six US time zones on the G2.
* [Tasks for Sunsama](https://github.com/gildror/even-sunsama) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-23 - Shows today's Sunsama tasks on the G2 and lets you check them off.
* [G2 Status](https://github.com/khj0209/even-g2-status) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-19 - Shows an always-on status HUD on the G2 that changes with time, place, and calendar.
* [EvenHUD](https://github.com/laolao91/EvenHUD) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-22 - Shows hydration, movement and day bars, timers and the next subway departure on the G2.
* [PL PROMPTER](https://github.com/maurricemccann/even-hub-teleprompter) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-16 - Shows a pasted script on the G2 in scroll, card or cue mode.
* [g2-glance](https://github.com/miinimal/g2-glance) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-14 - Shows your next action, deadlines and voice notes on the G2 and MentraOS glasses.
* [Hitme](https://github.com/mumoryan/hitme) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Shows motivational quotes on the G2 when you say Hey Even, hit me.
* [flipper-g2](https://github.com/pricem0595/flipper-g2) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2026-09-24 - Controls a Flipper Zero from the G2 through an Android bridge app.
* [EG2Apps](https://github.com/rod-git-hub/EG2Apps) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-12 - Two offline Even Hub apps: notes and checklists, and a talk presenter with a stopwatch.
* [PolLens](https://github.com/staude/pollens-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-31 - Shows six-type pollen forecasts for four days using Open-Meteo, with no API key.
* [even-g2-fft](https://github.com/watlablog/even-g2-fft) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-25 - Records glasses microphone audio and shows a live waveform and averaged FFT spectrum on the G2.
* [Smart Dive](https://github.com/zeke-japan/smart-dive-reinvent) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-07 - Browses AWS re:Invent sessions on the G2 and R1 ring using Amazon Bedrock.
* [GhostBuild](https://github.com/tanushsavadi/GhostBuild) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-10-18 - Gives hands-free help for build and repair tasks on the G2.
* [cf-connect-g2](https://github.com/walm/cf-connect-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-19 - Shows the Cloudflare Connect 2026 schedule on the G2.
* [g2-even-note-taking](https://github.com/NicChoo96/g2-even-note-taking) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-12 - Syncs pasted or spoken text from a web page to the G2 as sorted notes.
* [g2Rest](https://github.com/Boycham/g2Rest) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-18 - Shows restaurant floor tasks to servers on the G2; an LA Hacks project.
* [even\_g2\_keep](https://github.com/yuzuru0/even_g2_keep) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-17 - Shows Google Keep notes on the G2.
* [pacecue](https://github.com/tsuchiyatakahirolab/pacecue) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-06 - Shows one routine step at a time and recalculates time left when the user runs late.
* [g2-timer](https://github.com/John9927/g2-timer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-25 - Counts down preset times on the G2.
* [er-clock](https://github.com/Ertejeonline/er-clock) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-25 - Shows the current time on the G2 at a set position.
* [evenNotes](https://github.com/CesarPetrescu/evenNotes) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-23 - Shows real-time notes on the G2.
* [even\_g2\_glass\_ui](https://github.com/a44056283-maker/even_g2_glass_ui) ⭐ 0 | 🐛 3 | 🌐 Python | 📅 2026-05-05 - Provides an operations assistant that combines the G2, R1 ring, and phone camera.
* [anchor](https://github.com/rachelz2154/anchor) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-05-03 - Detects drifting focus and asks the wearer a short checkpoint question on the G2.
* [gapvision](https://github.com/futurebasicsrepo/gapvision) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-22 - Shows customer data to retail staff on the G2; a simulator-first prototype.
* [footnote](https://github.com/sohailgidwani/footnote) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-18 - Shows unfamiliar company terms and their owners on the G2.
* [dashboardplus](https://github.com/semokamo/dashboardplus) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-13 - Shows a dashboard on the G2 built with the Even Hub SDK.
* [g2-jw-daily-text](https://github.com/iantle/g2-jw-daily-text) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-29 - Fetches and shows a daily text on the G2, as a Finnish test app.
* [g2-keep](https://github.com/aramood/g2-keep) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-12 - Connects Google Keep to the G2 and R1 as an experiment.

## Apps - Reading and Reference

* [epub-reader-g2](https://github.com/chortya/epub-reader-g2) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-22 - Read EPUB ebooks on the G2 display.
* [powerslides](https://github.com/jappyjan/powerslides) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-24 - Control presentation slides and read speaker notes from the G2.
* [even-browser](https://github.com/fabioglimb/even-browser) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-14 - Web browser for the G2: enter a URL on your phone and read pages hands-free with scroll, link navigation, history, and bookmarks.
* [Glance](https://github.com/tntpsu/Glance) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-09 - Glasses web reader that renders clean article text from any URL across a three-layer source, article, and reader view.
* [evenBooks](https://github.com/KennyLowe/evenbooks) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-01 - Reads EPUB, text and PDF books on the G2 with gesture paging.
* [G2-Gmail](https://github.com/r-castelo/G2-Gmail) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-14 - Gmail reader for the G2.
* [g2-bridge](https://github.com/kvx17/g2-bridge) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-13 - Exposes a read-only Obsidian vault API so the Obsidian on G2 app can read notes.
* [Nutshell](https://github.com/refact0r/nutshell) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-19 - Reads PDFs, articles, and links on the G2 with AI-generated summaries and question answering.
* [whisprompt](https://github.com/ewfefrs/whisprompt) ⭐ 1 | 🐛 0 | 📅 2026-07-24 - Offline Android teleprompter that drives scripted text onto the G2.
* [G2-md-browser](https://github.com/r-castelo/G2-md-browser) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - Markdown file reader with folder browsing, search, and phone-managed favourites.
* [Obsidian on G2](https://github.com/luqezr/Obsidian-on-G2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-13 - Reads Obsidian notes with pixel-accurate pagination, fed by a companion Obsidian plugin over localhost.
* [Obsidian on G2 (Lawiak)](https://github.com/Lawiak/even-g2-obsidian) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-16 - Reads your Obsidian notes on the G2 through a small read-only backend that you host.
* [Obsidian on G2 (kvx17)](https://github.com/kvx17/Obsidian-on-G2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-13 - Reads Obsidian notes on the glasses with a phone companion and an Obsidian plugin.
* [even-web-reader](https://github.com/yamakake2580/even-web-reader) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-06 - Reads Hameln web novels on the G2 through a personal scraping backend.
* [matrix-g2](https://github.com/logicalpeyote777/matrix-g2) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-19 - Matrix client that reads chats on the HUD and dictates replies by voice through a Python bridge.
* [Even Browser (screen reader)](https://github.com/NoodleOfDeath/even-browser) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-03 - Web browser that linearises each page into an accessibility reading order and activates the focused link or button on a tap.
* [Glim](https://github.com/Roger1of1/Glim) ⭐ 0 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-15 - iOS app and Node backend pairing several G2 surfaces: calorie and heart-rate tracking, a novel reader, and ring-driven Google Slides control.
* [Even-LotH](https://github.com/sangularvilue/Even-LotH) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-01 - Reads Liturgy of the Hours prayers as a smooth-scrolling teleprompter.
* [Reader for Substack](https://github.com/CHL-work/substack-reader-for-evenhub) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-08 - Reads public Substack posts on the G2, one page at a time.
* [Orbital HUD](https://github.com/Zachary-ZiyueZhao/Orbital-HUD-for-Even-G2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-21 - HUD for the G2 with monochrome info cards, voice and location features, and a teleprompter.
* [Readwise for Even Realities G2](https://github.com/antonmogul/readwise-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-21 - Browses Readwise Reader items on the G2, with optional AI summaries and archive by hold.
* [WhisPrompt](https://github.com/ewfefrs/teleprompt) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2026-10-01 - Sends teleprompter scripts from an Android app to the G2 over BLE.
* [X for G2](https://github.com/ihorkatkov/x-for-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-03 - Reads the X For You and Following timelines on the G2, one post at a time.
* [arxeven](https://github.com/kg6-sleipnir/arxeven) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-06 - Lets you find and read arXiv papers on the G2, with an AI copilot.
* [Pageborne](https://github.com/mjtomei/pageborne) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-24 - Reads Markdown, text and PDF files on the G2 with voice questions.
* [teleprompter](https://github.com/robsartin/teleprompter) ⭐ 0 | 🐛 9 | 🌐 TypeScript | 📅 2026-07-11 - Scrolls teleprompter text on the G2.
* [biblia-even-g2](https://github.com/gilvancorrea/biblia-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-15 - Shows a paginated long-text reader on the G2, used for a Bible.
* [even-note-reader-gateway](https://github.com/j3tm0t0/even-note-reader-gateway) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-24 - Provides a CloudFront CORS proxy for a G2 note reader.

## Apps - Messaging and News

* [Sandevistan](https://github.com/hmmhmmhm/sandevistan) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-23 - Personal HUD with dashboard, map, weather, and news views, tested on physical hardware.
* [even-messages](https://github.com/thibautrey/even-messages) ⭐ 15 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-09 - Unified inbox client bringing messages from multiple services to the glasses.
* [rdt-even-g2](https://github.com/fuutott/rdt-even-g2-rddit-client) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-13 - Reddit client for the G2.
* [VOX](https://github.com/ablakateam/evenrealitiesG2) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-26 - Dictate and send SMS or email from the G2 through a self-hosted server with your own Twilio and mail accounts.
* [VozGram](https://github.com/AdalCast/vozgram) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-06 - Dictates and sends Telegram and WhatsApp messages by voice from the glasses.
* [even-g2-apps](https://github.com/mfethe1/even-g2-apps) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-15 - Collection of custom Even Hub SDK apps for the G2, including a Telegram HUD, calendar events, and dashboard notifications.
* [reddit-feed-even](https://github.com/plungarini/reddit-feed-even) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-30 - Full-featured Reddit client rendering feeds, posts, and comments through a Cloudflare Worker proxy.
* [MeshCore G2](https://github.com/haydenkz/meshcore-g2) ⭐ 2 | 🐛 3 | 🌐 Java | 📅 2026-11-24 - Shows MeshCore mesh radio messages on the G2 through an Android helper app.
* [Daily App](https://github.com/marcometz/daily-app-even-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Multi-screen G2 app with a dashboard, RSS reader, and shopping list, with persisted state and navigation.
* [NOSnieuws\_G2](https://github.com/SachaEpskamp/NOSnieuws_G2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-03 - Unofficial NOS (Dutch public broadcaster) news reader for the G2.
* [Send to G2](https://github.com/GenomiskDiagnostik/share-with-g2) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-29 - Sends shared text and links from Android to the G2 through a local inbox app.
* [Even Messenger](https://github.com/antonioeram/even-app-messenger) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-13 - Reads WhatsApp chats and replies by voice on the G2, using a self-hosted Go gateway.
* [Glance for iOS](https://github.com/toladele/glance-ios) ⭐ 1 | 🐛 0 | 🌐 Swift | 📅 2026-09-28 - Turns messages from your own backend into iOS notifications that the Even app mirrors to the G2.
* [even-matrix](https://github.com/narfman0/even-matrix) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-19 - Matrix messaging on the G2 with voice input and message-history browsing.
* [even-my-news-hub](https://github.com/r-tkbyc/even-my-news-hub) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-11-18 - Personal news hub for the G2, built as a dependency-free HTML, CSS, and JavaScript app.
* [TeleGlance](https://github.com/jalatif/even-g2-tele-glance) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-22 - Reads Telegram chats and sends short replies, with voice transcription that runs locally.
* [CyberNews](https://github.com/zakpatrik/CyberNews-evenrealities-app) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-26 - Merges four cybersecurity news feeds into one scrollable headline list.
* [Messages for Faceclaw](https://github.com/DeeJanuz/deej-faceclaw-messenger) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2026-09-24 - Signal and SMS inbox on the glasses through the Faceclaw SDK.
* [TG Glance (Gemmahadi)](https://github.com/Gemmahadi/tg-glance) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-19 - Shows Telegram chats on the glasses and sends AI-drafted replies.
* [TG Glance (Klowor2002)](https://github.com/Klowor2002/tg-glance) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-11-26 - Shows Telegram digests on the glasses and sends AI-drafted replies with one tap.
* [GeekReader KR](https://github.com/PDSAPWCV/g2-geekreader) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-18 - Reads GeekNews titles and Korean summaries on the G2, with save for later.
* [Alem dos Pontos (farol-noticias)](https://github.com/andrebadini/farol-noticias) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-12 - News reader for Brazilian outlets from RSS feeds, with voice search and offline favorites.
* [Field Mastery](https://github.com/ansarireza/Field-Mastery) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-11-26 - Builds a daily study and news digest for a research field and shows it on the glasses.
* [G2 Meldinger](https://github.com/herlids/g2-meldinger) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2026-11-17 - Shows SMS, Messenger, Snapchat, and Gmail notifications on the G2 with AI reply suggestions.
* [Inbox 30](https://github.com/tegar07257/inbox30) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-19 - Shows Gmail, Calendar and Tasks on the G2 for 30-second inbox triage.
* [Wee Hours](https://github.com/tianhaoz95/wee-hours) ⭐ 0 | 🐛 0 | 🌐 Swift | 📅 2026-10-15 - Newborn feed, diaper, and nap log with voice, watch, and G2 ring input.
* [even-inbox](https://github.com/byndcloud/even-inbox) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-16 - Shows a Telegram and WhatsApp inbox on the G2 through Evolution API.
* [even-g2-tabnews](https://github.com/atzingen/even-g2-tabnews) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-22 - Reads recent TabNews posts on the G2 with paginated pages.
* [bluersky](https://github.com/elijahsgh/bluersky) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-24 - Reads a Bluesky feed on the G2.

## Apps - Navigation and Transit

* [even-transit](https://github.com/langerhans/even-transit) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-21 - Public transit information on your glasses.
* [G2 Drive Nav](https://github.com/matthewmiglio/g2-drive-nav) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-07 - Turn-by-turn driving navigation for the G2 using Mapbox directions and live GPS.
* [RoadView-G2](https://github.com/double-r-squared/RoadView-G2) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-14 - Live WSDOT highway camera feeds on the G2, browsable by highway.
* [TideView](https://github.com/gabrielevierti/tideview) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-18 - Marine conditions HUD showing speed, course, wind, sea state, and weather from phone GPS and public forecasts.
* [EvenGo-Paris](https://github.com/Arkinos1/EvenGo-Paris) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Paris public transport, all modes in one app.
* [HUD-Navigation-Integration-Even-Hub](https://github.com/ArmasF31/HUD-Navigation-Integration-Even-Hub) ⭐ 2 | 🐛 1 | 🌐 Swift | 📅 2026-07-01 - Live turn-by-turn navigation and OBD-II vehicle metrics on the G2 via a Swift bridge.
* [Wondereye](https://github.com/cmdlabtech/Wondereye) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Landmark exploration app surfacing context about places around you.
* [ALPR Scout](https://github.com/bluboylou/alpr-scout) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-02 - Shows nearby public licence-plate camera locations from OpenStreetMap and helps prepare a DeFlock report.
* [wander](https://github.com/laolao91/wander) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-30 - Surfaces nearby points of interest on the G2.
* [World-Monitor](https://github.com/Danikrlop47/World-Monitor-EvenRealities-G2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-25 - 3D globe world-monitor demo for the G2.
* [MetroTracker](https://github.com/ltrademark/EvenG2-Metro-Tracker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-08 - Real-time DC Metro arrivals board on the G2 lens with a phone map companion.
* [even-simple-compass](https://github.com/r-tkbyc/even-simple-compass) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2026-07-18 - Minimal compass HUD for the G2.
* [apexline-g2](https://github.com/Apolly009/apexline-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-31 - Motorcycle-first navigation app for the G2.
* [Prague metro even hub](https://github.com/OndrejHlavacc/prague-metro-even-hub) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-24 - Shows live Prague metro departures on the G2 using the Golemio PID API.
* [departure](https://github.com/andoshin11/departure) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-03 - Shows the next train from your nearest Japanese station, using ODPT open data.
* [Drive HUD](https://github.com/khj0209/even-g2-HUD) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-20 - Shows speed, speed limit, camera alerts, and turn-by-turn directions on the glasses while driving.
* [ApexLine](https://github.com/romanseemann/apexline-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-31 - Motorcycle-focused turn-by-turn navigation on the G2 using OSRM routes.
* [Perron-NS](https://github.com/JustinasLa/perron-ns-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-07 - Dutch Railways (NS) journey planner for the G2 with live departure boards and station search.
* [JapanTrainTransit](https://github.com/TakaakiIchijo/JapanTrainTransit-EvenG2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-27 - Voice-activated Japan train routing for the G2, backed by the Transit API.
* [even-g2-geocache](https://github.com/marcometz/even-g2-geocache) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-26 - Geocaching on the G2 showing nearby caches, direction, and distance from the OpenCaching OKAPI.
* [Checkin](https://github.com/typester/even-swarm) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-09 - Foursquare Swarm check-in app that surfaces nearby venues on the G2.
* [EUC-G2-Hud](https://github.com/Jessica-Hunt/EUC-G2-Hud) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Electric-unicycle telemetry HUD showing real-time speed, battery, and ride metrics on the G2.
* [even-adventure-hud](https://github.com/myclark/even-adventure-hud) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-17 - Heads-up display for hiking and biking on the G2 with live GPS speed and distance.
* [G2BusTracker](https://github.com/jamie950315/G2BusTracker) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-04 - Real-time Taiwan bus arrivals on the G2 with location-based stop finding.
* [HUD-KVV-Depatures-G2](https://github.com/ArmasF31/HUD-KVV-Depatures-G2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-03 - Next Karlsruhe (KVV) tram departures from your nearest stop, located by GPS.
* [glass-transit-511](https://github.com/contextablemark/glass-transit-511) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-16 - SF Bay Area BART and Muni arrivals via the 511.org feed.
* [subwaylens](https://github.com/laolao91/subwaylens) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-20 - Real-time NYC subway arrivals on the G2.
* [Aviation HUD](https://github.com/cianfru/HUD) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-07 - Primary-flight-display view with ground speed, GPS altitude, and nearby diversion airports from a Garmin GLO receiver.
* [HSL Stops](https://github.com/Pihlapuro/HSL-stops-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-06 - Live Helsinki-region public transport departures for saved stops via the Digitransit API.
* [Peak Radar](https://github.com/kissyjpf/evenhub-peak-radar) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-29 - Nearby mountain summits with direction and distance, from OpenStreetMap and weather data.
* [Flight](https://github.com/karyzan/FlightG2) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-08-06 - Tracks up to three flights offline, with optional lookup by flight number.
* [SubwayQuickExit](https://github.com/KimUJeon/SubwayQuickExit) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-20 - Shows Seoul subway routes, best train car and live arrivals on the G2 display.
* [Cyberpunk HUD](https://github.com/MSPKS/Cyberpunk-HUD-for-EvenG2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Cyberpunk-style HUD with a street map, time, speed, heading, and battery levels.
* [Simple Transit](https://github.com/dragonautilus/simple-transit) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-11 - Shows nearby departures, a street map, and live journey progress on the G2 using Transitous data.
* [BART Go](https://github.com/grundysf/eveng2_bart_go) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 - Shows live BART departures on the G2 with station and direction filters.
* [Even-G2 Transit HUD](https://github.com/hongsan13/Even-G2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-22 - Shows which train to catch now on the G2, with walking time and transfers for Tokyo lines.
* [Waypoint](https://github.com/hridaya423/waypoint-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Gives London walking and bus guidance on the G2 with automatic boarding detection.
* [Bus Approach AR](https://github.com/iinuma/bus-approach-ar) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-25 - Shows next bus departures and approaching buses for Kawasaki bus stops on the G2.
* [G2 Peak View](https://github.com/iinuma/g2peakview) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-04 - Shows names and ridge lines of nearby mountains on the G2 based on your heading.
* [Even Nav](https://github.com/jiajiezhou95/even-nav) ⭐ 0 | 🐛 1 | 📅 2026-10-22 - Imports Google Maps links and shows routes, position, and instructions on the glasses.
* [RealMapCN](https://github.com/jiangmuran/amap-hud-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-05 - Navigation HUD using Amap that shows turn arrows, maps, and directions on the glasses.
* [ortsblick-g2](https://github.com/staude/ortsblick-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-31 - Lists nearby Wikipedia landmarks with distance and direction on the G2.
* [Train JP](https://github.com/ymkthr/train-jp) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-06 - Finds Japanese train routes by voice and shows them on the G2.
* [railglance](https://github.com/TakuroFukamizu/railglance) ⭐ 0 | 🐛 13 | 🌐 TypeScript | 📅 2026-10-07 - Shows train speed, route, direction, and next station on the G2 display.
* [navigateven](https://github.com/na2kera/navigateven) ⭐ 0 | 🐛 15 | 🌐 TypeScript | 📅 2026-08-16 - Plans public transit routes from the phone and shows them on the G2.
* [abfahrtszeit-g2](https://github.com/staude/abfahrtszeit-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-31 - Shows nearby public transit departures on the G2 from Transitous data.
* [alwaysontrack](https://github.com/bobydong/alwaysontrack) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Shows New York subway information on the G2 with an Android phone.
* [ar-glasses-gps-guidance](https://github.com/jordan-public/ar-glasses-gps-guidance) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-28 - Guides navigation on the G2 with the Even Hub SDK.
* [even-travel-companion](https://github.com/thibautrey/even-travel-companion) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-25 - Provides a travel companion app for Even Realities glasses.
* [moto-hud](https://gitlab.com/homeauto.cc/moto-hud) - Motorcycle heads-up display that scrapes turn-by-turn directions and media from the Android notification tray.

## Apps - Smart Home and Car

* [tesla-even-g2](https://github.com/nickustinov/tesla-even-g2) ⭐ 29 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-14 - Tesla vehicle status and controls.
* [even-home-assistant](https://github.com/maik353-debug/even-home-assistant) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-13 - Home Assistant dashboard and control from the glasses.
* [g2\_macrodroid](https://github.com/gpsnmeajp/g2_macrodroid) ⭐ 3 | 🐛 0 | 🌐 HTML | 📅 2026-05-11 - Trigger MacroDroid automations from the G2.
* [Homekit-Integration-Even-Hub](https://github.com/ArmasF31/Homekit-Integration-Even-Hub) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-01 - Apple HomeKit control via a local Mac bridge.
* [connect-remote](https://github.com/Jack-Berry/connect-remote) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-28 - Remote companion for Genesis, Kia, and Hyundai vehicles showing battery, range, and climate on the G2.
* [KlipKommander](https://github.com/doombadroid/KlipKommander) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-21 - Controls a Klipper 3D printer from the G2 through Moonraker.
* [alfred](https://github.com/maxglynjones/alfred) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-10-11 - English-butler assistant for the G2 and iPhone, hosted in your own Home Assistant.
* [Bambu G2](https://github.com/NishBuilds/bambu-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-28 - Bambu Lab 3D printer status and basic print controls through a self-hosted Linux bridge.
* [glass-car-dash](https://github.com/drrobotk/glass-car-dash) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Driving dashboard and media remote for the G2.
* [Tesla Even G2](https://github.com/sangularvilue/tesla-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-27 - Shows Tesla status and sends vehicle commands from the G2 through the Tessie API.
* [EvenSmartThings](https://github.com/dmyster145/EvenSmartThings) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-17 - Runs SmartThings scenes and controls devices from the G2.
* [lahacks](https://github.com/matheusfarocha/lahacks) ⭐ 0 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-18 - Shows live vehicle speed in miles per hour on the G2.
* [homeutilities](https://github.com/ggmark18/homeutilities) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-10-24 - Shows bus times and cat litter box status on the G2.

## Apps - Fitness and Health

* [G2 Gym App](https://github.com/r-castelo/G2_Gym_App) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-22 - Workout tracking app for the G2 via Even Hub.
* [rewind](https://github.com/nam-m/rewind) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Answers repeated questions from people with early dementia, using answers from their family.
* [even-realities](https://github.com/amirhayeri/even-realities) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-19 - Shows Apple Watch workout data on the G2 and starts Spotify playlists.
* [evenhub-running-tracker](https://github.com/kissyjpf/evenhub-running-tracker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28 - GPS and accelerometer running pace tracker for the G2.
* [golf-caddie-glasses](https://github.com/moisesvargasjr/golf-caddie-glasses) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-11 - Live round data and shot logging on the G2, paired with an iOS and watchOS tracker.
* [GolfCaddie](https://github.com/moisesvargasjr/golf-caddie) ⭐ 1 | 🐛 4 | 🌐 Swift | 📅 2026-11-22 - Tracks golf shots on iPhone and Apple Watch with a G2 companion display.
* [even-g2-meal-log](https://github.com/sora-uzu/even-g2-meal-log) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-26 - Shows remaining calories and macros for the day on the G2.
* [hevy-g2](https://github.com/Alireza29675/hevy-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-20 - Drives Hevy gym workouts from the glasses: pick a routine on your phone and see sets and reps on the display.
* [even-workout](https://github.com/fabioglimb/even-workout) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Guided workout tracking on the G2.
* [Glucose HUD for Even G2](https://github.com/Bhanu047/glucose-hud-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Shows continuous glucose readings from Libre, Dexcom, or Nightscout on the G2, with low predictions.
* [G2 Eye Trainer](https://github.com/danielnguyen/g2-eye-trainer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-13 - Guides short eye-movement exercises with moving targets on the G2.
* [EvenDex](https://github.com/kaloyansarafov/EvenDex) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-20 - Shows Nightscout glucose, trend graph and loop data on the G2.
* [Laborwerte G2](https://github.com/lollylan/G2-Laborwerte) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-02 - Quick reference for lab values on the G2, with severity ranges and red flags.
* [PL FOCUS](https://github.com/maurricemccann/focus-dots) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-16 - Ten vision-training drills for the G2, with four routines and phone-side settings.
* [Posture Cat](https://github.com/unicco/even-g2-posture) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-04 - Shows a cat on the G2 that reacts to your head posture using the built-in IMU.
* [Neck Stretch](https://github.com/yuk1-kondo/neck-stretch-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-06 - Guides seven neck stretches on the G2 using head tracking from the IMU.
* [locate-sound](https://github.com/KevinBalkoski/locate-sound) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-19 - Helps people with single-sided hearing loss find the direction of a sound.
* [set-rest-timer](https://github.com/h2ocloud/set-rest-timer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-10 - Times rest between workout sets on the G2.
* [er-bacpacer](https://github.com/Ertejeonline/er-bacpacer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-24 - Logs drinks and shows a countdown to the next one on the G2.
* [halo\_la](https://github.com/shreyaanchhabra/halo_la) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-25 - Assists people with dementia and their families through the G2; an LA Hacks project.
* [LA\_AI\_HACKS\_26\_TEAM](https://github.com/SamVD/LA_AI_HACKS_26_TEAM) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Helps people with aphasia find words on the G2; an LA Hacks project.
* [Cadence](https://github.com/nosmx/Cadence) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-11-16 - Coaches CPR practice on the G2 with a wrist sensor; not a medical device.
* [patientsync](https://github.com/nalostta/patientsync) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Records clinical notes and handoffs by voice on the G2.
* [Hong-Kong-AR-Glasses](https://github.com/lukas-schm/Hong-Kong-AR-Glasses) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-07 - Gives voice-first antibiotic decision support for ICU sepsis on the G2.
* [even-g2-fuel-timer](https://github.com/mohammedari/even-g2-fuel-timer) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-16 - Counts down the time between drinks to help the wearer pace alcohol.
* [even-g2-pickleball-score](https://github.com/behrad777/even-g2-pickleball-score) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-25 - Tracks pickleball score by side press and voice on the G2.

## Apps - Finance and Markets

* [even-market](https://github.com/fabioglimb/even-market) ⭐ 10 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-06 - Stock market quotes and watchlists on the glasses.
* [Even Balance](https://github.com/Morfeussession2/EVEN-G2-Balance) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-17 - Personal finance HUD tracking balances and spending categories on the G2.
* [even-g2-crypto-ticker](https://github.com/ARNLTony/even-g2-crypto-ticker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-30 - Live cryptocurrency price ticker for the G2.
* [evenhub-news-ticker](https://github.com/valve4/evenhub-news-ticker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-11 - Live financial news ticker for the G2.
* [Market Intel G2](https://github.com/gracereel/market-intel-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-15 - Live crypto, futures, stock, and oil prices with AI-generated market sentiment on the G2.
* [g2-currency-hub](https://github.com/evde-ga4/g2-currency-hub) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-04 - Currency converter for the G2.
* [MarketGlimpse](https://github.com/adamtorgerson/market-glimpse) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-20 - Shows exchange candlestick charts and prediction-market odds on the G2 on a timer.
* [HeadsUp Pay](https://github.com/jozzy001mail/headsup-pay) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-22 - Shows agent-payment alerts on the glasses and mirrors them to Telegram.
* [GlanceFi](https://github.com/naplex666/glancefi-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-18 - Shows live Hyperliquid prices and runs one-tap paper trades on the G2.
* [Market Glance](https://github.com/pikrimahardhika-alt/even-market-glance) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-20 - Shows live Coinbase BTC, ETH, and SOL prices on the G2 with price markers.
* [CryptoGlance](https://github.com/zynthlabsio/cryptoglance-even-realities) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-19 - Shows live crypto prices and alerts and runs paper trades on the G2.
* [tw-invoice-lottery](https://github.com/h2ocloud/tw-invoice-lottery) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-08-10 - Checks Taiwan uniform invoice lottery numbers hands-free on the G2.
* [even-crypto-hud](https://github.com/ragecoke1466/even-crypto-hud) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-23 - Shows a cryptocurrency watchlist on the G2.

## Apps - Voice and Speech-to-Text

* [stt-even-g2](https://github.com/nickustinov/stt-even-g2) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-20 - Real-time on-glasses speech-to-text via Soniox.
* [Taraweeh Companion](https://github.com/wasimlhr/taraweeh-companion-g2) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2026-11-22 - Recognises live Quran recitation and shows the matching Arabic text, transliteration, and translation.
* [pleno-live](https://github.com/plenoai/pleno-live) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-21 - Transcribes speech live and renders the text on the G2 through an Even Hub plugin.
* [soniox-translate](https://github.com/intelc/soniox-translate) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-14 - Real-time speech translation with live captions, powered by Soniox.
* [even-bridge](https://github.com/invendor/even-bridge) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-05 - Transcribes G2 speech and sends it on to Telegram, Slack, or Gmail.
* [ERGram](https://github.com/tiagodeoliveira/ERGram) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-10 - Server-free push-to-talk voice messaging to a Telegram group from the G2.
* [Cue (iuriiKolyadin)](https://github.com/iuriiKolyadin/lahacks) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-10-20 - Shows sound alerts such as sirens and doorbells, with direction, on the G2 for deaf users.
* [live-translation-local](https://github.com/kqb/live-translation-local) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-04-08 - Transcribes, translates and identifies speakers locally, with output to the G2.
* [G2 Captions](https://github.com/iamantonio/g2-captions) ⭐ 1 | 🐛 7 | 🌐 TypeScript | 📅 2026-07-20 - Accessibility-first real-time captioning prototype for the G2 using AssemblyAI and OpenAI Realtime.
* [VoiceID](https://github.com/haoyou-qi/voiceid) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-19 - Identifies who is speaking from G2 microphone audio and shows the name on the glasses.
* [Super Intelligence](https://github.com/mourad-ghafiri/evenrealities-g2-super-intelligence) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-29 - Translates live speech on the G2 and switches between meaning and intent modes.
* [relaysight](https://github.com/kickstartcrew/relaysight) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-16 - Provides an open-source, serverless G2 voice client for AI agents.
* [g2-reply-assist-backend](https://github.com/harbl/g2-reply-assist-backend) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-01 - Runs a self-hosted WebSocket backend for G2 Reply Assist with local Whisper and Ollama.
* [Convo Exchange](https://github.com/XXXStars0/STT_G2_Demo) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-15 - Real-time transcription and keyword detection on the G2 via Deepgram.
* [Soniox Note](https://github.com/kissyjpf/evenhub-sonioxnote) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-31 - Real-time Soniox transcription saved as a local voice note on the G1 and G2.
* [PitchBeam](https://github.com/btstevens1984az/Even-G2-pitchBeam) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-09 - Scrolls a teleprompter script on the lens and gives live speech-pace feedback from the phone microphone.
* [EVENCOMMS](https://github.com/9vibes/EVENCOMMS) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-28 - Sends wearer questions to a browser console and shows approved replies on the glasses.
* [Helix G2](https://github.com/FJiangArthur/Even-G2-Intelligence) ⭐ 0 | 🐛 10 | 🌐 TypeScript | 📅 2026-11-24 - Shows live captions, answers, summaries, and fact checks on the glasses, using your own AI keys.
* [Conversate Sync](https://github.com/GLOBIS-AI-Front/even-g2-conversate-sync) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-13 - Records G2 conversations, transcribes and summarizes them, and saves them to Obsidian.
* [Dot](https://github.com/ItsRuntimeException/even-g2-dot-assistant) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-30 - Voice assistant that wakes on 'Hey Dot' and answers through your own n8n workflow.
* [evenG2mount](https://github.com/LinYu-Ch/offline_g2_language_server) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-10-21 - Translates speech offline and sends captions to the G2.
* [Foundry Local XR](https://github.com/TakahiroMiyaura/FoundryLocalXR) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2026-10-22 - Runs on-device speech-to-text and chat on XR glasses, including a G2 sample.
* [Open Caption](https://github.com/alexmeowOvO/open-caption) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-17 - Shows live English captions on the G2, then replaces them with a short summary in your language.
* [Noor Recite](https://github.com/alhusariuk-cell/noor-recite) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-23 - Identifies the Quran ayah you recite with Groq Whisper and shows it in Mushaf layout.
* [G2 Offline Transcribe](https://github.com/amenbox/g2-offline-transcribe) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-25 - Transcribes speech offline on an Android phone and shows the text on the glasses.
* [Even G2 Soniox Captions](https://github.com/andjelaturkovic/even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-01 - Streams live Soniox speech captions to the G2.
* [Borderless](https://github.com/atlas-open-sources/borderless) ⭐ 0 | 🐛 0 | 🌐 Swift | 📅 2026-11-05 - Two-way spoken translation on an iPhone that also shows text on Meta Ray-Ban Display and G2 glasses.
* [Media Bridge Captions](https://github.com/capierc3/mentra-media-bridge) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-13 - Shows live captions of phone audio on the G2 through MentraOS.
* [g2-vi-en-realtime](https://github.com/carlmasters02/g2-vi-en-realtime) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - Translates Vietnamese speech to English on the G2 in about one second.
* [Thai Translator for Even G2](https://github.com/gyflea-web/even-g2-thai-translator) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-20 - Translates Thai speech to Korean subtitles on the glasses, using a Gemini API key.
* [Hear](https://github.com/lim0513/even-g2-plugin-hear) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-06 - Shows live captions on the glasses with optional translation through Soniox.
* [even-honyaku](https://github.com/oggunderscore/even-honyaku) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-04 - Translates live English and Japanese speech on the G2 using Deepgram.
* [Raphael](https://github.com/nekomoti22/Raphael) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-05 - Runs a real-time voice assistant with the Gemini Live API in a browser or on the G2.
* [even](https://github.com/Pitcha-ru/even) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-05 - Provides a text-only speech assistant MVP with configurable persona and models.
* [vrex-even](https://github.com/bkdev98/vrex-even) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-24 - Streams speech-to-text and AI answers to the G2, with local knowledge search and MCP.
* [glass-voice-agent](https://github.com/sternestehen/glass-voice-agent) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-21 - Transcribes a short spoken question and shows an AI answer on the G2.
* [g2-tutor](https://github.com/mkvjp/g2-tutor) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-05-19 - Transcribes conversation live on the G2 and explains terms with AI.

## Apps - Games and Learning

* [EvenChess](https://github.com/dmyster145/EvenChess) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-01 - Chess for the G2.
* [Paddle for Even G2](https://github.com/nickustinov/paddle-even-g2) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Plays paddle against an AI on the G2 with swipe controls.
* [snake-even-g2](https://github.com/nickustinov/snake-even-g2) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Classic Snake game.
* [tetris-even-g2](https://github.com/nickustinov/blocks-even-g2) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Tetris for the G2.
* [gloss](https://github.com/dxiv/gloss) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-13 - Type or dictate text and view it as a stack of American Sign Language slides.
* [EVEN-G2-Tamagotchi](https://github.com/Morfeussession2/EVEN-G2-Tamagotchi) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-11 - Tamagotchi-style virtual pet for the G2.
* [G2 Planetarium](https://github.com/kuma0128/planetarium-even-g2) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-15 - Shows a sky map for a chosen place and time on the G2.
* [arkanoid-even-g2](https://github.com/nickustinov/arkanoid-even-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Arkanoid brick-breaker for the G2.
* [G2 Flashcards](https://github.com/tomtau/g2-flashcards) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-28 - Flashcard app for the G2 with FSRS scheduling.
* [lingua-lens](https://github.com/kolife01/lingua-lens) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-20 - Ambient English coach that offers full phrases when you stall and stays silent when you don't.
* [Bible Memory](https://github.com/jodanis/bible-memory-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - Helps memorize Bible verses on the G2 with AI verse suggestions and fill-in-the-blank practice.
* [Bricks](https://github.com/nickustinov/bricks-even-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-19 - Plays an Arkanoid-style brick breaker on the G2.
* [Blackjack](https://github.com/plungarini/blackjack-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Strategy trainer with Hi-Lo card counting on the G2.
* [This Day](https://github.com/plungarini/this-day-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Shows one curated history event per day on the G2.
* [EvenSolitaire](https://github.com/dmyster145/EvenSolitaire) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-21 - Solitaire card game for the G2.
* [Lenski](https://github.com/Xuefeng-Zhu/Lenski) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-18 - Spaced-repetition flashcards for the G2 with Anki import, phone deck management, and AI deck generation.
* [Card Pack](https://github.com/tntpsu/CardPack) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-04 - Seven classic card games, including Hearts, Spades, and Cribbage, for the G2.
* [House Games](https://github.com/tntpsu/HouseGames) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-04 - Four casino games for the G2: Blackjack, Video Poker, Three Card Poker, and Roulette.
* [Even G2 Math Reader](https://github.com/ErikRusanov/Even-G2-Math-Reader) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-22 - Renders dense maths formulas as bitmaps and autoscrolls through a personal document library.
* [anki-glasses](https://github.com/kenjimax/anki-glasses) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-19 - Reviews Anki cards on the G2 and grades them with the R1 ring.
* [Anger Management](https://github.com/n-yokomachi/eg2-anger-management) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-06 - Counts down on the G2 and shows a random quote or stamp as a joke.
* [Date with a Cool Skeleton](https://github.com/n-yokomachi/eg2-date-with-cool-skeleton) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-05 - Draws a parody dating-screen display around whoever you look at.
* [AstroLens](https://github.com/shreySodhi/astrolens) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-03 - Draws constellations on the glasses as you point your head at the sky.
* [flappy-g2](https://github.com/200even/flappy-g2) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-03-13 - Flappy Bird clone for the G2.
* [Heads or Tails](https://github.com/dmyster145/EvenHeadsOrTails) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-23 - Animated coin-flip game for the G2 with a running tally counter.
* [HoppyRoads](https://github.com/dmyster145/EvenRoads) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-14 - Crossy Road-style crossing game for the G2 with deterministic text-first gameplay.
* [Vault Zero](https://github.com/fraugho/dungeon) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-18 - First-person dungeon crawler with textured raycast 3D rendering on the G2.
* [even-doom](https://github.com/narfman0/even-doom) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-04 - Doom E1M1 raycaster rendered as ASCII art on the G2.
* [EvenFoundryVTT](https://github.com/Aiacos/EvenFoundryVTT) ⭐ 0 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-31 - D\&D 5e on the G2 and R1 ring, synced with FoundryVTT via a phosphor-green tactical HUD.
* [darts-even-g2](https://github.com/JustinasLa/darts-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-07 - Darts checkout counter for the G2.
* [Quiz Flashcards](https://github.com/KamalQ/g2-flashcards) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-16 - Multiple-choice quiz flashcards with JSON, CSV, and plain-text deck import.
* [even-sliding-puzzle](https://github.com/r-tkbyc/even-sliding-puzzle) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-06-22 - Sliding puzzle in 3x3 and 4x4 for the G2.
* [even-japanese-map-quiz](https://github.com/r-tkbyc/even-japanese-map-quiz) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-08-04 - Silhouette quiz covering all 47 Japanese prefectures, played entirely with the R1 ring.
* [evenTaipan](https://github.com/opinsky/evenTaipan) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-12 - Taipan-style trading game for the G2.
* [kubectl Drill](https://github.com/hiimivantang/g2-kubectl-drill) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-04 - Spaced-repetition kubectl practice for CKA, CKAD, and CKS preparation.
* [WAD Player](https://github.com/jpneagle/WAD-Player-for-Even-G2) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-08-02 - Runs the DOOM-compatible PureDOOM engine on the phone and streams the display to the G2.
* [CubeNet](https://github.com/r-tkbyc/even-cube-net) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-09-23 - Cube puzzle played as its unfolded net, with faces turned by the R1 ring.
* [Rabbit Hole](https://github.com/Irfan-S/g2-rabbit-hole) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-17 - Turns a spoken topic into a Claude-written Wikipedia breakdown shown one word at a time.
* [EvenDominoes](https://github.com/LeonardoMendoncaDev/EvenDominoes) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-05 - Plays double-six dominoes against the CPU on the G2.
* [G2 Race Spotter](https://github.com/MS-aesthetic/g2-race-spotter) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-28 - Sends spotter messages from a pit-wall web app to a driver HUD on the G2 through a Cloudflare relay.
* [CS2 HUD](https://github.com/SmoothExec/cs2-hud) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-16 - Shows Counter-Strike 2 health, ammo, bomb, and score on the G2 using Valve game state integration.
* [Delve](https://github.com/Z-Gamez/delve-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-24 - Plays a voice-controlled D\&D roguelike on the G2 with an AI Dungeon Master.
* [BoneGlimpse](https://github.com/adamtorgerson/bone-glimpse) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-13 - Detects chords from live audio to teach keyboard playing on the G2.
* [Fantasy Sports for Even G2](https://github.com/ajmark/even-g2-fantasy-sports) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-18 - Shows Sleeper and Yahoo fantasy football scores on the glasses.
* [Treasure Hunt](https://github.com/alexdennis/even-first) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-25 - Runs a location-based treasure hunt that checks off real places by phone GPS.
* [G-kentei Quiz for Even G2](https://github.com/azek-dev/g-kentei-quiz-g2) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-11-21 - Runs a multiple-choice quiz for the Japanese G-kentei AI exam on the G2.
* [Parley](https://github.com/cosmicz/parley) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-05 - Coaches live French practice by suggesting the next phrase when you stall.
* [Micro Learning](https://github.com/ivlaevski/micro-learning) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Generates AI study cards from a topic and reviews them on the G2.
* [Even G2 FlightSim HMD](https://github.com/jpneagle/Even-G2-FlightSimHMD) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-01 - Shows Microsoft Flight Simulator 2024 flight instruments on the G2.
* [Even G2 Interactive Experience](https://github.com/katsuki-a/even-g2-sample) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - Interactive story prototype for the G2 with state restore and 1-bit image transfer.
* [G2 Study](https://github.com/lb2002/g2-study) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-24 - Turns lecture audio into flashcards and runs review rounds on the G2.
* [G2TD: Tower Defense](https://github.com/lukemeyer/g2td) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-17 - Plays a sci-fi tower defense game on the G2 with image tiles and text layers.
* [Bubbles](https://github.com/reseed-ops/bubbles-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-31 - Plays a sideways bubble-shooter game on the G2 with touchpad aiming.
* [G2 Showdown](https://github.com/rishi-zamvar/g2-showdown) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-02 - Plays Pokemon random battles on the G2 using the Pokemon Showdown engine.
* [Pokemon Showdown G2](https://github.com/rishi-zamvar/pokemon-showdown-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-23 - Plays Gen 9 random Pokemon battles on the G2, with an automated test harness.
* [Fighter HUD](https://github.com/staka121/fighter-simulator) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-30 - Shows an F-16 style heads-up display on the G2 driven by phone GPS and motion.
* [MindIOU](https://github.com/velamints2/mindiou) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-25 - Coaches voice explanations of AI-assisted work, with the G2 as a low-detail terminal.
* [adaptive-learning](https://github.com/Princelll/adaptive-learning) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-04-10 - Schedules spaced-repetition reviews on the G2.
* [encore](https://github.com/timothyouu/encore) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Tells beginner pianists what to practice after they play a short passage.
* [bluebook](https://github.com/rishabhroyy/bluebook) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-18 - Teaches hands-on tasks in short steps on the G2; an LA Hacks sponsor winner.
* [LanguageAdviser](https://github.com/RikuK0j1ma/LanguageAdviser) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-21 - Gives language advice on the G2, with README in five languages.
* [g2-wanikani-pocket](https://github.com/Darielquinta/g2-wanikani-pocket) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-30 - Runs WaniKani reviews and lessons on the G2 with a Bluetooth keyboard.
* [Electrosphere3D-Even-glasses](https://github.com/Ayrtonarc/Electrosphere3D-Even-glasses) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-12 - Plays a multiplayer aircraft detection game on the G2.
* [even-reality-lahacks](https://github.com/aman23ks/even-reality-lahacks) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Runs an emotional wellness pet on the G2; an LA Hacks project.
* [sake\_quest\_g2](https://github.com/mh-mobile/sake_quest_g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-11 - Runs a sake-themed quest game on the G2.
* [card-odds-coach](https://github.com/m1kewong/card-odds-coach) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-29 - Trains Blackjack basic strategy on the G2.
* [schmace-invuders](https://github.com/cnatale/schmace-invuders) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-24 - Plays a Space Invaders clone on the G2.

## Apps - Media and Music

* [DisplayPlusMusic](https://github.com/Oliemanq/DisplayPlusMusic) ⭐ 14 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-03 - Spotify now-playing viewer for the G2.
* [lyrics-glow](https://github.com/tntpsu/lyrics-glow) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-09 - Time-synced karaoke lyrics on the G2 display, backed by LRCLIB.
* [even-realities-lyrics](https://github.com/marioduartelanseros-eng/even-realities-lyrics) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-02 - Shows time-synced song lyrics on the G2.
* [even-g2-matrix](https://github.com/wmoto-ai/even-g2-matrix) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-23 - Matrix-style digital rain animation for the G2 display.
* [MuSe](https://github.com/ltrademark/EvenG2-Music-Search) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-26 - Ambient music identification on the G2 showing song, artist, and cover art with searchable history.
* [even-now-playing](https://github.com/r-tkbyc/even-now-playing) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-11-25 - Now-playing media display and ring control, paired with an Android media bridge.
* [orpheus-g2](https://github.com/L3G/orpheus-g2) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06 - Synced lyrics and now-playing for both Apple Music and Spotify.
* [even-g2-media-remote](https://github.com/aramood/even-g2-media-remote) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-11 - Media remote driven by the G2 and R1 ring, with an Android helper.
* [Even-G2-Guitar-Tuner](https://github.com/Comm4nd0/Even-G2-Guitar-Tuner) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-19 - Guitar tuner that shows detected pitch on the glasses.
* [spotify-g2](https://github.com/yannrapaport/spotify-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-14 - Spotify playback control plugin driven by the R1 ring.
* [HUD-Music-Integration-Even-Hub](https://github.com/ArmasF31/HUD-Music-Integration-Even-Hub) ⭐ 0 | 🐛 0 | 🌐 Swift | 📅 2026-07-01 - Apple Music now-playing display via a local Mac bridge.
* [Sudden Karaoke](https://github.com/inutano/sudden-karaoke) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-30 - Song recognition and time-synced karaoke lyrics on the G2 via the AudD and LRCLIB APIs.
* [g2-multi-instrument-tuner](https://github.com/r-castelo/g2-multi-instrument-tuner) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-22 - Cross-platform tuner for guitar, bass, and ukulele with alternate tunings.
* [Ambience](https://github.com/evcap/even-ambience) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-02 - Animated ASCII moodscapes for the G2, such as a fireplace, snow, and waves.
* [G2 MD3 Lyrics](https://github.com/LeiGuangTianYi/EvenG2-MD3Music-Lyrics) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2026-11-21 - Shows the current MD3Music song lyrics on the glasses in three highlighted lines.
* [Bad Apple for G2](https://github.com/Timothylock/even-bad-apple) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-04 - Plays the Bad Apple animation on the G2 as a stream of still frames.
* [Glass Shelf](https://github.com/UnfundedNag/glass-shelf) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-19 - Reads Calibre-Web EPUB books on the glasses with KOReader-compatible progress sync.
* [Instrument Tuner](https://github.com/VitasGuo/instrument-tuner) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-03 - Tunes guitar, ukulele, bass, and violin on the G2 with YIN pitch detection.
* [EvenLyrics Companion](https://github.com/litas615/evenlyrics-companion) ⭐ 0 | 🐛 0 | 🌐 Kotlin | 📅 2026-10-09 - Reads the playing song on Android and sends synced lyrics to the EvenLyrics plugin.
* [Riff](https://github.com/lolswirl/riff) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-31 - Shows Spotify now playing and gives remote controls on the G2.
* [Sheet Music for G2](https://github.com/lorenzwetscher-bit/sheet-music-lollo-g2) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-10 - Shows uploaded sheet music on the G2 with one to eight staff lines.
* [Headstock](https://github.com/smavromatis/headstock-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-06 - Guitar tuner that shows the note, cents offset, and turn direction on the glasses.
* [novel-reader-g2](https://github.com/Niwri/novel-reader-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-01 - Reads web novels in EPUB format on the G2.
* [even-g2-spotify](https://github.com/charliewinters/even-g2-spotify) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-24 - Shows the current Spotify track on the G2 and controls playback.
* [now-playing](https://github.com/aarcn/now-playing) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-07 - Shows what Spotify plays on the G2, with gesture controls.
* [invisible-tuner](https://github.com/typester/invisible-tuner) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-19 - Provides a chromatic tuner on the G2.
* [evenflow](https://github.com/bobbyhiddn/evenflow) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-05 - Draws full-screen animated patterns on the G2.
* [geek-radio-support](https://github.com/matsuikentaro1/geek-radio-support) ⭐ 0 | 🐛 0 | 📅 2026-08-27 - Gives support and contact details for GEEK Radio, a visual radio app for the G2.
* [displayplusmusic-hybrid](https://github.com/juanmotz/displayplusmusic-hybrid) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-11 - Shows a media viewer on Even Hub.
* [g2-pace-reader](https://github.com/jcpsimmons/g2-pace-reader) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-04 - Reads EPUB books on the G2 and keeps reading context.

## Apps - Streaming

* [EvenTwitchChat](https://github.com/kevin-huff/EvenTwitchChat) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-21 - Twitch chat client for the G2 with configurable display and username filtering.
* [g2-twitch-hud](https://github.com/tomsamwel/g2-twitch-hud) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-07 - Twitch chat HUD for outdoor IRL streaming with priority and alert filter modes.
* [Trickplayer](https://github.com/lukemeyer/trickplayer-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-12 - Shows Plex or Jellyfin trick-play frames and matching subtitles on the glasses.

## Apps - Coding Agents and Terminals

* [Pane](https://github.com/greenfield-inc/Pane) ⭐ 684 | 🐛 334 | 🌐 TypeScript | 📅 2026-11-26 - Shows agent notifications from many computers on the G2 and opens live terminals.
* [tellurion](https://github.com/steventsvik/tellurion) ⭐ 144 | 🐛 0 | 🌐 Zig | 📅 2026-11-25 - Shows a Mac terminal for AI coding agents on the G2 through a QR-paired Even Hub app.
* [CanvasTTY](https://github.com/howdeploy/CanvasTTY) ⭐ 141 | 🐛 9 | 🌐 TypeScript | 📅 2026-11-21 - Adds an Even G2 companion to an AI-agent desktop for terminal and agent workflows.
* [claude-code-g2](https://github.com/sam-siavoshian/claude-code-g2) ⭐ 42 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-17 - Run Claude Code hands-free from the G2 via voice and temple taps, billed against a Claude subscription.
* [OpenVide](https://github.com/open-vide/openvide) ⭐ 34 | 🐛 6 | 🌐 TypeScript | 📅 2026-07-06 - Remote control for Claude Code and Codex sessions with a G2 WebView client over an SSH and HTTPS bridge.
* [cc-g2](https://github.com/wmoto-ai/cc-g2) ⭐ 33 | 🐛 4 | 🌐 TypeScript | 📅 2026-11-24 - Control a Claude Code session from the G2: approve or deny prompts and enter voice commands.
* [G2CC](https://github.com/expectbugs/G2CC) ⭐ 27 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-14 - Direct-BLE Claude Code dispatch for the G2 with DJI two-mic noise cancellation and Parakeet ASR.
* [t3-even](https://github.com/Nsttt/t3-even) ⭐ 17 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-26 - Shows T3 Code agent threads on the G2 and lets you answer questions with the ring.
* [g2mirror](https://github.com/jimrandomh/g2mirror) ⭐ 12 | 🐛 2 | 🌐 Rust | 📅 2026-09-24 - Rust utility for mirroring a terminal session to the G2 display.
* [evenhub-app-ui](https://github.com/JustinasLa/evenhub-app-ui) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-03 - Even Hub design system packaged as a Claude Code skill, with color tokens, typography, layout rules, and 193 SVG icons.
* [Smart Glasses Skills](https://github.com/hinty-eu/smart-glasses-skills) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2026-11-15 - Provides agent skills that teach coding agents to build apps for G2 and other smart glasses.
* [even-better](https://github.com/pawaca/even-better) ⭐ 7 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-15 - Mirrors live Claude Code and Codex terminal sessions to the G2 over the Even Terminal protocol.
* [even-terminal-pi](https://github.com/lallenlowe/even-terminal-pi) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-16 - Runs the pi coding agent on the G2 as an Even Terminal provider.
* [HeadLenss](https://github.com/takashicompany/headlenss) ⭐ 6 | 🐛 9 | 🌐 TypeScript | 📅 2026-11-15 - Drive Claude Code on your PC by voice from the G2, plus tmux control from a phone browser.
* [polaris](https://github.com/luxdotdev/polaris) ⭐ 6 | 🐛 4 | 🌐 TypeScript | 📅 2026-11-24 - Includes a G2 extension for coding-agent sessions, approvals, and voice replies.
* [cos-glasses-server](https://github.com/ukaoma/cos-glasses-server) ⭐ 5 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-18 - Self-hosted heads-up-display server that drives the G2 from a local Claude Code CLI.
* [Hrdle](https://github.com/hrdle/hrdle) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-26 - Controls coding agents such as Claude Code and Codex from the G2 and a phone over Tailscale.
* [G2C (TMUXor)](https://github.com/liyiyuian/tmuxor) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Shows Claude Code and Codex sessions from Herdr on the G2 and continues them by voice.
* [tmux-on-g2](https://github.com/Tohoso/tmux-on-g2) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-19 - Streams a tmux pane to the glasses with double-tap voice input.
* [even-g2-hermes](https://github.com/wingk1314/even-g2-hermes) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-09 - Connects the G2 to Hermes agents through AI-proxy, Terminal Mode, and Even Hub plugin integrations.
* [Work Bench](https://github.com/aaronrau/workbench) ⭐ 4 | 🐛 0 | 🌐 Dart | 📅 2026-11-25 - Sends hands-free requests and approvals to Claude Code or Codex on a paired computer, using G2 audio and R1 ring gestures over native BLE.
* [even-terminal-opencode](https://github.com/WichardRiezebos/even-terminal-opencode) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-15 - Adapter that runs opencode sessions from OpenChamber in the official Even terminal mode.
* [EvenToggle](https://github.com/killmashinator/even-toggle) ⭐ 4 | 🐛 3 | 🌐 Makefile | 📅 2026-07-23 - macOS menu bar app that starts and stops the even-terminal server for Claude Code.
* [GlanceCode](https://github.com/sousyllc/glancecode) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-21 - Controls Claude Code, Codex and Gemini CLI sessions from the G2.
* [T3 Code G2](https://github.com/xrehpicx/t3-g2) ⭐ 4 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-28 - Shows pinned T3 Code threads on the glasses with streaming replies and voice messages.
* [claude-hud](https://github.com/m4rpqfbbc2-debug/claude-hud) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-15 - Voice-driven Claude Code terminal HUD for the G2.
* [quiet-terminal](https://github.com/hmmhmmhm/quiet-terminal) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-23 - Shows text typed on the phone on the G2 and links to a terminal, X timeline, and news.
* [EvenCode](https://github.com/TheOmran/EvenCode) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-27 - Voice-driven Claude Code conversations on the G2, including scrolling results and answering interactive prompts.
* [Agent Home](https://github.com/jalatif/even-agent-home) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-02 - Bridge server connecting multi-provider coding agents, such as Claude and Codex, to the G2.
* [Crossbar for Even G2](https://github.com/nicholpt/g2-crossbar) ⭐ 2 | 🐛 3 | 🌐 JavaScript | 📅 2026-11-08 - Shows a cross-bar menu that watches and answers coding agents in tmux.
* [Even Terminal Launcher](https://github.com/3mintimer/even-terminal-launcher) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-05 - macOS and Windows tray app for managing Even Terminal connection profiles and supervising agent sessions.
* [GitGlass](https://github.com/ARCANGEL0/GitGlass) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-21 - GitHub client for the G2 with dashboard, pull requests, issues, feed, and notifications.
* [g2-channels](https://github.com/Alireza29675/g2-channels) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-31 - Two-way terminal for Claude Code sessions: talk to a session and read its replies on the glasses.
* [muxway-glasses-even](https://github.com/notmarkopadjen/muxway-glasses-even) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Shows tmux panes on the glasses and lets you answer AI coding agents by voice.
* [terminal-mode-console](https://github.com/sunasaji/terminal-mode-console) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-04 - Drives one Claude Code, Codex or local LLM session from PC, phone, G2 and CLI.
* [remoteagent](https://github.com/appback/remoteagent) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-05 - Controls coding sessions from Telegram or a terminal, with an optional G2 API.
* [claude-fleet](https://github.com/answertree/claude-fleet) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-23 - Shows every Claude Code session on one G2 slide and takes answers from the ring.
* [PRLens](https://github.com/VTorres09/PRLens) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-22 - Reads your open GitHub pull requests on the G2.
* [even-g2-gsd-bridge](https://github.com/Luc3as/even-g2-gsd-bridge) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-11-11 - Views and steers live GSD-PI coding agents from the G2 over the even-terminal protocol.
* [G2 Claude Code](https://github.com/atillasaadat/g2_claude_rc) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-21 - Controls Claude Code from the G2: see status, approve tools and speak prompts.
* [omp-terminal](https://github.com/danielrod36/omp-terminal) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-13 - Runs oh-my-pi coding sessions on the G2 through the stock Even Terminal app.
* [glasses-g2](https://github.com/foncdev/glasses-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-12 - Controls Claude Code sessions on a Mac from the G2 touchpad.
* [T3 Even G2](https://github.com/michft/t3-even-g2) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-25 - Adds G2 and R1 ring control, thread picker and dictation to the T3 Code agent app.
* [float-code](https://github.com/palon7/float-code) ⭐ 0 | 🐛 4 | 🌐 TypeScript | 📅 2026-04-07 - Monitors and controls Claude Code sessions from the G2.
* [eveng2-remote](https://github.com/na2kera/eveng2-remote) ⭐ 0 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-20 - Sends approvals and voice commands from the G2 to cmux and coding agents on a Mac.
* [claudedeck](https://github.com/clausm0n/claudedeck) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-29 - Shows Claude Code sessions on the G2 and lets the user approve tool calls.
* [even-hub-sdk](https://github.com/jasprw/even-hub-sdk) ⭐ 0 | 🐛 0 | 📅 2026-08-26 - Teaches coding agents to build, test, package, and publish G2 apps with the Even Hub SDK.
* [even-codex](https://github.com/manif3station/even-codex) ⭐ 0 | 🐛 0 | 🌐 Perl | 📅 2026-06-02 - Bridges the G2 to a local Codex terminal session.
* [coding-room](https://github.com/shiron-dev/coding-room) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-18 - Provides clients and services for coding sessions, with a G2 app.
* [even-g2-codex-meter](https://github.com/hawkymisc/even-g2-codex-meter) ⭐ 0 | 🐛 3 | 🌐 JavaScript | 📅 2026-07-18 - Shows Codex usage limits and reset times on the G2.
* [hermiehub](https://github.com/b33fydan/hermiehub) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-24 - Talks to a Hermes or Codex agent hands-free through the G2.
* [even-terminal](https://github.com/viniciussouza/even-terminal) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-29 - Extends Even Terminal with extensible CLI integrations, including GitHub Copilot.
* [Even Hub docs: Claude Code guide](https://hub.evenrealities.com/docs/learn/claude-code) - Explains how to install the everything-evenhub plugin so Claude Code builds G2 apps.

## AI and Agent Integrations

* [openagi](https://github.com/spshulem/openagi) ⭐ 19 | 🐛 9 | 🌐 JavaScript | 📅 2026-11-26 - Hosts an always-on local agent with a G2 guide and voice supervisor.
* [Dots Bridge Kit](https://github.com/Corvelis/dots-bridge-kit) ⭐ 18 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-11 - Local Mac bridge that connects a ChatGPT Dot to apps, with a G2 app for voice and calls.
* [hermes-even-ai-plugin](https://github.com/kisaragi-mochi/hermes-even-ai-plugin) ⭐ 15 | 🐛 3 | 🌐 Python | 📅 2026-08-28 - Adds the G2 as a HUD front end for Hermes Agent through the Even App Add Agent feature.
* [Hermes G2 HUD](https://github.com/zd87pl/hermes-g2-hud) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-11 - Monitors Hermes agents and cron jobs on the G2 with voice commands.
* [Even Reality Memory System](https://github.com/Tej-Sharma/even-reality-memory-system) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-07-26 - Ambient AI memory for the G2 that captures thoughts, answers queries, and transcribes meetings with on-lens cues.
* [EvenHub-LocalLLM](https://github.com/axchristie/EvenHub-LocalLLM) ⭐ 12 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-05 - Voice-controlled local LLM interface for the G2, backed by open-webui over Tailscale.
* [OcuClaw for Hermes Agent](https://github.com/ocuclaw/ocuclaw) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2026-11-19 - Puts a Hermes agent on the G2 through an Even Hub app and a Hermes plugin.
* [Unofficial Even G2 Local Assistant](https://github.com/marienbaptiste/unofficial-even-g2-local-assistant) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-04-19 - Local-first voice assistant for the G2 with Whisper STT and dual-model routing between local Qwen and a cloud fallback.
* [Grok Bot G2](https://github.com/SergioAppen/grokbot-g2) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-06 - Talks to your Grok Bots from the G2 with push-to-talk voice.
* [even-g2-agentic-app](https://github.com/brianmatzelle/even-g2-agentic-app) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-05 - Agentic framework for the G2 with voice input, MCP tools, and interactive widgets on the display.
* [g2-claude-remote](https://github.com/ThatCrispyToast/g2-claude-remote) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-25 - Controls Claude remote-control sessions from the G2 with a HUD app, companion panel, and uvx-runnable bridge.
* [hermes-evenhub-bridge](https://github.com/huntsyea/hermes-evenhub-bridge) ⭐ 7 | 🐛 14 | 🌐 Python | 📅 2026-11-23 - Python adapter exposing the G2 as a Hermes agent platform.
* [Glint](https://github.com/redhelix/glint-public) ⭐ 7 | 🐛 0 | 📅 2026-02-21 - Streams OpenClaw AI answers to the glasses through a relay server.
* [Even-Voice-AI](https://github.com/MrScautHD/Even-Voice-AI) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-01 - Wake-word voice assistant using the browser's speech recognition, GPT-4o-mini, and streaming text-to-speech routed to the phone.
* [hermes-even-hub-app](https://github.com/huntsyea/hermes-even-hub-app) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-16 - G2 WebView client that drives locally running Hermes agents hands-free with voice and streaming responses.
* [Dot Link](https://github.com/YusukeIt0/dot-link) ⭐ 5 | 🐛 8 | 🌐 TypeScript | 📅 2026-11-26 - Connects a ChatGPT Dot to the glasses with location, route, and weather context.
* [Marginalia](https://github.com/benikigai/marginalia) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2026-10-20 - On-device voice agent that runs Gemma 4 on an iPhone and shows commentary on the glasses.
* [openclaw-even-g2-bridge-skill](https://github.com/dAAAb/openclaw-even-g2-bridge-skill) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-09 - Connects the G2 to OpenClaw agents through a Cloudflare Worker.
* [Cue](https://github.com/tntpsu/Cue) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-09 - Real-time conversation coach suggesting responses live, powered by Deepgram speech-to-text and Claude.
* [evenai-gemini-bridge](https://github.com/langerhans/evenai-gemini-bridge) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-03-04 - Rewrites the built-in Even-AI voice intents to Google Gemini, with request deduplication.
* [EDITH](https://github.com/aliabbasackkka-glitch/edith-g2) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-29 - Talks to any AI with your own key on the G2, in a browser or on a PC.
* [glasses-platform](https://github.com/100yenadmin/glasses-platform) ⭐ 4 | 🐛 13 | 🌐 Python | 📅 2026-11-21 - Puts a Hermes agent on G2 and other glasses with a gateway and Even Hub app.
* [even-jarvis](https://github.com/iDigz/even-jarvis) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-07 - OpenClaw-powered assistant with glasses-mic voice input, streamed responses, and image generation.
* [EvenG2-OpenAI-Agent](https://github.com/UniqueBanana78/EvenG2-OpenAI-Agent) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-06-23 - Connects the Even AI custom agent to the OpenAI API with a Python server.
* [rev/eyes](https://github.com/rube11/rev-eyes) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2026-11-08 - Gives a voice assistant on the G2 with memories, reminders, and watches synced to a web app.
* [openclaw-g2-hud](https://github.com/kqb/openclaw-g2-hud) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-08 - Heads-up display for monitoring OpenClaw agents, with voice capture and tap and scroll navigation.
* [evenai-anthropic-bridge](https://github.com/jase-perf/evenai-anthropic-bridge) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-03-08 - Replaces the built-in Even AI assistant with Claude via a small local server.
* [AR Vision](https://github.com/lonelyobserver0/even-ar-vision) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-14 - Android app that detects objects through the phone camera and shows labelled boxes and vision-LLM remarks on the G2.
* [EvenDash](https://github.com/beomjungil/EvenDash) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-31 - Self-hosted agent dashboard showing a clock and live agent feed cards from your own Cloudflare Worker.
* [xangi for G2](https://github.com/karaage0703/xangi-even-g2) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-10-25 - Connects the G2 to the xangi AI agent, with voice input transcribed by a local Whisper server.
* [ExEye](https://github.com/sng516157-web/ExEye) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-08 - Adds vision to the camera-less G2 by sending a frame from an ESP32 camera or webcam with a spoken prompt to a vision model.
* [g2-gateway](https://github.com/danielnguyen/g2-gateway) ⭐ 2 | 🐛 2 | 🌐 TypeScript | 📅 2026-11-25 - Gateway that connects a G2 app to an LLM memory stack with token-protected endpoints.
* [Even Realities x OpenClaw](https://github.com/mfethe1/even-realities-openclaw) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-15 - Collects G2 and R1 ring apps for OpenClaw agents, including Telegram and glucose displays.
* [Hermes G2](https://github.com/not-benny/hermes-g2) ⭐ 2 | 🐛 25 | 🌐 TypeScript | 📅 2026-10-30 - Runs a Hermes Agent on G2 glasses and documents the R1 ring health BLE protocol.
* [cervos](https://github.com/marienbaptiste/cervos) ⭐ 2 | 🐛 0 | 🌐 Dart | 📅 2026-03-29 - Provides an open-source, privacy-first AI assistant for the G2.
* [GlassAI](https://github.com/BondIT-ApS/glass-ai) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-15 - Voice-first assistant for the G2 bridging to a Hermes agent over an OpenAI-compatible API, with a companion phone app.
* [AI Sales Assistant](https://github.com/ObadaSayed/EvenRealities-AI-Sales-Assistant) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-22 - Browses Salesforce accounts and surfaces live meeting cues on the lens from speech transcription and GPT.
* [Muse Relay](https://github.com/3mintimer/muse-relay) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-24 - Sends chat messages and images to a Muse agent and shows its replies on the G2.
* [Even G2 Fact Checker](https://github.com/Jackmin801/even-g2-fact-checker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-09 - Fact-checks the last 30 seconds of speech when you tap the G2.
* [BUD (Bots Up Display)](https://github.com/cmdlabtech/bud) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Sends spoken tasks from the G2 to your Grok Bots.
* [even-discord-bridge](https://github.com/pilwonhur/even-discord-bridge) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-22 - Sends your speech from the G2 to a Discord AI assistant and shows the reply.
* [joatGlass](https://github.com/LopeWale/joatGlass) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-11-26 - Runs a personal AI assistant for the G2 on a Mac Studio, with an iPhone as relay.
* [openclaw-even-g2-node](https://github.com/solavrc/openclaw-even-g2-node) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-03 - Connects the G2 to a private OpenClaw Gateway.
* [spriite](https://github.com/VontariusF/spriite) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-15 - Controls an AI software factory by voice from the G2, with a self-hosted relay.
* [Cue (ambient memory)](https://github.com/abhishekj720/Cue-evenRealitiesG2) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-04-20 - Ambient social-memory app for the G2 that captures voiceprints and speaker context locally with Resemblyzer and Whisper.
* [G2 OpenClaw](https://github.com/kyle-deprow/g2_openclaw) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-20 - Bridges the G2 to a local OpenClaw agent via a PC gateway with Whisper STT and streaming responses.
* [completion-telegram-bridge](https://github.com/matsei-ruka/completion-telegram-bridge) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-14 - OpenAI-compatible completion API bridging the G2 to a personal Telegram agent.
* [even-deimos](https://github.com/dxiv/even-deimos) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-17 - Pick your AI provider, chat from your phone, and stream replies to a minimal lens HUD, with keys stored on-device.
* [Synthetic Multimodal Executive Agent](https://github.com/AbuElNour/ministerial-evenrealities-poc) ⭐ 0 | 🐛 11 | 🌐 TypeScript | 📅 2026-10-29 - Extracts commitments from synthetic meeting transcripts and sends them to the G2 through an Even Hub adapter.
* [Agent Relay](https://github.com/Blaine-Reid/agent-relay) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-22 - Self-hosted gateway that links the glasses to a local AI backend over Tailscale.
* [Focal](https://github.com/Borislo83/LAAIhacks) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-28 - Runs voice-driven Fetch.ai agents on web pages you view through the G2.
* [EvenG2-Muse-Hub-M5](https://github.com/GOB52/EvenG2-Muse-Hub-M5) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2026-11-12 - Sends Even AI questions to Muse through an M5Stack gadget and shows replies on the G2.
* [G2 Assistant (Lutreras333)](https://github.com/Lutreras333/g2-assistant) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-17 - Answers voice questions with Claude on the G2 and translates photographed signs.
* [Even G2 x Microsoft Foundry Voice Live](https://github.com/TakahiroMiyaura/eveng2-foundry-samples) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-19 - Streams G2 microphone audio to a Microsoft Foundry agent and shows the text reply.
* [Sergey AI](https://github.com/avgur264-bot/sergey-ai-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - Sends G2 voice questions through Deepgram to an LLM with tools and shows short answers.
* [JARVIS (even-edith)](https://github.com/cijamie/even-edith) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-02 - Voice assistant for the G2 and R1 ring that answers with Gemini and gives walking directions.
* [g2-vega-hud](https://github.com/danielnguyen/g2-vega-hud) ⭐ 0 | 🐛 3 | 🌐 TypeScript | 📅 2026-11-24 - Sends G2 speech through Deepgram and a gateway to a chat orchestrator and shows replies.
* [Claude for Even AI](https://github.com/dsdadsasdaaaaaaaa/claude-for-even-ai) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-15 - Answers Even AI questions with Claude through a Home Assistant integration.
* [CoachLens](https://github.com/galenjauss/coachlens) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-16 - Turns a spoken note from an instructor into logs, parent emails and plan changes.
* [sc-even](https://github.com/gcc3/sc-even) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-03 - Connects the G2 to the Simple AI CLI with speech input and lens replies.
* [G2 ChatGPT Relay](https://github.com/gugupig/g2-chatgpt-relay) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-16 - Talks to ChatGPT from the G2 by driving chatgpt.com on an Android phone.
* [G2 Assistant (khj0209)](https://github.com/khj0209/even-g2-assistant) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-25 - Shows Claude answers on the G2 with a small pixel bear mascot.
* [Pull Tab](https://github.com/liaonet/pull-tab-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-06 - Lets you talk to your Tab assistant from the glasses by triple-tap voice.
* [Even G2 Local Agent](https://github.com/marcosncosta1/even-g2-local-agent) ⭐ 0 | 🐛 0 | 📅 2026-06-06 - Runs a local voice agent for G2 notes and lists with an Ollama model.
* [Okou for G2](https://github.com/okou-ai/okou-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-26 - Syncs your Okou chat threads and events to the G2 with Clerk sign-in and Ably push.
* [Even G2 Agent Dashboard](https://github.com/rassi0429/even-agent) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-27 - Posts agent progress and custom screens from a PC server to the G2.
* [Genesis G2](https://github.com/rickndanger-ctrl/genesis-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-19 - Shows conversations from Agent Micro Controller on the G2 and follows live agent output.
* [EvenRealities-Claw](https://github.com/xesws/EvenRealities-Claw) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - Talks to a private agent from the glasses and lets any MCP client draw on the display.
* [Even G2 Personal Assistant](https://github.com/youssefelsane-hash/Even_G2-) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-22 - Describes what a camera sees on the G2 display, with head-gesture scrolling.
* [DadKnowsEVERYTHING](https://github.com/zwcheng/dadknowseverything) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-19 - Shows three answer options on the G2 when a child asks a question.
* [VeritasLens](https://github.com/madslundt/VeritasLens) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-29 - Listens to conversation context and shows silent hints on the G2.
* [mindmirror-app](https://github.com/jattbackup/mindmirror-app) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27 - Listens for 10 to 15 minutes and coaches the wearer toward set goals.
* [VaNiiBoard](https://github.com/gpsnmeajp/VaNiiBoard) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-08-23 - Provides a simple timeline front end and server for talking to AI agents.
* [evenclaw](https://github.com/abfshaal/evenclaw) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-04 - Sends G2 requests to a local OpenClaw through a small Mac proxy.
* [G2-Meets](https://github.com/VictorChenCA/G2-Meets) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-18 - Shows live conversation context and meeting recaps on the G2; an LA Hacks project.
* [cursor-cli-even-g2](https://github.com/tererun/cursor-cli-even-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-03 - Controls the Cursor CLI by voice from the G2, with an ACP server.
* [g2\_openclaw](https://github.com/p-kjdeprow/g2_openclaw) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-20 - Bridges the G2 to a local OpenClaw.
* [clawed.chat](https://github.com/isaiahb/clawed.chat) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-15 - Adds the G2 as a channel for OpenClaw messages.
* [friday-glasses](https://github.com/holydiscord801/friday-glasses) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-01 - Shows output of any AI agent on the G2 as an Even Hub plugin.
* [roku-ai](https://github.com/srimaan215/roku-ai) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-02-06 - Runs a privacy-first AI assistant on local models for the G2.
* [even-g2-memory-agent](https://github.com/melikcankarabulak/even-g2-memory-agent) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-21 - Serves an OpenAI-compatible endpoint with Supabase memory for Even AI.
* [openclaw-even-g2-voice-gateway](https://github.com/gideonheart/openclaw-even-g2-voice-gateway) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-04 - Accepts G2 audio, transcribes it, and sends it to OpenClaw.
* [g2-caduceus](https://gitlab.com/Qu4ndo/g2-caduceus) - FastAPI bridge connecting G2 voice input to any OpenAI-compatible chat endpoint (bring your own model).

## Related and Legacy (G1)

* [even\_glasses](https://github.com/emingenc/even_glasses) ⭐ 79 | 🐛 3 | 🌐 Python | 📅 2024-11-24 - Controls G1 glasses over BLE from Python, sending text and notifications.
* [Fahrplan](https://github.com/meyskens/fahrplan) ⭐ 50 | 🐛 3 | 🌐 C | 📅 2026-08-26 - Day-to-day life assistant for the G1 with notification mirroring, dashboard widgets, and voice control.
* [eveng1\_python\_sdk](https://github.com/binarythinktank/eveng1_python_sdk) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2025-12-06 - Controls G1 glasses over Bluetooth LE with a Python SDK.
* [awesome-even-realities-g1](https://github.com/galfaroth/awesome-even-realities-g1) ⭐ 35 | 🐛 0 | 📅 2024-12-07 - Companion list for the first-generation G1 glasses.
* [G1 Extended](https://github.com/LabbeSimon/G1_Extended) ⭐ 11 | 🐛 0 | 🌐 Dart | 📅 2026-10-14 - Telemetry-free Android client for the G1 with a reverse-engineered BLE protocol, custom HUD layouts, and external hardware integration.
* [Open G1 SDK](https://github.com/gabrielevierti/openg1-sdk) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-18 - Python SDK and simulator for building and testing G1 apps without the official app.
* [GeauxAiPrompt](https://github.com/GeauxAi-Labs/GeauxAiPrompt) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-06 - Voice AI assistant for the G1 glasses, built on MentraOS, with text-to-speech readback.
* [Helix](https://github.com/FJiangArthur/Helix-iOS) ⭐ 4 | 🐛 12 | 🌐 Swift | 📅 2026-10-21 - Native iOS companion for the G1 that transcribes conversation in real time and shows AI answers on the HUD.
* [Even G1 Java SDK](https://github.com/lohmuller/even-g1-java-sdk) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2025-06-01 - Unofficial Java SDK for G1 BLE control, with commands, queueing and gesture events.
* [Even Realities G1 Examples and Posts](https://github.com/hpssjellis/my-examples-and-posts-of-g1-even-realities-smart-glasses) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2025-09-18 - Field notes, hacks, and examples for the G1.
* [Nametag](https://github.com/ThatChocolateGuy/nametag) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-11-13 - MentraOS app for the G1 that recognizes people by voice and shows past conversation notes.
* [Robot Status](https://github.com/VR-Nima/Robot-Status) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-13 - Shows humanoid robot servo temperatures and battery level on G1 glasses through MentraOS.
* [even-utils](https://github.com/radioegor146/even-utils) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2025-11-28 - Reverse-engineering utilities and protocol experiments for the first-generation G1, including custom dashboard content.
* [Everse](https://github.com/knd8128/Everse) ⭐ 1 | 🐛 0 | 🌐 Swift | 📅 2026-08-19 - iOS companion for the G1 with a heads-up dashboard, quick notes, teleprompter, and navigation.
* [G1 Companion](https://github.com/hndrk-020/g1-whisper) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-02-21 - Android companion app for the G1 on a Samsung Galaxy Z Flip 7 with BLE and OpenAI widgets.
* [AR Spotify Lyrics](https://github.com/owensantoso/AR-spotify-lyrics) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-30 - Shows synced Spotify lyrics on G1 glasses with CJK romanization.
* [RSS News Reader](https://github.com/KonradBartlett/evenrealities-rss-reader) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-16 - RSS feed reader for the G1 with touch and gesture scrolling.
* [g1-ble-backend](https://github.com/SuperInstance/g1-ble-backend) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-20 - Scans, connects and renders text on G1 glasses over BLE, and runs an LLM pipeline for answers.
* [Clairvoyant (fractal-nyc)](https://github.com/fractal-nyc/context-clairvoyant) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-24 - Transcribes speech, detects questions and shows GPT-4o answers on the G1 through MentraOS.
* [Cue (nodesbio)](https://github.com/nodesbio/cue) ⭐ 0 | 🐛 31 | 🌐 TypeScript | 📅 2026-11-26 - Shows a scrolling teleprompter script on the G1 glasses from a phone app.
* [CodeWords AI Chat](https://github.com/playerclosed/g1-ai-chat) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-23 - Sends G1 voice input to OpenAI and shows the reply on the glasses through MentraOS.
* [Clairvoyant (with-context-engine)](https://github.com/with-context-engine/context-clairvoyant) ⭐ 0 | 🐛 3 | 🌐 TypeScript | 📅 2026-03-01 - Records speech, answers questions and shows results on the G1 display.

## Community

* [Shadow OS ICD-10](https://github.com/Blake402/shadow-os-icd10) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-12-09 - Streams ICD-10-CM diagnosis code lookups to the G2 using retrieval over 74,719 codes.
* [G2ModelViewer](https://github.com/gabrielevierti/g2modelviewer) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-18 - Renders OBJ and GLB 3D models in software to the G2 576x288 grayscale display.
* [Phase](https://github.com/plungarini/phase-even) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-30 - Shows physical, emotional and intellectual biorhythm cycles on the G2.
* [Even G2 Smart Classroom](https://github.com/havvk/even-g2-smart-classroom) ⭐ 1 | 🐛 0 | 🌐 Swift | 📅 2026-11-03 - iOS gateway that sends transcript text to the glasses over BLE, with Apple Watch gestures.
* [Taraweeh Companion for MentraOS](https://github.com/wasimlhr/mentra-taraweeh-companion) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2026-08-30 - MentraOS app that follows live Quran recitation and shows the current ayah.
* [even-g2](https://github.com/awakia/even-g2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-28 - Collects experimental G2 apps in one repository.
* [cyberspace-g2](https://github.com/ARCANGEL0/cyberspace-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-21 - Cyberspace social client with feed, chat rooms, mail, and voice replies on the glasses.
* [codrawer-bridge](https://github.com/Caerii/codrawer-bridge) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-25 - Streams reMarkable Paper Pro pen strokes live to the G2, phones, browsers, and agents.
* [Even\_G2\_OS](https://github.com/MiroslavProchazka/Even_G2_OS) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-31 - Collects several self-contained G2 projects, including a voice client for a self-hosted service.
* [G2 World Anchor Lab](https://github.com/atonalfreerider/g2-world-anchor-evenhub) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-19 - Even Hub companion that tests display calibration and image transport for a world-anchor prototype.
* [Visual Sound HUD](https://github.com/devbydaz/Visual-Sound-Hud-Even-Realities-G2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-06 - Classifies ambient sounds and shows visual cues on the glasses and a companion app.
* [V1 SmartGlass G2](https://github.com/girdav01/V1SmartGlassG2) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-06-24 - Shows Trend Vision One security alerts and top risks on the glasses by voice.
* [dc-connect-proxy](https://github.com/jaden-clovervnd/dc-connect-proxy) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-12 - Small Node proxy that lets the dc-connect glasses app read DCInside.
* [Heads-Up Digest](https://github.com/nocteaquilaeking/heads-up-digest) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-23 - Shows Telegram highlights and a read-only crypto watchlist on the glasses.
* [HUDeck](https://github.com/penta2himajin/HUDeck) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-04 - Provides head-gesture confirms, a glance-up deck and a recording indicator for the G2.
* [dorfkino-g2](https://github.com/staude/dorfkino-g2) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-27 - Shows a local cinema program with grayscale film posters on the G2.
* [TailSight](https://github.com/toriumib/tailsight) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-04 - Proof of concept for investigator tracking on Rokid and G2 with a SHA-256 evidence chain.
* [xr\_apps](https://github.com/englander1996-boop/xr_apps) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-24 - Holds a personal workspace of small G2 apps built with the Even Hub SDK.
* [HackUTD](https://github.com/matthewthomasbeck/HackUTD) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-08 - Shows rescue tasks to a first responder on the G2; a HackUTD project.
* [g2-app-demo](https://github.com/y16ra/g2-app-demo) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-20 - Collects practice and demo apps for Even Hub, starting from a Vite first app.
* [la-hacks-2026](https://github.com/lily1c/la-hacks-2026) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-18 - Streams drone views and AI analysis to G2 glasses for firefighters; an LA Hacks project.
* [eveng2s](https://github.com/festivixy/eveng2s) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-02 - Experiments with the Even Hub SDK.
* [connecter\_eveng2\_m5stack](https://github.com/englander1996-boop/connecter_eveng2_m5stack) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-23 - Shows M5Stack Core2 sensor values on the G2 lens as a technical test.
* [developersight](https://github.com/badkangaroo/developersight) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-06 - Collects a dated dataset of AI-glasses apps and developer tools, with a static site.
* [Even Realities Discord](https://discord.com/invite/AZc3by2v9J) - Official community where pilot developers share demos, feedback, and tips.
* [More Even Realities G2 Gems Built with Cursor](https://forum.cursor.com/t/more-even-realities-g2-gems-built-with-cursor/164252) - Shows three G2 apps built with Cursor and the Even Hub SDK.
* [Even Realities on taoofmac](https://taoofmac.com/space/hw/even) - Summarizes the G2 and links community example apps and tools.
* [g2-apps](https://github.com/studiotemple/g2-apps) - Holds a monorepo of Even Hub apps in Korean.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first, then open a pull request.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-26._
