# NagisinnraLinux


**NagisinnraLinux** is an ultra-lightweight, Debian-based custom Linux distribution built by 13-year-old student developer `nagisinnra`. First released in August 2026, it is specifically designed to revive older hardware and provide a snappy, minimal, yet fully functional desktop environment for daily use.

---

##  Key Features

- **Ultra-Lightweight Footprint**
  - **Idle RAM Usage:** ~**476 MB** (after boot)
  - **Minimal Disk Footprint:** ~**2.45 GB** (installed)
- **Out-of-the-Box Out-of-Box Japanese Support**
  - Prefitted with **fcitx5 + mozc** for seamless, low-overhead Japanese input processing.
- **Advanced Memory Optimization**
  - Powered by **zram** compression out of the box to guarantee smooth multitasking even on highly constrained hardware.
- **Production-Ready Cleanliness**
  - Stripped of bloatware and redundant `systemd` services to maximize battery life and CPU responsiveness.

---

##  Technical Specifications

| Component | Specification |
| :--- | :--- |
| **Base Distribution** | Debian GNU/Linux (Stable Core) |
| **Memory Management** | Optimized `zram` kernel swap compression |
| **Input Framework** | fcitx5 |
| **Input Method Engine**| mozc |
| **Target Architecture**| x86_64 (64-bit) |

---

##  Quick Start & Build

To clone the configuration and explore the optimization scripts:

```bash
git clone https://github.com/NagisinnraLinux.git
cd NagisinnraLinux
```

*For ISO downloads, please refer to our latest stable [GitHub Releases](https://github.com/NagisinnraLinux/releases).*

---

## Latest Update: v1.0.2 Stable
The latest **v1.0.2 stable** release squashes a critical bug from previous development builds where the live session environment defaulted to an unprivileged `guest` user instead of launching the proper localized desktop session. **Upgrading to v1.0.2 is highly recommended.**

---

## About the Developer

- **Handle:** nagisinnra
- **Age:** 13 (as of 2026)
- **Tech Blog:** [Zenn (@nagisinnra)](https://zenn.dev/nagisinnra) (Japanese)

> *"I started this project because I fell in love with the sheer satisfaction of stripping away bloatware until an OS boots at maximum velocity. NagisinnraLinux is my ongoing journey into the deep waters of low-level Linux systems, aiming to build the most efficient environment possible."*

---

##  License

This project is licensed under the **MIT License** - feel free to fork, mod, and distribute!
