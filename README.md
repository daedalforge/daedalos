# DaedalOS

A custom operating system built from the ground up using [Linux From Scratch](https://www.linuxfromscratch.org/).

## Overview

DaedalOS is a Linux-based operating system assembled from source code, following the Linux From Scratch methodology. Every package is compiled and configured by hand, providing complete control over the system and a deep understanding of how a Linux OS works from the kernel up.

## Goals

- Build a minimal, reproducible Linux system entirely from source
- Maintain full control over every component in the toolchain
- Document each build step for transparency and reproducibility
- Create a lightweight, purpose-built operating system

## Prerequisites

- A Linux host system with a working compiler toolchain
- At least 10 GB of free disk space
- Basic knowledge of shell scripting and package compilation
- Refer to [LFS host system requirements](https://www.linuxfromscratch.org/lfs/view/stable/chapter02/hostreqs.html) for details

### Host System Versions (Arch Linux)

| Package | Installed | Minimum Required |
|---|---|---|
| Bash | 5.3.9 | 3.2 |
| Binutils | 2.45.1 | 2.13.1 |
| Bison | 3.8.2 | 2.7 |
| Coreutils | 9.10 | 8.1 |
| Diffutils | 3.12 | 2.8.1 |
| Findutils | 4.10.0 | 4.2.31 |
| Gawk | 5.3.2 | 4.0.1 |
| GCC | 15.2.1 | 5.4 |
| GCC (C++) | 15.2.1 | 5.4 |
| Grep | 3.12 | 2.5.1a |
| Gzip | 1.14 | 1.3.12 |
| Linux Kernel | 6.18.7 | 5.4 |
| M4 | 1.4.20 | 1.4.10 |
| Make | 4.4.1 | 4.0 |
| Patch | 2.8 | 2.5.4 |
| Perl | 5.42.0 | 5.8.8 |
| Python | 3.14.2 | 3.4 |
| Sed | 4.9 | 4.1.5 |
| Tar | 1.35 | 1.22 |
| Texinfo | 7.2 | 5.0 |
| Xz | 5.8.2 | 5.0.0 |

Run `bash scripts/version-check.sh` to verify your host.

## Project Structure

```
daedalos/
```

> Project structure will evolve as the build progresses.

## Building

> Build instructions will be documented as the project develops.

## License

This project is licensed under the [GPL-3.0](LICENSE).
