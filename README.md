# ⚡ OOUPSSram — Ultimate System Optimizer ⚡

![Platform](https://img.shields.io/badge/platform-Windows-blue?logo=windows)
[![Version](https://img.shields.io/badge/Version-English-orange?logo=github)](https://github.com/OOUPSS/OOUPSSram_eng)
[![License](https://img.shields.io/github/license/OOUPSS/OOUPSSram_eng)](https://github.com/OOUPSS/OOUPSSram_eng/blob/main/LICENSE)
![VirusTotal](https://img.shields.io/badge/VirusTotal-Scan%20Passed-brightgreen?logo=virustotal&logoColor=white)
![Python](https://img.shields.io/badge/python-3.11+-yellow?logo=python&logoColor=white)
![GUI](https://img.shields.io/badge/GUI-PySide6-%233377AA?logo=qt&logoColor=white)
[![Downloads](https://img.shields.io/github/downloads/OOUPSS/OOUPSSram_ru/v1.0/OOUPSSram.exe?color=brightgreen)](https://github.com/OOUPSS/OOUPSSram_eng/releases/tag/v1.0)

**OOUPSSram** is an advanced, cyberpunk-neon style system optimizer and monitoring tool for Windows.

📊 Real-time monitoring, 🔥 AI analysis, 🧼 one-click memory, cache, and temp file cleaning — all in a sleek PySide6 interface.

![UI Screenshot](https://github.com/OOUPSS/OOUPSSram_eng/blob/main/oupseng.png?raw=true)

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

<div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;">

  <div style="background-color: #111; border: 1px solid #444; border-radius: 12px; padding: 10px; width: 300px; text-align: center;">
    <h3 style="color: white; display: inline-block; margin: 10px auto;">Monitoring</h3>
    <img src="https://github.com/OOUPSS/OOUPSSram_eng/blob/main/oupsdiageng.png?raw=true" style="width: 100%; border-radius: 8px;" />
  </div>

  <div style="background-color: #111; border: 1px solid #444; border-radius: 12px; padding: 10px; width: 300px; text-align: center;">
    <h3 style="color: white; display: inline-block; margin: 10px auto;">AI Analysis</h3>
    <img src="https://github.com/OOUPSS/OOUPSSram_eng/blob/main/oupsaieng.png?raw=true" style="width: 100%; border-radius: 8px;" />
  </div>

  <div style="background-color: #111; border: 1px solid #444; border-radius: 12px; padding: 10px; width: 300px; text-align: center;">
    <h3 style="color: white; display: inline-block; margin: 10px auto;">Startup Manager</h3>
    <img src="https://github.com/OOUPSS/OOUPSSram_eng/blob/main/oupsautoeng.png?raw=true" style="width: 100%; border-radius: 8px;" />
  </div>

</div>

---

## 📦 Download

⬇️ [Download the latest Windows version (.exe)](https://github.com/OOUPSS/OOUPSSram_eng/releases/download/v1.0/OOUPSSram.exe)

> 🛑 It is recommended to run as administrator.  
> 📁 No installation required — just run the `.exe`.

---

## 📹 Video Tutorial

<p align="center">
  <a href="https://youtu.be/uphSnLLJ-aA?si=QCszFikg6g9Nf0mG" target="_blank">
    <img src="https://github.com/OOUPSS/OOUPSSram_eng/blob/main/ytlog.png?raw=true" alt="Превью YouTube" width="1000" />
  </a>
</p>

<p align="center">
  <a href="https://youtu.be/uphSnLLJ-aA?si=QCszFikg6g9Nf0mG" target="_blank">
    <img src="https://github.com/OOUPSS/OOUPSSram_eng/blob/main/yt1.png?raw=true" alt="Смотреть на YouTube" width="220" />
  </a>
</p>

---

## 👤 Author

**OOUPSS**

- Discord: `oouuppss`

---

## 🛡️ Virus Scan

The executable `OOUPSSram.exe` has been scanned via [VirusTotal](https://www.virustotal.com/gui/file/9be6eef3e4d7120ff4a1106fc36e91f7e514a7683310ac81e5f0af7a413d5fe2?nocache=1) and detected by **4 out of 70** antivirus engines.

![VirusTotal Scan](https://github.com/OOUPSS/OOUPSSram_eng/blob/main/oupsvirtoteng.png?raw=true)

| Parameter         | Value                                                        |
|-------------------|--------------------------------------------------------------|
| SHA256            | `9be6eef3e4d7120ff4a1106fc36e91f7e514a7683310ac81e5f0af7a413d5fe2` |
| File Size         | 49.52 MB                                                     |
| Architecture      | 64-bit                                                      |
| File Type         | PE Executable                                               |

### Detections

- **4 out of 70** security engines flagged the file as potentially malicious  
- The detections are mostly false positives related to PyInstaller packaging  

---

**Detected by:** 4 out of 70 antivirus engines  
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

🔗 [View full VirusTotal scan report](https://www.virustotal.com/gui/file/9be6eef3e4d7120ff4a1106fc36e91f7e514a7683310ac81e5f0af7a413d5fe2?nocache=1)

---

## ⭐ Support

If you like the project, please ⭐ star it and share the link with your friends — it helps the project grow!
