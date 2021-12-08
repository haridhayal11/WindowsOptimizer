# WindowsOptimizer
 Enhance the Windows Experience!

## Supported Windows Versions
- Windows 11
- Windows 10 20H2 or later

## How to Use
1. Open Windows Terminal/Powershell (as Adminstrator)
2. Paste the string below into Windows Terminal/Powershell.
```
iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JDJTZ'))
```

## What it does?
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
