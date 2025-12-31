# Ticket 1 – No Internet Connection

## Issue
User reports no internet access. Websites are not loading.

## Environment
- Windows 11 VM
- Ethernet connected

## Tools Used
- Command Prompt
- ipconfig
- ping

## Troubleshooting Steps
1. Verified IP configuration using `ipconfig`
2. Tested connectivity with `ping 8.8.8.8`
3. Tested DNS resolution with `ping google.com`
4. Flushed DNS cache using `ipconfig /flushdns`
5. Retested DNS resolution

## Root Cause
Corrupted or outdated DNS cache prevented hostname resolution.

## Resolution
Flushed DNS cache and restored normal DNS resolution.

## Verification
Successfully pinged `google.com` and accessed websites.

## Screenshots
(../screenshots/ticket1.png)


