# 🔐 FIM-PKI-Tool

A secure, modern File Integrity Monitoring (FIM) tool with Public Key Infrastructure (PKI) support, built using Python and delivered with a professional GUI and Docker support.

---

## 📦 Features

- ✅ **PKI-based User Authentication**
- 🔏 **Digital Signing & Verification of Logs**
- 📂 **Real-time File Monitoring**
- 📤 **Export Logs as CSV**
- 🧑‍💻 **Modern Tkinter GUI**
- 🐳 **Docker Support for Easy Deployment**

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/coolwaaris/fim-pki-tool.git
cd fim-pki-tool
```

### 2. Run using Docker
Make sure Docker is installed on your system.

```bash
docker pull mdwaaris/fim-tool:latest
docker run -it --rm fim-tool:latest
```

> 🛠️ If you want to build it yourself:
```bash
docker build -t fim-tool:latest .
docker run -it --rm fim-tool:latest
```

---

## 🧪 Manual Usage

If you’re not using Docker:

```bash
python3 fim_gui_v2_full.py
```

Make sure the following Python packages are installed:
- `watchdog`
- `cryptography`
- `matplotlib`
- `pillow`
- `tkinter` *(usually preinstalled with Python)*
- and others listed in `requirements.txt`

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 📁 Project Structure

```
fim_pki_tool/
├── certs/              # Stores user certificates
├── keys/               # Stores private keys
├── CSV_logs/           # Exported CSV logs
├── logs/               # Encrypted log files
├── fim_gui_v2_full.py  # Main GUI launcher
├── monitor.py          # Core file monitoring
├── signer.py           # Digital signature manager
├── pki_manager.py      # Key & certificate management
├── Dockerfile
└── README.md
```

---

## 👤 Author

**Mohammad Waaris Ali Khan**  
[GitHub: coolwaaris](https://github.com/coolwaaris)  
[DockerHub: mdwaaris](https://hub.docker.com/u/mdwaaris)

---

## 🗓️ Last updated: 2025-07-10
