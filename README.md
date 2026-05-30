<div align="center">
  <img src="https://raw.githubusercontent.com/cosmix-app/.github/main/assets/logo.png" 
       width="120px" alt="Cosmix Logo"/>

  <h1>Cosmix</h1>

  <p>
    <b>Free, open-source streaming app for Android, Android TV & Windows.</b><br/>
    Powered by a community-driven extension system.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Platform-Android-green?style=flat-square&logo=android"/>
    <img src="https://img.shields.io/badge/Platform-Android%20TV-blue?style=flat-square&logo=android"/>
    <img src="https://img.shields.io/badge/Platform-Windows-blue?style=flat-square&logo=windows"/>
    <img src="https://img.shields.io/badge/License-GPL--3.0-red?style=flat-square"/>
    <img src="https://img.shields.io/badge/Built%20With-Kotlin-orange?style=flat-square&logo=kotlin"/>
  </p>
</div>

---

## What is Cosmix?

Cosmix is a free and open-source media streaming app built with 
Kotlin Multiplatform. It works on Android, Android TV, and Windows 
through a powerful community-driven extension system (.csx format).

No ads. No subscriptions. No login required.

---

## Features

- Extension system (.csx) — install sources from the community
- Android, Android TV & Windows support
- Built-in video player with subtitle support
- Cloudflare bypass support
- Download support
- Completely open source (GPL-3.0)

---

## Repositories

| Repository | Description |
|-----------|-------------|
| [cosmix](https://github.com/cosmix-app/cosmix) | Main app |
| [cosmix-gradle-plugin](https://github.com/cosmix-app/cosmix-gradle-plugin) | Gradle plugin for building .csx extensions |
| [cosmix-extension-template](https://github.com/cosmix-app/cosmix-extension-template) | Template for building your own extension |

---

## Build Your Own Extension

Anyone can build a Cosmix extension using our 
official template and CsxApi base class.

1. Fork [cosmix-extension-template](https://github.com/cosmix-app/cosmix-extension-template)
2. Extend `CsxApi()` and write your scraping logic
3. Push to GitHub — Actions will automatically build your `.csx` file

---

## Contributing

All contributions are welcome! Feel free to open issues, 
submit pull requests, or build extensions for the community.

---

<div align="center">
  <sub>Licensed under GPL-3.0 © 2026 Cosmix</sub>
</div>
