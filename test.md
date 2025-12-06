## Xp
        https://archive.org/download/windows-xp-all-sp-msdn-iso-files-en-de-ru-tr-x86-x64/en_win_xp_pro_x64_with_sp2_vl_x13-41611.iso

        Supermium
        Supermium needs at least XP SP1, SS3, and around 2 GB of RAM to function properly.

        A screenshot of Supermium running on XP
        Supermium running
        Open Internet Explorer (or whatever browser you have installed)
        Navigate to http://win32subsystem.live/supermium/legacy/
        Download the Setup executable for your VM's bit width and run it
        You will get a few options in the setup. All of them are optional but I recommend installing the Noto Emoji font and creating shortcuts for Supermium. Hit OK
        If all went well, Supermium should be working!

        *Use a legal license key to activate.*

## Vista
        https://computernewb.com/isos/windows/Windows%20Vista%20SP2%20x64.iso

        Supermium
        Supermium is a Chromium fork that works in Vista. It needs around 2 GB of RAM to function.

        Supermium running in Windows Vista under QEMU
        Open Internet Explorer (or whatever browser you have installed)
        Navigate to http://win32subsystem.live/supermium/legacy/
        Download the Setup executable for your VM's bit width and run it
        You will get a few options in the setup. All of them are optional but I recommend installing the Noto Emoji font and creating shortcuts for Supermium. Hit OK
        If all went well, Supermium should be working!

        *Use a legal activation method for Windows Vista.*

## win7
        https://computernewb.com/isos/windows/en_windows_7_ultimate_with_sp1_x64_dvd_u_677332.iso

        Supermium
        Supermium is a Chromium fork that works in Windows 7. It needs around 2 GB of RAM to function.

        Supermium running in Windows 7 under QEMU
        Open Internet Explorer (or whatever browser you have installed)
        Navigate to http://win32subsystem.live/supermium/legacy/
        Download the Setup executable for your VM's bit width and run it
        You will get a few options in the setup. All of them are optional but I recommend installing the Noto Emoji font and creating shortcuts for Supermium. Hit OK
        If all went well, Supermium should be working!

        *Use a legal activation method for Windows 7.*

## win8.1
        https://computernewb.com/isos/windows/en_windows_embedded_8_1_industry_enterprise_x64_dvd_2710518.iso

        Supermium
        Supermium is a Chromium fork that works in Windows 8.1. It needs around 2 GB of RAM to function.

        Supermium running in Windows 8.1 under QEMU
        Open Internet Explorer (or whatever browser you have installed)
        Navigate to http://win32subsystem.live/supermium/legacy/
        Download the Setup executable for your VM's bit width and run it
        You will get a few options in the setup. All of them are optional but I recommend installing the Noto Emoji font and creating shortcuts for Supermium. Hit OK
        If all went well, Supermium should be working!

        If you don't like the Windows 8.1 Start Screen (does anyone?) you can download and install the latest release of Open Shell https://github.com/Open-Shell/Open-Shell-Menu/releases/latest to get a customizable start menu that by default looks similar to Windows 7

        *Use a legal activation method for Windows 8.1.*

## win10
        windows_10_iot_enterprise_ltsc
        https://computernewb.com/isos/windows/en-us_windows_10_iot_enterprise_ltsc_2021_x64_dvd_257ad90f.iso

        windows_10_stock
        https://computernewb.com/isos/windows/Windows%2010%2022H2.iso

        for browser you can use edge or download chrome from it

        *Use a legal activation method for Windows 10.*

## win11
        windows_11_iot_enterprise_ltsc
        https://computernewb.com/isos/windows/en-us_windows_11_iot_enterprise_ltsc_2024_x64_dvd_f6b14814.iso

        windows_11_stock
        https://computernewb.com/isos/windows/Windows%2011%2024H2.iso

        Bypassing Installation Requirements
        The IoT Enterprise LTSC ISO does not have restrictive installation requirements like the stock ISOs do. If you chose that ISO, skip this section.

        Consumer versions of Windows 11 have the arbitrary requirements of UEFI with Secure Boot enabled, TPM 2.0, and some CPU features. While it's technically possible to virtualize these in QEMU, it's quite a pain in the ass. Instead, bypassing these requirements is pretty simple.

        Once setup reaches the language selection screen, press Shift + F10 to open a command prompt. Run the following commands:

        reg add HKLM\SYSTEM\Setup\LabConfig
        reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassTPMCheck /d 1
        reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassSecureBootCheck /d 1
        reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassRAMCheck /d 1
        reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassCPUCheck /d 1

        You can now close command prompt and install Windows 11 as normal

        for browser you can use edge or download chrome from it

        *Use a legal activation method for Windows 11.*
