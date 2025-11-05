## RAPTOR - FB Tool (Termux Guide)

### Overview
This repository contains the RAPTOR tool. Follow the steps below to run it on Termux.

### Disclaimer
- This tool is for educational purposes only.
- Use responsibly and at your own risk.
- The tool is paid and trusted.

### Join WhatsApp Channel
- Channel link: https://whatsapp.com/channel/0029VbCH5uXBvvsk85xpl73s

### Termux Installation and Run
Copy–paste these commands in Termux:

```bash
pkg update -y && pkg upgrade -y
pkg install -y python git

# Optional (to access shared storage if needed)
termux-setup-storage

# Clone the repository (replace with your GitHub username and repo if needed)
git clone https://github.com/abdullahhhasddd/FB-CLONING-TOOL.git
cd FB-CLONING-TOOL

# Install dependencies
pip install requests urllib3 mechanize rich beautifulsoup4

# Run the tool
python RAPTOR.py
```

### Update to Latest Version
```bash
cd FB-CLONING-TOOL
git pull
python RAPTOR.py
```

### Notes
- Results (OK IDs) will be saved inside the `results/` folder in the project directory.
- If any Python package is missing, install it using `pip install <package-name>`.


