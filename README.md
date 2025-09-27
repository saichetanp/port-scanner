# Port Scanner

**Lightweight Python TCP port scanner — threaded, fast, and easy to extend.**

A simple, beginner-friendly port scanner written in pure Python. It uses a thread pool for safe concurrency, can optionally grab service banners, and can export results to JSON or CSV. Designed for learning and demos — **only scan hosts you own or have explicit permission to test**.

---

## Features
- Thread-pooled TCP port scanning for speed and control  
- Optional banner grabbing for open ports (`--banner`)  
- JSON/CSV export (`-o results.json` / `-o results.csv`)  
- Minimal dependencies — Python standard library only  
- Safety confirmation flag (`--i-understand`) to reduce accidental misuse

---

## Requirements
- Python 3.8+ (works with 3.10 / 3.11 / 3.13)
- No third-party packages required for the core script

---

## Installation / prepare
1. Save `port_scanner.py` in a folder.
2. (Optional) create & activate a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate    # macOS / Linux
.\venv\Scripts\activate     # Windows PowerShell
