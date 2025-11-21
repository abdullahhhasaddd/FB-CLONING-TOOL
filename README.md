# 🦅 RAPTOR - Facebook Cloning Tool

<div align="center">

![RAPTOR](https://img.shields.io/badge/RAPTOR-FB%20Tool-green?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.7+-blue?style=for-the-badge&logo=python)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Android%20%7C%20Linux-lightgrey?style=for-the-badge)

**A powerful Facebook account cloning tool with advanced features**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Support](#-support)

</div>

---

## 📋 Table of Contents

- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
  - [Windows](#windows)
  - [Android (Termux)](#android-termux)
  - [Linux](#linux)
- [Usage](#-usage)
- [Troubleshooting](#-troubleshooting)
- [Disclaimer](#-disclaimer)
- [Support](#-support)

---

## ✨ Features

- 🔐 **Secure Key System** - 3 attempts with cooldown protection
- 📱 **WhatsApp Integration** - Automatic channel opening
- 🎯 **Multiple Cloning Methods** - Old account series support
- 💾 **Smart File Saving** - Results folder + SD card fallback
- 🔒 **Anti-Tampering** - Built-in security checks
- 🌐 **Cross-Platform** - Works on Windows, Android, and Linux
- 🎨 **Beautiful UI** - Colorful terminal interface
- ⚡ **Fast Processing** - Multi-threaded execution

---

## 📦 Requirements

### For All Platforms:
- Python 3.7 or higher
- Internet connection
- Required Python packages (auto-installed)

### For Android (Termux):
- Termux app (latest version)
- Termux API app (for WhatsApp links)
- Storage permission

---

## 🚀 Installation

### Windows

1. **Install Python:**
   - Download from [python.org](https://www.python.org/downloads/)
   - Make sure to check "Add Python to PATH" during installation

2. **Clone Repository:**
   ```bash
   git clone https://github.com/abdullahhhasddd/FB-CLONING-TOOL.git
   cd FB-CLONING-TOOL
   ```

3. **Install Dependencies:**
   ```bash
   pip install requests urllib3 mechanize rich beautifulsoup4 httpx
   ```

4. **Run Tool:**
   ```bash
   python RAPTOR.py
   ```

### Android (Termux)

1. **Install Termux:**
   - Download from [F-Droid](https://f-droid.org/en/packages/com.termux/) or [GitHub Releases](https://github.com/termux/termux-app/releases)
   - Install Termux API from Google Play Store

2. **Update System:**
   ```bash
   pkg update -y
   pkg upgrade -y
   ```

3. **Install Python & Git:**
   ```bash
   pkg install -y python git termux-api
   ```

4. **Setup Storage:**
   ```bash
   termux-setup-storage
   ```

5. **Clone Repository:**
   ```bash
   cd ~
   git clone https://github.com/abdullahhhasddd/FB-CLONING-TOOL.git
   cd FB-CLONING-TOOL
   ```

6. **Install Dependencies:**
   ```bash
   pip install requests urllib3 mechanize rich beautifulsoup4 httpx
   ```

7. **Run Tool:**
   ```bash
   python RAPTOR.py
   ```

### Linux

1. **Install Python & Git:**
   ```bash
   sudo apt update
   sudo apt install python3 python3-pip git -y
   ```

2. **Clone Repository:**
   ```bash
   git clone https://github.com/abdullahhhasddd/FB-CLONING-TOOL.git
   cd FB-CLONING-TOOL
   ```

3. **Install Dependencies:**
   ```bash
   pip3 install requests urllib3 mechanize rich beautifulsoup4 httpx
   ```

4. **Run Tool:**
   ```bash
   python3 RAPTOR.py
   ```

---

## 📖 Usage

1. **Start the Tool:**
   ```bash
   python RAPTOR.py
   # or
   python3 RAPTOR.py
   ```

2. **Join WhatsApp Channel:**
   - Tool will automatically open WhatsApp channel
   - Join the channel to get your access key
   - Channel Link: [Join Here](https://whatsapp.com/channel/0029VbCH5uXBvvsk85xpl73s)

3. **Enter Key:**
   - You have 3 attempts to enter the correct key
   - After 3 wrong attempts, wait 8 seconds before retrying

4. **Select Options:**
   - Choose cloning method (A, B, or C)
   - Enter ID count
   - Select method (A or B)
   - Wait for results

5. **Check Results:**
   - Results are saved in `results/` folder
   - Files: `RAPTOR-OLD-M1-OK.txt` or `RAPTOR-OLD-M2-OK.txt`

---

## 🔧 Troubleshooting

### Common Issues:

**1. Module Not Found Error:**
```bash
pip install requests urllib3 mechanize rich beautifulsoup4 httpx
```

**2. WhatsApp Link Not Opening (Android):**
- Install Termux API app from Google Play Store
- Grant necessary permissions

**3. Permission Denied (Android):**
```bash
termux-setup-storage
```

**4. Python Not Found:**
- Windows: Add Python to PATH
- Linux: Use `python3` instead of `python`
- Android: Install Python via `pkg install python`

**5. Key Not Working:**
- Make sure you joined the WhatsApp channel
- Check for latest key in channel
- Contact owner if key expired

**6. Results Not Saving:**
- Check `results/` folder in project directory
- On Android, check `/sdcard/` folder
- Ensure write permissions

---

## ⚠️ Disclaimer

This tool is for **educational purposes only**. 

- ❌ Do not use for illegal activities
- ❌ Do not use to harm others
- ❌ Do not violate Facebook's Terms of Service
- ✅ Use responsibly and ethically
- ✅ Respect privacy and security

**The developers are not responsible for any misuse of this tool.**

---

## 📞 Support

### 📱 WhatsApp Channel
Join our channel for updates, keys, and support:
- [Join WhatsApp Channel](https://whatsapp.com/channel/0029VbCH5uXBvvsk85xpl73s)

### 📧 Contact
- Owner WhatsApp: `923282717996`
- GitHub Issues: [Create Issue](https://github.com/abdullahhhasddd/FB-CLONING-TOOL/issues)

### 🔄 Updates
To update to latest version:
```bash
cd FB-CLONING-TOOL
git pull
python RAPTOR.py
```

---

## 📝 License

This project is for educational purposes. Use at your own risk.

---

## 🙏 Credits

- **Developer:** Abdullah Asad
- **Tool Name:** RAPTOR
- **Version:** 2.5

---

<div align="center">

**⭐ Star this repo if you find it useful! ⭐**

Made with ❤️ by RAPTOR Team

</div>
