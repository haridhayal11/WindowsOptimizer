# WindowsOptimizer
There are two variants of this script. Read below for more info.
1. [Debloat Variant](https://github.com/haridhayal11/WindowsOptimizer#debloat-version-removes-microsoft-apps)
2. [No-Debloat Variant](https://github.com/haridhayal11/WindowsOptimizer#no-debloat-version-keeps-microsoft-apps)


## Supported Windows Variants
- Windows 11
- Windows 10 20H2 or later


## Debloat Variant (Removes Microsoft Apps)

### What it does?
- Creates a System Restore Point.
- Removes 
    - OneDrive
    - Cortana
    - Bloat (Check [here](https://github.com/haridhayal11/WindowsOptimizer/blob/main/optimizer.ps1#L84) for a list)
- Runs O&O Shutup with Recommended Settings
- Disables 
    - Telemetry
    - Wifi Sense
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
    - Driver offering through Windows Update
    - News and Interests
    - Diagnostics Tracking Service
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


## No-Debloat Variant (Keeps Microsoft Apps)

### What it does?
- Everything from Debloat Variant except removal of Microsoft Apps.

### How to Use No-Debloat Variant
1. Open Windows Terminal/Powershell (as Adminstrator)
2. Paste the string below into Windows Terminal/Powershell.
```
iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JDJYM'))
```