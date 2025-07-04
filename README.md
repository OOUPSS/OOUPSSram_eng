# ⚡ OOUPSSram — Ultimate System Optimizer ⚡

![Platform](https://img.shields.io/badge/platform-Windows-blue?logo=windows)
[![Version](https://img.shields.io/badge/Version-English-orange?logo=github)](https://github.com/OOUPSS/OOUPSSram_eng)
[![License](https://img.shields.io/github/license/OOUPSS/OOUPSSram_eng)](https://github.com/OOUPSS/OOUPSSram_eng/blob/main/LICENSE)
![VirusTotal](https://img.shields.io/badge/VirusTotal-Scan%20Passed-brightgreen?logo=virustotal&logoColor=white)
![Python](https://img.shields.io/badge/python-3.11+-yellow?logo=python&logoColor=white)
![GUI](https://img.shields.io/badge/GUI-PySide6-%233377AA?logo=qt&logoColor=white)
[![Downloads](https://img.shields.io/github/downloads/OOUPSS/OOUPSSram_eng/total?color=brightgreen)](https://github.com/OOUPSS/OOUPSSram_eng/releases)

**OOUPSSram** is an advanced, cyberpunk-neon style system optimizer and monitoring tool for Windows.

📊 Real-time monitoring, 🔥 AI analysis, 🧼 one-click memory, cache, and temp file cleaning — all in a sleek PySide6 interface.

![UI Screenshot]()

---

## 🚀 Features

- ✅ Real-time monitoring: CPU, RAM, VRAM, disk, network  
- 🧠 AI system analysis with recommendations  
- 🧹 Memory and temporary files cleaning  
- ⚙️ Startup and services manager  
- 📦 Installed programs viewer  
- 🌐 Cache cleaning for Windows Store, DNS, updates  
- 🖥 VRAM monitoring via `pynvml` or `nvidia-smi`  
- 🎨 15 neon themes: from Cyberpunk to Emerald  
- 🔒 Fully offline — works without internet  

---

## 🧪 Platform & Component Support

| Component      | Status                              |
|----------------|-----------------------------------|
| Windows 10/11  | ✅ Full support                   |
| Linux/macOS    | ❌ Not supported                  |
| PyInstaller    | ✅ Supported                     |
| Admin mode     | ⚠️ Recommended for all functions |
| NVIDIA GPU     | 🔧 Supported (for VRAM analysis) |

---

## 🖼️ Screenshots

| Monitoring | AI Analysis | Startup Manager |
|------------|-------------|-----------------|
| ![Monitoring](./screenshots/monitoring.png) | ![AI Analysis](./screenshots/ai_analysis.png) | ![Startup](./screenshots/autostart.png) |

---

## 📦 Download

⬇️ [Download the latest Windows version (.exe)]()

> 🛑 It is recommended to run as administrator.  
> 📁 No installation required — just run the `.exe`.

---

## 📹 Video Tutorial

<p align="center">
  <a href="">
    <img src="" alt="YouTube Preview" width="640" />
  </a>
</p>

<p align="center">
  <a href="">
    <img src="" alt="Watch on YouTube" width="220" />
  </a>
</p>

---

## 👤 Author

**OOUPSS**

- Discord: `oouuppss`

---

## 🛡️ Virus Scan

The executable `OOUPSSram.exe` has been scanned via [VirusTotal](https://www.virustotal.com/) and detected by **5 out of 71** antivirus engines.

![VirusTotal Scan](https://github.com/OOUPSS/OOUPSSram_eng/blob/main/virtotrameng.png?raw=true)

| Parameter         | Value                                                        |
|-------------------|--------------------------------------------------------------|
| SHA256            | `f9401fdc0e8e1ef2625e591648acb2f2c816312dc74263d7cce410526511eeb4` |
| File Size         | 49.47 MB                                                     |
| Architecture      | 64-bit                                                      |
| File Type         | PE Executable                                               |

### Detections

- **5 out of 71** security engines flagged the file as potentially malicious  
- The detections are mostly false positives related to PyInstaller packaging  

---

**Detected by:** 5 out of 71 antivirus engines  
**Label:** `Trojan` *(generic match, usually a false positive)*

> ⚠️ **Why this happens:**  
> This is a **false positive** commonly seen with PyInstaller-packed `.exe` files.  
> Some antivirus engines flag it because:
> - It uses **PyInstaller**, which bundles all code and dependencies into a single `.exe`  
> - The file is **not digitally signed**  
> - It contains **embedded icons and resources**, which resemble malware behavior  
> - It matches a **YARA rule for PyInstaller**, which only detects packaging — not malicious behavior  
> ([YARA rule source](https://github.com/bartblaze/Yara-rules) by @bartblaze)

---

### Additional Analysis Details

- The file calls WMI, contains overlay, and is 64-bit.  
- Behavior typical for packaged Python apps (e.g., Python Core loaded by non-Python process).  
- Sigma rules flagged one MEDIUM risk (Python Image Load by Non-Python Process), related to PyInstaller/Py2Exe packaging and not necessarily a threat.

---

🔐 **This tool is fully open source and safe. You can always review the source code and build the application yourself.**

🔗 [View full VirusTotal scan report](https://www.virustotal.com/gui/file/f9401fdc0e8e1ef2625e591648acb2f2c816312dc74263d7cce410526511eeb4/detection)

---

## ⭐ Support

If you like the project, please ⭐ star it and share the link with your friends — it helps the project grow!
