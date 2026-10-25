# NagisinnraLinux


**NagisinnraLinux** is an ultra-lightweight, Debian-based custom Linux distribution built by 13-year-old student developer `nagisinnra`. First released in August 2026, it is specifically designed to revive older hardware and provide a snappy, minimal, yet fully functional desktop environment for daily use.

---

##  Key Features

- **Ultra-Lightweight Footprint**
  - **Idle RAM Usage:** ~**476 MB** (after boot) Memory usage may vary depending on hardware and running services.
  - **Minimal Disk Footprint:** ~**2.45 GB** (installed)
- **Out-of-Box Japanese Support**
  - Prefitted with **fcitx5 + mozc** for seamless, low-overhead Japanese input processing.
- **Advanced Memory Optimization**
  - Powered by **zram** compression out of the box to guarantee smooth multitasking even on highly constrained hardware.
- **Production-Ready Cleanliness**
  - Optimized default service configuration to maximize battery life and CPU responsiveness.

---

##  Technical Specifications

| Component | Specification |
| :--- | :--- |
| **Base Distribution** | Debian GNU/Linux (Stable Core)|
| **Memory Management** | Optimized `zram` kernel swap compression |
| **Input Framework** | fcitx5 |
| **Input Method Engine**| mozc |
| **Target Architecture**| x86_64 (64-bit) |

---

##  Quick Start & Build

To clone the configuration and explore the optimization scripts:

```bash
git clone https://github.com/nagisinnra/NagisinnraLinux.git
cd NagisinnraLinux
```

*For ISO downloads, please refer to our latest stable [GitHub Releases](https://github.com/NagisinnraLinux/releases).*

---
## Latest Update: v1.1.1 Stable
The latest **v1.1.1 stable** release introduces various stability improvements, bug fixes, and system refinements to provide a more reliable user experience. In addition, the project has begun a gradual transition away from Debian-branded visual elements in order to strengthen the NagisinnraLinux identity and respect Debian trademark guidelines. **Upgrading to v1.1.1 is recommended.**
---

## About the Developer

- **Handle:** nagisinnra
- **Tech Blog:** [Zenn (@nagisinnra)](https://zenn.dev/nagisinnra) (Japanese)

> *"I started this project because I fell in love with the sheer satisfaction of stripping away bloatware until an OS boots at maximum velocity. NagisinnraLinux is my ongoing journey into the deep waters of low-level Linux systems, aiming to build the most efficient environment possible."*

---

##  License

NagisinnraLinux includes software components licensed under different open-source licenses.

Project-specific configurations, scripts, and custom assets are licensed under the MIT License.
Debian packages and Debian-derived components remain licensed under their respective original licenses, primarily the GNU General Public License (GPL) and other Debian-compatible open-source licenses.
Please refer to each component's source code and package documentation for detailed licensing information.
