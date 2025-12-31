# Ticket 3 – File Access / Permission Issue

## Issue
User cannot access a shared folder. Access is denied when trying to open the folder.

## Environment
- Windows 11 VM
- Local folder used for simulation

## Tools Used
- Folder Properties → Security Tab

## Troubleshooting Steps
1. User attempted to open folder → received “Access Denied” error  

2. Checked folder permissions: Right-click → Properties → Security  

3. Added user account to allowed group / restored permissions  

4. Retested folder access → folder opens successfully

## Root Cause
Folder permissions were incorrectly set, preventing the user from accessing it.

## Resolution
Restored proper folder permissions for the user account.

## Verification
User successfully opened and accessed files in the folder.

## Screenshots
[Before](../Screenshots/ticket3-before.png)
[Progress](../Screenshots/ticket3-progress.png)
[After](../Screenshots/ticket3-after.png)




