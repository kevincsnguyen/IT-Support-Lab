# IT Support Lab

## Overview
This project demonstrates hands-on experience troubleshooting common IT support issues in a Windows virtual environment, similar to real-world help desk operations.

## Environment
- Windows 10/11 (VirtualBox VM)
- Command Prompt
- Network tools: ipconfig, ping, nslookup

## Ticket 1: No Internet Connection (DNS Issue)
**Issue:** User reported no internet access.

**Troubleshooting Steps:**
- Verified IP configuration using `ipconfig`
- Tested connectivity with `ping 8.8.8.8`
- Identified DNS resolution failure with `ping google.com`
- Flushed DNS cache using `ipconfig /flushdns`

**Resolution:**
- Cleared corrupted DNS cache and restored internet access

## Skills Demonstrated
- Network troubleshooting
- DNS resolution
- Command-line diagnostics
- Technical documentation
