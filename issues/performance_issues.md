# Performance Issues Troubleshooting

This guide helps resolve slow computer performance issues commonly reported to IT helpdesk teams.

## Symptoms
- System lags or responds slowly to inputs.
- Applications take long to open or crash.
- High CPU, memory, or disk usage reported.

## Common Causes
- Insufficient memory (RAM) or disk space.
- Too many background processes or startup programs.
- Malware, outdated drivers, or system misconfiguration.

## Troubleshooting Steps
1. **Check Resource Usage**:
   - **Windows**: Open Task Manager (Ctrl+Shift+Esc) to view CPU, Memory, and Disk usage. Identify high-usage processes.
   - **macOS**: Use Activity Monitor (Applications > Utilities) to monitor system resources.
   - End unnecessary processes (e.g., close unused apps).
2. **Free Up Disk Space**:
   - Run Disk Cleanup (Windows) or delete unnecessary files (macOS).
   - Check storage: Ensure at least 10-20% of the drive is free.
3. **Manage Startup Programs**:
   - **Windows**: In Task Manager, go to Startup tab and disable non-essential programs.
   - **macOS**: Go to System Preferences > Users & Groups > Login Items and remove unneeded apps.
4. **Update System and Drivers**:
   - Run Windows Update or macOS Software Update to install patches.
   - Update drivers (e.g., graphics, chipset) from manufacturer websites.
5. **Scan for Malware**:
   - Use Windows Defender or a third-party antivirus (e.g., Malwarebytes) to scan and remove threats.
   - **macOS**: Use built-in XProtect or a tool like Malwarebytes.
6. **Optimize Settings**:
   - **Windows**: Adjust for best performance in System Properties > Advanced > Performance Settings.
   - **macOS**: Reduce animations in System Preferences > Accessibility > Display.
7. **Advanced Steps**:
   - Run `sfc /scannow` (Windows) to repair system files.
   - Check for memory leaks using Resource Monitor or Activity Monitor.
   - Consider hardware upgrades (e.g., add RAM, switch to SSD) if issues persist.
8. **Escalate if Needed**:
   - Contact senior IT for hardware diagnostics or system reimaging.

## Tools and Resources
- **Checklist**: Use [Troubleshooting Checklist](../resources/troubleshooting_checklist.md) for step-by-step verification.
- **External Tools**: HWMonitor for temperature checks, CrystalDiskInfo for drive health.
- **References**: Microsoft’s Performance Troubleshooter (https://support.microsoft.com/en-us/windows/optimize-windows-for-better-performance).
