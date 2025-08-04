# Port_scan
# Local Network Port Scan Summary

## Overview
This project documents a local area network (LAN) scan conducted using **Nmap** to discover active devices, open ports, running services, and identify potential risks.

## Scan Highlights
- Devices scanned: 7
- Devices with open ports: 3
- Notable open ports:
  - **53/tcp** – DNS (dnsmasq) 
  - **7070/tcp** – Possible SSL service

## Potential Risks Identified
- **Port 53:** DNS cache poisoning, zone transfer leaks, info disclosure.
- **Port 7070:** Potential malware backdoor, proxy abuse.

## Files Included
- `scanning.txt`: Raw Nmap output with IPs, open ports, services, and risk notes.

## Usage
Review `scanning.txt` for detailed scan data, including device-specific findings and MAC addresses.

## Tool Used
- **Nmap** – Network discovery and security auditing tool.
