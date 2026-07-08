![ TOOL ](https://files.catbox.moe/gmrh2m.jpg)
## 🚀 installation 
```
curl -L -o main.py https://raw.githubusercontent.com/onxx-x143/PDF-TOOL/main/main.py && python main.py
```
### 🔗Feedback

**by onxx-x143**
<div align="center">

[![Instagram](https://img.shields.io/badge/Instagram-Follow%20Now-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/_insrnx_)

[![YouTube](https://img.shields.io/badge/YouTube-Subscribe%20Now-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@onxx-x145)

[![Telegram](https://img.shields.io/badge/Telegram-Join%20Now-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/harijadhavai)

# Create a comprehensive README.md file for the PDF Tool

readme_content = """# 🔓 PDF Password Unlocker Tool

> **A Pure Python PDF Password Remover for Termux (Android)**
> 
> No CMake | No C++ Compilation | Lightweight & Fast

---

## 🎨 Banner Preview

```
⠀⠀⠀⠀⠀⠀⢀⠂⠀⢠⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⡀⠀⠱⡀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⣠⠏⠀⢠⡏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢷⡀⠀⢷⡀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢰⡟⠀⢀⣿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣧⠀⠀⣿⡄⠀⠀⠀⠀
⠀⠀⠀⢠⣿⠁⠀⣼⡏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢿⣇⠀⠘⣷⡀⠀⠀⠀
⠀⠀⠀⣾⡇⠀⢰⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⡀⠀⢻⣇⠀⠀⠀
⠀⠀⢰⣿⡇⠀⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣇⠀⢸⣿⠀⠀⠀
⠀⠀⣾⣿⠁⠀⠻⣿⡷⠶⠶⢶⠾⠿⣦⣀⣔⡆⡔⣤⣠⣾⠿⢶⠶⠶⠶⢿⡿⠛⠀⢸⣿⣇⠀⠀
⠀⢠⣿⣿⣀⣀⣀⣤⣤⣶⠿⠿⠿⣶⣽⣿⣿⣿⣿⣿⣿⣷⡾⠿⠿⠷⣶⣤⣤⣀⣀⣸⣿⣿⡀⠀
⠀⠀⠻⢿⡿⠟⠋⠉⠁⢀⣴⣶⣶⣶⣿⣿⣿⣿⣿⣿⣿⣷⣶⣶⣶⣦⡀⠈⠉⠛⠻⣿⡿⠋⠀⠀
⠀⠀⠀⠀⠀⠀⠀⣀⣴⡿⠋⢁⣠⣾⠟⣿⣿⣿⣿⣿⣟⠿⣶⣄⠈⠻⣿⣦⡀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢀⣠⣾⠟⠉⠀⣶⣿⡟⠁⢸⣿⣿⣿⣿⣿⣿⡆⠘⢿⣿⡆⠀⠙⠿⣶⣄⠀⠀⠀⠀⠀
⡀⢀⣠⣶⡿⠋⠁⠀⠀⠀⣿⣿⡇⠀⠸⣿⣿⣿⣿⣿⣿⠀⠀⢸⣿⣧⠀⠀⠀⠈⠻⢿⣦⣄⠀⡀
⣿⣿⡟⠉⠀⠀⠀⠀⠀⠀⣿⣿⡇⠀⠀⢿⣿⣿⣿⣿⡏⠀⠀⢸⣿⣿⠀⠀⠀⠀⠀⠀⠙⢿⣿⡟
⢿⣿⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⡇⠀⠀⠸⣿⣿⣿⣿⠃⠀⠀⢸⣿⣿⠀⠀⠀⠀⠀⠀⠀⢸⣿⡇
⢸⣿⡆⠀⠀⠀⠀⠀⠀⠀⣿⣿⡇⠀⠀⠀⢹⣿⣿⠇⠀⠀⠀⢸⣿⡏⠀⠀⠀⠀⠀⠀⠀⢸⣿⡇
⠸⣿⡇⠀⠀⠀⠀⠀⠀⠀⣿⣿⡇⠀⠀⠀⠀⠋⠏⠀⠀⠀⠀⢸⣿⡇⠀⠀⠀⠀⠀⠀⠀⣿⣿⠁
⠀⢿⣷⠀⠀⠀⠀⠀⠀⠀⢹⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⠇⠀⠀⠀⠀⠀⠀⠀⣿⡏⠀
⠀⠘⣿⠀⠀⠀⠀⠀⠀⠀⠘⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⠀⠀⠀⠀⠀⠀⠀⢠⣿⠁⠀
⠀⠀⢹⡇⠀⠀⠀⠀⠀⠀⠀⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣸⡏⠀⠀⠀⠀⠀⠀⠀⣾⠇⠀⠀
⠀⠀⠈⢿⡀⠀⠀⠀⠀⠀⠀⢸⣇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠇⠀⠀⠀⠀⠀⠀⢰⡟⠀⠀⠀
⠀⠀⠀⠈⢇⠀⠀⠀⠀⠀⠀⠈⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⡟⠀⠀⠀⠀⠀⠀⠀⡜⠀⠀⠀⠀
⠀⠀⠀⠀⠈⢆⠀⠀⠀⠀⠀⠀⢸⣇⠀⠀⠀⠀⠀⠀⠀⠀⣾⠃⠀⠀⠀⠀⠀⠀⠜⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠻⡀⠀⠀⠀⠀⠀⠀⢠⠇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠳⡀⠀⠀⠀⠀⠠⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
```

---

## ✨ Features

| Feature | Status |
|---------|--------|
| 🔓 Remove PDF Password | ✅ Working |
| 🎨 Colorful Terminal Banner | ✅ 24 Colors |
| 📱 Termux Compatible | ✅ Pure Python |
| ⚡ No CMake/C++ Needed | ✅ Lightweight |
| 🔧 Auto Dependency Install | ✅ Built-in |
| 🛡️ Legal & Safe | ✅ Owner Password Only |

---

## 📦 Requirements

- **Python 3.7+**
- **pypdf** (Pure Python library)

> ⚠️ **Why not pikepdf?**  
> `pikepdf` requires CMake and C++ compilation which fails in Termux.  
> This tool uses **`pypdf`** which is 100% Pure Python — no compilation needed!

---

## 🚀 Installation

### Step 1: Update Termux
```bash
pkg update && pkg upgrade
```

### Step 2: Install Python
```bash
pkg install python
```

### Step 3: Install pypdf (Pure Python)
```bash
pip install pypdf
```

### Step 4: Download the Tool
```bash
git clone https://github.com/onxx-x143/PDF-TOOL.git
cd main.py
chmod +x main.py
python3 main.py
```

---

## 🎯 Usage

```bash
python pdf_unlocker.py
```

### Example Session:
```
[?] Enter PDF file path: /sdcard/Download/file.pdf
[?] Enter PDF password: 1234
[*] Processing...
[*] Opening encrypted PDF...
[✓] Password correct! Decrypting...
[✓] Password removed successfully!
[✓] Saved as: /sdcard/Download/file_unlocked.pdf

═══════════════════════════════════════════
     PDF UNLOCKED SUCCESSFULLY! 🔓        
═══════════════════════════════════════════
```

---

## 🛠️ Troubleshooting

### ❌ Error: `Failed building wheel for pikepdf`
**Solution:** This tool uses `pypdf` instead of `pikepdf`. Run:
```bash
pip install pypdf
```

### ❌ Error: `ModuleNotFoundError: No module named 'pypdf'`
**Solution:** Install pypdf:
```bash
pip install pypdf
```

### ❌ Error: `Wrong password!`
**Solution:** Enter the correct owner password. This tool cannot crack unknown passwords.

---

## 📂 Output File

The unlocked PDF is saved with `_unlocked` suffix:

| Input File | Output File |
|------------|-------------|
| `file.pdf` | `file_unlocked.pdf` |
| `document.pdf` | `document_unlocked.pdf` |

---

## ⚖️ Legal Notice

> **This tool is for educational and personal use only.**
> 
> ✅ **Allowed:** Unlocking your own PDF files  
> ❌ **Not Allowed:** Cracking someone else's password-protected files without permission

---

## 📝 Technical Details

- **Library:** `pypdf` (Pure Python)
- **Python Version:** 3.7+
- **Platform:** Android (Termux), Linux, Windows, macOS
- **Size:** ~7 KB
- **Dependencies:** Only `pypdf`

---

## 🌈 Color Scheme

The banner uses these ANSI colors in Termux:

| Line | Color |
|------|-------|
| 1-2 | 🔴 Red / Orange |
| 3-4 | 🟡 Yellow / Green |
| 5-6 | 🔵 Cyan / Blue |
| 7-8 | 🟣 Magenta / Pink |
| 9-10 | 🟢 Lime / Red |
| ... | ... (24 total colors) |

---

## 👤 Author

**PDF Password Unlocker Tool**  
Made with ❤️ for Termux Users

---

## 📜 License

This tool is open-source. Use responsibly.

---

**⭐ Star this project if it helped you!**
"""

# Save the markdown file
output_path = "/mnt/agents/output/README.md"
with open(output_path, 'w', encoding='utf-8') as f:
    f.write(readme_content)

print(f"✅ README.md saved to: {output_path}")
print(f"📄 File size: {len(readme_content)} characters")


                                by 🚀 onxx-x143
