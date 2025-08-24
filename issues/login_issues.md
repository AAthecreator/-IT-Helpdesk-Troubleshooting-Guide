# Login Issues Troubleshooting

This guide covers common login problems, including failed logins and account lockouts, for IT helpdesk support.

## Symptoms
- "Incorrect username or password" error.
- Account locked after multiple failed attempts.
- Slow login or "Preparing Windows" delays.

## Common Causes
- Incorrect credentials or caps lock enabled.
- Account lockout due to security policies (e.g., Active Directory settings).
- Network issues preventing authentication (e.g., domain controller unreachable).

## Troubleshooting Steps
1. **Verify Credentials**:
   - Confirm username and password; check for typos or caps lock.
   - Ensure user is logging into the correct domain (if using Active Directory).
2. **Reset Password**:
   - **End User**: Use "Forgot Password" link on login screen or company portal.
   - **Admin**: Reset password via Active Directory Users and Computers or helpdesk tool (e.g., Zendesk, Freshservice).
3. **Check Account Status**:
   - Use Active Directory to verify if the account is locked, disabled, or expired.
   - Unlock account: `net user username /active:yes` (Command Prompt) or AD interface.
4. **Network Authentication**:
   - Ensure the computer is connected to the network (see [Network Issues](../issues/network_issues.md)).
   - Ping the domain controller: `ping dc.company.com`.
5. **Clear Cached Credentials**:
   - **Windows**: Log in with a local admin account and clear cached profiles if corrupted.
   - **macOS**: Delete cached credentials in Keychain Access if needed.
6. **Check Group Policies**:
   - Verify password policies (e.g., complexity, expiration) in Active Directory.
   - Ensure no misconfigured GPOs are causing delays.
7. **Test with Another Account**:
   - Try logging in with a different account to isolate user-specific issues.
8. **Escalate if Needed**:
   - Contact senior IT for domain controller issues or account recovery.

## Tools and Resources
- **Checklist**: Refer to [Troubleshooting Checklist](../resources/troubleshooting_checklist.md).
- **Tools**: Active Directory Users and Computers, PowerShell for account management.
- **External**: Microsoft’s Account Lockout Guide (https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/account-lockout-policy).
