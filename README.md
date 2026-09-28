<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android" alt="Platform: Android" />
  <img src="https://img.shields.io/badge/Version-2.6.9-FFD93D?style=for-the-badge" alt="Version: 2.6.9" />
  <img src="https://img.shields.io/badge/Kotlin%20%7C%20Compose-7F52FF?style=for-the-badge&logo=kotlin" alt="Kotlin and Compose" />
</p><h1 align="center">PhoneIDE</h1><p align="center">
  A full-featured Android IDE that lives entirely on your phone —
  write, build, sign, preview and ship real Android apps on-device.
  No PC, no root, no cloud.
</p><p align="center">
  <a href="https://t.me/phoneide">
    <img src="https://img.shields.io/badge/Telegram-Join%20Us-1DA1F2?style=for-the-badge&logo=telegram" alt="Join on Telegram" />
  </a>
</p><!-- PhoneIDE Screenshot --><p align="center">
  <img src="./PhoneIDE.png" alt="PhoneIDE Screenshot" width="900" />
</p>---

✨ Features

📱 Projects & Build

- [x] Create new Android & Flutter projects from built-in templates
- [x] Open & manage existing Gradle projects on-device
- [x] One-tap Gradle builds with real-time build logs
- [x] Smart build-error detection with auto-remedy suggestions
- [x] Build, sign, inspect & share APKs directly in the app
- [x] Zip export — download your entire project
- [x] File tree explorer with file & content search
- [x] SDK manager screen — install build tools, NDK & more

📝 Editor & Language Support

- [x] Multi-file tabbed code editor with syntax highlighting
- [x] Multiple editor themes
- [x] Find & replace across files
- [x] Kotlin / Java language server
- [x] XML language support
- [x] Dart / Flutter language server
- [x] Code completion
- [x] Hover information
- [x] Diagnostics
- [x] Go-to-definition
- [x] Quick fixes
- [x] Jetpack Compose + XML layout live preview
- [x] Visual layout inspector

🐧 Linux Environment & Terminal

- [x] Ubuntu rootfs installed inside the app
- [x] Real Linux environment without root
- [x] Full terminal with PTY & xterm rendering
- [x] nano, vi, htop, git and other CLI tools
- [x] On-device toolchain manager
- [x] JDK, Gradle, Android SDK & Flutter management
- [x] Custom environment variables for builds & terminal

🤖 AI Agent

- [x] Project-aware AI assistant
- [x] Reads, edits & runs your code
- [x] 16 built-in agent tools
- [x] File operations
- [x] Build tools
- [x] Search tools
- [x] Apply-patch support
- [x] Auto bug-fix suggestions
- [x] Code generation
- [x] Session history
- [x] Full transcript export

🔐 Signing & Keys

- [x] Create JKS / keystore files inside the app
- [x] Import existing keystores
- [x] Sign APKs with your own keys
- [x] Resign APKs without a PC

🛠️ Developer Tools

- [x] Icon manager
- [x] Generate app & adaptive icons visually
- [x] String translator
- [x] Localization manager
- [x] IDE log viewer
- [x] Process diagnostics
- [x] In-app update checker

---

🚧 Roadmap

- [ ] Multi-device preview grid
- [ ] Dependency updater
- [ ] Plugin system
- [ ] Interactive live preview
- [ ] Additional language servers
- [ ] More project templates

«Suggestions for the roadmap are welcome on Telegram.»

---

🧩 App Modules

Module| Description
"editor"| Code editor, Gradle build runner, LSP completions & live preview
"project"| Templates, project generator, file tree, search & zip export
"terminal"| Ubuntu Linux guest, shell & rootfs installer
"toolchain"| JDK, Gradle, Android SDK & Flutter management
"lsp"| Language Server Protocol client
"ai"| AI agent, tools, LLM client, sessions & UI
"feature/*"| APK, JKS, icons, preview, settings, SDK, logs & setup wizard
"ui"| UI components and theming
"data"| Application data and state
"localization"| Localization and translations
"update"| Self-update dialog, manager & background checker

---

📦 Packages Used

- "androidx.compose.*" — UI framework
- "com.termux.termux-app:terminal-view" — terminal engine
- "io.github.Rosemoe.sora-editor" — code editor
- "io.coil-kt:coil-compose" — image loading
- "coil-svg" — SVG support
- "kotlinx-coroutines" — asynchronous operations
- "androidx.work" — background work
- "commons-compress" — archive handling
- "xz" — XZ compression support
- Bundled "libproot" native libraries — Linux guest without root

---

⚖️ Open Source Licenses

PhoneIDE is built on top of popular open-source projects.

Library| License| Usage
"Jetpack Compose" (https://developer.android.com/jetpack/compose)| Apache License 2.0| UI toolkit
"AndroidX" (https://developer.android.com/jetpack/androidx)| Apache License 2.0| Navigation, lifecycle & background work
"Material Icons Extended" (https://github.com/androidx/androidx)| Apache License 2.0| Application icons
"Kotlin" (https://github.com/JetBrains/kotlin)| Apache License 2.0| Programming language
"Kotlin Coroutines" (https://github.com/Kotlin/kotlinx.coroutines)| Apache License 2.0| Async runtime
"Coil" (https://github.com/coil-kt/coil)| Apache License 2.0| Image loading
"Termux" (https://github.com/termux/termux-app)| Apache License 2.0| Embedded terminal
"sora-editor" (https://github.com/Rosemoe/sora-editor)| GNU LGPL v2.1| Code editor

«🙏 PhoneIDE was built entirely on-device using AndroStudio IDE.»

---

⚠️ Limitations

- arm64-v8a devices only
- Android 7.0+
- Minimum API level: 24
- Linux guest and bundled native libraries currently ship for arm64

💾 Storage Requirements

What you plan to build| Approx. storage
Kotlin / Java / XML projects| ~5 GB
Flutter projects| ~7–8 GB
Full toolchain| ~12–13 GB

«Storage requirements may vary depending on installed SDKs, Gradle versions, NDK versions and project dependencies.»

---

📲 Installation

1. Download the latest PhoneIDE APK from the releases section.
2. Install the APK on an Android arm64 device.
3. Open PhoneIDE.
4. Complete the initial toolchain setup.
5. Create or open a project.
6. Start coding directly from your phone.

---

💬 Community

Have a bug, suggestion or feature request?

- Open an issue on GitHub
- Join the Telegram community
- Share your feedback and ideas

---

<p align="center">
  <b>⭐ Star the repo if PhoneIDE helps you build apps on the go!</b>
</p><p align="center">
  Made with ❤️ for developers who code everywhere.
</p>