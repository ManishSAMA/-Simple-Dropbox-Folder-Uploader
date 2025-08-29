# Simple-Dropbox-Folder-Uploader

# 📁 Simple Dropbox Folder Uploader

A desktop GUI tool for fast, bulk uploading of folders-full-of-photos to Dropbox, complete with detailed progress tracking and automatic Excel/CSV report generation—**no code or Python knowledge required**!

---

## ✨ Features

- **Connect seamlessly to Dropbox** with your API token
- **Bulk add folders or subfolders** for batch photo uploads
- **Automatic image detection** in popular formats
- **Drag-and-drop, cancel, and live progress indicators**
- **Automatic creation of Dropbox folder structure**
- **Clickable Dropbox share links** for every uploaded image
- **Product code extraction** from folder names
- **One-click exports:** detailed Excel (per-photo), summary Excel (per-folder), and CSV
- **Clean, scrollable GUI** for smooth handling of big batches

---

## 🖥️ Screenshots

<!-- You can upload screenshots and add them here. Example: -->
<!-- ![Main UI](screenshots/ui_main.png) -->
<!-- ![Progress](screenshots/ui_progress.png) -->

---

## 📦 Download

### Windows Users

**Download the ready-to-run EXE:**  
[Download Simple Dropbox Folder Uploader (Windows EXE)]()  
*No Python or installation required. Tested on Windows 10 and 11.*

> **Note**: If you see a warning from Windows Defender or your antivirus about unknown publisher, click “More info” → “Run anyway.”  
> Always download from the official GitHub releases or trusted sources.

### Mac/Linux Users

- Please run the Python script version (see below).

---

## 🚀 Quick Start (Python Script)

### 1. Install Python Dependencies

### 2. Get Your Dropbox API Token

- Visit [Dropbox Developers Console](https://www.dropbox.com/developers/apps)
- Create a new app and generate an API token

### 3. Run the App


---

## 🔑 Usage Guide

**1️⃣ Connect to Dropbox**
- Paste your Dropbox API token
- Enter your target Dropbox folder (default `/ProductCatalog`)
- Click **Connect**

**2️⃣ Select Folders**
- Click **Add Folder** for one folder, or **Add Multiple** to select a parent containing several folders (with images)

**3️⃣ Start Upload**
- Click **START UPLOAD**
- Watch progress for each photo and folder
- Cancel any time

**4️⃣ Export Results**
- Use "Detailed Excel" for a complete per-photo log
- Use "Summary Excel" for an overview per folder
- Use "CSV Export" for simple lists

---

## ✅ Supported Image Formats

- `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`, `.tiff`, `.webp`, `.heic`

---

## 🛠️ Advanced: Building Your Own EXE

To build your own EXE from source, run:

The EXE will be in the `dist/` folder.

---

## 📂 File Structure

- `dropbox_uploader_v3.py` — Main application script
- `dist/SimpleDropboxUploader.exe` — Windows EXE release

---

## 🚧 Ideas & To Do

- [ ] Drag-and-drop folder selection
- [ ] Retry failed uploads
- [ ] Settings persistence
- [ ] .app packaging for Mac

---

## 📄 License

MIT License — free to use, modify, and distribute!

---

**Feedback, bug reports, and contributions welcome!**




