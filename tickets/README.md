# Ticket: Password Reset / Account Lockout

**Ticket ID:** HD-001  
**User Issue:** User unable to log in after password change  

## Environment
- Windows 10
- Active Directory domain user

## Troubleshooting Steps
1. Verified user account status in Active Directory
2. Confirmed account was locked due to multiple failed login attempts
3. Reset password and unlocked account
4. Confirmed password met domain complexity requirements

## Resolution
User successfully logged in after password reset. No further issues reported.

## Root Cause
User entered incorrect password multiple times after recent password change.

## Notes
Educated user on password requirements and lockout policy.

#########################################################################################################

# Ticket: Wi-Fi Connectivity Issue

**Ticket ID:** HD-002  
**User Issue:** Unable to connect to company Wi-Fi  

## Environment
- Windows 10 laptop
- Wireless network connection

## Troubleshooting Steps
1. Verified Wi-Fi adapter was enabled
2. Ran `ipconfig` to check IP address assignment
3. Detected invalid IP (169.254.x.x)
4. Renewed IP address using `ipconfig /release` and `ipconfig /renew`
5. Flushed DNS cache

## Resolution
Device obtained valid IP address and successfully connected to network.

## Root Cause
DHCP lease failure due to temporary network issue.

## Notes
Advised user to restart device if issue reoccurs.

#########################################################################################################

# Ticket: Outlook Email Not Syncing

**Ticket ID:** HD-003  
**User Issue:** Outlook not receiving new emails  

## Environment
- Windows 10
- Microsoft Outlook (Desktop)

## Troubleshooting Steps
1. Verified internet connectivity
2. Confirmed Outlook was not in Offline Mode
3. Restarted Outlook application
4. Repaired Outlook profile
5. Verified mailbox sync status

## Resolution
Email sync restored after repairing Outlook profile.

## Root Cause
Corrupted Outlook profile preventing sync.

## Notes
Recommended restarting Outlook periodically and reporting future sync issues.
