# Network Issues Troubleshooting

This guide covers common network connectivity problems encountered in IT helpdesk support.

## Symptoms
- Unable to connect to the internet or local network.
- Slow or intermittent connection.
- "No network" or "Limited connectivity" errors.

## Common Causes
- Loose or unplugged Ethernet cables.
- Incorrect Wi-Fi credentials or weak signal.
- Router/modem issues or incorrect IP/DNS settings.

## Troubleshooting Steps
1. **Check Physical Connections**:
   - Ensure Ethernet cables are securely plugged in.
   - Verify Wi-Fi is enabled and connected to the correct network.
2. **Restart Networking Equipment**:
   - Power cycle the router/modem (unplug for 30 seconds, then plug back in).
   - Restart the computer’s network adapter.
3. **Verify Network Settings**:
   - Windows: Run `ipconfig /all` in Command Prompt to check IP and DNS.
   - macOS: Check Network settings in System Preferences.
   - Ensure DHCP is enabled or static IP is correct.
4. **Test Connectivity**:
   - Ping the gateway: `ping 192.168.1.1`.
   - Ping an external site: `ping google.com`.
5. **Advanced Diagnostics**:
   - Update network drivers from the manufacturer’s website.
   - Use Wireshark for packet analysis (see [Diagnostic Tools](../resources/diagnostic_tools.md)).
6. **Escalate if Needed**:
   - Contact ISP for external issues or IT admin for network configuration.

## Tools and Resources
- **Checklist**: Use the [Troubleshooting Checklist](../resources/troubleshooting_checklist.md) for step-by-step verification.
- **External**: Microsoft’s Network Troubleshooter (https://support.microsoft.com/en-us/windows/fix-network-connection-issues-in-windows).
