![Made for MX Linux](https://img.shields.io/badge/made%20for-MX%20Linux-blue?logo=debian&logoColor=white)
![Debian Based](https://img.shields.io/badge/compatible-Debian%20%2F%20Ubuntu-green?logo=linux&logoColor=white)
![Shell Script](https://img.shields.io/badge/script-Bash-lightgrey?logo=gnu-bash)
![License: MIT](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0-orange)

# ⚡ mxlpp – MX Linux Power Pack

`mxlpp` is a lightweight, terminal-based performance optimization toolkit for **MX Linux**, inspired by Garuda Linux's tuning philosophy — minus the eye candy.

It’s built for users who want **maximum speed and system responsiveness** on both old and modern hardware, without bloating the system.

---

## 🚀 Features

- ✅ Interactive CLI menu with user-friendly options
- ✅ ZRAM (compressed RAM swap) support with `lz4`
- ✅ Preload for faster app startup
- ✅ Tweak system swappiness for optimal RAM behavior
- ✅ Enable TRIM for SSD longevity
- ✅ Optional: install `TLP`, `Timeshift`, `htop`, `btop`
- ✅ Safe and reversible system changes
- ✅ Zero graphical dependencies – pure terminal

---

## 📦 Installation

To install `mxlpp` on **MX Linux** or any Debian-based system:

```bash
wget https://github.com/SarwerAhmedKhan/mxlpp/releases/download/v1.0/mxlpp-1.0.deb
sudo dpkg -i mxlpp-1.0.deb

