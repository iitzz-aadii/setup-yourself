# Setup Yourself 🚀

A curated collection of essential apps, tools, and activation scripts to quickly set up a fresh Windows machine.

> ✅ **Every tool and script listed here has been personally tested and verified by me.** I use these on my own systems, and I've made sure they work safely and reliably. This is the exact setup I follow whenever I configure a new Windows machine!

---

## 📋 Table of Contents

- [Quick Start](#-quick-start)
- [Essential System Tools](#-essential-system-tools)
- [Browsers](#-browsers)
- [Productivity](#-productivity)
- [Download Managers](#-download-managers)
- [System Utilities](#-system-utilities)
- [Development Tools](#-development-tools)
- [Media & Entertainment](#-media--entertainment)
- [File Sharing & Compression](#-file-sharing--compression)
- [Network & VPN](#-network--vpn)
- [Graphics & Drivers](#-graphics--drivers)
- [How to Run Scripts](#-how-to-run-scripts)
- [Troubleshooting](#-troubleshooting)
- [Credits](#-credits)

---

## ⚡ Quick Start

> [!IMPORTANT]
> **All PowerShell scripts must be run as Administrator!**
> 
> Right-click on the Windows Start menu → Select **"Terminal (Admin)"** or **"PowerShell (Admin)"**

---

## 🖥️ Essential System Tools

### Windows 11
**What is it?** The latest operating system by Microsoft with a modern design, improved performance, and better security features.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download Windows 11](https://www.microsoft.com/en-us/software-download/windows11) |

#### Windows Activation Script
Activates Windows 11 to unlock all features and remove the watermark.
```powershell
irm https://get.activated.win | iex
```

---

### Windows Utility by Chris Titus Tech
**What is it?** A powerful all-in-one tool that helps you debloat Windows (remove unnecessary pre-installed apps), optimize performance, apply privacy tweaks, and install common software with one click.

```powershell
iwr -useb https://christitus.com/win | iex
```

---

## 🌐 Browsers

**What are browsers?** Browsers are applications that let you access websites and surf the internet.

| App | Download Link | Description |
|-----|---------------|-------------|
| **Google Chrome** | [Download Chrome](https://www.google.com/chrome/what-you-make-of-it/) | The most popular browser by Google. Fast, syncs with your Google account, and has tons of extensions. |
| **Brave Browser** | [Download Brave](https://brave.com/download/) | Privacy-focused browser that blocks ads and trackers by default. Faster browsing with less data usage. ⭐ |

> [!TIP]
> **Brave** is highly recommended for its built-in ad blocker and privacy features. You won't see annoying ads on websites!

---

## 📝 Productivity

### Microsoft Office 365
**What is it?** The essential office suite that includes **Word** (documents), **Excel** (spreadsheets), **PowerPoint** (presentations), **Outlook** (email), and more. Required for almost all office and school work.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download Office 365](https://www.microsoft.com/en-us/microsoft-365/download-office#download) |

#### Office Activation Script
Activates Office 365 to unlock full features without subscription.
```powershell
irm https://get.activated.win | iex
```

---

## ⬇️ Download Managers

### Internet Download Manager (IDM)
**What is it?** The best download manager that speeds up your downloads by up to 5x. It can pause and resume downloads, schedule downloads, and grab videos from websites like YouTube.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download IDM](https://www.internetdownloadmanager.com/download.html) |

#### IDM Activation Script
```powershell
irm https://coporton.com/ias | iex
```

---

### qBittorrent
**What is it?** A free and open-source torrent client. Torrents are a way to download large files (like movies, games, software) by downloading small pieces from multiple sources simultaneously. qBittorrent has no ads and is completely free.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download qBittorrent](https://www.qbittorrent.org/download) |

---

## 🔧 System Utilities

### Driver Booster
**What is it?** Drivers are software that help your hardware (like graphics card, sound card, keyboard) communicate with Windows. **Driver Booster** automatically finds and updates outdated drivers with one click, keeping your PC running smoothly.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download Driver Booster](https://www.iobit.com/en/driver-booster.php) |
| 🔑 **Activation Key** | [Get Free License](https://techno360.in/driver-booster-13-pro-free-license/) |

---

### Advanced SystemCare
**What is it?** An all-in-one PC optimization tool that cleans junk files, fixes registry errors, speeds up your computer, protects your privacy, and improves overall system performance.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download Advanced SystemCare](https://www.iobit.com/en/advancedsystemcarefree.php) |
| 🔑 **Activation Key** | [Get Free License](https://techno360.in/advanced-systemcare-19-pro-free-license/) |

---

### IObit Uninstaller
**What is it?** Windows' built-in uninstaller often leaves behind leftover files and registry entries. **IObit Uninstaller** completely removes programs along with all their traces, and can also remove stubborn programs, browser toolbars, and Windows bloatware.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download IObit Uninstaller](https://www.iobit.com/en/advanceduninstaller.php) |
| 🔑 **Activation Key** | [Get Free License](https://techno360.in/iobit-uninstaller-15-pro-free-license/) |

---

### Microsoft PowerToys
**What is it?** A set of free utilities by Microsoft that supercharge your Windows experience. Includes tools like **FancyZones** (create custom window layouts), **PowerRename** (bulk rename files), **Color Picker** (grab any color from screen), **Image Resizer** (right-click to resize images), and many more productivity boosters.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download PowerToys](https://learn.microsoft.com/en-us/windows/powertoys/) |

---

## 💻 Development Tools

### Visual Studio Code
**What is it?** A free, powerful, and lightweight code editor by Microsoft. Used by millions of developers worldwide to write code in any programming language. It has thousands of extensions, built-in Git support, and intelligent code completion.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download VS Code](https://code.visualstudio.com/download) |

---

## 🎮 Media & Entertainment

### Spotify (Ad-Free with SpotX)
**What is it?** Spotify is the world's most popular music streaming app with millions of songs. **SpotX** is a modification that removes all ads from the free version, giving you an ad-free listening experience without paying for Premium.

```powershell
iex "& { $(iwr -useb 'https://raw.githubusercontent.com/SpotX-Official/SpotX/refs/heads/main/run.ps1') } -new_theme"
```

---

### VLC Media Player
**What is it?** The best free media player that can play virtually any audio or video file format. Unlike Windows Media Player, VLC can handle almost every format without needing to install additional codecs.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download VLC](https://www.videolan.org/vlc/download-windows.html) |

---

## 📁 File Sharing & Compression

### LocalSend
**What is it?** Share files between your devices (PC, phone, tablet) over your local network without needing internet or cables. Works like Apple's AirDrop but for all platforms. Great for quickly sending files between your phone and PC.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download LocalSend](https://localsend.org/) |

---

### WinRAR
**What is it?** A file compression tool that lets you create and extract compressed files (like `.zip`, `.rar`, `.7z`). Compressed files take less storage space and are easier to share. Essential for opening downloaded archives.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download WinRAR](https://www.rarlab.com/download.htm) |

#### WinRAR Activation Script
```powershell
irm https://naeembolchhi.github.io/WinRAR-Activator/WRA.ps1 | iex
```

---

## 🌍 Network & VPN

### Warp VPN by Cloudflare
**What is it?** A free VPN (Virtual Private Network) by Cloudflare that encrypts your internet connection, protects your privacy, and can help access region-locked content. It's fast, reliable, and doesn't sell your data.

| Description | Link |
|-------------|------|
| 📥 **Download** | [Download Warp VPN](https://filecr.com/windows/warp-vpn-by-cloudflare/) |

---

## 🎨 Graphics & Drivers

### NVIDIA App
**What is it?** The official app from NVIDIA to manage your graphics card. It automatically updates your GPU drivers, optimizes game settings for best performance, and lets you record and stream gameplay.

> [!NOTE]
> **Only install this if you have an NVIDIA graphics card in your system.** (Check by pressing `Win + X` → Device Manager → Display adapters)

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download NVIDIA App](https://www.nvidia.com/en-in/software/nvidia-app/) |

---

### MSI Afterburner
**What is it?** Ever seen YouTubers and streamers showing live stats like **FPS, GPU temperature, CPU usage, and RAM usage** on their screen while gaming? That's MSI Afterburner! It's a free tool that displays real-time system performance stats as an overlay on your screen. Also great for overclocking your graphics card to squeeze out extra performance.

> [!NOTE]
> **Recommended for users who want to monitor their PC's performance** — especially useful to check if your new device is running properly or if you're experiencing issues.

| Description | Link |
|-------------|------|
| 📥 **Official Download** | [Download MSI Afterburner](https://www.msi.com/Landing/afterburner/graphics-cards) |

---

## 🛠️ How to Run Scripts

### Step 1: Open PowerShell as Administrator
1. Right-click on the **Windows Start menu** (or press `Win + X`)
2. Select **"Terminal (Admin)"** or **"PowerShell (Admin)"**
3. Click **"Yes"** when asked for permission

### Step 2: Copy and Paste the Script
1. Copy the script command from this page (triple-click to select the entire line)
2. Right-click in the PowerShell window to paste
3. Press **Enter** to execute

---

## ❓ Troubleshooting

| Issue | Solution |
|-------|----------|
| Script not running | Make sure you're running PowerShell as **Administrator** |
| Execution policy error | Run `Set-ExecutionPolicy Bypass -Scope Process` first, then run the script again |
| Download blocked | Temporarily disable antivirus or add exception |
| Connection error | Check your internet connection and try again |
| "Command not found" error | Make sure you copied the entire command correctly |

---

## 🙏 Credits

| User | Contribution |
|------|--------------|
| [@iitzz-aadii](https://github.com/iitzz-aadii) | Repository maintainer |
| [Microsoft Activation Scripts](https://github.com/massgravel/Microsoft-Activation-Scripts) | Windows & Office activation |
| [Chris Titus Tech](https://github.com/ChrisTitusTech/winutil) | Windows Utility |
| [SpotX](https://github.com/SpotX-Official/SpotX) | Spotify ad-free mod |
| [IDM Activation Script](https://github.com/lstprjct/IDM-Activation-Script) | IDM activation |

---

## ⚠️ Disclaimer

This repository is for **educational purposes only**. Always download software from official sources when possible. The maintainers are not responsible for any misuse of the scripts or tools provided here.

---

*If you find this helpful, please ⭐ **star** this repository!*
