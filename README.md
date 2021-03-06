# WindowsOptimizer
There are many variants of this script. Read below for more info.

## Supported Windows Versions
- Windows 11
    1. Debloat Variant ([Here](https://github.com/haridhayal11/WindowsOptimizer#1-windows-11-debloat-variant-removes-microsoft-apps))
    2. No-Debloat Variant ([Here](https://github.com/haridhayal11/WindowsOptimizer#2-windows-11--no-debloat-variant-keeps-microsoft-apps))

- Windows 10 20H2 or later (testing)

- Windows 10 LTSC 2019,2021 ([Here](https://github.com/haridhayal11/WindowsOptimizer/tree/win10-ltsc))

## 1. Windows 11 Debloat Variant (Removes Microsoft Apps)

### What it does?
- Creates a System Restore Point.
- Removes 
    - OneDrive
    - Cortana
    - Bloat (Check [here](https://github.com/haridhayal11/WindowsOptimizer/blob/main/optimizer.ps1#L84) for a list)
- Runs O&O Shutup with Recommended Settings
- Disables 
    - Telemetry
    - Wifi Sense (Wifi will still work)
    - Location Tracking
    - Feedback
    - Tailored Experiences
    - Error reporting
    - Diagnostics Tracking Service
    - WAP Push Service
    - Home Groups services
    - Remote Assistance
    - Storage Sense
    - Superfetch service
    - Hibernation
    - Driver offering through Windows Update
    - Windows Update automatic restart
    - News and Interests
    - AutoLogger file and restricting directory
    - Unnessary services

- Restricts Windows Update P2P only to local network    
- Enables F8 boot menu
- Shows task manager details by default
- Changes default Explorer view to This PC
- Enables NumLock after startup
- Hides 3D Objects icon from This PC
- Removes Meet Now from taskbar
- Shows known file extensions

### How to Use Debloat Variant
1. Open Windows Terminal/Powershell (as Adminstrator)
2. Paste the string below into Windows Terminal/Powershell.
```
iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JDJTZ'))
```


## 2. Windows 11  No-Debloat Variant (Keeps Microsoft Apps)

### What it does?
- Everything from Debloat Variant except removal of Microsoft Apps.

### How to Use No-Debloat Variant
1. Open Windows Terminal/Powershell (as Adminstrator)
2. Paste the string below into Windows Terminal/Powershell.
```
iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JDJYM'))
```
