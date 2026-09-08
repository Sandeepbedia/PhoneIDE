<p align="center">
  <img src="https://img.shields.io/badge/PhoneIDE-v1.0.0-blue?style=for-the-badge&logo=android&logoColor=white" />
</p>

<h1 align="center">📱 PhoneIDE</h1>

<p align="center">
  <b>The most advanced Android IDE that runs entirely on your phone.</b><br/>
  Write code. Build APKs. Run terminal. Deploy — all from your pocket. No PC needed.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Android-7.0%2B-brightgreen?style=flat-square&logo=android" />
  <img src="https://img.shields.io/badge/Architecture-ARM64-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/SDK-35-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Language-Kotlin-purple?style=flat-square&logo=kotlin" />
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-yellow?style=flat-square" />
</p>

---

## 🚀 What is PhoneIDE?

PhoneIDE is a **full-featured, production-grade Android development environment** that runs 100% on your Android phone. It's not a toy editor — it's a real IDE with a code editor, build system, terminal, file manager, and an **AI-powered coding agent** that can write, edit, debug, and build your code autonomously.

> Build real Android apps. On your phone. Anywhere.

---

## 📊 Feature Status

> **✅ Available Now** | **🔄 In Progress** | **📅 Coming Soon**

| Feature | Status | Description |
|---|---|---|
| 📝 Code Editor | ✅ Available | Syntax highlighting, 6 themes, find & replace, multi-tab |
| 🔨 Build System | ✅ Available | Gradle builds, error parsing, build remedies, APK signing |
| 🤖 AI Agent | ✅ Available | 6 modes, 15 tools, 4 providers, sandboxed permissions |
| 💻 Terminal | ✅ Available | Full Linux terminal (proot), multi-tab, background service |
| 📁 File Manager | ✅ Available | Project tree, search, workspace, file operations |
| 📦 SDK & Toolchain | ✅ Available | JDK, Gradle, Android SDK, Flutter, NDK, CMake management |
| 🎨 Theme Engine | ✅ Available | 6 editor themes, light/dark app, Material 3 |
| 📱 Onboarding | ✅ Available | Welcome wizard, environment picker, tool setup |
| 🔍 Project-wide Search | ✅ Available | Fuzzy file search + full-text content search |
| 📋 Project Templates | ✅ Available | Java, Kotlin, Compose, Flutter templates |
| 🧩 Workspace View | ✅ Available | Open files, recent projects, quick access |
| 📊 IDE Logs | ✅ Available | Full IDE log viewer with filters |
| 👤 User Profile | ✅ Available | Profile setup with avatar |
| 🔄 Git Clone | 🔄 In Progress | Clone repositories directly into the IDE |
| 🧪 Unit Testing | 🔄 In Progress | Run tests from IDE with results |
| 📐 Layout Preview | 🔄 In Progress | Preview XML layouts visually |
| 🗄️ Database Viewer | 🔄 In Progress | View & query SQLite databases |
| 📊 Performance Profiler | 📅 Coming Soon | CPU, memory, network monitoring |
| 🌐 Network Inspector | 📅 Coming Soon | HTTP requests, API debugging |
| 🎭 Emulator Support | 📅 Coming Soon | Run apps in virtual device |
| 📦 ADB Integration | 📅 Coming Soon | Full ADB commands from IDE |
| 🔗 Dependency Manager | 📅 Coming Soon | Visual Gradle dependency graph |
| 📝 Live Templates | 📅 Coming Soon | Code snippets & shortcuts |
| 🌍 Multi-language | 📅 Coming Soon | UI in Hindi, Spanish, Arabic, etc.
| 📱 Widget Support | 📅 Coming Soon | Quick actions from home screen |

---

## ✨ Features

### 📝 Code Editor
- Syntax highlighting for **Java, Kotlin, XML, Gradle, JSON, Dart**
- Line numbers, code folding, magnifier cursor
- Undo/redo with full history
- Find & replace with regex support
- Symbol input bar (brackets, arrows, operators)
- **6 built-in themes:** Default, Monokai, Dracula, GitHub Dark, One Dark, Solarized Dark & Light
- Pinch-to-zoom font resizing
- Multi-tab editing with session persistence

