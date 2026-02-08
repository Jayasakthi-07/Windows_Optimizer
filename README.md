# 🚀 Windows_Optimizer

<div align="center">

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Windows](https://img.shields.io/badge/Platform-Windows-blue)](https://www.microsoft.com/windows/)
[![Batch](https://img.shields.io/badge/Language-Batch-green)](https://en.wikipedia.org/wiki/Batch_file)
![Downloads](https://img.shields.io/badge/Status-Active-brightgreen)

**A Powerful Windows Optimization Tool to Boost Your PC Performance**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Contributing](#-contributing) • [License](#-license)

</div>

---

## 📋 Overview

**Windows_Optimizer** is a comprehensive batch script designed to take full control of your Windows system, cleaning up unnecessary files, optimizing performance, and keeping your PC running at its best. Whether you're dealing with a sluggish system or just want preventative maintenance, this tool has everything you need.

> ⚡ **One-Click System Optimization** - Clean, Repair, and Boost Your PC Performance!

---

## ✨ Features

### 🗑️ **Temporary File Cleaning**
- Remove system temporary files
- Clear application cache and data
- Delete browser cache and cookies
- Clean Windows prefetch files
- Remove crash dump files

### 🔧 **System Repair**
- Scan System for corrupted files (SFC scan)
- Check Windows image health
- Scan Windows image for errors
- Restore Windows image integrity

### 📦 **Advanced Cleaning**
- **Log Files**
  - Clear system logs (.log, .old, .trace files)
  - Windows update logs
  - Event viewer logs (all channels)
  - Windows Defender logs and cache

- **Cache & Temporary Data**
  - Explorer thumbnail cache
  - Windows update cache
  - Memory dump files
  - Crash dumps and minidumps

- **Driver Files**
  - AMD driver remnants
  - NVIDIA driver cache
  - Intel driver files

### ⚡ **Performance Optimization**
- Enable Windows Ultimate Performance Power Plan
- Optimize DNS resolver cache
- Reset TCP/IP stack
- Reset Winsock settings
- Configure network interfaces

### 🛡️ **Safe Operations**
- Administrator privilege verification
- Automatic UAC elevation
- Error handling for locked files
- Safe file deletion procedures

---

## 🖥️ System Requirements

| Requirement | Specification |
|-------------|---------------|
| **OS** | Windows 10 / Windows 11 (64-bit) |
| **Privileges** | Administrator Rights Required |
| **Architecture** | x64 Processor |
| **Internet** | Optional (for GitHub access) |
| **Disk Space** | Varies (Usually 500MB+ freed) |

---

## 💾 Installation

### Method 1: Direct Download
1. Download `Windows_Optimizer.bat` from the repository
2. Right-click the file and select **"Run as Administrator"**
3. Allow UAC prompt when it appears

### Method 2: Clone Repository
```bash
git clone https://github.com/Jayasakthi-07/Windows_Optimizer.git
cd Windows_Optimizer
```

Then run:
```bash
Windows_Optimizer.bat
```

---

## 🎮 Usage

### Quick Start
1. **Launch the script** as Administrator
2. **Select an option** from the menu:

#### Menu Options:

| Option | Function |
|--------|----------|
| **1** | Delete Temporary Files & Deep Clean |
| **2** | Scan System & Repair Windows Image |
| **3** | View Program Information |
| **4** | Open GitHub Repository |
| **5** | Exit Program |

### Example Workflow
```
1. Run Windows_Optimizer.bat as Administrator
2. Press "1" to start deep cleaning
3. Wait for the process to complete
4. Press "2" to scan and repair system
5. Restart your PC for optimal results
```

---

## 🔍 What Gets Cleaned?

### Temporary Files Removed
```
✓ %TEMP% folder contents
✓ %APPDATA% cache files
✓ Windows SoftwareDistribution cache
✓ Prefetch files
✓ Thumbnail cache
✓ Crash dumps
✓ WER (Windows Error Reporting) logs
✓ Browser cookies
```

### System Optimizations Applied
```
✓ Clear DNS cache
✓ Reset TCP/IP settings
✓ Reset Winsock settings
✓ Enable Ultimate Performance power scheme
✓ Optimize network parameters
```

---

## ⚙️ Advanced Features

### System File Checker (SFC)
Automatically runs:
```
sfc /scannow
```

### Windows Image Repairs (DISM)
Executes:
```
DISM /Online /Cleanup-Image /CheckHealth
DISM /Online /Cleanup-Image /ScanHealth
DISM /Online /Cleanup-Image /RestoreHealth
```

### Power Plan Optimization
Enables the Ultimate Performance power scheme with optimized settings for maximum speed.

---

## 📊 Performance Benefits

After running Windows_Optimizer, you can expect:

- 🚀 **Faster Boot Times** - Delete unnecessary startup files
- 💨 **Improved System Speed** - Free up RAM and disk space
- 🎮 **Better Gaming Performance** - Enable ultimate performance mode
- 📉 **Reduced Disk Usage** - Reclaim gigabytes of space
- 🔧 **System Stability** - Repair corrupted Windows files
- 🧹 **Cleaner Registry** - Remove orphaned entries

---

## ⚠️ Important Notes

### Before Running:
- ⚡ **Run as Administrator** - This tool requires elevated privileges
- 💾 **Backup Important Data** - Always keep backups of your important files
- 🔄 **Close Applications** - Close unnecessary programs before running
- 🔌 **AC Power** - Keep your laptop plugged in during operation

### What It Does NOT Do:
- ❌ Does not delete personal files
- ❌ Does not modify user documents
- ❌ Does not uninstall programs
- ❌ Does not require internet connection (except for GitHub link)

---

## 🐛 Troubleshooting

### Issue: Script won't run
**Solution:** Right-click `Windows_Optimizer.bat` → Run as Administrator

### Issue: Some files couldn't be deleted
**Solution:** This is normal for files in use. Restart your PC and try again.

### Issue: Permission Denied Error
**Solution:** Ensure you're running with Administrator privileges. Some operations require system restart.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/YourFeature`)
3. **Commit** your changes (`git commit -m 'Add YourFeature'`)
4. **Push** to the branch (`git push origin feature/YourFeature`)
5. **Open** a Pull Request

### Suggestions Welcome:
- 🐛 Bug reports
- ✨ Feature requests
- 📚 Documentation improvements
- 🧪 Testing and feedback

---

## 📝 License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE.txt](LICENSE.txt) file for details.

```
Windows_Optimizer
Copyright (C) 2025 JAYASAKTHI

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
```

---

## 👨‍💻 Author

**JAYASAKTHI**
- 📧 Email: your.email@example.com
- 🐙 GitHub: [@Jayasakthi-07](https://github.com/Jayasakthi-07)
- 💼 Portfolio: your-portfolio.com

---

## 🌟 Show Your Support

If this project helped you, please consider:
- ⭐ Giving it a **star** on GitHub
- 🔔 Following for updates
- 📢 Sharing with others
- 💬 Providing feedback

---

## ✅ Tested On

- ✓ Windows 11 (Latest Build)
- ✓ Windows 10 (21H2)
- ✓ Windows Server 2022

---

## 📞 Support & Contact

- 📥 Open an [Issue](https://github.com/Jayasakthi-07/Windows_Optimizer/issues) for bugs
- 💡 Request features via [Discussions](https://github.com/Jayasakthi-07/Windows_Optimizer/discussions)
- 📧 Email for urgent matters

---

<div align="center">

### Made with ❤️ by JAYASAKTHI

**[⬆ Back to Top](#-windows_optimizer)**

</div>
