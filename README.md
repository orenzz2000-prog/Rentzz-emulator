<!--
# SPDX-FileCopyrightText: Copyright 2025 Eden Emulator Project
# SPDX-License-Identifier: GPL-3.0-or-later

# SPDX-FileCopyrightText: 2018 yuzu Emulator Project
# SPDX-License-Identifier: GPL-2.0-or-later
-->

<h1 align="center">
  <br>
  <b>RENTZZ EMULATOR</b>
  <br>
  <sub>Experimental Nintendo Switch 2 emulator project</sub>
  <br>
</h1>

<p align="center">
  <b>Built for experimentation, performance research and open-source development.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-in%20development-1677ff?style=for-the-badge" alt="Project status: in development">
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-222222?style=for-the-badge" alt="Platforms">
  <img src="https://img.shields.io/badge/language-C%2B%2B-00599C?style=for-the-badge" alt="C++">
</p>

---

## About Rentzz

**Rentzz Emulator** is an experimental open-source emulator project based on the Eglantine codebase. The project aims to maintain and improve the inherited emulator architecture while exploring stability, compatibility and performance improvements.

Rentzz is currently under development. Features, compatibility and performance may change as the project evolves.

## Project goals

- Maintain a reliable and understandable codebase.
- Investigate performance bottlenecks through testing and measurement.
- Improve stability and game compatibility where possible.
- Keep development transparent and document meaningful changes.
- Preserve the licenses and attribution of upstream projects.

## Development

The project is written primarily in **C++** and uses **CMake** as its build system.

Before submitting changes:
1. Keep modifications focused and documented.
2. Build and test the affected components.
3. Include reproducible details for bug reports.
4. Do not remove upstream copyright notices or license headers.

## Building

Build instructions are available in the repository:

- [General Build Guide](docs/Build.md)
- [Tools](tools/)
- [User documentation](docs/user/README.md)

Build requirements and supported configurations may vary by operating system and by the current state of the codebase.

## Upstream acknowledgements

Rentzz is based on the Eglantine codebase and inherits work from projects including **Eden**, **yuzu** and **Sudachi**. We acknowledge the developers and contributors whose work made this codebase possible.

Rentzz is an independent development project and is not the official project of those upstream teams.

## License

This repository contains code distributed under the licenses specified by its original authors. The inherited codebase includes GPL-licensed components. Refer to the repository's license files and the SPDX headers in individual source files for the applicable terms.

Do not remove or alter original copyright and license notices when modifying inherited code.
