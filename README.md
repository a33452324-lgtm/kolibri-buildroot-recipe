# Kolibri-Hacker OS Buildroot Recipe

A custom, highly minimal Linux operating system built with Buildroot.
Inspired by the minimalism of KolibriOS but designed for hacking and network analysis.

## Features
- **Architecture:** x86_64
- **Interface:** Pure TUI (Terminal User Interface) using `tmux` and `ncurses`.
- **Hacking Tools:** Nmap, Tcpdump, Netcat, Aircrack-ng, OpenSSH, Python3.
- **Size:** Extremely small, aiming for under 100MB.

## How to Build
1. Download Buildroot (version 2024.02 or later).
2. Copy `configs/kolibri_hacker_defconfig` into the `configs/` directory of Buildroot.
3. Run `make kolibri_hacker_defconfig`
4. Run `make`
5. Find your OS image in `output/images/`.

*Note: This is a recipe for building a minimal kernel. It does not include a graphical desktop.*
