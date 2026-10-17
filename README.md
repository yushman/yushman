### Hi, I'm Ivan Yushenkov 👋

Android engineer. I build developer tooling around three things I care about:
**AI agents** that actually help (and don't leak your data), **build & CI infrastructure** for large Android monorepos, and **architecture** that stays simple as it grows.

Day to day: Kotlin, Android, Gradle. On the side: Go, Rust, Python, Claude Code plugins and MCP servers.

#### 🤖 AI & agents

- [**droidjudge**](https://github.com/yushman/droidjudge) — adversarial tests for AI agents inside Android apps: plant a prompt-injection payload into a notification, clipboard or intent, then assert on the tool calls the agent made. Plain instrumented tests, runs in your CI.
- [**slimspec**](https://github.com/yushman/slimspec) — lightweight spec-driven development for Claude Code: explore → plan → apply → verify → ground, with mandatory red-green TDD and specs as module `CLAUDE.md` files.
- [**review-shift**](https://github.com/yushman/review-shift) — reviews your local branches overnight and leaves a report and an apply-able patch by morning. `pipx install review-shift`
- [**logcat-mcp**](https://github.com/yushman/logcat-mcp) — MCP server in Go that gives AI assistants access to Android logcat via ADB.

#### ⚙️ Build & dev tooling

- [**lightning**](https://github.com/yushman/lightning) — flaky-test radar, build telemetry, remote build cache and affected-module test selection for Gradle & Android monorepos. Self-hosted, one Rust binary, no build plugins.
- [**looqlog**](https://github.com/yushman/looqlog) — single-binary log viewer with a local web UI for files and live stdin (`adb logcat` included). Logs never leave your machine. `cargo install looqlog`

#### 🧩 Kotlin & IDE

- [**EntityIt**](https://github.com/yushman/EntityIt) — KSP processor that generates entities and two-way mappers for domain classes. On Maven Central.
- [**literate**](https://github.com/yushman/literate) — IntelliJ plugin that fixes text typed in the wrong keyboard layout (`Ghbdtn` → `Привет`). On JetBrains Marketplace.

#### 📫 Contacts

[Telegram](https://t.me/yush_man) · [Habr Career](https://career.habr.com/chagiman)
