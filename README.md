# WindowsOptimizer for LTSC

## Supported Windows Versions
- Windows 10 LTSC 2021
- Windows 10 LTSC 2019 

### What it does?
- Creates a System Restore Point.
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

### How to Use
1. Open Windows Terminal/Powershell (as Adminstrator)
2. Paste the string below into Windows Terminal/Powershell.
```
iex ((New-Object System.Net.WebClient).DownloadString('https://bit.ly/3qB9iG4'))
```

