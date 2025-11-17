---

# Qemu-Vortax V1.8
![Qemu-Vortax](assets/qemuvortax_v1.8.png)

Run any operating system (ISO, QCOW2, or compressed archive) directly on **GitHub Actions** with full graphical access through **RDP**, **VNC** and **NoMachine** Via **Tailscale** and **Ngrok**



![Forks](https://img.shields.io/github/forks/qemuvortax/qemuvortax?style=plastic&logo=github&logoColor=white&color=00bfff).           ![Tag](https://img.shields.io/github/v/tag/qemuvortax/qemuvortax?style=plastic&logo=github&logoColor=white&color=00bfff)

---

## ⚙️ Overview

**Qemu-Vortax V1.8** is an educational and experimental workflow that boots complete virtual machines inside GitHub Actions using QEMU + XFCE.  
You can run Linux distributions, Android builds, or pre-made cloud images (ISO/QCOW2) from any source.

> 🧠 For educational use only.  
> The author holds no responsibility for bans, data loss, or misuse.  
> Use entirely **at your own risk**.

---

## 🚀 Features

- 🧩 Supports `.iso`, `.qcow2`, `.zip`, `.7z`, `.rar`, `.tar`, `.tar.gz`
- 💻 XFCE desktop accessible via RDP, VNC, or NoMachine  
- 🛰️ Private encrypted tunnel through Tailscale or Ngrok
- 📦 Automatic decompression for archives  
- 🔁 Preset OS templates ready to boot  
- 🧠 Auto-detects ISO vs QCOW2 modes  
- 👾 Fixable choice between UEFI and BIOS
- ⏱️ Runtime limiter to control session length  
- 🌐 Cross-device access (Windows, macOS, Linux, Android)  
- 💾 Temporary QCOW2 storage for realistic disk simulation  
- ⚡ Boots in under 4–5 minutes depending on image size    

---

## 🛠️ Usage Guide

### 1. Fork the repository  
Click **Fork** on the project page.

### 2. Add your Auth Keys  

Go to **Settings → Secrets → Actions → New repository secret** and add the following:

- Name: `TAILSCALE_AUTHKEY`  
  Value: your Tailscale key  

- Name: `NGROK_AUTH`  
  Value: your Ngrok authtoken

### 3. Run the workflow  
1. Open the **Actions** tab.  
2. Select **Qemu-Vortax V1.8**.  
3. Click **Run workflow** and fill the inputs.

---

## 🧾 Inputs

| Input | Description | Example |
|-------|--------------|----------|
| `system_choice` | Pre-set OS to run | `mint`, `ubuntu`, `kali`, `deepin` |
| `boot_mode` | Boot type (`iso` or `qcow2`) | `iso` |
| `source_url` | Custom URL (MediaFire, Mega, direct) | `https://example.com/os.iso` |
| `vm_name` | VM name | `test-linux` |
| `runtime` | Session duration in minutes | `350` |
| `connection_method` | `tailscale` or `ngrok` | `tailscale` |
| `connection_program` | `RDP`, `VNC`, `NoMachine` | `RDP` |
| `bios_mode` | Firmware mode (`UEFI` or `BIOS`) | `UEFI` |

> ⚠️ Do not include spaces in URLs.  
> Match boot mode to file type.  
> Archives are automatically extracted if supported.

---

## 🧩 Pre-set Systems

| System | Boot Type | Description | Screenshot |
|--------|------------|--------------|-------------|
| `bazite` | ISO | Minimal distro focused on performance and clean design. | ![Bazite](assets/bazite.png) |
| `bliss` | ISO/QCOW2 | Android-based OS with Google Apps pre-installed. | ![Bliss](assets/bliss.png) |
| `centos_qcow2` | QCOW2 | CentOS Stream 10 GenericCloud image for stable enterprise environments. | ![CentOS](assets/centos_qcow2.png) |
| `cutefish` | ISO | CutefishOS 22.04, Ubuntu-based system with a clean macOS-like interface. | ![Cutefish](assets/cutefish.png) |
| `deepin` | ISO/QCOW2 | Deepin Linux with an elegant UI and strong customization. | ![Deepin](assets/deepin.png) |
| `garuda_mokka` | ISO | Garuda Linux Mokka edition for gaming and speed. | ![Garuda](assets/garuda.png) |
| `kali` | ISO/QCOW2 | Kali Linux for penetration testing and ethical hacking labs. | ![Kali](assets/kali.png) |
| `manjaro` | ISO | Manjaro GNOME 25.0.10, a fast and user-friendly Arch-based distribution. | ![Manjaro](assets/manjaro.png) |
| `mint` | ISO/QCOW2 | Linux Mint XFCE edition for smooth and modern experience. | ![Mint](assets/mint.png) |
| `neon` | ISO | KDE Neon with the latest Plasma environment. | ![Neon](assets/neon.png) |
| `pear` | ISO | Pear Linux, macOS-style Ubuntu derivative focused on elegance and simplicity. | ![Pear](assets/pear.png) |
| `pop_os` | ISO/QCOW2 | Pop!_OS optimized for developers and creators. | ![PopOS](assets/popos.png) |
| `ubuntu` | ISO | Classic Ubuntu desktop with XFCE, stable and lightweight. | ![Ubuntu](assets/ubuntu.png) |
| `win7` | QCOW2 | Windows 7 Professional with classic interface and broad software support. | ![Win7](assets/win7.png) |
| `debian_qcow2` | QCOW2 | Debian 12 Bookworm cloud image preconfigured for QEMU. | ![Debian](assets/debian_qcow2.png) |

> All previous releases (V1.3, V1.4, V1.5, V1.6, V1.7) are included as previous released.

---

## 🖥️ Connection Details

| Type | Address | Tool |
|------|----------|------|
| RDP | `ip:3389` | Remote Desktop Client |
| VNC | `ip:5900` | VNC Viewer / Remmina |
| NoMachine | `ip:4000` | Fast remote desktop |
| Tailscale | secure | Private VPN-style access |
| Ngrok | secure | Private tunnel forward access |

> When connected through RDP or NoMachine, open **Connect_VNC.sh** inside the desktop to view the QEMU display.

---

## ⚡ Performance Tips

- Use `qcow2` for faster subsequent boots.  
- Longer runtime = longer session before auto shutdown.  
- Avoid huge compressed archives for quicker starts.  
- Verify links before running custom sources.

---

## 🧠 Credits

Developed by **Mohamed Ahmed Saad**  
Project: **Qemu-Vortax V1.8**  
Goal: Simplify and accelerate virtual machine testing in the cloud.

---

## ⚖️ License and Disclaimer

Released under the **MIT License**.  
You may use, modify, and redistribute with attribution.  

This project is for educational and experimental purposes only.  
By running it, you accept full responsibility for any consequences.

---
