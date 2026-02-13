# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

DaedalOS is a custom Linux operating system built from source using the [Linux From Scratch](https://www.linuxfromscratch.org/) methodology. Every package is compiled and configured by hand. The project is in early stages.

## Key Commands

```bash
# Verify host system meets LFS prerequisites
bash scripts/version-check.sh
```

There is no build system, test suite, or linter yet. Build instructions will be added as the project develops.

## Project Layout

- `scripts/` — Host system utilities (e.g., `version-check.sh`)
- `sources/` — Tarball and patch storage (git-ignored)
- `build/` — Build output (git-ignored)
- `tools/` — Cross-compilation toolchain (git-ignored)
- `logs/` — Build logs (git-ignored)

## Host Requirements

The build host must be Linux with a full compiler toolchain. Run `version-check.sh` to verify. The project is developed on Arch Linux with GCC 15.x and Linux kernel 6.18.x. See the README for the full version table.

## License

GPL-3.0. All contributions must be compatible with this license.
