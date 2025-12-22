# CyberSecurity-labs
# RDP Brute Force Testing Lab

## Project Goal
Demonstrate credential testing on RDP protocol using Crowbar and Ncrack in a controlled lab environment.

## Tools Used
- Crowbar (Python-based brute force tool)
- Ncrack (reliable RDP brute forcer)
- Wordlist: rockyou.txt

## Lab Setup
- Target: Windows 11 VM (IP: 192.168.107.133) with RDP enabled and NLA disabled
- Attacker: Ubuntu VM

## Execution Steps
1. Attempted with Crowbar – encountered FreeRDP warning
2. Switched to Ncrack – successfully scanned RDP service
3. No credentials discovered (expected with strong password)

## Results
- Tool execution screenshots attached below
- This lab simulates real-world credential attack testing

## Screenshots
(See images below)
<img width="1920" height="1080" alt="Screenshot from 2025-12-23 02-48-33" src="https://github.com/user-attachments/assets/2523e920-2b87-465e-b855-77c822bc4d2d" />

This project shows practical use of brute force tools in a safe lab setting for educational purposes.
