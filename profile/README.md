<div align="center">

[![Project Helix OS](https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=52&duration=3000&pause=2000&color=00CFFF&center=true&vCenter=true&width=800&height=100&lines=PROJECT+HELIX+OS)](https://git.io/typing-svg)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Mono&size=15&pause=1000&color=00CFFF&center=true&vCenter=true&width=650&lines=Built+for+power+users.;Minimal+bloat.+Maximum+control.;Open+source.+Zero+compromises.;Android+16+—+Helix+Edition.)](https://git.io/typing-svg)

<p align="center">
  <a href="https://t.me/ProjectHelixOSS"><img src="https://img.shields.io/badge/Telegram-Channel-0088CC?style=flat-square&logo=telegram&logoColor=white"/></a>
  <a href="https://github.com/ProjectHelixOSS"><img src="https://img.shields.io/badge/GitHub-ProjectHelixOSS-181717?style=flat-square&logo=github&logoColor=white"/></a>
  <br/>
</p>

</div>

---

## 🌀 What is Project Helix?

**Project Helix OSS** is a clean, performance-first custom Android ROM built on **AOSP/LineageOS**, made for users who want full control over their device without sacrificing stability. No bloat. No gimmicks.

---

## ✨ Why Helix?

<table>
  <tr>
    <td width="230px">⚡ <b>Performance Tuned</b></td>
    <td>Optimized builds, scheduler tweaks, and RAM management — every build is compiled for speed and smoothness</td>
  </tr>
  <tr>
    <td>🎨 <b>Tasteful Customization</b></td>
    <td>Status bar tweaks, QS customization, lock screen options, per-app volume, theme engine — powerful without being overwhelming</td>
  </tr>
  <tr>
    <td>🔒 <b>Security First</b></td>
    <td>Open source codebase — every commit is public, auditable, and transparent</td>
  </tr>
  <tr>
    <td>🧱 <b>Solid Foundation</b></td>
    <td>Built on LineageOS/AOSP — battle-tested, community-backed, with Helix's own enhancements layered on top</td>
  </tr>
  <tr>
    <td>🔓 <b>Fully Open Source</b></td>
    <td>Every line is public. Fork it, audit it, contribute to it — Helix belongs to the community</td>
  </tr>
</table>

---

## 📱 Supported Android Versions

<div align="center">

| Branch | Android | Status | Security Patch | Manifest |
|--------|---------|--------|---------------|----------|
| 🔵 **Lineage-23.2** | Android 16 | ![Active](https://img.shields.io/badge/Active-00CFFF?style=flat-square) | June 2026 | [Helix-v1](https://github.com/ProjectHelixOSS/android/tree/lineage-23.2) |

</div>

---

## 📊 At a Glance

<div align="center">

![Repos](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/orgs/ProjectHelixOSS&query=$.public_repos&label=Public+Repos&style=for-the-badge&color=00CFFF&labelColor=0D1117)
![Followers](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/orgs/ProjectHelixOSS&query=$.followers&label=Followers&style=for-the-badge&color=FF6C37&labelColor=0D1117)

</div>

---

## 🔗 Important Links

| Resource | Link |
|----------|------|
| 📦 Manifest | [github.com/ProjectHelixOSS/android](https://github.com/ProjectHelixOSS/android) |
| 💬 Telegram Channel | [t.me/ProjectHelixOSS](https://t.me/ProjectHelixOSS) |
| 💬 Telegram Chat | [t.me/ProjectHelixOSSChat](https://t.me/ProjectHelixOSSChat) |
| 🐙 GitHub Org | [github.com/ProjectHelixOSS](https://github.com/ProjectHelixOSS) |

---

## 🚀 Getting Started

<details>
<summary><b>🔧 Building from source</b></summary>

<br>

```bash
# Initialize the repo
repo init -u https://github.com/ProjectHelixOSS/android -b lineage-23.2

# Sync sources
repo sync -c --no-clone-bundle --no-tags -j$(nproc --all)

# Set up environment
source build/envsetup.sh

# Lunch your device target
lunch lineage_<codename>-bp4a-userdebug

# Build
mka bacon -j$(nproc --all)
````

> 💡 Recommended: Use `ccache` to speed up incremental builds. Set `export USE_CCACHE=1` and `ccache -M 50G` before building.

</details>

<details>
<summary><b>🛠️ Becoming a device maintainer</b></summary>

<br>

Want to bring Helix to your device? Here's what you need:

- A working, clean device tree based on AOSP/LineageOS
- Active testing and willingness to provide OTA updates

Reach out via [Telegram](https://t.me/ProjectHelixOSS) to get started.

</details>

<details>
<summary><b>🤝 Contributing code</b></summary>

<br>

Contributions are welcome! Here's the workflow:

1. Fork the relevant repository under [ProjectHelixOSS](https://github.com/ProjectHelixOSS)
2. Create a feature branch.
3. Commit with a clean, descriptive message.
4. Open a Pull Request — clearly describe what the change does and why

> Please do not submit cherry-picks without proper attribution. Include `Change-Id` and `Signed-off-by` headers where applicable.

</details>

---

---

## 🤝 Credits & Inspirations

<div align="center">

**Project Helix integrates and builds upon features from several open-source Android ROMs.**  
**We acknowledge and appreciate the work of these projects and their contributors.**

<br/>

🔹 **[DerpFest](https://github.com/DerpFest-AOSP)**  
Vendor base and core enhancements  

🔹 **[crDroid](https://github.com/crdroidandroid)**  
UI improvements and feature-rich framework additions  

🔹 **[AxionAOSP](https://github.com/AxionAOSP)**  
Customization features and Google Mobile Services integration  

🔹 **[LunarisAOSP](https://github.com/Lunaris-AOSP)**  
Additional UI/UX enhancements and unique features  

🔹 **[Evolution X](https://github.com/Evolution-X)**  
PixelProps and Pixel feature implementations  

<br/>

**...and many other open-source contributors across the Android community.**

</div>

---

## 💖 Support the Project

Project Helix is built by developers, for the community — entirely in free time. If you find it useful, consider starring the repo, sharing it, or contributing code.

<div align="center">

[![GitHub](https://img.shields.io/badge/Star%20on%20GitHub-ProjectHelixOSS-00CFFF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ProjectHelixOSS/android)

</div>

---

<div align="center">

### 🌀 Thanks for being part of Project Helix!

**Clean. Fast. Yours. 🚀**

*Built with passion from India — for Android users everywhere.*

</div>
