---

````markdown
# InstaGrep v4.0 🔍  
### Professional Instagram OSINT Toolkit

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-black)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/Use-Educational-orange)

InstaGrep v4.0 is a modern GUI-based Instagram OSINT tool designed for researchers, cybersecurity learners, and digital investigators.

It provides structured profile analysis, activity visualization, media extraction, and export capabilities — all within a clean and professional interface.

---

## ⚡ Quick Start

```bash
git clone https://github.com/yourusername/instagrep.git
cd instagrep
pip install -r requirements.txt
python instagrep.py
````

---

## 🧪 Recommended Setup (Virtual Environment)

```bash
git clone https://github.com/yourusername/instagrep.git
cd instagrep

python -m venv my-venv
source my-venv/bin/activate  # Linux/macOS
my-venv\Scripts\activate     # Windows

pip install -r requirements.txt
python instagrep.py
```

---

## 📁 Project Structure

```
Instagrep/
├── instagrep.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🍪 Session Setup

InstaGrep uses authenticated Instagram session cookies.

### Firefox (Recommended)

Install **Cookie Importer by Neeno**:

[https://addons.mozilla.org/firefox/addon/cookie-importer-by-neeno/](https://addons.mozilla.org/firefox/addon/cookie-importer-by-neeno/)

**Steps:**

1. Install the extension
2. Log into Instagram
3. Export cookies as JSON
4. Save as `cookies.json`
5. Import inside InstaGrep

---

### Chrome Alternative

Use **EditThisCookie** extension:

1. Install extension
2. Log into Instagram
3. Export cookies as JSON
4. Save as `cookies.json`
5. Import inside the application

---

## 🖱 Drag & Drop Support

The application supports drag-and-drop importing of `cookies.json`.

---

## ⌨ Keyboard Shortcuts

| Key      | Action           |
| -------- | ---------------- |
| Enter    | Analyze username |
| Ctrl + S | Save JSON        |
| Ctrl + D | Download media   |
| Ctrl + E | Export PDF       |
| Ctrl + H | Recent searches  |
| ?        | Show shortcuts   |

---

## 🧭 Usage

1. Import `cookies.json`
2. Enter target username
3. Click **ANALYZE** or press **Enter**
4. Navigate through available tabs:

   * Overview
   * Activity
   * Media
   * Analytics
   * Export

---

## ✨ Features

* Modern CustomTkinter interface
* Cookie-based authenticated sessions
* Recent search tracking
* Activity charts and visual analytics
* Media downloader
* JSON export
* PDF export
* Full keyboard navigation
* Toast notifications
* Sparklines and animated counters
* Drag-and-drop session import

---

## 💻 Platform Installation

### Linux / Kali

```bash
sudo apt update
sudo apt install python3 python3-pip -y
pip install -r requirements.txt
python3 instagrep.py
```

---

### Windows

1. Install Python 3.9 or newer
2. Run:

```bash
pip install -r requirements.txt
python instagrep.py
```

---

### macOS

```bash
brew install python
pip3 install -r requirements.txt
python3 instagrep.py
```

---

## 🛠 Troubleshooting

**No session detected**
Ensure `cookies.json` is exported correctly.

**ModuleNotFoundError**

```bash
pip install -r requirements.txt
```

**429 Too Many Requests**
Wait 15–30 minutes before retrying.

**Charts not rendering**
Verify `matplotlib` is installed.

**PDF export errors**
Verify `reportlab` is installed.

---

## ⚠ Disclaimer

This tool is intended for educational and research purposes only.
Users are responsible for complying with Instagram’s Terms of Service and applicable laws.

---

## 📌 Version

**InstaGrep v4.0**

Professional Instagram OSINT Interface

---

⭐ If you find this project useful, consider starring the repository.

```

---

