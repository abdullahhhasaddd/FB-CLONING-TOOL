## RAPTOR - FB Tool (Termux Guide)

### Overview
RAPTOR is a Facebook tool. Follow the steps below to run it on Termux.

### Disclaimer
- This tool is for educational purposes only.
- Use responsibly and at your own risk.
- The tool is paid and trusted.

### Join WhatsApp Channel
- Channel link: https://whatsapp.com/channel/0029VbCH5uXBvvsk85xpl73s

### Requirements
- Termux app (latest)
- Internet connection
- Python and Git

### Termux Setup (run this single command instead)
```bash
pkg update -y && pkg upgrade -y && pkg install -y python git && termux-setup-storage

```

### Clone the repository
```bash
cd ~
```
```bash
git clone https://github.com/abdullahhhasaddd/FB-CLONING-TOOL.git
```
```bash
cd FB-CLONING-TOOL
```

### Install dependencies (Single Command)
```bash
pip install requests urllib3 mechanize rich beautifulsoup4

```

### Run the tool
```bash
python RAPTOR.py
```
If that fails, try:
```bash
python3 RAPTOR.py
```
- Missing packages: install with `pip install <package-name>`
- Results (OK IDs) are saved inside the `results/` folder in the project directory.