### 🔨 Build System
- One-tap **Gradle builds** (assembleDebug, assembleRelease, clean, test, lint)
- Real-time **error parsing** — click any error to jump to the exact line
- Smart **build remedies** — auto-suggests fixes for common build failures
- Background builds with foreground service (keeps running with screen off)
- APK signing, installation & sharing — all in-app
- Full **Gradle console** with scrollback

---

### 🤖 AI Agent — *The Most Powerful Feature*

PhoneIDE ships with a **fully autonomous AI coding agent** that can understand your project, write code, fix bugs, and verify its own work — all inside the app.

#### 🧠 6 AI Modes

| Mode | What it does |
|---|---|
| **💬 Chat** | Ask questions about your code. Read-only — nothing is changed. |
| **🤖 Agent** | Multi-step autonomous work: reads files, edits code, runs builds, verifies output. |
| **✏️ Edit** | Targeted code changes to the selection or open file. |
| **🐛 Debug** | Diagnoses build failures, applies fixes, re-runs the build automatically. |
| **📋 Plan** | Breaks work into a checklist of tasks before doing anything. |
| **📖 Explain** | Walks through how code works, step by step. |

#### 🛠️ 15 Professional Tools

The agent has access to **15 professional-grade tools** — just like a real developer:

| Tool | Capability |
|---|---|
| `read_file` | Read any file with line numbers |
| `list_files` | Browse project directories |
| `search_code` | Full-text search across all files |
| `search_files` | Fuzzy file-name search |
| `create_file` | Create new files with content |
| `edit_file` | Precise snippet-level edits (preferred) |
| `write_file` | Full file rewrites |
| `apply_patch` | Multi-file unified diffs |
| `delete_file` | Remove files & folders |
| `terminal` | Run shell commands in Linux environment |
| `run_build` | Trigger Gradle builds with click-to-fix errors |
| `diagnostics` | Read build errors with file & line info |
| `git_status` | Check modified/staged/untracked files |
| `git_diff` | View uncommitted changes |
| `open_in_editor` | Jump to a specific file & line in the editor |

#### 🔐 Sandboxed Permission System

The AI agent runs inside a **sandboxed permission system** — it cannot do anything without your approval:

- **Granular permissions** — control file read, file modify, file delete, terminal, and build access independently
- **Command risk classification** — every shell command is auto-classified as Safe / Build / Install / Git / Destructive before execution
- **Destructive command blocking** — `rm -rf`, `git reset --hard`, `curl | sh` etc. are always blocked without explicit user approval
- **Workspace trust** — untrusted projects require approval before running any build scripts
- **Auto-apply modes** — choose between Always Ask, Safe Auto-apply, or Full Auto-apply
- **Session-scoped grants** — permissions reset every session
- **Diff preview** — see exactly what will change before approving any edit

#### 🌐 Multi-Provider Support

Connect the AI to any LLM provider:

| Provider | Description |
|---|---|
| **OpenCode Zen** | Curated coding models (Claude, Qwen) with one key |
| **OpenRouter** | Hundreds of models behind one API |
| **Custom Endpoint** | Any OpenAI-compatible server |
| **Local Server** | llama.cpp, Ollama, LM Studio — runs on-device or LAN |

- **Streaming responses** — text appears token by token
- **Reasoning/thinking display** — see the model's chain-of-thought
- **Context-aware** — agent reads your project structure, file contents, and build output automatically
- **Session persistence** — conversations survive screen rotations and tab switches

---

### 💻 Terminal
- Full **Linux terminal** via proot (Ubuntu or Termux environment)
- Run `apt`, `gradle`, `flutter`, `git`, `npm`, and any CLI tool
- Multi-tab sessions — each running independently in the background
- Foreground service keeps shells alive with screen off
- Pinch-to-zoom, copy/paste, extra keys bar
- Start terminal from any project directory ("Open terminal here")

### 📁 File Manager & Workspace
- Visual **project tree** with file-type icons (SVG-rendered)
- **Project-wide search** — by filename (fuzzy) and by content
- Workspace view — see all open files, recent projects
- Create, rename, delete files & folders
- Clone Git repositories

### 📦 SDK & Toolchain Management
- One-tap install for **JDK, Gradle, Android SDK, Flutter, NDK, CMake**
- Automatic version management & environment variable setup
- Device compatibility checks (ABI, libc, API level)
- Storage analysis — see how much space each tool uses
- Remote catalog — new tool versions without app updates

