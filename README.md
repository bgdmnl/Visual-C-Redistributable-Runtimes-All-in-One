# 💾 Visual C++ Redistributable Runtimes All in One

A simple all-in-one installer that automatically installs all major Microsoft Visual C++ Redistributable runtimes (2005 → 2022) using a single `.bat` script.

It helps fix missing DLL errors, improve game compatibility, and reduce setup time on fresh Windows installations.

---

## ✨ Features

* 📦 Installs all Visual C++ runtimes (2005–2022)
* ⚙️ Supports both x86 and x64 systems automatically
* 🚀 Fully automated batch installer (`.bat`)
* 🧩 Silent / passive installation (no user input needed)
* 🪟 Works on fresh Windows installs and gaming PCs
* 🔧 Fixes common runtime / DLL errors

---

## 🧩 What This Fixes

* `MSVCP140.dll is missing`
* `VCRUNTIME140.dll is missing`
* `MSVCR100.dll missing`
* `api-ms-win-crt-runtime-l1-1-0.dll missing`
* `0xc000007b` application error
* Games not launching
* Missing Visual C++ runtime dependencies

---

## 📁 Included Files

* 12x Visual C++ Redistributable `.exe` installers
* 1x `install_all.bat` script (main installer)

---

## 🚀 How To Use

### 1. Download

There is no GitHub Release available yet.

Download the project as a ZIP:

* Click the green **Code** button
* Select **Download ZIP**

Or clone it:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
```

---

### 2. Extract Files

Unzip the archive anywhere on your PC.

⚠️ Important:
Keep all `.exe` files and `install_all.bat` in the same folder.

---

### 3. Run Installer

Double-click:

```
install_all.bat
```

The script will:

* Detect your system (x86 or x64)
* Install all required Visual C++ runtimes automatically
* Run everything silently

No admin setup or manual configuration required.

---

## ⚙️ Notes

* Compatible with Windows 7 / 8 / 10 / 11
* Fully offline installer package
* Safe to run multiple times (it will skip/overwrite as needed)
* Designed for gaming PCs and fresh OS installs

---

## 📄 License

This project redistributes official Microsoft Visual C++ Runtime installers for convenience.
All rights belong to Microsoft.
