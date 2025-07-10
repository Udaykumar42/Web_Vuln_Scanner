# 🔍 Web Application Vulnerability Scanner

A Python-based scanner that detects basic web application vulnerabilities like SQL Injection and Cross-Site Scripting (XSS). Includes both a CLI and Flask-based web UI.

## ✅ Features
- URL crawling
- HTML form extraction
- Payload injection (XSS, SQLi)
- Vulnerability detection with severity
- Logging to text file
- Flask UI dashboard

## 📂 Structure
- `main.py` – Command line version
- `app.py` – Flask web app
- `scanner/` – All backend modules
- `templates/` – HTML frontend
- `reports/` – Scan logs

## 🛠 Tools Used
- Python 3
- Requests, BeautifulSoup
- Flask
- Regex
- HTML/Jinja2

## 🚀 How to Run

### CLI Mode:
```bash
python main.py
