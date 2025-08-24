# Printer Problems Troubleshooting

This guide addresses issues with printers not working or failing to print.

## Symptoms
- Printer shows as "Offline" or "Not connected."
- Print jobs stuck in queue or not printing.
- Error messages like "Driver unavailable."

## Common Causes
- Printer is powered off or disconnected.
- Outdated or missing printer drivers.
- Network issues for wireless printers.

## Troubleshooting Steps
1. **Check Printer Status**:
   - Ensure printer is powered on and connected (USB or Wi-Fi).
   - Verify printer’s display shows "Ready."
2. **Clear Print Queue**:
   - Windows: Go to Control Panel > Devices and Printers, right-click printer, and select "See what’s printing" > Cancel All Documents.
   - macOS: Open System Preferences > Printers & Scanners, select printer, and clear queue.
3. **Update Drivers**:
   - Download latest drivers from the printer manufacturer’s website (e.g., HP, Canon).
   - Install and restart the printer/computer.
4. **Network Printers**:
   - Ensure printer and computer are on the same Wi-Fi network.
   - Check printer’s IP address matches network settings.
5. **Restart Print Spooler**:
   - Windows: Run `services.msc`, find "Print Spooler," restart service.
6. **Test Print**:
   - Print a test page directly from the printer’s control panel.
   - Try printing from another computer to isolate the issue.

## Tools and Resources
- **Checklist**: Use [Troubleshooting Checklist](../resources/troubleshooting_checklist.md).
- **External**: HP Printer Support (https://support.hp.com/us-en/printer).