### 🎨 Theme Engine
- **6 editor themes:** Default, Monokai, Dracula, GitHub Dark, One Dark, Solarized
- Light & dark app themes
- Material 3 dynamic colors
- Persistent theme preference

---

## 📋 Requirements

| Requirement | Minimum |
|---|---|
| **Android** | 7.0 (API 24) |
| **Processor** | ARM64 (arm64-v8a) |
| **Storage** | ~500 MB for tools & Linux environment |
| **RAM** | 2 GB recommended |

---

## 📥 Installation

1. Go to [**Releases**](https://github.com/Sandeepbedia/PhoneIDE/releases)
2. Download the latest APK
3. Enable **"Install from unknown sources"** if prompted
4. Install & launch PhoneIDE
5. Complete onboarding — choose your environment & install tools

---

## 🏗️ Architecture

```
PhoneIDE/
├── 🧠 AI Agent         → Autonomous coding (15 tools, 6 modes, 4 providers)
├── 📝 Code Editor      → sora-editor with syntax highlighting & themes
├── 🔨 Build System     → Gradle integration with error parsing & remedies
├── 💻 Terminal          → proot-based Linux (Ubuntu/Termux)
├── 📁 File Manager     → Project tree, search, workspace
├── 📦 Toolchain        → JDK, Gradle, SDK, Flutter, NDK, CMake management
├── 🎨 UI               → Jetpack Compose + Material 3
└── 🔧 Engine           → Kotlin coroutines, zero external HTTP library
```

---

## 🙏 Acknowledgements

PhoneIDE was built using [**AndroStudio**](https://t.me/AndroStudioOfficial) — an Android IDE for building Android apps on your phone.

### Open-Source Libraries

| Library | License | Purpose |
|---|---|---|
| [sora-editor](https://github.com/Rosemoe/sora-editor) | LGPL-3.0 | Code editor surface |
| [Termux Terminal](https://github.com/termux/termux-app) | GPL-3.0 | PTY + VT100/xterm rendering |
| [Apache Commons Compress](https://github.com/apache/commons-compress) | Apache 2.0 | Archive extraction |
| [XZ for Java](https://github.com/tukaani-project/xz-java) | Public Domain | Compression |
| [Coil](https://github.com/coil-kt/coil) | Apache 2.0 | Image & SVG loading |
| [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines) | Apache 2.0 | Async programming |
| [AndroidX / Jetpack](https://github.com/androidx/androidx) | Apache 2.0 | UI framework |
| [Material Components](https://github.com/material-components/material-components-android) | Apache 2.0 | Material Design |
| [Guava ListenableFuture](https://github.com/google/guava) | Apache 2.0 | Concurrency |

> Full license details in [`THIRD_PARTY_NOTICES.txt`](THIRD_PARTY_NOTICES.txt)

---

## 👨‍💻 Developer

<table>
  <tr>
    <td align="center" width="150">
      <a href="https://github.com/Sandeepbedia">
        <img src="https://github.com/Sandeepbedia.png" width="100" style="border-radius:50%"/><br/>
        <b>Sandeep Bedia</b>
      </a>
      <br/>Creator of PhoneIDE
    </td>
  </tr>
</table>

| | |
|---|---|
| 🐙 GitHub | [@Sandeepbedia](https://github.com/Sandeepbedia) |
| 💬 Telegram | [@phoneide](https://t.me/phoneide) |
| 📢 Channel | [PhoneIDE Channel](https://t.me/phoneide) |
| 📦 Repo | [Sandeepbedia/PhoneIDE](https://github.com/Sandeepbedia/PhoneIDE) |

---

## 📄 License

```
Copyright © 2025 Sandeep Bedia. All Rights Reserved.

This is proprietary software. No part of this software may be copied,
modified, distributed, sublicensed, or used in any form without the
prior written consent of the copyright holder.
```

See [`LICENSE`](LICENSE) for full details.

---

<p align="center">
  Built with ❤️ entirely on Android<br/>
  <sub>Powered by <a href="https://t.me/AndroStudioOfficial">AndroStudio</a></sub>
</p>
