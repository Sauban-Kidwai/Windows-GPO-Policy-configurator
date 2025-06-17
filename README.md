## Windows Server 2016 GPO configurator for Computing Topics Unit

------

The questions below were answered and applied in the group policy editor - the result is in the chrome document attached


User Account Policies (24 Marks)

- Task 1: Password complexity requirements must be met.
- Task 2: All password must contain at least 14 characters.
- Task 3: A minimum of 15 different new passwords must be used before an old password can be employed again.
- Task 4: New passwords must be changed no later than 45 days.
- Task 5: Make sure that the built-in Administrator account is enabled.
- Task 6: Ensure that the built-in Guest account is not available.
- Task 7: A locked account can only be unlocked manually by an administrator.
- Task 8: Users have a maximum of 5 failed logon attempts before being locked out.
- Task 9: The account lockout counter resets following 20 minutes from an unsuccessful login attempt.
- Task 10: Servers disconnect clients when their logon hours expire.
- Task 11: Kerberos V5 Key Distribution Center must validate all session ticket requests.
- Task 12: The maximum time difference between the time on the client clock and the time on the domain controller that provides Kerberos authentication is 2 minutes.

User Rights (10 Marks)

- Task 13: Network access to the computer is only available to Administrators and Authenticated Users.
- Task 14: The server can only be shut down remotely by users in the Administrators group.
- Task 15: Only Administrators and Backup Operators are allowed to back up files and directories on the server.
- Task 16: Only the built-in Administrator is allowed to modify firmware environment values.
- Task 17: Only the built-in Administrator has the privilege to create symbolic links.
- Task 18: Only Administrators can run maintenance tasks on a volume, such as remote defragmentation.
- Task 19: No one can read all objects and properties in the directory, regardless of the protection on the objects and properties.
- Task 20: Ensure that standard users are not allowed to change the Trusted for Delegation setting on any computer object.
- Task 21: Only LOCAL SERVICE, NETWORK SERVICE are allowed to create audit records in the security event log.
- Task 22: Only LOCAL SERVICE, NETWORK SERVICE, Administrators can change the maximum memory that can be consumed by a process.

User Account Control (9 Marks)
- Task 23: Admin Approval Mode is required for the built-in Administrator account
- Task 24: Administrators receive prompts when executing administrative tasks.
- Task 25: All administrators must provide their credentials to authenticate when performing administrative tasks.
- Task 26: Standard users requesting for elevation are denied automatically.
- Task 27: All application installation requests must be approved by administrators.
- Task 28: The secure desktop must be used for all elevation prompts.
- Task 29: Only UIAccess applications installed in secure locations are permitted to run with elevated privileges.
- Task 30: UIAccess applications must use the secure desktop to prompt for elevation.
- Task 31: When a non-UAC compliant application tries to write to protected areas, implement virtualization for file and registry writes to user-specific locations.

Network Security (9 Marks)
- Task 32: Domain members must use a minimum of 128-bit key strength for encrypting secure channel data.
- Task 33: A domain member must attempt to negotiate encryption for all secure channel traffic that it initiates.
- Task 34: The Server Message Block (SMB) redirector must not send plaintext passwords to non-Microsoft SBM servers that do not support password encryption during authentication.
- Task 35: An anonymous user is not allowed to enumerate the accounts and shares in the Security Accounts Manager.
- Task 36: Credentials and passwords are not to be stored for later use when domain authentication is requested.
- Task 37: Client LDAP BIND requests must be signed whenever possible.
- Task 38: All NTLM SSP based clients can require the negotiation of 128-bit encryption and NTLMv2 session security.
- Task 39: Only use NTLMv2 for LAN Manager authentication level and refuse LM & NTLM protocols.
- Task 40: All clients are not allowed to print to Internet printers over HTTP.

Windows Firewall (14 Marks)
- Task 41: Enable Windows firewall in all profiles (Domain, Public, and Private).
- Task 42: Block all inbound connections by default in all profiles (Domain, Public, and Private).
- Task 43: Allow all outbound connections by default in all profiles (Domain, Public, and Private)
- Task 44: Allow local firewall rules written by local administrators to be merged with rules distributed through Group Policy in all profiles (Domain, Public, Private).
- Task 45: Create an inbound rule, named HTTP, that allows incoming HTTP connections in all profiles.
- Task 46: Create an outbound rule, named TELNET, that blocks outgoing TELNET connections in all profiles.
- Task 47: Create a new firewall rule, named 134.7, that provides authentication exemption for computers within the IP address range from 134.7.1.100 to 134.7.1.110.

Audit Policies (14 Marks)
- Task 48: Allow audit policy subcategory settings to override audit policy category settings.
- Task 49: Do not audit the use of backup and restore privilege.
- Task 50: Do not audit the access of global system objects.
- Task 51: Audit both Success and Failure events of account management activity.
- Task 52: Audit all Success events of directory service access.
- Task 53: Do not audit logon events.
- Task 54: Do not audit object access.
- Task 55: Audit all Success events of policy change.
- Task 56: Audit all Failure events of privilege use.
- Task 57: Do not audit process tracking.
- Task 58: Audit all Failure system events such as restart or shutdown or other events that may affect the system security or security logs.
- Task 59: Set maximum system log size to 65,536KB
- Task 60: Overwrite the oldest events in the system log to continue logging new events when the system log file reaches its maximum size.
- Task 61: Do not allow local guests group on older Windows to access the system log.

Software Restriction Policies and Additional Security Settings (20 Marks)
- Task 62: Do not allow users to run C:\Windows\regedit.exe
- Task 63: Turn off media Autoplay from all drives.
- Task 64: Enable Windows Update: automatically download the updates daily and install at 1.00AM.
- Task 65: Disable remote desktop sharing.
- Task 66: Requiring RPC clients to authenticate prior to communicating with an RPC server.
- Task 67: Turn off the Windows messenger customer experience improvement program
- Task 68: Turn on Security Center for all domain PCs.
- Task 69: Disable FTP publishing service.
- Task 70: Disable Telephony service.
Task 71: Disable SmartCard service.
