```markdown
![Qemu-Vortax](assets/qemuvortax_v1.8.png)

# Qemu-Vortax — OS Images & Quick Copy Commands ✨

Note: Only the content inside code blocks is intended to be copied. Each code block contains a single command or a single direct link so you can copy items individually. Explanations and notes are plain text.

---

## Windows XP 🪟🧩
![Windows XP screenshot](assets/xp.png)

Download ISO (this release is not auto-downloaded here; use your local ISO if you purchased it):

https://archive.org/download/windows-xp-all-sp-msdn-iso-files-en-de-ru-tr-x86-x64/en_win_xp_pro_x64_with_sp2_vl_x13-41611.iso

Copyable download commands (if you have a direct link and want to download):

```bash
wget -c "https://archive.org/download/windows-xp-all-sp-msdn-iso-files-en-de-ru-tr-x86-x64/en_win_xp_pro_x64_with_sp2_vl_x13-41611.iso" -O en_win_xp_pro_x64_with_sp2_vl_x13-41611.iso
```

```bash
curl -L "https://archive.org/download/windows-xp-all-sp-msdn-iso-files-en-de-ru-tr-x86-x64/en_win_xp_pro_x64_with_sp2_vl_x13-41611.iso" -o en_win_xp_pro_x64_with_sp2_vl_x13-41611.iso
```

Supermium (project page) — copyable:

```text
http://win32subsystem.live/supermium/legacy/
```

### Activation (Using Microsoft Activation Scripts)
Follow these steps to activate. For Windows XP use your purchased local MAS file (do NOT download the public MAS_AIO for XP if you have a local licensed copy).

1. Install PowerShell 2.0 (if needed).
2. Install .NET Framework 3.5 SP1 (if needed).
3. Use your local MAS file for XP (example commands to run your local file shown below).
4. Run the script and choose: 3 → TSForge 1 → Activate Windows

Run the local XP MAS script (replace path with your actual path):

```cmd
cd /d "C:\path\to\your\mas"
MAS_AIO_XP.cmd
```

If you ever need the public MAS AIO (for non-XP systems), the official raw URL is:

```text
https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd
```

---

## Windows Vista 🪟✨
![Windows Vista screenshot](assets/vista.png)

You can download the ISO from this link:
https://computernewb.com/isos/windows/Windows%20Vista%20SP2%20x64.iso

Copyable download commands:

```bash
wget -c "https://computernewb.com/isos/windows/Windows%20Vista%20SP2%20x64.iso" -O Windows_Vista_SP2_x64.iso
```

```bash
curl -L "https://computernewb.com/isos/windows/Windows%20Vista%20SP2%20x64.iso" -o Windows_Vista_SP2_x64.iso
```

Supermium (project page) — copyable:

```text
http://win32subsystem.live/supermium/legacy/
```

### Activation (Using Microsoft Activation Scripts)
1. Install PowerShell 2.0 (if needed).
2. Install .NET Framework 3.5 SP1 (if needed).
3. Download MAS script.
4. Run script → choose: 3 → TSForge 1 → Activate Windows

Download MAS (copyable commands):

```bash
wget -O MAS_AIO.cmd "https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd"
```

```bash
curl -L "https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd" -o MAS_AIO.cmd
```

Or use PowerShell to download (copyable):

```powershell
powershell -Command "Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd' -OutFile MAS_AIO.cmd"
```

Run MAS (copyable):

```cmd
MAS_AIO.cmd
```

---

## Windows 7 🪟🎉
![Windows 7 screenshot](assets/win7.png)

You can download the ISO from this link:
https://computernewb.com/isos/windows/en_windows_7_ultimate_with_sp1_x64_dvd_u_677332.iso

Copyable download commands:

```bash
wget -c "https://computernewb.com/isos/windows/en_windows_7_ultimate_with_sp1_x64_dvd_u_677332.iso" -O en_windows_7_ultimate_with_sp1_x64.iso
```

```bash
curl -L "https://computernewb.com/isos/windows/en_windows_7_ultimate_with_sp1_x64_dvd_u_677332.iso" -o en_windows_7_ultimate_with_sp1_x64.iso
```

Supermium (project page) — copyable:

```text
http://win32subsystem.live/supermium/legacy/
```

### Activation (Using Microsoft Activation Scripts)
1. Install PowerShell 2.0 (if needed).
2. Install .NET Framework 3.5 SP1 (if needed).
3. Download MAS script.
4. Run script → choose: 3 → TSForge 1 → Activate Windows

Download MAS (copyable):

```bash
wget -O MAS_AIO.cmd "https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd"
```

Run MAS (copyable):

```cmd
MAS_AIO.cmd
```

---

## Windows 8.1 🪟⚙️
![Windows 8.1 screenshot](assets/win8.1.png)

You can download the ISO from this link:
https://computernewb.com/isos/windows/en_windows_embedded_8_1_industry_enterprise_x64_dvd_2710518.iso

Copyable download commands:

```bash
wget -c "https://computernewb.com/isos/windows/en_windows_embedded_8_1_industry_enterprise_x64_dvd_2710518.iso" -O en_windows_embedded_8_1.iso
```

```bash
curl -L "https://computernewb.com/isos/windows/en_windows_embedded_8_1_industry_enterprise_x64_dvd_2710518.iso" -o en_windows_embedded_8_1.iso
```

Open Shell (optional) — copyable link:

```text
https://github.com/Open-Shell/Open-Shell-Menu/releases/latest
```

### Activation (Using Microsoft Activation Scripts)
1. Install PowerShell 2.0 (if needed).
2. Install .NET Framework 3.5 SP1 (if needed).
3. Download MAS script.
4. Run script → choose: 3 → TSForge 1 → Activate Windows

Download MAS (copyable):

```bash
wget -O MAS_AIO.cmd "https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd"
```

Run MAS (copyable):

```cmd
MAS_AIO.cmd
```

---

## Windows 10 🪟🚀
![Windows 10 screenshot](assets/win10.png)

You can download the ISO (IoT LTSC) from this link:
https://computernewb.com/isos/windows/en-us_windows_10_iot_enterprise_ltsc_2021_x64_dvd_257ad90f.iso

Copyable download command (IoT LTSC):

```bash
wget -c "https://computernewb.com/isos/windows/en-us_windows_10_iot_enterprise_ltsc_2021_x64_dvd_257ad90f.iso" -O win10_iot_ltsc_2021_x64.iso
```

Stock Windows 10 ISO:
https://computernewb.com/isos/windows/Windows%2010%2022H2.iso

Copyable download command (stock):

```bash
wget -c "https://computernewb.com/isos/windows/Windows%2010%2022H2.iso" -O Windows_10_22H2.iso
```

### Activation (Using Microsoft Activation Scripts)
1. Install PowerShell 2.0 (if needed).
2. Install .NET Framework 3.5 SP1 (if needed).
3. Download MAS script.
4. Run script → choose: 3 → TSForge 1 → Activate Windows

Download MAS (copyable):

```bash
wget -O MAS_AIO.cmd "https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd"
```

Run MAS (copyable):

```cmd
MAS_AIO.cmd
```

---

## Windows 11 🪟🔒
![Windows 11 screenshot](assets/win11.png)

You can download the ISO (IoT LTSC — fewer restrictions) from this link:
https://computernewb.com/isos/windows/en-us_windows_11_iot_enterprise_ltsc_2024_x64_dvd_f6b14814.iso

Copyable download command (IoT LTSC):

```bash
wget -c "https://computernewb.com/isos/windows/en-us_windows_11_iot_enterprise_ltsc_2024_x64_dvd_f6b14814.iso" -O win11_iot_ltsc_2024_x64.iso
```

Stock Windows 11 ISO:
https://computernewb.com/isos/windows/Windows%2011%2024H2.iso

Copyable download command (stock):

```bash
wget -c "https://computernewb.com/isos/windows/Windows%2011%2024H2.iso" -O Windows_11_24H2.iso
```

Bypass install checks (when at the language selection screen press Shift+F10 to open Command Prompt). Run each command below separately (one per block).

```cmd
reg add HKLM\SYSTEM\Setup\LabConfig
```

```cmd
reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassTPMCheck /d 1
```

```cmd
reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassSecureBootCheck /d 1
```

```cmd
reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassRAMCheck /d 1
```

```cmd
reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassCPUCheck /d 1
```

### Activation (Using Microsoft Activation Scripts)
1. Install PowerShell 2.0 (if needed).
2. Install .NET Framework 3.5 SP1 (if needed).
3. Download MAS script.
4. Run script → choose: 3 → TSForge 1 → Activate Windows

Download MAS (copyable):

```bash
wget -O MAS_AIO.cmd "https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd"
```

Run MAS (copyable):

```cmd
MAS_AIO.cmd
```

---

Thank you for using Qemu-Vortax. If you want:
- different file naming conventions for downloaded ISOs,
- SHA256 checksum commands added,
- or removal of curl/wget alternatives to keep only one downloader,

tell me which option you prefer and I will update the document with the chosen style. 🎨✨
```