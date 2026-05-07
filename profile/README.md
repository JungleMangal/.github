# E-Segments

An independent software studio. We ship tools we wanted to exist.

[esegments.com](https://esegments.com) · [info@esegments.com](mailto:info@esegments.com)

---

## What we ship

### 🦜 [fang-kit](https://github.com/JungleMangal/fang-kit)
A developer's everyday toolkit. **70 self-contained tools** ("fangs")
for the small jobs that pile up across a working day — hashing,
encoding, formatting, certificate decoding, JSON shaping, network
math, time conversion, and 60-odd more. Available as a desktop app,
CLI, MCP server, and web UI — same tools, four surfaces.

### ⚔️ [git-talon](https://github.com/JungleMangal/git-talon)
A terminal-native git client built around how engineers actually
work. Real-time diffs, conventional commit enforcement, and an
optional AI assistant (KeenAI) that knows your conventions.

### 🐍 [cobra-term](https://github.com/JungleMangal/cobra-term)
A fast SSH and terminal app with a built-in secrets vault. Auto-locks
when you're idle, imports OpenSSH config, supports TOFU known-hosts.

---

## What's underneath

All three apps are built on **[enyra](https://github.com/JungleMangal/enyra)**
— our open-source Rust framework for tool-native applications. It
handles plugin loading, secrets, telemetry, and runtime adapters
for desktop (Tauri), CLI, MCP, and web. Plugins live in their own
repos: [enyra-git](https://github.com/JungleMangal/enyra-git),
[enyra-ssh](https://github.com/JungleMangal/enyra-ssh),
[enyra-shell-integration](https://github.com/JungleMangal/enyra-shell-integration).

The React/TypeScript half of the stack —
[ui](https://github.com/JungleMangal/ui),
[shell](https://github.com/JungleMangal/shell),
[code-editor-react](https://github.com/JungleMangal/code-editor-react),
[terminal-react](https://github.com/JungleMangal/terminal-react) —
is published to GitHub Packages and shared across all our apps.

---

## More coming

We build outside developer tooling too. New products land here when
they're ready.

---

*MIT or Apache-2.0 across the board. We accept contributions; see
each repo's CONTRIBUTING.md.*
