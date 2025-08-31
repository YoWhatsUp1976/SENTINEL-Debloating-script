# SENTINEL v1.0

**Windows System Optimizer & Security Tools Installer**

A comprehensive tool for removing Windows bloatware and installing essential security/privacy tools with built-in threat detection capabilities.

## Important Disclaimer

**FOR EDUCATIONAL AND AUTHORIZED USE ONLY**

- Only use on systems you own or have explicit permission to modify
- Always create a system backup before running
- Test in a virtual environment first if possible
- Use responsibly and in compliance with applicable laws

## Features

### System Optimization
- **Bloatware Removal**: Removes 40+ common Windows bloatware applications
- **Privacy Enhancement**: Disables telemetry and tracking features
- **Performance Optimization**: Applies Windows performance tweaks
- **Firewall Configuration**: Sets up security-focused firewall rules

### Security Tools Installation
- **Network Analysis**: Wireshark, Nmap, PuTTY, WinSCP
- **Privacy Tools**: Tor Browser, VeraCrypt, KeePass, GPG4Win
- **System Monitoring**: Sysinternals suite, Process Hacker, Malwarebytes
- **Development Tools**: Git, Python, VS Code, Notepad++

### Threat Detection
- **Process Analysis**: Identifies suspicious running processes
- **Network Monitoring**: Detects unusual network connections
- **Startup Inspection**: Scans startup programs for threats
- **Registry Analysis**: Checks for persistence mechanisms
- **File System Scan**: Examines common malware locations

## Requirements

- **Operating System**: Windows 10/11
- **Privileges**: Administrator rights required for full functionality
- **Internet Connection**: Required for downloading tools
- **Python**: 3.6+ (for running the script)

### Python Dependencies
```bash
pip install requests
```

## Installation & Usage

### Quick Start
1. **Download** the script to your Windows machine
2. **Open PowerShell as Administrator**
3. **Navigate** to the script directory
4. **Run** the tool:
   ```bash
   python SENTINEL.py
   ```

### Interactive Menu Options

```
1. Remove Bloatware Only     - Clean Windows apps
2. Install Network Tools     - Wireshark, Nmap, etc.
3. Install Privacy Tools     - Tor, VeraCrypt, etc.
4. Install Development Tools - Git, Python, VS Code
5. SENTINEL Threat Scan      - Custom security scan
6. Full Optimization         - Complete system setup
7. Create Restore Point      - Backup current state
8. Exit                      - Close application
```

## What Gets Removed

### Microsoft Bloatware
- Xbox services and games
- Bing Weather, Maps, News
- Skype, People, Camera apps
- Office Hub, Feedback Hub
- Solitaire, 3D Builder
- Mixed Reality Portal

### Third-Party Bloatware
- Candy Crush, Bubble Witch
- Facebook, Twitter apps
- Spotify, Pandora
- Adobe Photoshop Express
- Various OEM applications

## Installed Security Tools

### Network & Analysis
- **Wireshark** - Network protocol analyzer
- **Nmap** - Network discovery and security auditing
- **Burp Suite** - Web application security testing
- **PuTTY** - SSH/Telnet client
- **WinSCP** - Secure file transfer

### Privacy & Encryption
- **Tor Browser** - Anonymous web browsing
- **VeraCrypt** - Full disk encryption
- **KeePass** - Password management
- **GPG4Win** - Email/file encryption

### System Monitoring
- **Sysinternals Suite** - Advanced system utilities
- **Process Hacker** - Process/system monitor
- **Malwarebytes** - Anti-malware protection
- **Portable Tools** - Nirsoft utilities, TCPView, Autoruns

## Threat Detection Capabilities

SENTINEL includes a custom behavioral detection engine that identifies:

- **Suspicious Processes**: Programs running from unusual locations
- **Network Anomalies**: Connections to commonly exploited ports
- **Startup Persistence**: Malicious startup entries
- **File System Threats**: Executables in temporary directories
- **Registry Persistence**: Unusual system services

## Privacy Optimizations

- Disables Windows telemetry collection
- Turns off advertising ID tracking
- Blocks location access for apps
- Disables diagnostic data sharing
- Configures privacy-focused settings

## System Changes

### Registry Modifications
- Telemetry collection settings
- Advertising preferences
- Location access controls
- Search and Cortana settings
- File explorer optimizations

### Firewall Rules
- Blocks Microsoft telemetry servers
- Prevents advertising connections
- Enables enhanced protection profiles

## Safety Features

- **Restore Point Creation**: Automatic system backup before changes
- **Admin Privilege Checking**: Ensures proper permissions
- **Error Handling**: Graceful failure management
- **Detailed Logging**: Comprehensive operation reporting
- **Non-destructive Options**: Most operations are reversible

## Reporting

SENTINEL generates detailed reports including:
- List of removed applications
- Successfully installed tools
- Applied system optimizations
- Detected security threats
- Operation timestamps

Reports are saved to: `~/SENTINEL_optimization_report.json`

## Troubleshooting

### Common Issues

**"Administrator privileges required"**
- Right-click PowerShell → "Run as administrator"
- Ensure UAC is not blocking the application

**Chocolatey installation fails**
- Check internet connection
- Verify PowerShell execution policy
- Try running: `Set-ExecutionPolicy Bypass -Scope Process`

**Tool installation errors**
- Ensure sufficient disk space
- Check antivirus isn't blocking downloads
- Verify network connectivity

**Some apps won't uninstall**
- Apps may not be present on your system
- Some system apps require special removal procedures
- Check Windows version compatibility

##  Reversing Changes

### Restore System
1. Use created restore point: `System Properties > System Restore`
2. Reinstall removed apps from Microsoft Store
3. Reset privacy settings in Windows Settings

### Manual Reversals
- Re-enable telemetry: Windows Settings > Privacy
- Reinstall apps: Microsoft Store
- Restore firewall: Windows Security settings

##  Performance Impact

**Expected Improvements:**
- Faster boot times (reduced startup apps)
- Lower memory usage (fewer background services)
- Improved privacy (disabled tracking)
- Enhanced security (firewall rules + tools)

##  Contributing

Contributions welcome! Please:
- Test thoroughly before submitting
- Follow existing code style
- Update documentation for new features
- Ensure compatibility with Windows 10/11

##  Support

For issues or questions:
- Check the troubleshooting section above
- Review Windows event logs for detailed errors
- Ensure you're running with administrator privileges
- Verify your Windows version is supported

##  Legal Notice

This tool is provided for educational and legitimate system administration purposes only. Users are responsible for:
- Ensuring they have authorization to modify target systems
- Complying with applicable laws and regulations
- Understanding the implications of system modifications
- Using tools ethically and responsibly



---

**Created by YOWHATSUPIMGOOD**  
