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

### Termux Setup (run each command separately)
```bash
pkg update -y
```
```bash
pkg upgrade -y
```
```bash
pkg install -y python
```
```bash
pkg install -y git
```
```bash
termux-setup-storage
```

### Clone the repository
```bash
cd ~
```
```bash
git clone https://github.com/abdullahhhasddd/FB-CLONING-TOOL.git
```
```bash
cd FB-CLONING-TOOL
```

### Install dependencies
```bash
pip install requests
```
```bash
pip install urllib3
```
```bash
pip install mechanize
```
```bash
pip install rich
```
```bash
pip install beautifulsoup4
```

### Run the tool
```bash
python RAPTOR.py
```
If that fails, try:
```bash
python3 RAPTOR.py
```

### Update to latest version later
```bash
cd ~/FB-CLONING-TOOL
```
```bash
git pull
```
```bash
python RAPTOR.py
```

### Troubleshooting
- File not found: ensure you are inside the repo directory and the file exists
```bash
pwd
```
```bash
ls -la
```
```bash
ls -la *.py
```
- Missing packages: install with `pip install <package-name>`
- Results (OK IDs) are saved inside the `results/` folder in the project directory.


